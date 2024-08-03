# NLR vZero
NiTiS Languages' Runtime version Zero is the initial version containing all basic instructions and features, all following updates are based on this version.

## Instructions

Byte range|Instructions
:-:|---
0x00|[`nope`](/runtime/bytecode/nope/)
0x01|[`break`](/runtime/bytecode/break/)
0x02|[`push arg`](/runtime/bytecode/push/#push-argument)
0x03|[`push`](/runtime/bytecode/push/#push-local)
0x04|[`pop`](/runtime/bytecode/pop/)
0x05<br/>⋮<br/>0x1F|Unused
0x20<br/>⋮<br/>0x2D|[`push`](/runtime/bytecode/push/#push-literals)
0x2E<br/>⋮<br/>0xFF|Unused