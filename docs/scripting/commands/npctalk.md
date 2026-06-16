# `npctalk()`

!!! warning
	This page may contain outdated information, incompatible with the current version of Hercules and its coding standards.

## Syntax

```c
npctalk(<"message">);
```

!!! warning
	The rest of this document hasn't been converted to Markdown yet.

==Description==
This command will display a message to the surrounding area, as if the [NPC](../../basics/npc.md) running it, was a player talking, that is, the message, which is prefixed with NPC's display name appears above it's head and in the chat window.

==Examples==
 npctalk "Hello "+[[strcharinfo]](0)+", how are you?";
This will make everyone in the area see the NPC greet the character, who just invoked it.
