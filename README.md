**Hand-Gesture-Controlled-Car-using-nrf24l01_mpu6050**

This is my first Hardware Project: Hand Gesture Controlled Car using Arduino Nano,MPU6050 motion sensor and an nRF24L01 radio module for wireless control.

⚙️ **Project Description**


The project is split into two main components: a Transmitter (the remote controller) and a Receiver (the car). The transmitter uses the MPU6050 sensor to detect motion and converts the 

pitch and roll into control signals. These signals are then sent wirelessly via an nRF24L01 radio module.



The receiver, mounted on the car, uses a matching nRF24L01 radio to receive these signals. Based on the received data, it controls two DC motors to drive the car forward, backward, left, or right. A built-in safety feature stops the car if the radio signal is lost for more than 500 milliseconds.





📋 **Hardware Requirements**

**Transmitter**

Arduino Nano

MPU6050 6-Axis Accelerometer and Gyro Sensor

nRF24L01 radio module

Power supply (e.g., 9V battery)

Jumper wires

**Receiver**

Arduino Nano

L298N Motor Driver Module

nRF24L01 radio module

4x DC Motors

Chassis and wheels

Power supply (e.g., LiPo battery)

Jumper wires
