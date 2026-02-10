# Dabyl Air Quality Monitor

Dabyl is an IoT-based air quality monitoring device designed to measure
fine particulate matter (PM2.5 and PM10) and basic environmental parameters
in real time.

The project aims to increase awareness of air pollution and provide
accessible monitoring in regions with limited sensor infrastructure.

## Project Overview

The Dabyl system consists of three main parts:

- **Transmitter unit**  
  Collects data from air quality and environmental sensors and transmits it
  via Wi-Fi.

- **Receiver unit**  
  Displays PM2.5 levels using an OLED screen and LED indicators for
  intuitive visual feedback.

- **Web interface**  
  Provides real-time visualization of sensor data through a browser-based
  dashboard.

## Measured Parameters

- PM2.5 and PM10 concentration  
- Temperature  
- Humidity  
- Gas sensor readings  

## Technologies Used

- ESP8266 microcontrollers  
- BME280 environmental sensor  
- DSM501A particulate matter sensor  
- MQ-135 gas sensor  
- Wi-Fi communication  
- Telegram Bot for notifications  
- HTML & JavaScript for real-time data visualization  

## Repository Structure

transmitter/ - firmware for the sensing and data transmission unit

receiver/ - firmware for the display and indicator unit

web/ - web interface for real-time monitoring


## Purpose

Dabyl was developed as a scientific and engineering project focused on
environmental protection and human health.  
The system is designed to be scalable and can serve as a foundation for
future data analysis and intelligent air quality monitoring solutions.
