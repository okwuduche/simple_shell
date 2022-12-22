
<h1 align="center"> A Simple shell program built by Chinweike and Aisha

----------------------------------------------------------

<h2> General Highlights </h2>

This program is designed to run as specified by ALX Africa.
The only difference is when you print an error, the name of the program must be equivalent to your argv[0].
```commandline
$ echo "qwerty" | /bin/sh
/bin/sh: 1: qwerty: not found
$ echo "qwerty" | /bin/../bin/sh
/bin/../bin/sh: 1: qwerty: not found
$
```

```commandline
$ echo "qwerty" | ./hsh
./hsh: 1: qwerty: not found
$ echo "qwerty" | ./././hsh
./././hsh: 1: qwerty: not found
$
```

---------------------------------------------------------

<h2> List of allowed functions and system calls </h2>
- access (man 2 access)
- chdir (man 2 chdir)
- close (man 2 close)
- closedir (man 3 closedir)
- execve (man 2 execve)
- exit (man 3 exit)
- _exit (man 2 _exit)
- fflush (man 3 fflush)
- fork (man 2 fork)
- free (man 3 free)
- getcwd (man 3 getcwd)
- getline (man 3 getline)
- getpid (man 2 getpid)
- isatty (man 3 isatty)
- kill (man 2 kill)
- malloc (man 3 malloc)
- open (man 2 open)
- opendir (man 3 opendir)
- perror (man 3 perror)
- read (man 2 read)
- readdir (man 3 readdir)
- signal (man 2 signal)
- stat (__xstat) (man 2 stat)
- lstat (__lxstat) (man 2 lstat)
- fstat (man 2 fstat)
- strtok (man 3 strtok)
- wait (man 2 wait)
- waitpid (man 2 waitpid)
- wait3 (man 2 wait3)
- wait4 (man 2 wait4)
- write (man 2 write)

---------------------------------------------------------

<h2> Compilation </h2>
To compile this code, run the below code in your
```commandline
 $ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
```

alternatively, you can run this program by running the compilation script. (this runs with the valgrind memcheck tool, please install that before running this script)
```commandline
 $ ./compile.sh
```

--------------------------------------------------------------------------------

<h2> Libraries :scroll: </h2>

-> [shell.h](shell.h)
-> errno.h
-> fcntl.h
-> limits.h
-> signal.h
-> stddef.h
-> stdio.h
-> stdlib.h
-> string.h
-> sys/stat.h
-> sys/types.h
-> sys/wait.h
-> unistd.h

--------------------------------------------------------------------------------

<h2> Contributors </h2>



<a href="https://github.com/okwuduche"><b>okwuduche</b></sub></a>

<a href="https://github.com/Asheklm6"><b>Asheklm6</b></sub></a>


--------------------------------------------------------------------------------
