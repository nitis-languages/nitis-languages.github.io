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
0x05|[`ret`](/runtime/bytecode/ret/)
0x06<br/>⋮<br/>0x1F|Unused
0x20<br/>⋮<br/>0x2D|[`push`](/runtime/bytecode/push/#push-literals)
0x2E|[`add`](/runtime/bytecode/add/)
0x2F|[`sub`](/runtime/bytecode/sub/)
0x30|[`div`](/runtime/bytecode/div/)
0x31|[`mul`](/runtime/bytecode/mul/)
0x32|[`rem`](/runtime/bytecode/rem/)
0x33|[`and`](/runtime/bytecode/and/)
0x34|[`or`](/runtime/bytecode/or/)
0x35|[`xor`](/runtime/bytecode/xor/)
0x36|[`neg`](/runtime/bytecode/neg/)
0x37|[`not`](/runtime/bytecode/not/)
0x38<br/>⋮<br/>0xFF|Unused