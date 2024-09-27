---
icon: material/key
description: Member accessibility levels.
---
# Accessibility levels

Access modifier|Description
-:|:-
[`public`]()|Access isn't restricted.
[`friend`]()|Access is limited to the current library or types derived from the containing type.
[`protected`]()|Access is limited to container or types derived from containing type.
[`internal`]()|Access is limited to the current library.
[`family`]()|Access is limited to the container or types derived from the containing type within the current library.
[`private`]()|Access is limited to the container.

Member always can be accessed from the same container scope. This cannot be changed.

If no access modifier is presented in a member declaration, `private` modifier is used.

!!! warning
	Modifiers `protected`, `friend`, `family` are not valid on members inside modules or [sealed](inheritance.md#type-sealing) types.