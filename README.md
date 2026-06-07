# System Design Notes

This repository contains architecture and design breakdowns for projects I've built.

The focus is not on implementation details or setup instructions, but on the decisions behind the systems: how state is modeled, how data flows through the application, and how different components interact.

## Case Studies

### Relay RPG
An event-driven Discord RPG built around persistent characters, turn-based progression, and server-authoritative game state.

Topics:
- Event-driven architecture
- State machines
- Command processing
- Persistence and data modeling

→ [Read the case study](./relay-rpg.md)

---

### Zen Garden
A server-backed application where users create and modify persistent garden layouts that are rendered as SVG.

Topics:
- State-driven rendering
- Relational data modeling
- Authentication and ownership
- Persistence and visualization

→ [Read the case study](./zen-garden.md)

---

## Why I Write These

When building projects, I'm often more interested in the underlying system than the user interface.

These notes document the architecture, data models, and design tradeoffs behind the applications I build. They're intended to capture how the systems work and why they were designed that way.

## Related Links

- Portfolio: https://scott-portfolio-azure.vercel.app
- GitHub Profile: https://github.com/swokamoto
