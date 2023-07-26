# send-pic-bot-gui-rtsp-exe

![Screenshot 2023-07-26 225415](https://github.com/khanfar/send-pic-bot-gui-rtsp-exe/assets/16803586/3306d470-0471-4e0b-8f08-3d5f3ca16939)



here's a brief introduction and the features of the mkhanfar ALPR pictures Send to Telegram bot:

# M Khanfar Bot

M Khanfar Bot is a Python-based Telegram bot that monitors a specified folder for new images and sends them to a specified Telegram chat. It's a great tool for remote monitoring systems where images are captured and need to be sent to a remote location for review.

## Features

- Monitors a specified folder for new images.
- Sends new images to a specified Telegram chat.
- Extracts the text from the image filename and sends it as a separate message.
- Plays a beep sound when a new image is processed.
- Provides a GUI for easy setup and control.
- Saves and loads settings from a file.
- Displays a status indicator that changes color based on the bot's activity.
- the bot if there multible files in same directory with date , the bot chose last date new file to send these photos based on pc time to fit ALPR applications , so its monitor for new picture and send based on time.
- the bot work real time so not send old stored pictures in same directory . its look for new captured pictures coming from RTSP Software.
- the bot can handle send pictures and text of License Plate too with time detalis and date . and can be customized.

## Requirements

To run this bot, you need to have Python installed on your machine. The bot also requires the following Python libraries:

- `os`
- `time`
- `asyncio`
- `threading`
- `datetime`
- `telegram` (Install via pip: `pip install python-telegram-bot`)
- `winsound`
- `tkinter`
- `sys`
- `nest_asyncio` (Install via pip: `pip install nest_asyncio`)

## Setup

1. Install the required Python libraries if you haven't already.
2. Clone this repository to your local machine.
3. Run the bot script (`python bot_script.py`).
4. In the GUI, enter your Telegram bot token, the path to the main folder you want to monitor, and your Telegram chat ID.
5. Click "Save" to save your settings.
6. Click "Start" to start the bot. The status indicator will turn yellow.
7. When the bot detects and processes a new image, the status indicator will turn green for a few seconds.
8. Click "Stop" to stop the bot. The status indicator will turn red.

Please note that you need to create a Telegram bot and get a bot token from BotFather on Telegram. You also need to get your Telegram chat ID. There are many online guides on how to do this.

Enjoy using M Khanfar Bot!
