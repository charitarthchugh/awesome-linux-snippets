# Awesome Linux Command line snippets

## Some of them require POSIX compliant shells, indicated by a ^

___

* `for f in *.zip; do unzip -d "${f%*.zip}" "$f"; done`^ - A simple shell script that unzips all zip files into folders
* `gs -dNOPAUSE -sDEVICE=pdfwrite -sOUTPUTFILE=combine.pdf -dBATCH file1.pdf file2.pdf `- Requires Ghostscript. This merges two( or more) pdf files, `file1.pdf` and `file2.pdf` into `combine.pdf` within the same directory.
* `du -h | sort -hr | head -n 10`- Find the biggest files in the current directory
* `du -ah | sort -hr | head -n 10`- Find the biggest files and folders in the current directory
