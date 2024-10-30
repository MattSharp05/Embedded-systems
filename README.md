# Embedded Systems Projects

This repository contains the reports and project files for various assignments completed in the Embedded Systems class. Each assignment showcases different aspects of embedded system design, programming, and hardware integration using the MSP430 microcontroller and various external components. The projects demonstrate a range of concepts, from basic microcontroller I/O operations to more complex digital systems and real-time motor control.

## Assignments

### Assignment 1: MSP430 Push Button LED Control
In this assignment, we programmed the MSP430 microcontroller in assembly language to control an LED using push buttons. Using Code Composer Studio, we interfaced with the microcontroller, identifying buttons connected to P4.1 and P2.3 to trigger LED1 on P1.0. This project introduced us to low-level I/O handling and basic embedded programming.

- [Video Demonstration](https://www.youtube.com/shorts/B_az6cR_7Q0)

### Assignment 2: Digital Counter with TIMERB and Seven-Segment Display
This project involved designing a digital counter that counts from 00 to 59 and displays the count on two seven-segment displays. Using Digital I/O and TIMERB on the MSP430, we achieved precise one-second intervals with efficient use of limited I/O pins. The project required calculations for timer settings and integration with digital displays.

- [Video Demonstration](https://youtu.be/JjYLVobS7XY?si=riUmxbAgGE_u2i-9)

### Assignment 3: ADC-Controlled LED Blinking
Here, we created a system where an LED’s blinking frequency is controlled by an analog potentiometer input. The project utilized the MSP430's ADC to read the potentiometer’s value and adjust the LED’s blink rate in real time, demonstrating the use of analog-to-digital conversion and real-time embedded control.

- [Video Demonstration](https://youtu.be/airkn85PK7Y)

### Assignment 4: DC Motor Speed Control with Keypad and LCD Display
This project focused on controlling a 12V DC motor’s speed via a matrix keypad and displaying the speed percentage on a 2x16 I2C LCD. Using PWM signals and an H-bridge motor driver, the microcontroller controlled the motor speed based on keypad inputs. The real-time speed display on the LCD ensured precise feedback.

- [Video Demonstration](https://youtube.com/shorts/h6xr7qya_7I?si=EIHCT3Yqx9XI4txp)

### Assignment 5: Web-Based Motor Speed Control via Wifi
In this project, we developed a web-based interface to control a 12V DC motor’s speed over Wifi. The website interface allowed users to adjust the motor speed as a percentage (0-100%) using a slider or direct input. The setup enabled seamless and real-time speed control through a wireless network, making it ideal for applications requiring remote operation.

- [Video Demonstration](https://youtu.be/KqjSwryjNBI)

---

Each project folder contains detailed reports and source files for reproducing and understanding the systems designed in this course.
