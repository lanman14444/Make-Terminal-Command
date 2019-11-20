Table of Contents
=================

  * [Make Terminal Command](#make-terminal-command)
     * [Installation](#installation)
        * [Standard Installation](#standard-installation-doesnt-work-for-termux)
        * [Termux Installation](#termux-installation)
     * [Changelog](#changelog)
     * [Tested Distros](#tested-distros)

Make Terminal Command
=====================
A simple bash script to create a new command in Terminal from Terminal.

## Installation

You can use Make-Terminal-Command a few different ways.

### Standard Installation (Doesn't work for Termux!)
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

### Termux Installation

1. Clone the git repo with `git clone https://github.com/lanman14444/Make-Terminal-Command.git`
2. cd into the directory that was cloned.
3. Run `chmod 777 Make-Terminal-Command-Termux`
4. Then to run it, type `./Make-Terminal-Command-Termux`


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

## Tested Distros

* Linux Mint 17
* Ubuntu 14.04
* Arch Linux
* macOS
* Termux (Android Terminal Emulator)
