# Smart-Home
In this project we have built a smart home with different sensors like  Smoke Detector, PIR, Ultrasonic and LDR sensor. All these sensors are connected to an Arduino.

Things that you need:
<ul>
  <li>Arduino</li>
  <li>Smoke detector MQ6</li>
  <li>PIR</li>
  <li>LDR</li>
  <li>Ultrasonic Distance Sensor</li>
  <li>DC power source(Any 12V)</li>
  <li>Relay boards of 2 channels </li>
</ul>

The final view of circuit is as follows:

![view](https://github.com/udaychauhan293/Smart-home/assets/120339345/e6b6e991-3da6-4286-96dc-bd35c0974c78)


The functionality of various sensors is as follows:
## 1)Ultrasonic Distance sensor

This is a sensor which will detect a person at a certain distance in its range. Whenever it detects a human, it automatically opens the door using servo motor.

![uds off](https://github.com/udaychauhan293/Smart-home/assets/120339345/c9a53460-5fda-40f2-b4ae-ffe2eb086037)


When the person crosses this distance the servo motor is reset to it's original position and door is closed.

![uds](https://github.com/udaychauhan293/Smart-home/assets/120339345/eae6e3e5-46ee-4355-b0d7-596464068c98)


## 2)PIR sensor

This is a sensor which detects human in its surrounding region and will turn on the fan(which runs by a motor).

![pir on](https://github.com/udaychauhan293/Smart-home/assets/120339345/6fd99213-b3e7-4fd2-85c5-e079a9ef3555)


When the person goes out of its range it will turn off the fan after few seconds.

![pir sensor](https://github.com/udaychauhan293/Smart-home/assets/120339345/b804b70d-9901-4194-920e-ac509ac1a1ac)

Here the fan can also be controlled manually in our design using slide-switch attached to it.

## 3)LDR sensor

This is a sensor which helps us to turn on the lights in dark or night time. It will detect the brightness of surroundings and whenever it detects a human it will turn lights ON if it's dark.

![bulb](https://github.com/udaychauhan293/Smart-home/assets/120339345/d28284c7-0dfc-4933-b2d1-4368a7f64c28)


When it's day-time, it detects high brightness and switches off the lights

![bulb off](https://github.com/udaychauhan293/Smart-home/assets/120339345/ef9f0bdc-4348-44ab-8f6d-1bcfe23b7882)


## 4)Smoke Detector
This is a sensor which is connected to a piezo buzzer. When it detects LPG gas around it, the buzzer starts ringing as a caution.

![lpg off](https://github.com/udaychauhan293/Smart-home/assets/120339345/1fec50c9-a9a3-40eb-a06c-06e45379c726)


![gas on](https://github.com/udaychauhan293/Smart-home/assets/120339345/52b12a98-4722-47bb-b7bd-e95c049e06c0)

This project is implemented on Tinkercad platform. Link is attached here-->https://www.tinkercad.com/things/5sEH2qTah0q
