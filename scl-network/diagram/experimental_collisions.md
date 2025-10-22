# Experimental Collisions

**Related Diagrams:**  
- [Layered Rings](../diagrams/layered_rings.md)  
- [Recursive Evolution](../diagrams/recursive_evolution.md)  
- [Multi-Day Evolution](../diagrams/multi_day_evolution.md)  
- [Symbolic Network](../diagrams/symbolic_network.md)  
- [Full SCL Ecosystem](../diagrams/full_scl_ecosystem.md)  
- [Combined Overview](../diagrams/combined_overview.md)

**Related Simulations:**  
- [Experimental Collisions Simulation](../simulation/experimental_collisions.md)

---

## ⚡ Experimental Collisions of SCLs

This diagram shows **what happens when unconventional or “outside-the-box” SCLs interact** with established loops.  
It illustrates ripple effects, unexpected emergent symbols, and recursive feedback.

```mermaid
graph TD
    %% === TITLE ===
    A[Experimental Collisions of SCLs]:::title

    %% === ESTABLISHED SCLs ===
    subgraph Established[Core & Secondary SCLs]
        C1[Creation 🌱]:::creation
        C2[Effort / Adaptation ⚙️]:::effort
        C3[Reflection 💭]:::reflection
        C4[Influence 🌊]:::influence
        S1[Imagination 💡]:::secondary
        S2[Interpretation 🧩]:::secondary
        C1 --> C2 --> C3 --> C4 --> S1 --> S2
    end

    %% === EXPERIMENTAL INPUTS ===
    subgraph Experimental[Outside-the-Box Inputs]
        E1[Random Concept 🎲]:::experimental
        E2[Novel Symbol ✨]:::experimental
        E1 --> E2
    end

    %% === COLLISIONS ===
    E2 --> C3
    E1 --> S2
    C4 --> E2
    S1 --> E1

    %% === STYLE CLASSES ===
    classDef title fill:#222,color:#fff,stroke:#555,stroke-width:2px,font-size:18px,font-weight:bold;
    classDef creation fill:#1abc9c,color:#fff,stroke:#0e7c66,stroke-width:2px;
    classDef effort fill:#3498db,color:#fff,stroke:#1b5e91,stroke-width:2px;
    classDef reflection fill:#9b59b6,color:#fff,stroke:#5e3378,stroke-width:2px;
    classDef influence fill:#f1c40f,color:#000,stroke:#b38f00,stroke-width:2px;
    classDef secondary fill:#f39c12,color:#000,stroke:#b36d00,stroke-width:2px;
    classDef experimental fill:#8e44ad,color:#fff,stroke:#5e1f7c,stroke-width:2px;
