# Useful Commands

## Linux basics

### `pwd`

Shows where I am right now in the terminal.

Example meaning:

"I am currently inside this folder."

---

### `ls`

Shows the files and folders inside the current location.

Example meaning:

"What is inside this folder?"

---

### `cd folder-name`

Moves me inside a folder.

Example:

`cd documents`

Meaning:

"Go inside the documents folder."

---

### `mkdir new-folder`

Creates a new folder.

Example:

`mkdir test`

Meaning:

"Create a folder called test."

---

### `mkdir -p parent/child/grandchild`

Creates several folders inside each other.

Example:

`mkdir -p projects/devops/linux`

Meaning:

"Create projects, then devops inside it, then linux inside that."

---

### `touch file.txt`

Creates an empty file.

Example:

`touch notes.txt`

Meaning:

"Create a file called notes.txt."

---

### `cat file.txt`

Shows what is written inside a file.

Example:

`cat notes.txt`

Meaning:

"Show me the content of notes.txt."

---

### `cp file.txt copy.txt`

Copies a file.

Example:

`cp notes.txt notes-backup.txt`

Meaning:

"Create a copy of notes.txt called notes-backup.txt."

---

### `cp -r folder backup-folder`

Copies a folder and everything inside it.

Example:

`cp -r devops devops-backup`

Meaning:

"Copy the devops folder and all its content."

---

### `mv old-name.txt new-name.txt`

Renames a file.

Example:

`mv notes.txt linux-notes.txt`

Meaning:

"Rename notes.txt to linux-notes.txt."

---

### `rm file.txt`

Deletes a file.

Example:

`rm notes.txt`

Meaning:

"Delete notes.txt."

---

### `rm -r folder-name`

Deletes a folder and everything inside it.

Example:

`rm -r old-folder`

Meaning:

"Delete old-folder and all files inside it."

Warning: be careful with this command.

---

### `echo $SHELL`

Shows which shell I am using.

Example meaning:

"Am I using bash, zsh, or another shell?"