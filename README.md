# LED Dice Roll in Microcontroller for AT89C51

## Problem Statement
The objective of this project is to simulate the rolling of a dice using LEDs controlled by an AT89C51 microcontroller. Dice rolling is a fundamental feature in many games, and this project demonstrates how simple microcontroller logic can be used to simulate random outcomes with visual feedback via LEDs. The project is aimed at beginners in embedded systems and microcontroller programming, offering a hands-on approach to understanding input/output interfacing and randomization techniques in hardware.

## Key Objectives Include

- **Simulate Dice Roll**: Develop a system where pressing a button simulates the random roll of a dice and displays the result using LEDs.
- **Microcontroller Interface**: Utilize the AT89C51 microcontroller to control the LED display and manage button inputs.
- **Randomization of Dice Rolls**: Implement a pseudo-random algorithm to mimic the randomness of a real dice roll.
- **User Interface**: Provide a simple push-button mechanism to trigger the dice roll and display the result on the LEDs.
- **Efficient Code Implementation**: Write optimized C code to handle LED outputs and button debouncing effectively.
- **Comprehensive Documentation**: Provide clear instructions and documentation for building the hardware and coding the microcontroller.

## Features

### 1. LED Display for Dice Roll
   - **Description**: Uses 6 LEDs to represent the sides of a dice. When the button is pressed, a random number between 1 and 6 is generated, and the corresponding number is displayed by lighting up the appropriate LEDs.

### 2. Button Interface
   - **Description**: A push button is used to simulate the dice roll. Pressing the button triggers the randomization algorithm, which then updates the LED display.

### 3. Random Number Generation
   - **Description**: Implements a simple pseudo-random algorithm that generates a number between 1 and 6, simulating the roll of a dice. The randomness is determined by the timing of the button press, mimicking the variability of real dice rolls.

### 4. AT89C51 Microcontroller Integration
   - **Description**: The AT89C51 microcontroller is used to control the dice roll logic, manage button inputs, and update the LED display. It runs the program that handles random number generation and drives the corresponding LEDs.

### 5. Low Power Consumption
   - **Description**: The system is designed to be energy-efficient, consuming minimal power while idle and during operation, making it suitable for small-scale embedded applications.

### 6. Clear Documentation
   - **Description**: Includes detailed documentation for setting up the microcontroller, connecting the LEDs, writing the code, and using the system. This ensures ease of replication and understanding by other users or developers.

## Goals

- **Simulate Dice Roll Visually**: Provide a visual representation of dice rolls using LEDs controlled by a microcontroller.
- **Ensure Efficient Randomization**: Implement a pseudo-random number generator to create unpredictable dice roll results.
- **Develop User-Friendly Interface**: Allow users to interact with the system via a simple push-button mechanism.
- **Optimize for Low Power**: Keep power consumption low, making the system suitable for embedded or portable use.
- **Support Future Modifications**: Build the system in a way that it can be extended, such as adding more LEDs or additional features like sound.
- **Provide Complete Documentation**: Offer a clear and detailed guide to help users understand the system and modify it as needed.

## Benefits

- **Interactive Dice Simulation**: Offers a fun and interactive way to simulate dice rolls for games or educational purposes.
- **Simple and Intuitive Design**: Easy-to-use push-button interface allows for immediate interaction and feedback via LEDs.
- **Low-Cost Implementation**: Uses basic, inexpensive components (LEDs, button, AT89C51 microcontroller) to build the system.
- **Learning Platform**: Serves as a learning tool for beginners to understand microcontroller programming, input/output handling, and randomization in embedded systems.
- **Energy Efficient**: The low-power design ensures that the system can be used in portable or battery-powered setups.
- **Extensible Framework**: Provides a foundation for future improvements, such as additional game mechanics or the inclusion of different microcontroller platforms.

## Conclusion
This project demonstrates how an AT89C51 microcontroller can be used to simulate a dice roll using LEDs. By providing visual feedback through LED patterns, users can interact with the system in real-time, making it a great learning tool for understanding basic microcontroller operations and random number generation.
