# System Boundaries

This project separates gameplay concerns into independent, loosely coupled systems:

- Player State: core player attributes, skills, and non-lethal capabilities.

- Resource Collection: gathering of natural resources and recoverable materials, independent of location or narrative.

- Inventory: temporary storage and management of collected resources, subject to system constraints.

- Crafting & Transformation: conversion of resources into tools, equipment, or usable items.

- Work & Objectives: structured daily tasks, quotas, and progression requirements that drive the core gameplay loop.

- Progression: long-term player growth driven by completed objectives and system interactions.

Each system exposes clear inputs and outputs and avoids direct coupling with narrative, biome-specific logic, or environmental storytelling.