# Number-Guess-Game
A simple number guessing game built with C++. Guess a randomly generated number between 1-100.

INTRO :-
A time killing game in which you guess a number within 1-100 in as less trials as possible.

HOW IT WORKS :-
-> When you run the code, you will have to enter a number which you think might be the random number.
-> If the number you put in is higher than the random number, then you will be told "Go higher".
-> If the number you put in is lower than the random number, then you will be told "Go lower".
-> If the number you guessed is right, then you will be told ""You guessed it right!".
-> You can enter numbers until you get to the right number, but the number of trials will keep on increasing. 
-> The lower the number of trisls, the better.

HOW TO RUN :-
## How to run

### Method 1: Using g++ (Command line)

1. Make sure you have a C++ compiler installed (e.g., [MinGW](https://www.mingw-w64.org/) for Windows, or `g++` pre-installed on Linux/macOS).
2. Open a terminal in the project folder.
3. Compile the program:
```bash
   g++ number_guess_game.cpp -o number_guess_game
```
4. Run the compiled program:
```bash
   ./number_guess_game        # Linux/macOS
   number_guess_game.exe      # Windows
```

### Method 2: Using an IDE (Code::Blocks / Dev-C++ / VS Code)

1. Open your IDE and create a new C++ project (or just open the file).
2. Load `number_guess_game.cpp` into the editor.
3. Click **Build & Run** (or press `F5` / `Ctrl+F5`, depending on your IDE).
4. Follow the on-screen prompts to play!
