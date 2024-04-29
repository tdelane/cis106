# Notes 5: 

## Each of the commands used for handling text files 



## Cat 
### Definition 
The cat command is used for displaying the content of a file. 
### Usage 
`cat + option + file(s) to display`
### Examples 
* Display
  * `cat todo.list`
* Cat Using Absolute Path:
  * `cat ~/Documents/todo.list`
* Cat displaying the content of a file with line numbers: 
  * `cat -n ~/Documents/todo.md`

<hr>

## Tac
### Definition 
The tac command is used for displaying the content of a file in reverse order. 
### Usage 
`tac + option + file(s) to display` 
### Examples 
* Display the content of a file in the pwd:
  * `tac todo.md`
* Display the content of a file using absolute path:
  * `tac ~/Documents/todo.md` 

<hr>

## Head 
### Definition 
The head command displays the top N number of lines of a given file.
### Usage 
`head + option + file(s)`
### Examples 
* Display the first 10 lines of a file:
  * `head ~/Documents/Book/dracula.txt`
* Display the first 5 lines of a file:
  * `head -5 ~/Documents/Book/dracula.txt`

<hr>

## Tail 
### Definition 
The tail command displays the last N number of lines given by a file. 
### Usage 
`tail + option + file` 
### Examples 
* Display the last 10 lines of a file:
  * `tail ~/Documents/Book/dracula.txt`
* Display the last 5 lines of a file:
  * `tail -5 ~/Documents/Book/dracula.txt`

<hr>

## Cut
### Definition  
The cut command is used to extract a specific section of each line of a file and display it to the screen. 
### Usage 
`cut + option + file(s)`
### Examples 
* Display a list of all the users in your system:
  * `cut -d ';' -f1 /etc/passwd`
* Display a list of all the users in your system with their login shell:
  * ` cut -d ';' -f1.7 /etc/passwd` 
* Cut a rage of bites per line:
  * `cut -b 1-5 usernames.txt`

<hr>

## Sort 
### Definition 
The sort command is used for sorting files.
### Usage 
`sort + option + file`
### Examples 
* Basic Example:
  * `sort users.lst`
* Sort a file in reverse order: 
  * `sort -r users.txt`
* Check if a file is sorted:
  * `sort -c sorted.lst` 

<hr>

## Wc
### Definition 
The wc command is used for printing the number of lines, characters and bytes in a file. 
### Usage 
`wc + option + file(s)`
### Examples 
* Display the number of characters in a file:
  * `wc -m Users.txt` 
* Display the number of lines in a file: 
  * `wc -l users.txt`
* Display the number of words in a file: 
  * `wc -w users.txt` 

<hr>

## diff
### Definition  
The diff command compares files and displays the differences between them. 
### Usage 
`diff + option + file1 + file2` 
### Examples 
* Display the difference between two files:
  * `diff cars.csv cars-backup.csv`
* Display the difference between two files in a column format:
  * `diff -y cars.csv cars-backup.csv` 

<hr>

## Grep 
### Definition 
Grep is used to search text in a given file.
### Usage 
`grep + option + search criteria + file(s)`
### Examples 
* Basic Example 
  * `grep 'dracula' ~/Documents/dracula.txt` 