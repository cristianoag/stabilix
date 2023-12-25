# Stabilix

Stabilix is a spin-off of the self-balancing robot project called B-ROBOT EVO created by JJ Robotics. 

It is a platform for experiments with different sensors and algorithms. The robot is able to balance itself on two wheels and move around avoiding obstacles. The robot is based on ESP32 and it is remotely controlled using a smartphone via Bluetooth.

## Hardware

The robot is based on ESP32 microcontroller and it is remotely controlled using a smartphone via Bluetooth. The robot is equipped with the following hardware components:

* 1 x MPU6050 - 6-axis accelerometer and gyroscope
* 2 x NEMA17 stepper motors
* 2 x A4988 stepper motor drivers
* 1 x ESP32 microcontroller

The robot is powered by a 7.4V LIPO battery pack. The battery is connected to a voltage regulator that converts the voltage to 5V. The 5V is used to power the ESP32 microcontroller and the stepper motor drivers. The stepper motors are powered directly from the battery.

## Assembly

The robot is assembled using 3D printed parts. The 3D models are available in the `3D_models` folder. The robot is assembled using the following parts:

### Bill of materials

| Part name | Quantity | Link |
| --- | --- | --- |
| 3D printed parts | 1 | [Thingiverse](https://www.thingiverse.com/thing:2786294) |

## Software

The robot is programmed in C++ using Arduino IDE. The code is based on the B-ROBOT EVO project created by JJ Robotics. 

## Installation

1. Download and install Arduino IDE from [here](https://www.arduino.cc/en/software)
2. Download and install ESP32 board support for Arduino IDE from [here]()
3. Download the code from this repository and open it in Arduino IDE
4. Connect the robot to your computer using a USB cable
5. Select the correct board and port in Arduino IDE
6. Upload the code to the robot

## Usage

1. Download and install the B-ROBOT EVO app from [here](https://play.google.com/store/apps/details?id=com.jjrobots.brobotevoremotecontrol&hl=en&gl=US)

2. Turn on the robot and connect to it using the app

3. Use the app to control the robot

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

