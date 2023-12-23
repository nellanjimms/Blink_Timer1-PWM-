# Assembly through ATMEGA328P - Blinking using PWM Fast Mode
## Overview
This assembly program is designed for the ATmega328P microcontroller to demonstrate PWM (Pulse Width Modulation) functionality on PORTB1. 
PWM is a technique to control the brightness of an LED or the speed of a motor by varying the duty cycle of a pulsing signal.

## Functionality
The program sets up the Timer1 of the ATmega328P to generate PWM signals. The main components of the program include:

1. Setting up Pin 9 (PORTB1) as an output for the PWM signal.
2. Configuring Timer1 registers (TCCR1A and TCCR1B) for PWM generation.
3. Setting the TOP value to control the PWM frequency.
4. Setting the compare value to control the duty cycle of the PWM signal.
5. Running an infinite loop to keep the PWM signal active.

## Software
1. Microchip Studio
2. Proteus
