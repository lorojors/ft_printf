# ft_printf

_This project has been created as part of the 42 curriculum by rolorenz._

## Description

In this project we create a library to implement a simpler version of the `printf()` function.

## Instructions
The code is written in c, so we need the `gcc` compiler as prerequisite.

1. Clone the repository with `git clone`
2. Once the repository is cloned, navigate inside the folder and use `Make` to compile the library for use.


## Resources

AI has been used to help with the testing of the different functions used.

For debugging various online forums have been used, mostly StackOverflow.

## Usage and arguments
Usage for this function is to print via all given strings and variables, on our implementation of this function said cases are as follow
|Argument| Description |
|--|--|
| %c | Used to print single characters |
| %s | Used to print strings |
| %p | Used to print void * pointer in hexadecimal format |
| %d | Used to print decimal number |
| %i | Used to print `int` in base 10 |
| %u | Used to print decimal number without sing |
| %x | Used to print hexadecimal number in lowercase|
| %X | Used to print hexadecimal number in uppercase|
| %% | Used to print `%` symbol |

**Examples of usage**
`ft_prinft("Hello World")` 
`ft_prinft("%d", var1)`
`ft_printf("%d %s %x", var1 var2 var3)`
