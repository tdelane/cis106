# Notes 2: The Linux FS 

  ## Each of the commands used for navigating the file system 



## File System
### Definition 
The way files are stored and organized 
### Usage 
`/`, 
### Examples 
* Display with home 
   * `/home`
* Display with labs 
   * `/home/cis106/labs`
* Display with cheatsheet 
   * `/home/cis106/cheatsheet`
  
<hr>

## Pathnames 
### Definition 
In a file system, every file has a pathname which indicates the location of the file in the filesystem
### Usage 
`/`, `/home/user`
### Examples 
* Display with Absolute Path 
   * `/home/john/Downloads/song.mps`
* Display with Relative Path 
   * `Downloads/song.mp3`
* Display with Absolute Path 
   * `Downloads/Movies/Avatar.mp4` 

<hr>

## Absolute Path
### Definition 
 The location of a file starting a the root of the file system 
### Usage 
 `home`
### Examples 
* Display of Absolute path 
  * `home/john/Downloads/song.mp3`
* Display of Absolute Path
  * `home/john/Games/DragonBall.txt`
* Display of Absolute Path 
   * `home/john/Music/Leanonme.mp4`

<hr>

## Relative Path 
### Definition
The location of a file starting from the current working directory that is located inside the current working directory
### Usage 
`Downloads/etc`
### Examples 
* Display of Relative Path 
  * `Downloads/song.mp4` 
* Display of Relative Path
  * `Music/Leaonme.mp4`
* Display of Relative Path 
  * `Games/Dragonball.txt`
  
<hr>

## Difference between "Your Home Directory" and The  "The Home Directory" 
### Definition 
Your home directory is the top most directory in the file system hierarchy, while the home directory is specific to a user
### Usage 
`/home`. `/home/maria53` 
### Examples 
* Display of "Your Home directory"
  * `/home/trindell26`
* Display of "The Home Directory" 
  * /`home`
  
<hr>

## Parent Directory 
### Definition 
 a directory containing one or more directories and files.
### Usage 
`..`
### Examples 
* Display of Parent Directory 
  * `Downloads/New_Movies/action/horror/evil_dead`
* Display of Parent Directory 
  * `Downloads/Games/DLC_content/last_of_us`
* Display of Parent Directory 
  * `Downloads/Music/Jcole/Ablums/4_Your_Eyes_Only`

<hr>

## Child Directory 
### Definition 
 a better name for this is a subdirectory or subfolder.This is a directory inside another directory. See image for visual reference.
### Usage 
`Downloads/Games_Downloaded`
### Examples 
* Display of Child Directory 
  * `Downloads/Games`
* Display of Child Directory 
  * `Downloads/Snap`
* Display of Child Directory 
  * `Downloads/Pictures` 

<hr>

## Bash Special Characters 
### Definition 
Special characters are function like commands that tell the shell to perform a specific action without having to type the complete command. These special characters make working on the command line more efficiently. Here is short list to keep in mind.
### Usage 
`.`,`..`,`~/`,`/`,`-`,`#`,`!`,`!!`
### Examples 
* Display od Special characters 
  * `/home/maria53/Downlods`
* Display of Special characters 
  * `rm -r website/`
* Display of Special characters 
  * `cd../../`
   
<hr>

## Environment Variables
### Definition 
Environment variables store values of a user’s environment and can be used in commands in the shell. These values can be unique to the user’s environment which makes them ideal when writhing commands that you want to use regales of which user is using the computer.
### Usage 
`$USER`,`$HOME`,`$PWD`,`$OLDPWD`
### Examples 
* Display of Environment Variables 
  * `echo "The Current User: $USER"`
* Display of Environment Variables
  * `echo "The Current User: $SHELL"`
* Display of Environment Variables
  * `echo "The Current User: $HOME"`

<hr>

## User Defined Variables
### Definition
User variables are created by the user and exist inly in the script and subshell that runs the script 
### Usage 
`name=wtw`
* Display of User Defined Variables 
  * `Name=Pater`
* Display of User Defined Variables 
  * `Age=60`
* Display of User Defined Variables
  * `Email= google@gmail.com`

<hr>

## Why do we need use $ with variables in bash shell scripting?
### Definition 
This can prevent errors and unexpected behavior in your shell commands and scripts
### Usage 
`$USER`,`$HOME`
* Display of $ 
  * `echo "The Current User: $USER"`
* Display of $
  * `echo "The Current User: $SHELL"`
* Display of $
  * `echo "The Current User: $HOME"`
