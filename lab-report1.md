# Lab Report 1
## Tests for 'cd'
1. `cd` Tested using no arguments
   * ```
     [user@sahara ~]$ cd
     [user@sahara ~]$
     ```
   * The working directory was `/home` when `cd` was ran
   * No argument was given to the cd command, so the directory was never changed
   * There was no error

2. `cd` Test using a directory as an argument
   * ```
     [user@sahara ~]$ cd lecture1
     [user@sahara ~/lecture1]$
     ```
   * The working directory was `/home` when `cd lecture1` was ran
   * lecture1 was given as an argument to the cd command, since `lecture1` is a subdirectory of `/home`, the working directory
     was changed to `/home/lecture1`
   * There was no error

3. `cd` Test using a file as an argument
   * ```
     [user@sahara ~/lecture1]$ cd Hello.java
     bash: cd: Hello.java: Not a directory
     [user@sahara ~/lecture1]$
     ```
   * The working directory was `/home/lecture1` when `cd Hello.java` was ran
   * Hello.java was given as an argument to the cd command, and the directory was not changed because Hello.java is not
     a directory
   * There was an error because Hello.java is not a directory, `cd` means to "change directory" and only takes directories
     as arguments
## Tests for 'ls'
1. `ls` Tested using no arguments
   * ```
     [user@sahara ~]$ ls
     lecture1 quiz 2
     [user@sahara ~]$
     ```
   * The working directory was `/home` when `ls` was ran
   * `ls` means to "list files" and the files inside of `/home` were the directories `lecture` and `quiz2`
   * There was no error
    
2. `ls` Tested using a directory as an argument
   * ```
     [user@sahara ~]$ ls lecture1
     Hello.class Hello.java messages README
     [user@sahara ~]$
     ```
   * The working directory was `/home` when `ls lecture1` was ran
   * `ls lecture1` printed out the contents of `lecture1` because `lecture1` is a member of the parent directory
     `\home` so the terminal was able to access the contents of `lecture1` from `home`
   * There was no error
     
3. `ls` Tested using a file as an argument
   
