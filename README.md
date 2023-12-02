# DolphinShuffler

## Overview
DolphinShuffler is a Python script designed to automate game swapping in a specified list of save slots. This tool is especially useful for creating dynamic gaming experiences or challenges. It was originally created by Twitch streamer DougDoug, whose creative content can be found on his [YouTube channel](https://www.youtube.com/@DougDoug) and [Twitch stream](https://www.twitch.tv/dougdoug). The source files for this script were shared during one of his streams, which can be viewed [here](https://youtu.be/l0H1P2SWlQY&t=28060).

## Features
- Automatic swapping between different game save slots.
- Integration with OBS Websockets for live streaming updates.
- Audio alerts for different stages of the game swapping process.
- Spacebar interrupt for manual control over the game swapping.

## Downloading the Script
You can download the latest stable version of DolphinShuffler from the [releases](https://github.com/NolwenB/DolphinShuffler_Source/latest) section on the GitHub repository. This is the recommended way to obtain the script if you are not planning to modify the source code.

## Installation and Setup (Running from Source)
If you choose to run DolphinShuffler from the source code, follow these steps:
1. Clone or download the DolphinShuffler repository.
2. Navigate to the DolphinShuffler directory.
3. Install the required Python packages: `pip install -r requirements.txt`.
4. Ensure OBS Websockets and other dependent systems are correctly set up if you intend to use these features.

## Usage
To run the script, simply execute `python DolphinShuffler.py` in your terminal or command prompt. Make sure to configure the script settings according to your requirements before running.

## Creating an Executable File
To create an executable (`.exe`) file from the DolphinShuffler script, follow these steps:
1. Finish all steps from *Installation and Setup (Running from Source)*.
2. Install `auto-py-to-exe` via pip: `pip install auto-py-to-exe`.
3. Run `auto-py-to-exe` in the command prompt or terminal.
4. In the `auto-py-to-exe` interface, select your `DolphinShuffler.py` script.
5. Configure the settings according to your needs (e.g., single file, icon, etc.).
6. Click 'Convert .py to .exe'.
7. Find the generated executable in the output folder specified.

This executable can be distributed and run on Windows systems without requiring Python to be installed.

## Disclaimer
This code was not created by the person distributing this README. It was developed by DougDoug, a Twitch streamer known for his innovative and interactive gaming content. All credit for the creation and original idea of this tool goes to DougDoug.

## Note
This README was generated with the assistance of [ChatGPT](chat.openai.com).
