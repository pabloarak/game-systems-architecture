# Resource Collection & Classification System

## 1. Purpose

This system defines how the player interacts with waste materials in the world,
transforming them into classified resources used by other systems such as crafting,
environmental restoration, and progression.

The system reinforces the game's biocentric and non-lethal philosophy.

## 2. Player Interaction

- Player collects waste objects from the environment.
- Each object has a category and condition.
- Objects must be classified correctly to unlock their full value.

## 3. Resource Types (Abstract)

- Organic
- Recyclable
- Hazardous
- Reusable

## 4. Classification Rules

- Correct classification yields full resource value.
- Incorrect classification yields reduced or neutral value.
- Some materials require tools or skills to classify.

## 5. System Constraints

- Inventory capacity limits how much can be carried.
- Classification may require time or energy.
- Certain environments restrict available actions.

## 6. Outputs & Dependencies

Outputs:

- Classified resources
- Player experience or reputation

Dependencies:

- Inventory System
- Crafting System
- Progression System

## 7. Extensibility Notes

- New resource categories can be added without modifying core logic.
- Classification difficulty can scale with game progression.
- Environmental conditions may affect classification outcomes.