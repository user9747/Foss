
Bash
======
### 0.Editor
* ### nano
     `nano <filename>` = opens file with that name,creates it if doesn't exist
* ### vim
### 1.Basic commands

* #### man
    `man <command>` -To know more about a command<br/>
    `<command> --help`<br/>
    `<tldr <command>` -Smaller version of the man page.<br/>

* ####  ls
    `ls <path>` - list directory contents<br/>
    `ls -la` -list all files in details even hidden files
    
* ####  cd
    `cd <folderName>` = change directory<br/>
    `cd /` = go to root<br/>
    `cd ..` = go up one folder, tip: ../../../
* ####  pwd
     `pwd ` = prints working directory
* ####  mv
    `mv <file or folder location> <new destination>`<br/>
    if folder name has spaces use “\ “<br/>
    `mv <folderName>/ ..` = move folder up in hierarchy
    
* ####  mkdir
     `mkdir <foldername>` = makes new folder
     
* ####  cp
     `cp <file location> <new destination>` = copies file from location to new destination<br/>
     `cp -r <folder location> <new destination>` = copies folder from location to new destination
     
* ####  rm
     `rm <file name>` = deletes file(poyi macha file :p)<br/>
     `rm -r <folder name>` = deletes the folder and its contents.
     
* ####  touch
     `touch <file name>` = creates a new file with that name

* #### wild cards<br/>
    ? (question mark)<br/>

    This can represent any single character. If you specified something at the command line like "hd?" GNU/Linux would look for hda, hdb, hdc and every other letter/number between a-z, 0-9.<br/>
   
    \* (asterisk)<br/>

    This can represent any number of characters (including zero, in other words, zero or more characters). If you specified a "cd*" it would use "cda", "cdrom", "cdrecord" and anything that starts with “cd” also including “cd” itself. "m*l" could by mill, mull, ml, and anything that starts with an m and ends with an l.

        
    Paths<br/>
            . (dot) = current directory<br/>
            ~ (tilde) = home directory<br/>
            / (slash) = root directory

* #### echo
    `echo <string or variable>`-Print text<br/>
    usage: echo Heeloo World

* #### cat
    `cat <filename>` -Prints file<br/>

* #### clear
    `clear`-Clear terminal<br/>

* #### head
    `head <filename>`-Print Top 10 lines of the file(default)<br/>

* #### tail
     `tail <filename>`-Print last 10 lines of file(default)<br/>

* #### history
    `history`-Displays all previous commands executed in the current shell.<br/>

* #### uname
    `uname`-Print system information. '-a' parameter displays complete details.<br/>
* #### tree
    `tree <foldername>`-Display directory structure in tree structure<br/>

* #### curl
    `curl <url>`-Transfer data from url.<br/>
    '-o' Save file to filename specified.
    '-O' Save file to its original filename.
* #### wget
    `wget <url>`-Download file.<br/>
* #### grep
    `grep <string> <filename>` - Searches file for matches of the given string.<br/>
    `grep "is" file`-Displays all lines with substrings of "is".eg.his,is,miss.<br/>
    `grep -i "is" file`-Case insensitive.<br/>
    `grep -w "is" file`-NO subtrings only exact matches of is.<br/>
    -E -Extended grep or use egrep.Interpret PATTERN as an extended regular expression ."foo|bar".Searches for multiple patterns.<br/>
    Can implement above using -e.Use PATTERN as the pattern.  This can be used to specify multiple search patterns`grep -e foo -e bar file`<br/>
    ^,$<br/>
    .?,*,+<br/>
    

    
     
     
     
     
     
     
     
