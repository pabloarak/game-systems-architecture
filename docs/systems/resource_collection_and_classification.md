# Resource Collection & Classification System

## 1. Purpose

This system defines how the player interacts with waste and natural materials in the world, transforming them into classified resources that feed other systems such as crafting, environmental restoration, economy, and progression.

The system reinforces the game's biocentric, non-lethal, and purpose-driven philosophy.

## 2. Player Interaction

- Player collects waste and natural materials from the environment.
- Each object has a category, condition, and potential use.
- Objects must be classified correctly to unlock their full systemic value.
- A portion of classified materials must be delivered to fulfill assigned work quotas.

## 3. Resource Types (Abstract)

- Organic.
- Recyclable.
- Hazardous.
- Reusable.
- Natural (wood, stone, plants).

## 4. Classification Rules

- Correct classification yields full value and eligibility for quota delivery.
- Incorrect classification yields reduced value or rejection.
- Some materials require tools, skills, or facilities to classify properly.
- Certain materials cannot be retained until minimum quota requirements are met.

## 5. Work Quotas & Constraints

- Each work assignment defines required quantities per resource category.
- Quotas must be met before the end of the work period (e.g. day).
- Failing to meet quotas impacts income, reputation, or world state.
- Excess classified resources may be retained for personal use or crafting.

## 6. System Constraints

- Inventory capacity limits how much can be carried.
- Classification consumes time and/or energy.
- Environmental conditions may restrict available actions.
- Transportation points (e.g. trucks) define delivery boundaries.

## 7. Outputs & Dependencies

Outputs:

- Delivered resources (quota fulfillment)
- Retained resources
- Currency
- Player experience or reputation

Dependencies:

- Inventory System
- Economy / Quota System
- Crafting System
- Progression System

## 8. Extensibility Notes

- New resource categories can be added without modifying core logic.
- Quota rules can vary by biome or assignment.
- Environmental conditions may affect classification outcomes.
- Systems consuming resources do not assume ownership of all collected items.