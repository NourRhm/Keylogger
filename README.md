<h1 align="center">
Keylogger
</h1>

<p align="center">
  <a href="#Project-description">Project description</a>   |   
  <a href="#Features">Features</a>   |   
  <a href="#Requirements">Requirements</a>   |
  <a href="#Lets-have-fun">Let's have fun</a>   | 

</p>

## Project description
This project is a keylogger that captures both keyboard inputs and mouse positions. It logs the data in the background and sends it to a designated email address every hour. This project is desgned for educational and research purposes only to explore the security implications of keyloggers. Misuse of this tool is illegal and strictly prohibited.

- What is Keylogger?

## Features
- Logs keystrokes and mouse position in the background.
- Saves data in a text file locally.
- Automatically sends logged data to an email address every 1 hour.
- Runs discreetly in hidden mode.

## Prerequisites

Before running the keylogger, ensure you have the following installed:

- [Python 3.x](https://www.python.org/downloads/)
- Required Python libraries:
  - `pynput` (for capturing keyboard and mouse events)
  - `smtplib` (for sending emails)


To install the required libraries, run:

```bash
pip install pynput smtplib

