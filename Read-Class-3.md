# opene 
## Files on most modern file systems are composed of three main parts:

   - Header: metadata about the contents of the file (file name, size, type, and so on)
   - Data: contents of the file as written by the creator or editor
   - End of file (EOF): special character that indicates the end of the file
# File Paths
The file path is a string that represents the location of a file. It’s broken up into three major parts:

    - Folder Path: the file folder location on the file system where subsequent folders are separated by a forward slash / (Unix) or backslash \ (Windows)
    - File Name: the actual name of the file
    - Extension: the end of the file path pre-pended with a period (.) used to indicate the file type
# Opening and Closing a File in Python
by open() built-in function. open() has a single required argument that is the path to the file. open() has a single return, the file object:
file = open('dog_breeds.txt')

|Character| Meaning|

|'r'| 	Open for reading (default)|
|'w'| 	Open for writing, truncating (overwriting) the file first|
|'rb' or 'wb' |	Open in binary mode (read/write using byte data)|


