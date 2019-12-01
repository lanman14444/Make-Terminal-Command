<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Make Terminal Command](#make-terminal-command)
  - [Installation](#installation)
    - [Standard Installation](#standard-installation)
    - [How to make script a global command](#how-to-make-script-a-global-command)
  - [Changelog](#changelog)
  - [Tested Distros](#tested-distros)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

Make Terminal Command
=====================
A simple bash script to create a new command in Terminal from Terminal.

## Installation

You can use Make-Terminal-Command a few different ways.

### Standard Installation
1. Copy the code from make-terminal file.
2. Open a blank file right-click then left-click "Paste."
3. Left click "File" then left-click "Save as".
4. Save it with the name "Make-Terminal-Command".
6. Open the directory that "Make-Terminal-Command" is in.
7. Right-click the icon for "Make-Terminal-Command"
8. Left-click "Properties"
9. Left-click the "Permissions" tab
10. Left-click the checkbox Allow executing file as program
11. Left-click the "Close" button.
12. Open a terminal window
13. Naviagte to the directory that the script is in the terminal
14. Then to run it type ./Make-Terminal-Command

### How to make script a global command
1. Clone the git repo with `git clone https://github.com/lanman14444/Make-Terminal-Command.git`
2. Change directories to the cloned repo.
3. Type `chmod 777 Make-Terminal-Command`.
4. Run `./Make-Terminal-Command`
5. When asked for file name, provide the name of the script.
6. Choose the name of it you want for the command.
7. Follow the rest of the onscreen instructions.

## Changelog

(+) Added feature
(-) Remove feature
(*) Feature

1.0
  (+) Initial Release

1.1
  (+) added the ability to install it for user or globally.

1.2
  (+) Added a Termux Compatible script.

1.3
  (*) Fixed local commands with different filenames removing the original file.

1.4
	(+) Combined Make-Terminal-Command and Make-Terminal-Command-Termux

## Tested Distros

* Linux Mint 17
* Ubuntu 14.04
* Arch Linux
* macOS
* Termux (Android Terminal Emulator)
