# Lab Report Week 5
## Linux Commands to Inspect:
- less: similar to 'cat' command, except allows you to have all the contents of the file on 1 screen instead of just on the terminal.
- find: recursively lists all the relative paths of the files in a directory and its subdirectories onto the terminal.
- grep: accepts a string argument, in which it searches a file and prints all lines in it that have the given string.
    
    >   (All of this is done with files inside the 'technical' directory)

### 3 Interesting Command-Line Options for "less"
##### *(Working Directory: /Users/vontaylor/technical/biomed)*

1. -N command
    > `less -N <regularFile>`
    > - (For the output, I choose my \<regularFile> to be "rr74.txt")
    
    > Output:
    > ![lessN](Week-5-Lab-Report-Pics/lessN.jpg)
    > - What this command does is **display the line numbers** in the file that you open with the 'less' command. This is useful\
    > for quality-of-life purposes where you might want to know where you inside of a file that you are reading.

2. -p command
    > `less -p<string> <regularFile>`
    > - \<string> is any string the user wants to input
    > - (For the output, I choose my \<string> to be "med" and my \<regularFile> to be "rr74.txt")
    
    > Output:
    > ![lessp](Week-5-Lab-Report-Pics/lessp.jpg)
    > - What this command does is tells 'less' to **start at the first instance of "med"** in the file. This is also useful for\
    > quality of life purposes where you may want to start reading the file from a string that of your choosing.
    
3. -z command
    > `less -z<number> <regularFile>`
    > - \<number> is any positive integer the user wants to input
    > - (For the output, I choose my \<number> to be 5, my \<regularFile> to be "rr74.txt", and press 'space' on my keyboard once\
    > on after entering the 'less' screen)
    
    > Output:
    > ![lessz](Week-5-Lab-Report-Pics/less-z.jpg)
    > - What this command does it makes it so that when you press 'space' on your keyboard while in the 'less' screen of your file,\
    > the screen will only move down 5 lines instead of the default 1 entire screen down. This is also useful for quality-of-life\
    > purposes for when you want to skip a down the screen a few lines, but don't want to skip down to the entire next screen,\
    > which is the default.

### 3 Interesting Command-Line Options for "find"
##### *(Working Directory: /Users/vontaylor)*

1. -type command
    > `find technical -type <fileType>`
    > - \<fileType> is any one of the key letters that were preset by Linux
    > - The 2 main useful \<fileType>'s for my current purposes are 'd' for directory and 'f' for regular file
    > - (For the output, I choose my \<fileType> to be 'd')
    
    > Output:
    > ![findtype](Week-5-Lab-Report-Pics/findtype.jpg)
    > - What this command does is it recursively lists all files in a file that are directories. This is useful for when you want to\
    > only list all the subdirectories in a directory, but not all the files within them.
3. -iname command
    > `find technical -iname <fileName>`
5.

### 3 Interesting Command-Line Options for "grep"
1.
2.
3.
