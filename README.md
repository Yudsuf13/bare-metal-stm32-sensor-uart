# Bare-Metal STM32 Sensor UART

## About This Project

This is a selfish project for satisfying my thirst to understand the low-level microcontroller programming. The microcontroller chosen here is from the STM32 family, specifically the STM32F103C8T6.

The main objectives of this project are:

- blinking the MCU's onboard LED-- to indicate that the system is operational[not dead].

- to gain practical understanding of ADC configuration and analog-to-digital conversion. So that i can know how this ADC part honestly works. I have read enough vague theory in my academic courses like: instrumentation, computer architecture, embedded system, microprocessor but never actually had hands on understanding. 

- To send the temperature information to computer through UART communication [Again! I have heard this word in an intimate level; but, but but....]

## Problem Statement:

The goal of this project is to build a bare-metal firmware application for the STM32F103C8T6 microcontroller without using any vendor HALs, Arduino libraries, or RTOS. The system will directly manipulate memory-mapped registers to:

1. Blink an onboard LED to indicate the system is alive.

2. Read the internal temperature sensor via the ADC.

3. Transmit the temperature data over UART at 115200 baud to a host PC for monitoring.

## Hardware Requirements

1. STM32F103C8T6: The microcontroller development board (commonly the Blue Pill).
2. ST-Link: Used to program and debug the STM32 through its SWD interface.
3. CH340: USB-to-serial interface, allowing the computer to communicate with the MCU through UART.


## Project Progress

Just ordered the hardwares and installed STM32CubeIDE.
