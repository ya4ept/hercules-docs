# `openstorage()`

!!! warning
	This page may contain outdated information, incompatible with the current version of Hercules and its coding standards.

## Syntax

```c
openstorage();
```

!!! warning
	The rest of this document hasn't been converted to Markdown yet.

== Description ==
This will open the character's [[Kafra]] storage window on the client connected to the invoking character. It can be used from any kind of [NPC](../../basics/npc.md) or [[item script]], not just limited to Kafra Staff.

The storage window opens regardless of whether there are open NPC dialogs or not, but it is preferred to close the dialog before displaying the storage window, to avoid any disruption when both windows overlap.

== Examples ==
 [[mes]] "I will now open your stash for you";
 [[close2]];
 [[openstorage]];
 [[end]];
