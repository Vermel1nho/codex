Basic File and Directory Manipulation Commands

Description:

Essential Bash commands to create, move, copy, and delete files and directories.
Useful for daily navigation and system management.

---

Commands:

1- `touch` = Creates a new empty file.

touch <filename> 

Example:
touch 14-04-25.txt or .md

---

2- `mkdir` = Creates a new directory (folder)

mkdir <directory-name> 

Example:
mkdir projects

Tip: mkdir -p folder1/folder2 (Use -p to create nested directories)

---

3- `rm` = Removes files or directories.

rm <file>

rm -r <directory>

Example:

rm file.txt

rm -r old_folder

Warning:

Deleted files do not go to the trash.
Use -f to force removal, but be careful.

---

4- `cp` = Copies files or directories.

cp <source> <destination>

cp -r <source_dir> <destination_dir>

Example:

cp notes.txt backup.txt

cp -r folder1 folder2

Tip: Use -r (recursive) to copy directories

---

5- `mv` = Moves or renames files or directories.

mv <source> <destination>

Examples:

mv report.txt ~/Documents

mv old_name.txt new_name.txt

Tip: Used for both moving and renaming
