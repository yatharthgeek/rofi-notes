# Rofi Notes

A simple and efficient note management script that utilizes `rofi` as a menu selector. This script allows you to create new notes or open existing ones seamlessly, all from a single menu interface.

## Features

- Create new notes with a custom name.
- Open existing notes easily.
- Simple and intuitive interface using `rofi`.
- Notes are stored in a dedicated directory.

## Prerequisites

Before using this script, ensure you have the following installed:

- [rofi](https://github.com/davatorium/rofi) - A window switcher, application launcher, and dmenu replacement.
- [xed](https://github.com/linuxmint/xed) - A simple text editor (or any text editor of your choice).

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yatharthgeek/rofi-notes.git
   cd rofi-notes
   ```

2. **Make the script executable:**

   ```bash
   chmod +x notes.sh
   ```

## Usage

To run the script, simply execute:

```bash
./notes.sh
```
### How It Works

- When you run the script, a menu will appear listing all your existing notes along with an option to create a new note.
- Selecting "New Note" will prompt you to enter a name for the new note, which will be created in the `~/notes` directory.
- Selecting an existing note will open it in `xed`.

## Customization

You can change the directory where your notes are stored by modifying the `NOTE_DIR` variable in the script:

```bash
NOTE_DIR="$HOME/notes"
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
