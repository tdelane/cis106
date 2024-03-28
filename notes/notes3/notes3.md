# Notes 3: Managing Files and Directories 

 ## Each of the commands for Managing Files and Directories 



## mkdir 
## Definition 
Mkdir is used for creating a single directory or multiple directories. 
### Usage 
`mkdir +`
### Examples 
* Display of mkdir using relative path 
  * `mkdir wallpapers/ocean`
* Display of mkdir using absolute path 
  * `mkdir ~/wallpapers/forest` 
* Display of mkdir creating multiple directories 
  * `mkdir wallpapers/cars wallpapers/cities/ wallpapers/forest`

<hr>

## touch 
## Definition 
Touch is used for creating files 
### Usage
`touch +`
### Examples 
* Display of touch creating a file called "list" 
  * `touch list`
* Display of touch creating several files 
  * `touch list_of_cars.txt script.py names.csv` 
* Display of touch using absolute path 
  * touch ~/Downloads/games.txt 

<hr>

## rm 
## Definition 
rm removes files 
### Usage 
`rm -r +`
### Examples 
* Display of rm removing a file called "list"
  * `rm list`
* Display of rm removing a file and prompt confirmation before removal 
  * `rm -i list` 
* Display of rm remving all files inside a directory and ask before removing more than 3 files 
  * `rm -i Downloads/games/*` 

<hr>

## rmdir 
## Definition 
rmdir is used to remove empty directories
### Usage 
`rmdir +`
* Display of rmdir removing an empty directory 
  * `rmdir Downloads/games` 

<hr>

## mv 
## Definition 
mv moves and renames directories 
### Usage 
`mv + source + destination` 
### Examples 
* Display of mv moving a file using relative path 
  * `mv Downloads /homework.pdf Documents/` 
* Display of mv moving a file using absolute path 
  * `sudo mv ~/Downloads/theme /usr/share/themes` 
* Display of mv moving a file from one directory to another combining absolute path and relative path 
  * `mv games/ wallpapers/ rockmusic/ /media/students/flashdrive/` 

<hr>

## cp 
## Definition 
cp copies files/directories from a source to a destination
### Usage 
`cp + files to copy + destination`, `cp -r + directory to copy + destination`
### Examples 
* Display of cp copying directories, you must use the -r option 
  * `cp -r + cp -r + directory to copy + destination`
* Display of cp copying a fie 
  * `cp Downloads/wallpapers.zip Pictures/` 
* Display od cp to copy using absolute path 
  * `cp -r ~/Downloads /wallpapers ~/Pictures/` 

<hr>

## file 
## Definition 
file determines the file type of a file 
### Usage 
`file + file type name`
### Examples 
* Display of file type 
  * `file type`
* Display of file type without the file name 
  * `file -b filename` 

<hr>

## pdfinfo 
## Definition 
displays information about pdf files 
### Usage 
`pdfinfo filename.pdf` 
### Examples 
* Display of pdfinfo 
  * `pdfinfo homework1.pdf` 

<hr>

## mediainfo 
## Definition 
command line utility to display information about audio/video files 
### Usage 
`mediainfo whatever.png` 
### Examples 
* Display information about a media file 
  * `mediainfo example.png`
* Display full information of a media file 
  * `mediainfo -f example.png` 
* Display of Output information to an html file 
  * `mediainfo --output=HTML example.png > file.html` 

<hr>

## exiv2 
## Definition 
image metadata manipulation tool 
### Usage 
`exiv2 [option] [action] [file]` 
### Examples 
* Displaying information about an image file 
  * `exiv2 example.png` 
* Display all exif data about an image file 
  * `exiv2 -pt example.png` 

<hr>

## exiftool
## Definition 
read and write meta information  in files 
### Usage 
`exiftool` 
### Examples
* Display information about a file 
  * `exiftool example.png` 
* Writing to all files in a directory 
  * `exiftool -artist=me c:/images`
* Writning mutiple tags with exiftool 
  * `exiftool -artist="Phil Harvey" -copyright="2011 Phil Harvey" a.jpg`
