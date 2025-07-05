# -PUSH-BUTTON-COUNTER

COMPANY NAME : CODETECH IT SOLUTION

NAME : ATUL KUMAR SINGH

Intern ID :CT06DF1527

DOMAIN :Embedded Systems

DURATION :6 weeks

MENTOR:NEELA SANTOSH

DESCRIPTION
The Push Button Counter is a basic yet highly educational embedded systems project that involves using a tactile push button to increment a numerical value and display it on an output device, such as a 7-segment display or an LCD screen. It is a commonly implemented mini-project for students learning microcontrollers, digital electronics, or embedded C/C++ programming. This project introduces important concepts like digital input reading, signal debouncing, real-time display updates, and control logic.

Objective
The main objective of the Push Button Counter is to detect each valid press of a button and increase a counter value accordingly. This counter is then displayed in real-time to the user. The goal is to create a reliable system that only increments once per press, regardless of electrical noise or bouncing effects inherent in mechanical switches.

Working Principle
When the push button is pressed, it sends a digital HIGH (or LOW, depending on configuration) signal to a microcontroller’s GPIO (General Purpose Input Output) pin. The microcontroller monitors this pin using a polling or interrupt method. On detecting a valid state change, it increases an internal counter variable by one. This new value is then displayed using a suitable output device.

To ensure accurate counting, debouncing is essential. Mechanical buttons can generate multiple transitions in milliseconds due to physical bounce, leading to false multiple increments. Debouncing can be handled either in software using delays and state checking, or in hardware using resistors and capacitors (RC filters).

Components Used
Microcontroller (e.g., Arduino Uno, ESP32, or ATmega328P)

Push Button

Pull-down or Pull-up Resistor (typically 10kΩ)

7-Segment Display or 16x2 LCD Display

Breadboard and Jumper Wires

USB Cable for Programming

CIRCUTI DIAGRAM

![Image](https://github.com/user-attachments/assets/b07bbec2-25b0-42b9-befa-38fc97763e2c)
