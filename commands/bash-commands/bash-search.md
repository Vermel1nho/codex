# Basic Search Commands in Linux

Simple commands to find files and text in your system.

---

`grep`

Find text inside files.


grep "text" file.txt

Simple commands to find files and text in your system.

Options:

-i: ignore case

-r: search in folders

-n: show line number

Example:
grep -in "error" logs.txt

---

`find`
Find files or folders.

find <path> -name "filename"

Example:
find . -name "notes.txt"

---

`locate`
Fast file search (uses a database).

locate filename

Example:
locate passwd

---

`which`
Find the path of a command.

Example:
which nmap

Output:
/usr/bin/nmap

---

`head`
Show the first lines of a file. 10 lines

Example:
head file.txt

Show first 5 lines:

Example:
head -n 5 file.txt

---

`tail`
Shows the last lines of a file.

Example:
tail file.txt

Show the last 20 lines:

Example:
tail -n 20 file.txt

Follow a file in real time (useful for logs):

Example:
tail -f file.log

