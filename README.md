# GPS-Integrated Autonomous Surface Vehicle

This project involves the development of an autonomous surface vehicle (ASV) integrated with GPS for precise depth mapping using sonar sensors and real-time environmental water quality testing. The system is designed for continuous, high-resolution data collection with minimal human intervention.

## Table of Contents

- [Overview](#overview)
- [Abstract](#abstract)
- [Components](#components)
- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

Accurate and detailed information about water bodies is crucial for various applications, including environmental monitoring, hydrographic surveys, aquaculture management, and recreational activities. Traditional methods of gathering water depth and quality data can be labor-intensive, time-consuming, and limited in scope. Autonomous systems offer a promising solution to these challenges by enabling continuous, high-resolution data collection with minimal human intervention.

## Abstract
Autonomous Surface Vehicles (ASVs) equipped with advanced sensors and Global location System GPS technology are revolutionizing the exploration and monitoring of aquatic environments. This project focuses on enhancing depth mapping and environmental water testing through the integration of autonomous navigation systems. Traditional methods for depth mapping and water quality monitoring, often labor-intensive and limited in scope, face challenges in efficiency, accuracy, and coverage. The ASV addresses these issues by using sonar for high-resolution depth data collection and sensors to continuously measure water quality parameters such as temperature, pH, and turbidity. The integration of GPS technology enables precise navigation, allowing for comprehensive surveys over larger areas. By automating these processes, the ASV reduces operational costs, minimizes human error, and provides timely data for better environmental management. This project offers an advanced, cost-effective solution for monitoring aquatic environments and early detection of environmental changes and this project focuses on small scale. 

## Components

- **Microcontroller**: Arduino Pro Mini
- **GPS Module**: NEO-6M with extended antenna add-on
- **SD Card Reader**: HiLetgo 3-01-0038-5PCS
- **Electronic Speed Controller (ESC)**: RCelectricparts B071GRSFBD
- **Transmitter**: Flysky FS-i6X
- **Receiver**: Flysky FS-iA6B
- **Motors**: VGEBY1 F2838-350KV (requires soldering)
- **Magnetometer/Accelerometer**: Adafruit LSM303AGR (only magnetometer used)
- **Solar Charge Controller**: Genasun GV-5-PB-12V
- **Solar Panel**: Cheap eBay solar panel
- **Battery**: Batteries Plus AGM 12V 3.3AH .250 FASTON
- **Software**: MATLAB, Python, Ardupilot

## Features

- **GPS Integration**: For precise navigation and depth mapping.
- **Sonar Sensors**: For accurate depth measurement.
- **Environmental Sensors**: For real-time water quality testing.
- **Data Visualization**: Using MATLAB/Python for analyzing and visualizing collected data.
- **Sustainable Power**: Designed with sustainable power systems for extended operational autonomy.

## Setup and Installation




### Hardware Setup

1. **Microcontroller**: Connect the Arduino Pro Mini to the GPS module, SD card reader, magnetometer, and other components as per the circuit diagram provided in the repository.
2. **Motors and ESC**: Connect the motors to the ESC and the ESC to the battery and receiver.
3. **Sensors**: Install the sonar and environmental sensors on the ASV.
4. **Power System**: Set up the solar panel and charge controller with the battery.

### Software Setup

1. **Clone the Repository**
    ```sh
    git clone https://github.com/ajaybirva09/GPS-Integrated-Autonomous-Surface-Vehicle.git
    cd GPS-Integrated-Autonomous-Surface-Vehicle
    ```
2. **Arduino IDE**: Install the Arduino IDE and upload the provided code to the Arduino Pro Mini.
3. **MATLAB/Python**: Ensure you have MATLAB and Python installed with necessary libraries for data visualization and analysis.

## Usage

1. **Load GPS Coordinates**: Store the predetermined GPS coordinates on the onboard micro SD card.
2. **Start the ASV**: Power on the ASV and it will start navigating to the stored coordinates, collecting depth and environmental data.
3. **Data Analysis**: After the mission, retrieve the data from the SD card and use MATLAB/Python scripts for visualization and analysis.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
