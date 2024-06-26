# `push` instruction

Property|Value
---|---
Alias|`push`
Description|Push local variable value onto stack
Introduced in|
Code|`0x03`
Signature|`push <index: u16>`<br/>`push <name>`
Size|3

## Push argument

Property|Value
---|---
Alias|`push arg`
Description|Push argument value onto stack
Introduced in|
Code|`0x02`
Signature|`push arg <index: u16>`<br/>`push arg <name>`
Size|3

## Push literals

=== "i8"

	Property|Value
	---|---
	Alias|`push i8`
	Description|Push 8-bit integer onto stack
	Introduced in|
	Code|`0x20`
	Signature|`push i8 <value: i8>`
	Size|2

=== "i16"

	Property|Value
	---|---
	Alias|`push i16`
	Description|Push 16-bit integer onto stack
	Introduced in|
	Code|`0x21`
	Signature|`push i16 <value: i16>`
	Size|3

=== "i32"

	Property|Value
	---|---
	Alias|`push i32`
	Description|Push 32-bit integer onto stack
	Introduced in|
	Code|`0x22`
	Signature|`push i32 <value: i32>`
	Size|5

=== "i64"

	Property|Value
	---|---
	Alias|`push i64`
	Description|Push 64-bit integer onto stack
	Introduced in|
	Code|`0x23`
	Signature|`push i64 <value: i64>`
	Size|9

=== "u8"

	Property|Value
	---|---
	Alias|`push u8`
	Description|Push 8-bit unsigned integer onto stack
	Introduced in|
	Code|`0x25`
	Signature|`push u8 <value: u8>`
	Size|2

=== "u16"

	Property|Value
	---|---
	Alias|`push u16`
	Description|Push 16-bit unsigned integer onto stack
	Introduced in|
	Code|`0x26`
	Signature|`push u16 <value: u16>`
	Size|3

=== "u32"

	Property|Value
	---|---
	Alias|`push u32`
	Description|Push 32-bit unsigned integer onto stack
	Introduced in|
	Code|`0x27`
	Signature|`push u32 <value: u32>`
	Size|5

=== "u64"

	Property|Value
	---|---
	Alias|`push i64`
	Description|Push 64-bit unsigned integer onto stack
	Introduced in|
	Code|`0x28`
	Signature|`push u64 <value: u64>`
	Size|9

=== "f16"

	???+ danger
		
		This instruction may be removed in future!<br/>
		May be not...

	Property|Value
	---|---
	Alias|`push f16`
	Description|Push half-size float integer onto stack
	Introduced in|
	Code|`0x2A`
	Signature|`push f16 <value: f16>`
	Size|3

=== "f32"

	Property|Value
	---|---
	Alias|`push f32`
	Description|Push float integer onto stack
	Introduced in|
	Code|`0x2B`
	Signature|`push f32 <value: f32>`
	Size|5

=== "f64"

	Property|Value
	---|---
	Alias|`push f64`
	Description|Push double float integer onto stack
	Introduced in|
	Code|`0x2C`
	Signature|`push f64 <value: f64>`
	Size|9