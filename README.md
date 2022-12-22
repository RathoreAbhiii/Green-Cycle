# Objective
- Everyone who keeps indoor plants must have faced the problem of forgetting to water them regularly or being perplexed by various requirements of different plant species.
- So tackling this issue, we have developed an automated system to measure the needs like maintenance of humidity and temperature preferred for better growth of the plants by using a water pump with a sensor to check the water level and reduce the user's workload.

## Deliverables
- Our device will check the moisture and humidity levels of soil and water them suitably.
- A BMP280 sensor will calculate the temperature, humidity and pressure levels in a plant.
- We have used a GSM module to send messages regarding the plant to the user.
- Calculated moisture and humidity levels will be displayed on an LED screen.
## Hardware Used
- Arduino UNO (Av.)
- A dual-bus relay module. (Av)
- BMP 280 Module
- LCD character display module 16(green)
- 6V Water pump
- Soil-moisture sensor
- 9V Battery
- GSM Module
## Methodology
- We are using an Arduino Uno to regulate our 6V pump and power the entire system.
- We will use a soil moisture sensor for checking moisture and humidity levels accordingly.
- A Bmp280 sensor will measure all the necessary details required.
- Rest features are maintaining water level records and displaying details on the LCD screen.
In its most basic form, the system is programmed so that if the moisture level of the sensor is less than the specified value of threshold, which is predefined according to the particular plant, then the desired amount of water is supplied to the plant until its moisture level reaches the predefined threshold value.

## Experimental Results
- The system includes a humidity and temperature sensor (BMP 280) that keeps track of the system's present atmosphere and influences irrigation. 
- Furthermore, the system updates its status, sends a reminder message (SMS) about watering his/her plants to the recipient. All of this is accomplished with the Arduino GSM shield.






