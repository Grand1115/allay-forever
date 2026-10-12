# allay-forever

Allay Forever is a Minecraft datapack that prevents Allays from forgetting their linked note blocks.

## Downloads

Available on Modrinth.

## Bug Reports

If you encounter a bug, please create a new issue and include:

- Minecraft version
- Datapack version
- Steps to reproduce
- Screenshots (if possible)

## Current Known Issue

### Bug #001 - Allays stop responding to note block activations

Status: Investigating

Observed behaviour:
- Allay remains linked to the note block
- Memory remains present
- Allay eventually becomes idle or unresponsive
- Note block waves can reach the Allay without triggering a response

Current investigation suggests the issue may be related to the note block memory refresh logic.
