
Python allows for a user to import and export files. Use with open, to open and close a file. Without using ‘with open’ the file will stay open unless, which is not best practice. After code is created to open a file, it needs to be read. There is an option to use  with open <’name of file>, ‘r’ which allows the file to be opened in read-only mode. Other methods to read files include: .read(size = -1), .readline(size=-1), .readlines().

1.	Read(size=-1) – can read the file based on the size in bytes. If no argument is passed, it will read the whole file
2.	.readline( size=-1) – reads at most characters in size in the line. It will read the entire file if no argument is passed
3.	.readlines() – it reads the lines from the file and returns as a list

