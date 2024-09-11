# boot-txt-collection

This was created as the database for the telgram daily wisdom bot. 
The idea is to have different books in `.txt` format in different folders.
All folders should have files `001.txt` until end (maximum is `999.txt`).
Files without this format are skipped.

The folders should have the structure `<book id>-<book name>-<book author>-<book tag>`
* `<book id>` : 4 capital letters (after initiation, the book id will never change)
* `<book name>` : name of the book
* `<book author>` : author of the book
* `<book tag>` : small tag used by user to select the book (it can be changed later)
Folders with the tag `draft` in front will be skipped.

Ensure that the book title and the chapter are at the start of the txt file.
The rest of the body ensure that it is formatted like normal txt, aka each line doesn't go beyond 80 words. 
