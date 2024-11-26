The first thing that's different from C++ is the existence of format specifiers, which specify where in the output to palce numbers.
These are marked with the percent (%) character.

To compile I need to use the following command:

clang -std=c2x -Wall -lm -o getting-started getting-started.c

*EXPLANATION OF ALL OF THOSE FLAGS*

-std=c2x: tells the compiler to use the latest version of C (C23)
-Wall: enters the complete diagnostic mode
-lm: links to the c mathlibrary --> it looks like the linker that my machine uses is ld 
-o: specifies where to put the output

debugging bad.c was pretty fun... wasn't hard at all but it was fun to go through the compiler's errors one by one until it was all fixed :)
The main difference though, between bad and getting-started is how they assign values to the indexes of the array. Bad just assigns them in order,
leaving the last element empty, whereas getting-started assigns each index manually.
