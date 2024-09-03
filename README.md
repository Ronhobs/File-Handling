                                                                          File Merger in C
This repository contains a C program that merges the contents of two text files into a third file.

Overview
The program reads the contents of file1.txt and file2.txt and writes them sequentially into file3.txt. The first file's contents are written to file3.txt, followed by the contents of the second file.

How It Works
The program opens file1.txt and file2.txt for reading.
It opens (or creates) file3.txt for writing.
The contents of file1.txt are read and written to file3.txt.
The contents of file2.txt are then appended to file3.txt.
If any of the files cannot be opened, the program will print an error message and exit.


Usage
Clone the repository or copy the source code.
Make sure you have the files file1.txt and file2.txt in the same directory as the program.
Compile the program using a C compiler, e.g., gcc file_merger.c -o file_merger.
Run the compiled program: ./file_merger.
After running the program, file3.txt will contain the merged contents of file1.txt and file2.txt.
