# AFK Mouse Mover Bot

This simple Python script prevents your computer from going idle by continuously moving the mouse cursor within a random range of positions. 

## Features
- Moves the mouse cursor to a random position within a predefined range.
- Mimics human-like movements with random delays.
- Prevents screen lock, sleep mode, or inactivity kicks in certain applications.

## Requirements
To use this script, you need to have Python installed along with the `pyautogui` library.

### Install dependencies
```sh
pip install pyautogui
```

## Usage
Simply run the script in your terminal or command prompt:
```sh
python main.py
```

## How It Works
- The script generates random `x` and `y` coordinates within a defined range.
- Moves the mouse cursor smoothly to the generated position within 0.5 seconds.
- Waits for 2 seconds before repeating the movement.

## Notes
- You can modify the `random.randint()` values to change the movement range.
- Adjust the `time.sleep()` delay to customize the frequency of movement.
- Stop the script at any time using `CTRL + C` in the terminal.

## Disclaimer
Use this script responsibly. The author is not responsible for any unintended consequences of running this script.

## License
This project is licensed under the MIT License. See the `LICENSE` file in this repository for details.

