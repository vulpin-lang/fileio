# fileio
The Official Vulpin flieio module for have Power to control many files, folders about writing, append text and more

## Features

| Feature          | Description                  |
|------------------|------------------------------|
| r        | Read file                            |
| h        | View first line                      |
| t        | View last line                       |
| l        | View with num's                      |
| ce       | Create empty file                    |
| ct       | Create file with text                |
| a        | Append Text                          |
| ml       | Create Multi Line                    |
| c        | Copy File                            |
| m        | Copy file to Folder                  |
| d        | Delete File                          |
| df       | Delete Forcefully                    |
| dr       | Delete Folder                        |
| st       | Search text                          |
| sa       |  Search text in all files            |
| ci       | case insensitive                     |
| me       | make executable                      |
| fbn      | Find by name                         |
| fbi      | Find in directory                    |
| fbe      | watch for changes                    |

## Examples


```basic
U"fileio"
fileio.ct("hello.txt","Hello World! wrote in your file!")
fileio.r("hello.txt")
```
