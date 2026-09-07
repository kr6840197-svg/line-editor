# Simple Line Editor in C

Portfolio Building Studio Course - 3rd Semester Coding Competition

## Team Members
- KUSUMA.R
- CHITRASHREE
- BARSA

## Features Implemented
- **Display Document (`p`)**: Shows lines with numbers.
- **Insert Line (`i <line> <text>`)**: Inserts text and shifts lines down.
- **Delete Line (`d <line>`)**: Deletes line and shifts lines up.
- **Save / Load (`s <file>` / `l <file>`)**: Writes to and reads from `.txt` files.
- **Find & Replace (`r <old> <new>`)**: Substring replacement across the document.
- **Statistics (`c`)**: Word, line, and character counts.
- **Search (`/<text>`)**: Substring pattern matching.

## Compilation & Run Instructions
```bash
gcc -Wall -Wextra editor.c -o editor.exe
.\editor.exe
