# System Boundaries

This project separates gameplay concerns into independent systems:

- Player State.
- Inventory.
- Crafting.
- Interaction.
- Progression.

Each system exposes clear inputs and outputs and avoids direct coupling
with narrative or environmental context.