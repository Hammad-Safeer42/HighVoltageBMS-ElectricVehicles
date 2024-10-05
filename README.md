# ADI-Based BMS for Electric Vehicles

## Overview

This repository contains the design and implementation of a **Battery Management System (BMS)** for electric vehicles, utilizing **Analog Devices' LTC6813 voltage measurement ICs**. The design is highly modular and distributed, with each slave board capable of handling up to **18 cells**. The system is designed for high-precision voltage monitoring and ensures safe operation with isolated inter-board communication.

This BMS is ideal for high-performance electric vehicles and motorsport applications where accuracy and safety are paramount.

## Key Features

- **ADI LTC6813-Based**: Incorporates Analog Devices' LTC6813 ICs for accurate and reliable voltage measurement.
- **Modular and Distributed Design**: Scalable architecture, where each slave board can manage up to 18 cells, allowing for flexible system configurations.
- **Isolated Inter-board Communication**: Ensures secure, interference-free communication between the master and slave boards.
- **High Accuracy**: Designed for precision voltage measurement, offering a highly accurate monitoring system for electric vehicle batteries.

## System Architecture

The system is distributed across multiple slave boards and a master board:
- Each **slave board** handles up to 18 cells and is equipped with an LTC6813 IC for accurate voltage sensing.
- The **master board** communicates with all slave boards via an isolated communication bus, ensuring system integrity and safety.

This modular structure allows for easy scaling depending on the number of cells in the vehicle's battery pack.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

