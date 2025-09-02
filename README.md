**Hand-Gesture-Controlled-Car-using-nrf24l01_mpu6050**

This is my first Hardware Project: Hand Gesture Controlled Car using Arduino Nano,MPU6050 motion sensor and an nRF24L01 radio module for wireless control.

⚙️ **Project Description**


The project is split into two main components: a Transmitter (the remote controller) and a Receiver (the car). The transmitter uses the MPU6050 sensor to detect motion and converts the 

pitch and roll into control signals. These signals are then sent wirelessly via an nRF24L01 radio module.



The receiver, mounted on the car, uses a matching nRF24L01 radio to receive these signals. Based on the received data, it controls two DC motors to drive the car forward, backward, left, or right. A built-in safety feature stops the car if the radio signal is lost for more than 500 milliseconds.





📋 **Hardware Requirements**

**Transmitter**

1.Arduino Nano

2.MPU6050 6-Axis Accelerometer and Gyro Sensor

3.nRF24L01 radio module

4.Power supply (e.g., 9V battery)

5.Jumper wires

**Receiver**

1.Arduino Nano

2.L298N Motor Driver Module

3.nRF24L01 radio module

4.Chassis and wheels

5.4x DC Motors

6.Power supply (e.g., LiPo battery)

7.Jumper wires
