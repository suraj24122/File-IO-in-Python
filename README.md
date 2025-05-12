# File-IO-in-Python

🐍 Python File Operations & Utilities
This repository contains a collection of beginner-friendly Python scripts for basic file handling operations and some utility tasks using standard libraries like os, shutil, and argparse. It is perfect for those learning how to work with files and command-line arguments in Python.

📂 Project Structure
bash
Copy
Edit
├── write.py            # Write initial content to a file
├── Append.py           # Append data to an existing file
├── read.py             # Read full content from a file
├── line_by_line.py     # Read content line-by-line
├── argparse_.py        # Command-line calculator using argparse
├── os.py               # Basic file system operations
├── shutils.py          # File copying, moving, and deleting using shutil
├── john Doe.txt        # Output file used in write and append scripts
├── Suraj.txt           # Sample data file for reading and manipulation
🔧 Features
Write and append content to .txt files.

Read files fully or line-by-line.

Perform command-line math operations (add, sub, mul, div).

Manipulate the file system (check existence, remove directories/files).

Use shutil to copy/move/delete files and directories.

🧪 Usage
1. Write to a file
bash
Copy
Edit
python write.py
2. Append to the file
bash
Copy
Edit
python Append.py
3. Read entire file
bash
Copy
Edit
python read.py
4. Read line by line
bash
Copy
Edit
python line_by_line.py
5. Run command-line calculator
bash
Copy
Edit
python argparse_.py 4 5 add
Make sure to replace the numbers and operation (add, sub, mul, div) as needed.

⚠️ Notes
Some scripts (like os.py and shutils.py) expect a directory named dir to exist. You may need to create it manually.

Avoid running os.py and shutils.py without understanding their effect—they can delete directories and files.

👨‍💻 Author
Suraj Singh
Python & Web Developer | AI Enthusiast
