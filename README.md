<h2>In this first project of the 42 path, you learn to create for the first time a library of useful functions for subsequent 42 projects.</h2>

<h1>What is a library?</h1>

- A library is a sort of “toolbox” for programmers. In the specific case of programming, our tools are represented by the functions that are created within our library. Each function generally carries out a series of operations that are performed in order to solve a certain task (example: a function that reverses the characters of a word... HELLO -> OLLEH)

- In this project the objective is to recreate a series of very useful and recurring functions for the creation of many programs. These functions are also found in some typical, widely used standard libraries such as the 'string' or 'stdlib' library. A spontaneous question arises here. What's the point of recreating a library of already existing functions when you could simply use the ones already made?

- The reason is actually simple: everything is done for educational purposes, it allows us to immediately develop problem solving skills and we are immediately accustomed to the idea of learning to create our own functions and then customize the tools to our liking that we build and have on hand for future projects. (at 42 you will reuse and expand the functionality of your libft over time)

<h1>Makefile: what is it for?</h1>

- The makefile is a file that contains a series of instructions and directives created for the purpose of speeding up and optimizing the process of compiling our project files.

- For example, consider the case in which our project contains hundreds of files. You could easily rewrite the compilation instructions for each individual file by hand every time, but this would make the process very time consuming and tedious.

- This is one of the fundamental reasons why a makefile is used. With each change to the code I basically call up my makefile with the 'make' command and automatically my project files are compiled and our executable program is created (or in the case of libft an executable is not created, but rather a library that it's different). There are also numerous other advantages in using makefiles (some of which I am not yet aware of) which I do not intend to delve into now because it would be too long to explain and perhaps not understandable for beginners.


<h1>Knowledge that is learned and developed in this project</h1>

- Creation of a makefile
- Creation of library functions
- Ability to use pointers (the most difficult topic in C in imo which requires time and practice in the code to be understood better)
- Creation and manipulation of lists (Bonus)
