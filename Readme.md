# File Splitter And Merger

This project aims to automatically split and merge large files in a project, so they can be easily shared on GitHub.
This project is built using filesplit: https://github.com/ram-jayapalan/filesplit



usage: main.py [-h] [--split] [--merge] [--list] [--size SIZE]

optional arguments:
  -h, --help   show this help message and exit
  --split      split all files within this directory greater than specified
               size
  --merge      merge all files within this directory previously split by this
               program
  --list       list all files that will be split given the specified size
  --size SIZE  file size limit in bytes for splitting. Defaults to 100000000

To exclude files add the paths one per line in "excluded_files".
