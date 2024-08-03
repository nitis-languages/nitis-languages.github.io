# `push` instructions
Push instructions are pushing values onto stack for future using

## Push argument

Property|Value
--:|---
Code|`0x02`
Assembly|`push arg <name: literal>`<br/>`push arg <index: u16>`
Description|Push argument value onto stack
Size|3

## Push local
Property|Value
--:|---
Code|`0x03`
Assembly|`push <name: literal>`<br/>`push <index: u16>`
Description|Push local variable value onto stack
Size|3

## Push literals

=== "i8"

	Property|Value
	--:|---
	Code|`0x20`
	Assembly|`push <value: i8>`
	Description|Push 8-bit integer onto stack
	Size|2

=== "i16"

	Property|Value
	--:|---
	Code|`0x21`
	Assembly|`push <value: i16>`
	Description|Push 16-bit integer onto stack
	Size|3

=== "i32"

	Property|Value
	--:|---
	Code|`0x22`
	Assembly|`push <value: i32>`
	Description|Push 32-bit integer onto stack
	Size|5

=== "i64"

	Property|Value
	--:|---
	Code|`0x23`
	Assembly|`push <value: i64>`
	Description|Push 64-bit integer onto stack
	Size|9

=== "u8"

	Property|Value
	--:|---
	Code|`0x25`
	Description|Push 8-bit unsigned integer onto stack
	Assembly|`push <value: u8>`
	Size|2

=== "u16"

	Property|Value
	--:|---
	Code|`0x26`
	Assembly|`push <value: u16>`
	Description|Push 16-bit unsigned integer onto stack
	Size|3

=== "u32"

	Property|Value
	--:|---
	Code|`0x27`
	Assembly|`push <value: u32>`
	Description|Push 32-bit unsigned integer onto stack
	Size|5

=== "u64"

	Property|Value
	--:|---
	Code|`0x28`
	Assembly|`push <value: u64>`
	Description|Push 64-bit unsigned integer onto stack
	Size|9

=== "f32"

	Property|Value
	--:|---
	Code|`0x2B`
	Assembly|`push <value: f32>`
	Description|Push float integer onto stack
	Size|5

=== "f64"

	Property|Value
	--:|---
	Code|`0x2C`
	Assembly|`push <value: f64>`
	Description|Push double float integer onto stack
	Size|9