# Co2-Sensor
Done by: 

Mohammed Albalam  221424981

Salman Albu Shaqraa 219031677

Abdullah AlYousef 219031859

# Overview
This project demonstrates how to interface a carbon dioxide (CO2) sensor with an Arduino Nano BLE 33 using the I2C communication protocol. The CO2 sensor used in this project provides accurate readings of carbon dioxide levels in the surrounding environment, making it suitable for various applications such as indoor air quality monitoring and more.
# Requirements
Arduino Nano BLE 33 board

Carbon dioxide sensor with I2C interface

Jumper wires

Arduino IDE

Edge Impulse

# Implementation
1. Open Arduino IDE.
2. Inatal DFRobot_SCD4X library and use singleShotMeasure.
3. Connect the I2C interface to the Arduino Nano 33 BLE board.
4. Connect the Arduino Nano 33 BLE board to your device.
5. Start taking carbon dioxide readings from different places.
6. Save and arrange your data in Excle sheet.
7. Create an Edge Impulse account.
8. Analyze your data using Edge Impulse after converting your data to an Excel file in CSV (comma-separated value) form.

 #### Edge Impulse Integration
   1. Log/Sign in to your Edge Impulse account and create a new project.
   2. Follow the instructions to add a new data acquisition source and select Arduino as the device type.
   3. Configure the data acquisition parameters and collect training data for CO2 level detection.
   4. Train your machine learning model using Edge Impulse's built-in tools.

 # Opservations & Results 
 We took readings of carbon dioxide from various locations in the city of Al-Ahsa (Kingdom of Saudi Arabia) and at different times and days. We faced some difficulties in moving from one place to another to collect readings during hot weather conditions. Finally, we took readings from different places that were classified in :
 
 (1) as College of Business.
 
 (2) as College of Engineering.
 
 (3) as CCSIT Department.
 
 (4) as Deanship of Student (outdoor).
 
 (5) as Deanship of Student (indoor).
 
 (6) as Kitchen (not at cooking time).
 
 (7) as Living Room.
 
 (8) as Near to Small Garden.
 
 (9) as PYD Department.
 

 And after an estimated 7 minutes of training the flatten block has produce a results shown in the bellow figure:

 !(https://github.com/MohammedSami23/Co2-Sensor/assets/169708630/2733ba54-58b3-45fd-8224-dc93d3acd0e6)

 
 

   
