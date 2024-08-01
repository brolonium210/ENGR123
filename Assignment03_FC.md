# NetHack

![NetHack Logo](https://www.nethack.org/common/nethacklogo-348x128.png)

**test entry**
maybe i should keep my remnotes in this format >> maybes

**NetHack** is a single-player roguelike video game originally released in 1987. The game is considered one of the most complex and difficult roguelikes. This README will guide you through the basics, installation, gameplay, and resources.

## Table of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Gameplay](#gameplay)
   - [Controls](#controls)
   - [Basic Commands](#basic-commands)
   - [Classes](#classes)
   - [Monsters](#monsters)
4. [Tips & Tricks](#tips--tricks)
5. [Resources](#resources)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction

NetHack is not just a game of hack and slash; it requires strategy, patience, and knowledge. The goal is to descend through multiple dungeon levels, retrieve the Amulet of Yendor, and ascend to become a demigod.

### Difficulty Level

- **Beginner:** 1
- **Intermediate:** 3
- **Advanced:** 5

> "The DevTeam thinks of everything!"

## Installation

### Windows

1. Download the [installer](https://www.nethack.org/v360/ports/download-windows.html).
2. Run the installer and follow the on-screen instructions.

### macOS

1. Use Homebrew to install NetHack:
    ```sh
    brew install nethack
    ```

### Linux

1. Install via package manager:
    ```sh
    sudo apt-get install nethack-console
    ```

### Source

1. Clone the repository:
    ```sh
    git clone https://github.com/NetHack/NetHack.git
    ```
2. Build the game:
    ```sh
    cd NetHack/sys/unix
    sh setup.sh
    make all
    ```

## Gameplay

### Controls

- **Movement:**
  - Arrow keys or `h`, `j`, `k`, `l` for left, down, up, right.
- **Attack:**
  - Move into a monster's square.
- **Inventory:**
  - `i` to view inventory.

### Basic Commands

| Command | Action                 |
| ------- | ---------------------- |
| `a`     | Apply a tool           |
| `d`     | Drop an item           |
| `e`     | Eat food               |
| `q`     | Quaff a potion         |
| `r`     | Read a scroll/book     |
| `t`     | Throw an item          |
| `w`     | Wield a weapon         |

### Classes

NetHack offers various classes, each with unique abilities and challenges:

- **Archeologist**
- **Barbarian**
- **Caveman**
- **Healer**
- **Knight**
- **Monk**
- **Priest**
- **Ranger**
- **Rogue**
- **Samurai**
- **Tourist**
- **Valkyrie**
- **Wizard**

## Tips & Tricks

- Save often!
- Identify items before using them.
- Learn to recognize traps and avoid them.

## Resources

- [Official NetHack Website](https://www.nethack.org/)
- [NetHack Wiki](https://nethackwiki.com/)

## Contributing

Contributions are welcome! Please submit pull requests to the [GitHub repository](https://github.com/NetHack/NetHack).

## License

NetHack is released under the NetHack General Public License. See the [LICENSE](https://www.nethack.org/license.html) for more information.
