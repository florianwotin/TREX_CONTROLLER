# TREX_CONTROLLER
[TREX Embedded GPU project](https://github.com/florianwotin/TREX_PROJECT) controller

## Sources

Initial files come from : https://www.generationrobots.com/fr/401824-controleur-t-rex.html

## What did we change ?

We did a bugfix affacting two files (Bluetooth.ino and TREX_controller.ino) for bluetooth feature.

## Installation

### Clone git repository on your computer

Start a terminal and go where you want to install the app in your file system.

You can install the full project with these commands:

```bash
git clone https://github.com/florianwotin/TREX_PROJECT.git
git submodule update --init --recursive
```

Or you can install only the controller with this command:

```bash
git clone https://github.com/florianwotin/TREX_CONTROLLER.git
```

You can check everything is up to date with:

```bash
git status
```

### Compile your code and televerse it into the card

You can use [Arduino IDE](https://www.arduino.cc/en/software) to compile your code with the compile button and verify everything is OK by checking terminal.

Then, you just have to televerse your source code into the card with the televerse button.

Boot the card and it should be working !
