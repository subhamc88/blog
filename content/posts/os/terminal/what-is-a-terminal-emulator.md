+++
title = 'Discovering Terminals'
description = "A Beginner's Guide to What They Are and How They Power Your Computer"
date = 2024-09-17T09:46:59+05:30
draft = true
categories = [
    "Technology",
    "User Interfaces",
    "CLI",
    "TUI",
    "Software Development",
    "Productivity Tools",
    "Computer Science"
]
tags = [
    "CLI",
    "TUI",
    "GUI",
    "User Interfaces",
    "Command-Line Interface",
    "Text-Based User Interface",
    "Graphical User Interface",
    "Technology",
    "Computing",
    "Productivity",
    "Tech Tips",
    "Software"
]
[cover]
image = "images/computer/gnome-terminal-for-linux.png"
alt = "Gnome terminal"
+++

## Introduction

In your developing journey, you must have heard about terminals, consoles, command-line interfaces (CLI), or TTY windows.
These terms describe text-based interfaces that allow users to interact with their computer systems using text commands.
Terminals might seem daunting at first, but they are powerful tools that have been central to computing for decades.

## What is a Terminal?

A terminal is a text-based interface that allows users to interact with their computer by typing commands.
Unlike graphical user interfaces (GUIs), which use windows, icons, and menus, terminals rely on text to perform tasks by execute textual commands.

## Historical Evolution

Terminals as of we know today were not the same in the past.
They were physical electronic devices that were used to interact with computers in the early days of computing (mainly in the input and output).

Here's a brief overview of their evolution:

### Technology Evolution Timeline

1. **1920s** - **Teleprinter**:
    - The early teleprinter devices, such as the **TeleType Model 15**, began to be used for transmitting typed messages over telegraph lines.

![Teleprinter](teleprinter.webp "Teleprinter")
**Teleprinter**

2. **1930s** - **Teletyper (TTY)**:
    - The term "Teletyper" became commonly used to refer to devices that combined teleprinter functionality with typing.

3. **1950s** - **Line Printer**:
    - Developed for high-speed printing of text and data, these were often used with early computers.

![IBM 1403 Printer](ibm-1403-printer.jpg "IBM 1403 Printer")

**IBM 1403 Line Printer**

4. **1960s** - **Terminals**:
    - The introduction of **Video Display Terminals (VDTs)** like the **IBM 2250** offered a way to interact with computers via screens and keyboards.

![VDT Terminal](televideo925-terminal.jpg "VDT Terminal")
**Televideo925 Terminal**

5. **1970s** - **CRT Terminals**:
    - **Computer terminals** with **cathode-ray tube (CRT) displays** became popular, providing real-time interaction with computers.

![DEC VT100](dec-vt100.jpg "DEC VT100")
**DEC VT-100**

6. **1980s** - **Early Terminal Emulators**:
    - The development of **terminal emulators** like **Kermit** allowed personal computers to emulate the functionality of hardware terminals and interact with mainframes and minicomputers.

![Kermit](kermit-terminal-emulator-pd.gif "Kermit")
**Kermit Terminal Emulator**

## Architecture of a Modern Terminal Emulator

- **Graphical Interface**: Provides the window where the terminal session is displayed.
- **Input Handling**: Manages keyboard input and passes it to the [shell](../shell/introduction-to-shells.md) or command interpreter.
- **Output Display**: Renders the output from the shell or command interpreter in the terminal window.
