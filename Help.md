# Line Editor Help Guide

## Overview
This program is a simple line editor that allows users to perform text-editing operations using commands.

## Supported Commands

### 1. INSERT
**Purpose:** Inserts text into the editor.

**Usage:**
```text
insert <text>
```

**Example:**
```text
insert Hello World
```

### 2. DELETE
**Purpose:** Deletes a line or selected text.

**Usage:**
```text
delete <line_number>
```

**Example:**
```text
delete 2
```

### 3. PRINT
**Purpose:** Displays the contents of the editor.

**Usage:**
```text
print
```

**Example:**
```text
print
```

### 4. SAVE
**Purpose:** Saves the current text to a file.

**Usage:**
```text
save <filename>
```

**Example:**
```text
save output.txt
```

### 5. LOAD
**Purpose:** Loads text from an existing file.

**Usage:**
```text
load <filename>
```

**Example:**
```text
load input.txt
```

### 6. EXIT
**Purpose:** Exits the editor.

**Usage:**
```text
exit
```

**Example:**
```text
exit
```

## Notes
- Enter commands using the syntax supported by the program.
- Provide valid line numbers and filenames when required.
- Save your work before exiting.