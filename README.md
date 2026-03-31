# Smart Door Lock System (MSP430)

This project implements a password-based electronic door lock system using the MSP430 microcontroller and C++.

## Overview

The system provides secure access control using a keypad-based password authentication mechanism.  
It supports both administrator and user-defined passwords and allows dynamic password configuration.

## Features
- Password-based authentication system
- Multi-level access (admin and user passwords)
- Real-time feedback using LEDs and buzzer
- Embedded implementation using MSP430
- User password configuration and validation
- Error handling for incorrect inputs

## Hardware
- MSP430 microcontroller
- Keypad (user input)
- Relay module (lock control)
- LEDs (status indication)
- Buzzer (audio feedback)

## Demonstration

▶️ Video:
https://www.youtube.com/watch?v=w6N8GiQotUs

## Description

When powered on, the system initializes with visual and audio feedback.  
Users can enter passwords via the keypad.  

- Incorrect password → red LED indicates error  
- Correct admin password → allows setting a new user password  
- Key presses → indicated by LED feedback  
- Correct password → activates relay and unlocks the system  

## Notes

This project demonstrates embedded system design, user authentication, and real-time hardware interaction.  
The focus is on system functionality and hardware integration.
