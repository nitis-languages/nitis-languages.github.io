---
icon: material/cog-box
---
# `push` instructions
Push instructions are pushing values onto stack for future using

## Push arguments

Property|Value
--:|---
Code|`0x02`
Assembly|`push arg <name: literal>`<br/>`push arg <index: u16>`
Description|Push argument value onto stack
Size|3

Property|Value
--:|---
Code|`0x03`
Assembly|`push &arg <name: literal>`<br/>`push &arg <index: u16>`
Description|Push argument reference onto stack
Size|3

## Push locals

Property|Value
--:|---
Code|`0x05`
Assembly|`push local <name: literal>`<br/>`push local <index: u16>`
Description|Push local variable value onto stack
Size|3

Property|Value
--:|---
Code|`0x06`
Assembly|`push &local <name: literal>`<br/>`push &local <index: u16>`
Description|Push local variable reference onto stack
Size|3

## Push numerics

=== "i8"

	Property|Value
	--:|---
	Code|`0x10`
	Assembly|`push <value: i8>`
	Description|Push 8-bit integer onto stack
	Size|2

=== "i16"

	Property|Value
	--:|---
	Code|`0x11`
	Assembly|`push <value: i16>`
	Description|Push 16-bit integer onto stack
	Size|3

=== "i32"

	Property|Value
	--:|---
	Code|`0x12`
	Assembly|`push <value: i32>`
	Description|Push 32-bit integer onto stack
	Size|5

=== "i64"

	Property|Value
	--:|---
	Code|`0x13`
	Assembly|`push <value: i64>`
	Description|Push 64-bit integer onto stack
	Size|9

=== "u8"

	Property|Value
	--:|---
	Code|`0x14`
	Assembly|`push <value: u8>`
	Description|Push 8-bit unsigned integer onto stack
	Size|2

=== "u16"

	Property|Value
	--:|---
	Code|`0x15`
	Assembly|`push <value: u16>`
	Description|Push 16-bit unsigned integer onto stack
	Size|3

=== "u32"

	Property|Value
	--:|---
	Code|`0x16`
	Assembly|`push <value: u32>`
	Description|Push 32-bit unsigned integer onto stack
	Size|5

=== "u64"

	Property|Value
	--:|---
	Code|`0x17`
	Assembly|`push <value: u64>`
	Description|Push 64-bit unsigned integer onto stack
	Size|9

=== "f32"

	Property|Value
	--:|---
	Code|`0x18`
	Assembly|`push <value: f32>`
	Description|Push float integer onto stack
	Size|5

=== "f64"

	Property|Value
	--:|---
	Code|`0x19`
	Assembly|`push <value: f64>`
	Description|Push double float integer onto stack
	Size|9

## Push null

Property|Value
--:|---
Code|`0x1B`
Assembly|`push null`
Description|Push null onto stack
Size|1