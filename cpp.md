# C++ Glossar


## C

Low level programming language. Provides a mainly procedural programming style.

## C++

Programming language extended from [C](#C). Provides classes for object oriented programming

## comment

Used to describe what a particular code is or should be doing. A comment is made with [//](#//) or the [/*   */](#/*   */) syntax.

## compiler

A program that takes source and header files as input and creates an [object file](#object-file) also known as [machine code](#machine-code).
If something goes wrong during compile time a [compile-time-error](#compile-time-error) occurs.

## compile-time-error

An error that occures while compiling a [program](#program) and that is found by the [compiler](#compiler).

## declaration

Is a [program statement](#statement) specifying how a piece of code can be used.
It describes the actual implementation of a [definition](#definition).

## definition

Defines or implements a declaration.

## function

Callable piece of [code statements](#statement) which can be reused. A function consists of four parts:

- function name
- [return](#return) [type](#type)
- input/outpu argument list
- function body

## header

Contains [definitions](#definition) and has [.h](#h) as file name. The [decleration](#decleration) of the definitions is done in the [source file](#source) ending with [*.cpp](#cpp).

## library

A library is imply some code - usually written by others - that we access using [declerations](#decleration) found in an [#include](#include) file. Libraries contain a collection of functions and definitions (for example [#defines](#defines)). Libraries exist in different forms:

- Shared libraries
- Static libraries

## linker

A program that is used after calling the [compiler](#compiler) to link [object files](#object-file) or [translation units](#translation-units) which stem from [source code files](#source-code) and [libraries](#libraries).

## machine code

Code that a computer can understand and use to link a program into an [executable](#executable)

## object file

Object code files result from a [compiler](#compiler) invocation. These files contain the [machine code](#machine-code) which a computer understands but is not readable for humans. The object code files are given the suffix [.obj](#obj) (on Windows) or [.o](#o) (Unix). What the computer executes is called object file, [executable](#executable) or [machine code](#machine-code).

## program

A program usually consists of several seperate parts which can be a collection of header and source files including [libraries](#library).
These seperate parts are sometimes called [translation units](#translation-unit)

## source file

Refers to a source code file for example a [.cpp](#cpp) file that humans can read and create and is also known as [program](#program) text.

## statement

A line of code usually contained inside a [function](#function).

## translation unit

A unit that can be compiled by a [compiler](#compiler) to generate an [object file](#object-file)

## .cpp

File ending or suffix for a [source code file](#source-file) file.

## .h

File ending or suffix for a [header](#header) file.

## .o

File ending or suffix for [object files](#object-file) on Unix.

## .obj

File ending or suffix for [object files](#object-file) on Windows.

## #define


## #include

[Directive](#directive) to include another [header](#header) file which can be for example a [library](#library). #include directives are processed by the [preprocessor](#preprocessor) before compile time.

## //

Double slashes are used for [comments](#comment) which help the programmer to understand the code in a [header](#header) or [source](#source-file) file.

## /*   */

Is used for multiline [comments](#comment).

## <<

Commonly used as the left shift operator.
