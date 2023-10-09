# Lab Report 1
## Tests for 'cd'
1. `cd` Tested using no arguments
   * ```
     [user@sahara ~]$ cd
     [user@sahara ~]$
     ```
   * The working directory was `/home` after `cd` was ran
   * No argument was given to the cd command, so the directory was never changed
   * There was no error

2. `cd` Test using a directory as an argument
   * ```
     [user@sahara ~]$ cd lecture1
     [user@sahara ~/lecture1]$
     ```
   * The working directory was `/home/lecture1` after `cd lecture` was ran
   * lecture1 was given as an argument to the cd command, since `lecture1` is a subdirectory of `/home`, the directory was
     changed to lecture1
   * There was no error
