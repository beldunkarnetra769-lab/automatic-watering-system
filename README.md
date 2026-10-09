# Automatic Watering System for Plants 

## Project Overview

The **Automatic Watering System for Plants** is an IoT-based project developed to automate plant watering and monitor environmental conditions. The system uses a NodeMCU ESP8266 microcontroller and sensors to collect information about soil moisture, temperature, humidity, and water tank level.

Based on the configured soil moisture threshold and control logic, the system can control a water pump to water plants when the soil requires moisture. A Django-based web application provides a dashboard for viewing sensor readings, monitoring historical data, and displaying relevant alerts.

The project aims to reduce the need for manual watering and provide a convenient way to monitor plant conditions through a web interface.

## Objectives

* Automate plant watering based on soil moisture readings.
* Monitor soil moisture, temperature, and humidity.
* Monitor the water level in the tank.
* Display sensor information through a web dashboard.
* Maintain a history of sensor readings for monitoring.
* Provide alerts for relevant conditions, such as dry soil and low water levels.
* Explore the use of IoT technology for plant care and water management.

## Technologies Used

**Hardware**

* NodeMCU ESP8266
* Soil Moisture Sensor
* DHT11 Temperature and Humidity Sensor
* Water-Level Sensor
* Relay Module
* Water Pump
* Buzzer

**Software**

* Python
* Django
* HTML
* CSS
* JavaScript

## System Working

1. **Data Collection:** The sensors collect soil moisture, temperature, humidity, and water-level readings.
2. **Microcontroller Processing:** The NodeMCU ESP8266 reads the sensor values and supports communication with the monitoring application.
3. **Watering Control:** The relay module controls the water pump according to the configured soil moisture threshold and the implemented control logic.
4. **Web Application:** The Django application provides an interface for viewing sensor readings and related information.
5. **Data Monitoring:** The application provides access to sensor history and trend information.
6. **Alerts:** The application can display configured alerts for conditions such as dry soil or a low water level.

## Main Features

* Soil moisture-based automatic watering
* Temperature and humidity monitoring
* Water tank level monitoring
* Django-based web dashboard
* Sensor readings and historical data
* Sensor trend visualization
* Configured alerts for plant and water-level conditions
* Weather information integration
* Monitoring of pump-related activity, where recorded by the application

## Web Dashboard

The web application is developed using Django and provides a dashboard for monitoring sensor information. Depending on the available sensor data and configured integrations, the dashboard includes:

* Current sensor readings
* Soil moisture and environmental information
* Water tank level information
* Historical sensor records
* Trend charts
* Alerts and weather information

## Project Structure

The project includes a microcontroller and sensor setup for data collection, along with a Django web application for displaying and managing sensor information.

.

## Applications

* Home gardening
* Small-scale plant care
* Basic IoT-based irrigation demonstrations
* Learning and experimentation with sensor monitoring and automation

 ## Future Improvements

* Mobile-friendly remote monitoring
* Support for multiple plants and watering zones
* Improved watering schedules using weather forecasts
* Additional sensor integrations
* Enhanced water usage reporting

## Project Details

* **Project Name:** Automatic Watering System for Plants
* **Project Domain:** Internet of Things (IoT) and Web Development
* **Microcontroller:** NodeMCU ESP8266
* **Backend Framework:** Django
* **Programming Language:** Python
