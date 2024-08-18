# Desktop-Clock

A simple, transparent desktop clock application built with PyQt5.

## Description

This application creates a frameless, always-on-bottom clock that displays the current time on your desktop. The clock features a semi-transparent black background with rounded corners and white text.

## Features

- Displays current time in HH:MM:SS format
- Updates every second
- Transparent, frameless window
- Centered on the primary screen
- Always stays on bottom of other windows
- Rounded corners with semi-transparent background

## Requirements

- Python 3.x
- PyQt5

## Installation

1. Ensure you have Python 3.x installed on your system.
2. Install PyQt5 using pip:
3. Save the provided code in a file named `desktop_clock.py`.

## Usage

Run the script using Python:
The clock will appear centered on your primary screen.

## Customization

You can customize the appearance of the clock by modifying the following parameters in the code:

- Font size: Change the `font-size` value in the `setStyleSheet` method.
- Clock size: Modify the values in the `setGeometry` method.
- Background opacity: Adjust the `setOpacity` value in the `paintEvent` method.
- Corner roundness: Change the last two parameters in the `addRoundedRect` method.

## License

Made for my need 

## Author

Nivesh Jain

## Acknowledgments

This project uses the PyQt5 library, which is developed and maintained by the Qt Company and Riverbank Computing.
