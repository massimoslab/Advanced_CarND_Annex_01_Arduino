[image1]: ./images/arduino_uno.jpg
[image2]: ./images/arduino_micro.jpg
[image3]: ./images/arduino_micro_pins.jpg

# Annex 01 : Foreword

In This Annex we will explore some of the basics of the Arduino. More specifically, we will look at:

* the Arduino device itself
* the programming language used for the Arduino
* an example of project made with an Arduino

## 01. Arduino Basics

The idea of an Arduino is to use its microcontroller in order to:
* process data that are provided as an input to the Arduino through its input pins, or
* process data so that a signal can be sent to external device through its output pins.

The Arduino's microcontroller is a simple computer that can run one program at a time in a loop. An Arduino is particularly interesting to execute specific tasks. In our case these tasks will be:
* providing throttle signal to the motor
* provide the steering angle to a so called servo motor

## 02. The Arduino devices

The most commonly used Arduino is the Arduino Uno. The image below show an Arduino Uno:

![alt text][image1]

For our project, however, we do not need the full computational power and pins of the Arduino Uno and we can, therefore, use a cheaper version: the Arduino Micro. The image below shows the Arduino Micro:

![alt text][image2]

There are many other devices that belon to the Arduino family such as: the Arduino Due, Leonardo, Mega, Nano, Zero, M0 and many more.

## 03. Arduino Micro pins

All Arduino boards are equipped with sets of pins. The pins can be connected to a variety of sensors, motors, and other devices. The pins are of two types:
* digital, and
* analog

Furthermore, the pins can be used in two different ways, either as:
* input, or
* output

The image below shows the different pins of an Arduino Micro and how they can be used.

![alt text][image3]

## 04. Programming an Arduino

The language used to program the microcontrollers has very similar characteristics to C and C++. Therefore, if you have already programmed in either of these languages you should not have any particular issue.


```
Examples
```

### Purchases and Downloads
The Arduino can be purchased from the following link:
[Purchase an Arduino](https://store.arduino.cc/)

The Arduino IDE can be downloaded from the following link:
[Download the Arduino IDE here](https://www.arduino.cc/en/Main/Software)

## Authors

**Massimo Passamonti**: [email me](mailto:mpweb2.0@gmail.com)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
