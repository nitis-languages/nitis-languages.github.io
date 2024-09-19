---
icon: material/code-braces
description: Hi
---
# Coding style

Consistent code style is good practice to keep code more readable across whole project, that makes it more readable and makes it easier to collaborate within a development team or contributors.

## Language guidelines
+ Prefer modern features and constructions than older ones
+ Use latest language version (whenever it possible)
+ Use language keywords for data types instead of them full name:
	+ `u32` but not `std::numerics::UInt32` nor `UInt32`

## Prefer *fast* boolean operators
+ Use fast `&&` and `||` boolean operators instead of `&` and `|` operators

## Style prefer
+ Use [K&R](https://en.wikipedia.org/wiki/Indentation_style#K&R) style for braces
+ Prefer tabulation than spaces
	+ If spaces is used: use 4 spaces for indentation
	+ Store prefered indentation style to `.editorconfig` file of your project
+ Do not make too long lines