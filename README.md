# Range &nbsp; ![DEVELOPMENT STATUS: complete](https://badgen.net/badge/DEVELOPMENT%20STATUS/complete/green)

A simple bash script to display a specific range of lines from a file or input

## Usage examples:
```console
$ range 19 50 data.txt
```
Will display all the lines of the data.txt file between the 19th one and the 50th one, inclusive

```console
$ cat file.txt | range 10 20
```
Will display all the lines between the 10th one and the 20th one of what ever was piped into it, in this case the content of file.txt

## How-to:
1. Put the **range** script with your other **bin**aries, or in a separate folder, but then don't forget to include that folder to your **PATH** variable (There are plenty of resources out there if you don't know how to do the latter)
2. Add execution rights to it: ```$ chmod u+x range```
3. Rehash to use instantly: ```$ rehash``` 
