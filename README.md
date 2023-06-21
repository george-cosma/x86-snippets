# x86-snippets README

A handfuld of code snippets for intel x86 32-bit assembly for use with NASM. It's not much, but I use these handful of times, and I thought the world at large might enjoy using them too, if for whatever reason you are programming in assembly (and 32-bit at that!).  

For any bugs or feature requests, you can write an issue in the [project's repository](https://github.com/george-cosma/x86-snippets/issues).

Enjoy \\^o^/ !

## Features

Here's a comprehensive list of all snippets:
- Loops from 0 to n-1
  - `loop`, or `do-while`
  - `while`, or `for`
- Loops from n to 1 
  - `rev-loop`, or `rev-do-while`
  - `rev-while`, or `rev-for`
- Structs
  - `struct`, or `define-struct` (this creates the definition of a struct)
  - `field`, or `define-field` (this creates the definition of a struct field)
  - `init-struct`, or `instantiate-struct`
  - `init-field`, or `instantiate-field`
- Code structure
  - `section` (insert section header)
  - `ln` (define the length of an array)
  - `main` (define the main function)
  - `func` (define a function)
- Misc Macros
  - `helpers`, or `helper-macros` 