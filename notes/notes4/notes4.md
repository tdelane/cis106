# Notes 4: Wildcards and Brace Expansion 

## Each of the commands used for navigating the file system 



## Wildcard 
### Definition 
The main wildcard is a star, or asterisk (*) character.
### Usage 
`*`
### Examples 
* Display
  * `ls *.txt` 

<hr>

## The ? Wildcard 
### Definition 
The ? wildcard proves very useful when working with hidden files
### Usage 
`??`
### Examples 
* Display of wildcard ? 
  * `ls .??*`

<hr>

## The [] Wildcard 
### Definition 
The brackets wildcard use the exclamation mark to reverse the match 
### Usage 
`[]`
### Examples 
* Display of [] Wildcard who's name has at least one number 
  * `ls *[0-9]*`
* Display of [] using all files that have a range of letters after f 
  * `ls f[a-z]*`

<hr>

## Brace Expansion 
### Definition
Brace expansion {} is not a wildcard but another feature of bash that allows you to generate arbitrary strings to use with commands
### Usage 
`{}`
### Examples 
* Display using mkdir 
  * `mkdir -p music/{jazz,rock}/{mp3files,videos,oggfiles}/new{1..3}`
* Display using touch 
  * `touch website{1..5"}.html`