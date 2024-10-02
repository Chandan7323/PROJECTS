# Digital Clock Using Python

This project is a simple **Digital Clock** created using Python and the `Tkinter` library. The clock mimics a **7-segment display** style by using a monospaced font and displaying the current time in **HH:MM:SS** format. It updates every second, making it a real-time digital clock.

## Features

- Displays the current time in **HH:MM:SS** format.
- Updates every second.
- Uses a monospaced font to simulate the appearance of a **7-segment display**.
- Customizable font size and colors.

## Requirements

- Python 3.x
- Tkinter (comes pre-installed with Python)

Once you run the script, a window will appear with the digital clock updating every second.

## Code Overview

- **Tkinter** is used for creating the graphical user interface (GUI).
- The **`strftime()`** function from the `time` module is used to fetch the current time.
- The **clock** is displayed using a monospaced font (`Courier`) to replicate the look of a 7-segment display.
- The **`after()`** method is used to update the time every 1000 milliseconds (1 second).

## Customization

You can customize the look of the clock by modifying the following parts of the code:
- **Font size**: Change `font=('Courier', 80)` to adjust the font size.
- **Foreground/Background colors**: Modify `foreground='cyan'` and `background='black'` for different color schemes.
