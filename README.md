# Real-time Monitoring System for ECG, Heart Rate, and Blood Oxygen Saturation (SpO₂)

## Overview

This document provides details about a project designed to monitor key health parameters, including electrocardiogram (ECG), heart rate (HR), and blood oxygen saturation (SpO₂), in real-time. The system collects, processes, and visualizes data through clear, interactive graphs available via a web browser interface.

## Components Used

- **Raspberry Pi 3B+**: Serves as the main computational unit and server.
- **AD8232 Module**: Used for ECG signal acquisition.
- **MAX30102 Sensor**: Measures heart rate and SpO₂.
- **MCP3008 ADC**: Converts ECG analog signals to digital format.

## Communication Interfaces

- **SPI**: Used by the MCP3008 ADC.
- **I²C**: Utilized for communication with the MAX30102 sensor.

## Features

- Real-time ECG, HR, and SpO₂ data visualization.
- Accessible web-based user interface developed with Flask.
- Dynamic plotting using interactive charts for clear data presentation.

## Usage

1. Ensure sensors are correctly connected to the Raspberry Pi.
2. Launch the system and access the provided URL through a web browser.
3. Monitor and analyze real-time health data from the graphical interface.

## Potential Enhancements

- Improve ECG signal quality by advanced filtering techniques.
- Develop a mobile application for remote monitoring.
- Implement cloud-based long-term data storage and analysis.

## Intended Applications

- Educational and prototyping tool in biomedical engineering.
- Remote health monitoring.
- Sports and wellness tracking.

Developed by Bartłomiej Rudowicz and Paweł Kierkosz.
