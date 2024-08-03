# `push` instructions
Push instructions are pushing values onto stack for future using

## Push argument

Property|Value
---|---
Alias|`push arg`
Description|Push argument value onto stack
Code|`0x02`
Usage|`push arg <index: u16>`<br/>`push arg <name: literal>`
Size|3

## Push local
Property|Value
---|---
Alias|`push`
Description|Push local variable value onto stack
Code|`0x03`
Usage|`push <index: u16>`<br/>`push <name>`
Size|3



## Push literals

=== "i8"

	Property|Value
	---|---
	Alias|`push`
	Description|Push 8-bit integer onto stack
	Code|`0x20`
	Usage|`push i8 <value: i8>`
	Size|2

=== "i16"

	Property|Value
	---|---
	Alias|`push`
	Description|Push 16-bit integer onto stack
	Code|`0x21`
	Usage|`push i16 <value: i16>`
	Size|3

=== "i32"

	Property|Value
	---|---
	Alias|`push`
	Description|Push 32-bit integer onto stack
	Code|`0x22`
	Usage|`push i32 <value: i32>`
	Size|5

=== "i64"

	Property|Value
	---|---
	Alias|`push`
	Description|Push 64-bit integer onto stack
	Code|`0x23`
	Usage|`push i64 <value: i64>`
	Size|9

=== "u8"

	Property|Value
	---|---
	Alias|`push`
	Description|Push 8-bit unsigned integer onto stack
	Code|`0x25`
	Usage|`push u8 <value: u8>`
	Size|2

=== "u16"

	Property|Value
	---|---
	Alias|`push`
	Description|Push 16-bit unsigned integer onto stack
	Code|`0x26`
	Usage|`push u16 <value: u16>`
	Size|3

=== "u32"

	Property|Value
	---|---
	Alias|`push`
	Description|Push 32-bit unsigned integer onto stack
	Code|`0x27`
	Usage|`push u32 <value: u32>`
	Size|5

=== "u64"

	Property|Value
	---|---
	Alias|`push`
	Description|Push 64-bit unsigned integer onto stack
	Code|`0x28`
	Usage|`push u64 <value: u64>`
	Size|9

=== "f32"

	Property|Value
	---|---
	Alias|`push`
	Description|Push float integer onto stack
	Code|`0x2B`
	Usage|`push <value: f32>`
	Size|5

=== "f64"

	Property|Value
	---|---
	Alias|`push`
	Description|Push double float integer onto stack
	Code|`0x2C`
	Usage|`push <value: f64>`
	Size|9