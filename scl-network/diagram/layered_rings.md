# Layered Rings of SCL Flow

**Related Diagrams:**  
- [Recursive Evolution](../diagrams/recursive_evolution.md)  
- [Multi-Day Evolution](../diagrams/multi_day_evolution.md)  
- [Symbolic Network](../diagrams/symbolic_network.md)  
- [Full SCL Ecosystem](../diagrams/full_scl_ecosystem.md)  
- [Combined Overview](../diagrams/combined_overview.md)

**Related Simulations:**  
- [Experimental Collisions](../simulations/experimental_collisions.md)

---

## 🌀 Layered Rings of SCL Flow

This diagram shows **how SCLs are structured in concentric “rings”**, representing the flow of symbolic creation, adaptation, reflection, and influence.  
It visualizes both **internal loops** and **outward propagation**.

```mermaid
graph TD
    %% === TITLE ===
    A[Layered Rings of SCL Flow]:::title

    %% === INNER RING ===
    subgraph Inner[Core Creation Loop]
        C1[Creation 🌱]:::creation
        C2[Effort / Adaptation ⚙️]:::effort
        C3[Reflection 💭]:::reflection
        C4[Influence 🌊]:::influence
        C1 --> C2 --> C3 --> C4 --> C1
    end

    %% === MIDDLE RING ===
    subgraph Middle[Secondary Loops]
        S1[Imagination 💡]:::secondary
        S2[Interpretation 🧩]:::secondary
        S3[Application 🔧]:::secondary
        S4[Communication 📡]:::secondary
        S1 --> S2 --> S3 --> S4 --> S1
    end

    %% === OUTER RING ===
    subgraph Outer[Meta / Recursive Loops]
        M1[Integration 🔄]:::meta
        M2[Meta-Reflection 🪞]:::meta
        M3[Symbolic Rebirth ✴️]:::meta
        M1 --> M2 --> M3 --> M1
    end

    %% === INTER-RING CONNECTIONS ===
    C4 --> S1
    S4 --> M1
    M3 --> C1
    C2 --> S3
    S2 --> M2
    M2 --> C3

    %% === STYLE CLASSES ===
    classDef title fill:#222,color:#fff,stroke:#555,stroke-width:2px,font-size:18px,font-weight:bold;
    classDef creation fill:#1abc9c,color:#fff,stroke:#0e7c66,stroke-width:2px;
    classDef effort fill:#3498db,color:#fff,stroke:#1b5e91,stroke-width:2px;
    classDef reflection fill:#9b59b6,color:#fff,stroke:#5e3378,stroke-width:2px;
    classDef influence fill:#f1c40f,color:#000,stroke:#b38f00,stroke-width:2px;
    classDef secondary fill:#f39c12,color:#000,stroke:#b36d00,stroke-width:2px;
    classDef meta fill:#e74c3c,color:#fff,stroke:#8b1e15,stroke-width:2px;
