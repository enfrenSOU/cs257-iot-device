# Smart Coffee Maker Project

This project simulates the functionality of a **Smart Coffee Maker** that can brew coffee, manage water and coffee levels, and allow the user to set the brewing strength. It is implemented in C++.

## Features

- **Fill Water**: Add water to the coffee maker (no bounds checking).
- **Add Coffee**: Add ground coffee.
- **Brew Coffee**: Brew coffee based on requested cups and brew strength.
- **Clean**: Run a cleaning cycle to reset water level and temperature.
- **Display Status**: View the current status of the coffee maker.

## Bugs

Currently, there is a bug in the `fillWater()` method, which **does not check if the water level exceeds the 1000mL tank capacity**, potentially causing an overflow.

## Steps to Reproduce the Bug

1. Clone the repository and compile with:
   ```bash
   g++ -o device main.cpp
