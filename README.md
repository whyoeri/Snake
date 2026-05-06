# Snake
A classic snake game. Control the snake to eat food and grow, avoiding walls and its own tail.
![](assets/demogamesnake.gif)
## Features
- Continuous monitoring of the current count and the length of the snake on the screen
- A detailed summary of the results (score and final snake length) before returning to the main menu
- Optimised command processing that eliminates delays and key sticking, even during rapid typing
## Installation
### Option 1: Download the archive
1. Download the release from [GitHub Releases](https://github.com/whyoeri/Snake/releases)
2. Extract the archive to any folder
3. Run the file:
    - Linux: ./wsnake
    - macOS/windows: Not supported. The program is developed exclusively for Linux (POSIX-compatible systems).
### Option 2: Compilation from source files
1. Clone the repository:
    ```bash
    git clone https://github.com/whyoeri/Snake
    ```
2. Go to the project folder:
    ```bash
    cd Snake
    ```
3. Generate the build files using Makefile:
    ```bash
    make
    ```
4. Go to the build folder:
    ```bash
    cd build
    ```
5. After compilation, run the binary file located in the build folder:
    ```bash
    ./wsnake
    ```
## License
Copyright (c) whyoeri.  
Licensed under the [MIT](LICENSE.txt) license.