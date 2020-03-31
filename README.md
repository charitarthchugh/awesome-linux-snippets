# Awesome Linux Command line snippets
## Some of them require POSIX compliant shells, indicated by a ^
___
* `for f in *.zip; do unzip -d "${f%*.zip}" "$f"; done`^ - A simple shell script that unzips all zip files into folders
