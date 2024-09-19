---
icon: material/code-braces
description: Hi
---
# Coding style

Consistent code style is good practice to keep code more readable across whole project, that makes it more readable and makes it easier to collaborate within a development team or contributors.

## Language guidelines
+ Prefer modern features and constructions than older ones.
+ Use latest language version (whenever it possible).
+ Use language keywords for data types instead of them full name:
	+ `u32` but not `std::numerics::UInt32` nor `UInt32`.

## Prefer *fast* boolean operators
+ Use fast `&&` and `||` boolean operators instead of `&` and `|` operators.

## Style prefer
+ Use [K&R](https://en.wikipedia.org/wiki/Indentation_style#K&R) style for braces.
+ Prefer tabulation than spaces.
	+ If spaces is used: use 4 spaces for indentation.
	+ Store prefered indentation style to `.editorconfig` file of your project. ([see example](https://github.com/nitis-languages/example-projects/blob/main/.editorconfig#L7-L12))
+ Do not make too long lines.

## Use directive order
+ Sort `use` statements from less nested to most.
=== "Prefer"

	```nite
	use std;
	use std::numerics;
	use other_lib;
	use other_lib::extra;
	use other_lib::extra::download;
	use other_lib::extra::import;
	```
=== "Do not prefer"

	```nite
	use std::numerics;
	use std;
	use other_lib::extra::download;
	use other_lib::extra::import;
	use other_lib::extra;
	use other_lib;
	```
+ Don't interrupt using sequence.
=== "Prefer"

	```nite
	use other_lib;
	use other_lib::extra::download;
	use other_lib::extra::import;
	use other_lib::extra;
	use other_lib::modern;
	```
=== "Do not prefer"

	```nite
	use other_lib;
	use other_lib::extra::download;
	use other_lib::modern;
	use other_lib::extra::import;
	use other_lib::extra;
	```

## Place module after use statements
Highly recommended to place module declaration right after use statements with one empty line before the declaration.

=== "Prefer"
	```nite
	use std;

	module sigma_lib;

	...
	```
=== "Do not prefer"
	```nite
	module sigma_lib;
	
	use std;

	...
	```

## Comments style
+ Use single-line comments (`//`) for brief explanations.
+ Place comments before the explanation part, not at the end of the line.
+ Begin comment with uppercase letter.
+ Insert one space between `//` and the comment text.