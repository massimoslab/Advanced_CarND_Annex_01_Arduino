[image1]: ./images/arduino_uno.jpg
[image2]: ./images/arduino_micro.jpg
[image3]: ./images/arduino_micro_pins.jpg

# Annex 01 : Arduino Basics

In This Annex we will explore some of the basics of the Arduino. More specifically, we will look at:

* the Arduino device itself
* the programming language used for the Arduino
* an example of project made with an Arduino

## 01. The Arduino

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

Below is a "Hello World" code for the Arduino.

```
String message = "Hello World!";

void setup() {
  Serial.begin(9600);
}

void loop() {
  Serial.println(message);
}
```

#### Understanding the code

Initially we define a string named **message** with the text *Hellow World!*. The **void setup()** function is run first with its content between brackets. The **Serial.begin(9600)** sets up the speed of the serial port to 9600 baud. The baud setting in the serial monitor window must match this value so that the Arduino and serial monitor window are communicating at the same speed.

The **void loop()** function is run second with all its content between brackets.
The **Serial.println(message)** sends the content of the string variable **message** (i.e. the text *Hello World!*) to the serial / USB port for display in the serial monitor window.

## 05. Purchases and Downloads
The Arduino can be purchased from the following link:
[Purchase an Arduino here](https://store.arduino.cc/)

The Arduino IDE can be downloaded from the following link:
[Download the Arduino IDE here](https://www.arduino.cc/en/Main/Software)

## Author

**Massimo Passamonti**: [email me](me@massimoslab.com)

## License

This project and its source code are licensed under the MIT License. [See MIT License](https://github.com/github/choosealicense.com/blob/gh-pages/LICENSE.md) file for more details.
