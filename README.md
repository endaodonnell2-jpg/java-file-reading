readfile Java Class
Overview
The readfile class reads a text file word by word and prints each word to the console with all lowercase vowels (a, e, i, o, u) converted to their uppercase counterparts (A, E, I, O, U). Non-vowel characters remain unchanged.

Features
Opens and reads a specified text file.

Converts lowercase vowels to uppercase during output.

Handles file not found exceptions gracefully.

Supports sequential reading of words until the end of the file.

Usage
Create an instance of the readfile class.

Call openFile(String input) with the filename to open.

Call readFile() to process and print the file content.

Call closeFile() to close the file stream.

readfile rf = new readfile();
rf.openFile("example.txt");
rf.readFile();
rf.closeFile();
Requirements
Java Development Kit (JDK)

Notes
The class currently processes text word by word using a Scanner.

Only lowercase vowels are converted; uppercase vowels and other characters remain unchanged.

