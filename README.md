🐍 Snake Game (Tkinter)

A simple Snake Game built in Python using the tkinter GUI toolkit.
The game features a growing snake, randomly spawning food, score tracking, and collision detection with walls and itself.

🚀 Features

Classic Snake gameplay

Scoreboard with real-time updates

Food spawning at random positions

Collision detection (walls & self)

"Game Over" screen when the snake dies

Smooth movement with adjustable game speed

🛠️ Requirements

Python 3.x

Tkinter (comes pre-installed with Python on most systems)

No external dependencies required.

▶️ How to Run

Clone or download this repository.

Save the script as snake_game.py.

Run the file with:

python snake_game.py

🎮 Controls

⬅️ Left Arrow – Move Left

➡️ Right Arrow – Move Right

⬆️ Up Arrow – Move Up

⬇️ Down Arrow – Move Down

⚙️ Game Settings (Editable in Code)

You can tweak the game by modifying these variables at the top of the script:

GAME_WIDTH = 700        # Width of the window
GAME_HEIGHT = 700       # Height of the window
SPEED = 100             # Snake speed (lower = faster)
SPACE_SIZE = 50         # Size of each square block
BODY_PARTS = 3          # Initial length of snake
SNAKE_COLOR = "#00FF00" # Snake color (green)
FOOD_COLOR = "#FF0000"  # Food color (red)
BACKGROUND_COLOR = "#000000" # Background (black)

🏆 Future Improvements

Add difficulty levels

High score tracking

Sound effects (using winsound or pygame)

Pause/Restart functionality

👨‍💻 Author

Developed as a fun project to practice Python and Tkinter.
