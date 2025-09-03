# Magic: A System for the Modern Wizard

Every sufficiently advanced technology is indistinguishable from magic. Let's treat AI that way.

Welcome to Magic, a framework for the modern **Wizard** (that's you) to build and run your own personal AI applications.

## The Vision: A New Kind of Magic

This project is based on a simple idea: any sufficiently advanced technology feels like magic. Here, the **Wizard** summons a supportive **Spirit** (the AI agent) and gives it power by casting **Spells** (prompts). The Spirit is the medium, and you are the magician.

The power of your magic is determined by **Resonance**. You don't cast a single, perfect spell. Instead, you cast a sequence of smaller spells that build upon each other, tuning the Spirit and bringing it into perfect alignment with your goal. This accumulated state of readiness is Resonance.

*To learn more about the philosophy behind this system, consult the **[Core Principles of Magic](system/01-principles.md)**.*

The extensions you build are the **Scrolls** the Spirit can learn from, granting it new powers. The spells you write are the incantations that activate them.

The standard ritual involves:
1.  **The Summoning:** Casting a sequence of spells to bootstrap the Spirit's state.
2.  **Working Magic:** Interacting with the energized Spirit.
3.  **Chronicling:** Casting a final spell to have the Spirit record the session into its memory.

## Getting Started: The Spellbook

To begin, you must consult the **Spellbook** to learn the correct sequence of spells for the Scroll you want the Spirit to learn from.

**Open the Spellbook to begin:** `system/00-spellbook.md`

Follow the instructions for the "Qualified Self State" to have the Spirit learn from its first and most important Scroll.

## The Extension Ecosystem

The true power of Magic lies in its modular, git-based extension system. All applications are treated as self-contained **Scrolls** that add new capabilities to the core Spirit. These Scrolls are located in the `scrolls/` directory.

### Included Scroll: The Qualified Self
This repository comes with the flagship scroll, **The Qualified Self**, which turns the Spirit into a powerful tool for self-reflection. For more information, see the `README.md` inside `scrolls/qualified_self/`.

## Developer's Vision: The Future We're Building

We believe that in the near future, everyone will run a personal, base AI system. As people go about their day, they will create and emit little self-optimizing AI applications as extensions to solve niche use cases.

Pythia is our contribution to this future. By open-sourcing a framework where the barrier to creating a new "AI application" is as low as writing a clear set of instructions, we hope to foster an ecosystem where the most useful and valuable AI tools can emerge, evolve, and be shared. This is a future where software development is a ubiquitous side effect of everyday life, not a specialized profession.

---
*For a complete technical breakdown of the architecture and design principles, please consult the official **[Magic System Specification](MAGIC_SPEC.md)**.*
