# Welcome to the Castle Game

This is a CLI game. You use Command Line Interface Commands to play.

## How to play the game

The goal of the game is to find the Princess.
The Princess is a character who tell you she's the Princess when you talk to her.

There are other characters who may help you or not to find the Princess.
Three of these characters are diguised dragons. If you talk to a dragon, they will burn you and kill you. To win the game, you must avoid the dragons.

To see who's around, or where you may go, use the `ls` command.
To move from one place to another, use the `cd` command.
To talk to someone, use the `cat` command.

Good luck!

## Design Notes

### Places

- Places are structured as directories in the game.
- Directories are places where there may be people.
- Directories have names that start with lowercase letters as: mainRoom, kitchen, kingsChamber, etc.
- To move from one place to another, the player must use the `cd` command.

### People

- People are implemented as text files in the game.
- Text files are named with starting uppercase letters as: John, SoldierWithoutWeapons, etc.
- To speak with people, the player must use the `cat` command.
