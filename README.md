# IOT_Minor_Projects
**Software Required:** Arduino IDE

**The projects are explained below:**

# Led_control_using_Wifi
LED control using ESP8266 via a secured website.

**Hardware required**: Arduino Nano, Arduino Nano Cable, ESP8266 WiFi module, AMS 1113 step down power supply, Led, Push button, Jumper Wires.

**Steps:**

First upload the code to the ESP, after the code is successfully uploaded, then turn on the wifi on your end device, a wifi named Shivnano is created connect it by the password given in the code. After that , go to the web browser and type the IP 192.168.4.1 , a login page comes, login with the crediatials given in code, if the credentials are correct a page comes where you can control your led, else a pop up appears saying wrong credentials.

Please find attached pictures and screenshots

## Reverse_Car_parking_system
The vehicle will move in reverse direction.

Ultra sonic sensor finds distance frrom the wall.

According to distance, VIBGYOR Pattern will produce using RGB according to distance starting from violet.

At 5 cm, Green light emits and a buzzer starts, the buzzer continues till 0 cm.

**HARDWARES REQUIRED:**

Node MCU, trasonic Sensor, RGB LEB, Buzzer, Connecting Wires

## RGB_from_app
An app is made with the help of MIT App inventor with 5 buttons, red, blue, green, white and no color, the rgb glows according to the button clicked.

## LED_Intensity_Slider_controlle
An app is made with the help of MIT App inventor with sliders to control the intensity of leds and using the app, the intensity of leds are controlled.

## Servo_motor_control_using_Slider
A servo motor is controlled using a slider that is made on a webpage by the arduino code itself.

## Relay_control_on_temperature
A relay control based on temprature shows on a secure webpage using button on webpage and sends alert using buzzer.

## Pulse Monitoring System
A pulse sensor is connected to NodeMCU and heartrate is depicted on thingSpeak website on a graph.

## IR Sensor Entry and Exit(HEAD COUNTER)
With the help of 2 IR sensors we can keep a count of people entering the room and exiting at the same time.
