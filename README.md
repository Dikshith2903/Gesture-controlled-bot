# Gesture-controlled-bot
The gesture controlled robot is a wireless operated robot and has two parts: Transmitter and Receiver. When the robot is powered on, the transmitter part, which consists of Arduino, MPU6050, Encoder and RF Transmitter, will continuously monitor the MPU6050 sensor.


About this project:

*INTRO:

I wish I could control everything with my hands! Sitting in my chair and controlling things like a BOSS. I'd love it! So I finally came out with a cool DIY hand gesture recognition robot, which can follow the commands made by hand gestures. Sounds crazy but I promise it’s very simple. Making a gesture control robot is actually very simple. This robot is a improvement of my another DIY project RC car using RF module.
Here too, the robot is divided into two parts, transmitter and receiver. The receiver circuit is the same as that of the old post and there is only a slight change in the transmitter circuit, here we need to program the transmitter circuit. So I will be using an Arduino as the programming platform. To recognize the gestures made I will be using an accelerometer sensor. So let’s get building!



*Principle of Hand Gesture Controlled Robot:

In order to understand the principle of operation of Hand Gesture Controlled Robot, let us divide the project into three parts.

The first part is getting data from the MPU6050 Accelerometer Gyro Sensor by the Arduino. The Arduino continuously acquires data from the MPU6050 and based on the predefined parameters, it sends a data to the RF Transmitter.

The second part of the project is the Wireless Communication between the RF Transmitter and RF Receiver. The RF Transmitter, upon receiving data from Arduino (through the Encoder IC), transmits it through the RF Communication to the RF Receiver.

Finally, the third part of the project is decoding the Data received by the RF Receiver and sending appropriate signals to the Motor Driver IC, which will activate the Wheel Motors of the Robot.

*Block Diagram of Hand Gesture Controlled Robot:

The following images show the simple block diagram of Hand Gesture Controlled Robot for both Transmitter and Receiver Parts.

