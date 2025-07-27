COMPANY:CODTECH IT SOLUTIONS
NAME:MARILAKSHMI S 
INTERN ID:CT04DH848
DOMAIN:EMBEDDED SYSTEMS 
DURATION:4 WEEKS
# Task-3-Temperature-Monitor
Temperature sensor using TMP36

In this project, a Temperature Monitoring System is developed using Arduino and a temperature sensor (such as LM35 or TMP36). The system is capable of reading the temperature from the sensor and displaying the output either on a 16x2 LCD display with I2C module or on the Serial Monitor.

This system is helpful for learning the basics of embedded systems and sensor interfacing. It is a common use case in weather stations, smart agriculture, and safety monitoring applications.
Project Goals:
To measure temperature in real-time.
To display the measured temperature on Serial Monitor
To understand sensor-to-microcontroller data acquisition.
To gain hands-on experience in circuit building and coding in Arduino IDE.

Required Components:

Component Quantity

Arduino Uno 
TMP36 Sensor 

Working Principle:
The TMP36 temperature sensor gives analog output proportional to the temperature. The Arduino reads this analog voltage from the sensor using the analogRead() function and converts it into temperature (in °C) using a simple formula.
The temperature is printed to the Serial Monitor for observation.
