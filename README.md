# XO Game (Tic-Tac-Toe)

## 1. About the Project
A C++ desktop Tic-Tac-Toe (XO) game featuring a graphical user interface and a single-player mode against a scripted bot.

## 2. Motivation & Features
* **Motivation:** Built to practice and demonstrate GUI desktop application development and game logic implementation using C++.
* **Key Features:**
  * **Scripted Bot Opponent:** Play against a rule-based AI bot.
  * **Desktop GUI:** Clean and responsive graphical interface for smooth gameplay.
  * **Lightweight & Fast:** Compiled natively with C++ and CMake.

## 3. Prerequisites & Installation
Before building and running the game, ensure you have **Qt6** *(احذف Qt6 إذا استخدمت مكتبة أخرى)*, **CMake**, and a C++ compiler installed on your system:

### Linux
* **Ubuntu / Debian / Mint:**
  ```bash
  sudo apt-get update && sudo apt-get install qt6-base-dev cmake build-essential
  ```
* **Fedora / RHEL / CentOS:**
  ```bash
  sudo dnf install qt6-qtbase-devel cmake gcc-c++
  ```
* **Arch Linux / Manjaro:**
  ```bash
  sudo pacman -S qt6-base cmake base-devel
  ```
* **openSUSE:**
  ```bash
  sudo zypper install qt6-base-devel cmake gcc-c++
  ```
* **Alpine Linux:**
  ```bash
  sudo apk add qt6-qtbase-dev cmake build-base
  ```
* **Other Distributions:** Install via the [Official Qt Online Installer](https://qt.io) or your distribution's package manager.

### Windows
Download and install **Qt6** (along with MinGW and CMake) from the [Official Qt Download Page](https://qt.io).

## 4. Build & Run

### 1. Clone & Build
Open your Terminal (Linux) or Command Prompt (Windows) and run:
```bash
git clone https://github.com
cd XO-game
mkdir build && cd build
cmake ..
cmake --build .
```

### 2. Run the Game
* **On Linux:**
  ```bash
  ./XO-game
  ```
* **On Windows (CMD):**
  ```cmd
  XO-game.exe
  ```

## 5. Future Features (Roadmap)
* **Intelligent AI Bot:** Upgrade from a scripted bot to a smart opponent using the **Minimax algorithm** for unbeatable gameplay.

## 6. Version
`1.0.0`
