open function in File operations in python is inbuilt fucntion we build in python that helps us open files. this is the the synthax : open(filename, mode)

where ;
filename is the name of the file to be opened.
mode is the mode you want to open the file in.

modes include;
'r' is to read mode, used in reading files.
'w' is to write mode, create a new file or overwrite an existing one.
'a' append mode, adds new content without deleting date
'rb' 'wb' binary modes for non text files like images and videos.

## Example 1: read a file

the myData.txt is a file we want to read from. so we define the syntax and then input the file name. replace the file name with myData.txt and replace the mode with "r" then print out at the terminal by using print(file.read())

# file = open("file name", "mode")

file = open("myData.txt", "r")

print(file.read())

## Example 2: write a file

initially we didnt have a file name filename.txt but after writing with this syntax: newFile = open("filename", "mode")
newFile.write("we add the content of that file")

a filename.txt file will appear on the
right hand side of the screen as one of the files with the content of that file.

## Example 3 : deleting file with python codes:

we created a file named filenamings.txt with the intention of deleting it. so we use the syntax:

import os

os.remove("filenamings.txt")

# import os means import operating system that will be used to remove the file.

so once the code is run, the filenamings.txt will be removed. so if you are not seeing the file, it means it has been deleted. to test yours, open a file named filenamings.txt and run it again.

# A real world application for this is a simple To-Do List Web App project that involves CRUD (Create, Read, Update, Delete) operations.
