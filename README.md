# GET NEXT LINE

The aim of this project is to code a function that returns a line ending with a newline, read from a file descriptor.

The biggest challenge of this project is to make it work with any given BUFFER_SIZE defined during compilation time with the  -D flag.

## How to use it

Both the normal and bonus functions work the same, so it doesn't matter if you compile the _bonus.c functions or .c functions.

_bonus.c have to be included for project validation otherwise you will not be graded for them.

You will need to have your own main function which calls the get_next_line function in a loop until it reads the whole file.

Example of a compilation command
```
gcc-Wall -Wextra -Werror -D BUFFER_SIZE=32 main.c get_next_line.c get_next_line_utils.c
```

## Notes to 42 students

When sending the project for correction you must not have a main function, you should have your own main only for testing.

Moulinette will have its own main function that calls your GNL function in a loop.

## Contact

For any questions regarding my project email me at: Nuno_c11@hotmail.com

Or if you are a 42student my slack username is: ngregori
