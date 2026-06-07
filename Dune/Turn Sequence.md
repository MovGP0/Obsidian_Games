---
title: Dune Imperium Turn Sequence
tags:
  - Dune-Imperium
  - board-games
---
# Turn Sequence

```mermaid
flowchart TD
    A[Round Start: reveal Conflict and draw 5 cards] --> B[Player Turns]
    B --> C{Agent turn or Reveal turn?}
    C -->|Agent turn| D[Play one card for icons and send an agent]
    D --> B
    C -->|Reveal turn| E[Reveal remaining hand for persuasion, combat, and effects]
    E --> F[Combat]
    F --> G[Makers]
    G --> H[Recall]
```

The important strategic consequence is that you usually stop taking agent turns only when your remaining cards are more valuable as reveal than as board access.

Taking a Reveal turn early can be correct, but only if the reveal creates more value than the lost agent action.
