# libft

This project is a library of useful C functions that I have implemented from scratch for use in future projects. The functions are designed to be efficient, reusable, and follow the standard C library conventions.

## Getting Started

### Prerequisites

To use this library, you need to have a C compiler installed on your system. I have tested this library on macOS and Linux systems.

### Installing

To install this library, simply clone the repository to your local machine:

git clone https://github.com/seozkan/libft.git

Then, compile the library using the provided Makefile:

make

This will generate a static library file called `libft.a` in the root directory.

## Usage

To use the functions in this library, include the `libft.h` header file in your C source code:

```c
#include "libft.h"
Then, link your program with the libft.a static library file:

gcc -Wall -Werror -Wextra -L. -lft your_program.c -o your_program
Now you can use any of the functions in the library in your C source code.

Contributing
If you find a bug or have a suggestion for a new function, feel free to open an issue or submit a pull request.
```
## Test Result
#### Mandatory Part
![alt text](https://github.com/seozkan/libft/blob/master/test_result/mandatory.png)
#### Bonus Part
![alt text](https://github.com/seozkan/libft/blob/master/test_result/bonus.png)
