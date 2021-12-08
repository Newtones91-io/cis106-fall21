# Notes 5

## Working with links
            Links are nothing but a way to get to the data.
### Inodes (index files)
#### What is an inode?
* A data structure that contains all the information about a file except the file name and its content
* Every file 

### Hard Links
* Hard links are files that point to data on the hard drive.
* Hard links most be created on the same partition
* To create hard links we use: "ln + filename + destination/filename-hl

### Soft Links
* Symbolic links (soft links) are a special type of file that point to other files instead of data in the hard drive
* Soft links do not point to data on a hard drive
* To create a soft link use: ln -s filename


##Getting Help
* Man pages
* Wildcards/ File Globbing
#### THE * WILDCARD
#### THE ? WILDCARD
#### THE [] WILDCARD