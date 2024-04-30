# Online Cheater Bot for chess.com 
         
This is a Python-based Chess bot capable of playing chess games on chess.com. It uses Selenium for web automation, PyQt5 for GUI, and Stockfish engine for chess engine functionality.  
           
## Features    
 
- **Web Automation**: The bot automates interactions with chess.com using Selenium.
- **GUI Interface**: The bot has a graphical user interface built with PyQt5, allowing users to interact with it.
- **Stockfish Engine**: It utilizes the Stockfish engine for chess move evaluation and calculation.
- **Move Visualization**: The bot generates SVG representations of the chessboard with arrows indicating moves.
- **Evaluation Display**: The bot displays the evaluation of the current position during the game.
- **Responsive Design**: The GUI window automatically adjusts its size and position based on the user's screen resolution.

## Requirements

- Python 3.x
- PyQt5
- Selenium
- Stockfish engine
- Firefox web browser (for Selenium)

## Usage

1. Install the required dependencies mentioned in the `requirements.txt` file.
2. Ensure that you have Firefox installed on your system.
3. Run the `main.py` file to start the bot.
4. The GUI window will appear, allowing you to interact with the bot.
5. Sign in to your chess.com account in the opened Firefox browser.
6. Begin a game on chess.com, and the bot will automatically start playing.

## Configuration
 
- The bot's behavior can be configured using the `config.json` file.
- You can adjust settings such as window size, engine parameters, and more in the configuration file.

## Credits

- This project utilizes the following libraries and tools:
  - PyQt5
  - Selenium
  - Stockfish engine

## Disclaimer

- **Use at your own risk:** Using this bot to play games on chess.com may violate the terms of service of the website. Be sure to review and comply with chess.com's terms of service before using this bot.
- **Fair play:** It is essential to use this bot responsibly and maintain fair play standards in online chess games.
