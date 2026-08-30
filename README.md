# Architectural Isometric Diorama

A reusable image-generation Skill for turning travel, architecture, landmark, city, plaza, waterfront and landscape photographs into **strict orthographic isometric architectural diorama posters**.

## Visual language

- Strict orthographic / axonometric projection
- No perspective convergence or vanishing points
- Reference-faithful architectural reconstruction
- Selective scene simplification
- Physical miniature-model materials
- Thin architectural cut-out base
- Source-derived colors and atmosphere
- Warm ivory editorial background
- Restrained Japanese architecture-magazine typography
- Optional issue number, place and coordinates

## Usage

Provide a reference image and, when available, the location name. Ask the model to use the `Architectural-Isometric-Diorama` Skill.

Example:

> Use Architectural-Isometric-Diorama on this photo. Location: Yokohama Red Brick Warehouse, Japan.

The detailed generation workflow, prompt template, negative constraints and quality checks are in [`SKILL.md`](./SKILL.md).

## Design priority

**Structural fidelity > orthographic geometry > recognizable details > atmosphere > decoration.**

The goal is not a cute miniature. The goal is a collectible architectural archive plate that clearly corresponds to the supplied photograph.
