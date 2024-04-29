# Notes 6: 

## Each of the commands used for handling text files 



## Awk
### Definition 
Awk is a scripting language used for processing and displaying text. 
### Usage 
`awk + option + {awk command} + file + file to save (optional)`
### Examples 
* Basic Example: 
  * `awk {print $1}' ~/Documents/Csv/cars.csv` 
* Print of first field of /etc/passwd file 
  * `awk -F: '{print $1}' /etc/passwd` 
* Print the last field of /etc/passwd file 
  * `awk -F: '{print $NF}' /etc/passwd` 

<hr>

## Sed 
### Definition 
SED is a stream editor that performs operations on files and standard output.
### Usage 
`sed options + sed script + file` 
### Examples 
* Basic Example 
  * `sed 's/pizza/rice/' shopping-list.lst`
* Replacing string on a range of lines
  * `sed '1,3 s/pizza/rice/' shopping list.lst` 
* Replacing string on a specific line number 
  * `sed '3 s/pizza/rice/' shopping-list.lst` 

<hr>

## Less 
### Definition 
less command is a shows the linux terminal pager that shows a file's contents one screen at a time.
### Usage 
`less -` 
* Forces less to open non-regular files (a directory or a device-special file).
  * `less -f` 
* less automatically exits upon reaching the end of file.
  * `less -E` 
* Removes all highlights from strings found using search.
  * `less -G` 

<hr>

## Alias 
### Definition 
alias allows you to configure a single word to serve as an alias for a command number 
### Usage 
`alias` 
### Examples 
* Alias using absolute path.
  * `alias frename='Example/Test/file_rename.sh'`
* Alias to create a temporary one.
  * `alias c='clear'` 
* This displays the list in a format suitable for input to the shell
  * `alias -p` 

<hr>

