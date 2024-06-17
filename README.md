# Humidity-and-Temperature-sensor
Sensor allows to analyze environmental conditions like: humidity and temperature for specific plants. The program reads data from a sensor connected via a serial port, calculates various averages over time, and provides feedback on plant health based on these readings.

## Features
- Real-time Data Acquisition: Reads humidity and temperature data from a sensor via a serial port.
- Averaging Over Time: Calculates average readings for the last minute, 5 minutes, 30 minutes, and hour.
- Plant Health Monitoring: Provides feedback on plant health based on sensor data and predefined thresholds.
- Graphical User Interface: Uses PySimpleGUI for user interaction and displaying data, plots temperature and humidity trends using Matplotlib.
- Saving: Saves givae data in to .csv file

## GUI Layout

### Main Window:
- Dropdown for selecting plant type.
- Input field for naming the plant.
- Submit button to start monitoring.

### Sensor Data Window:
- Real-time and average readings for humidity and temperature.
- Status indicator for plant health.
- Buttons to view data charts and exit the application.

### Chart Window:
- Temperature and humidity trend charts.
- Back button to return to the sensor data window.
