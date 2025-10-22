# Layered Rings

**Purpose:**  
Visualizes core SCLs as circulating loops with outward ripples producing emergent SCLs.

**Related Diagrams:**  
- [Recursive Evolution](recursive_evolution.md)  
- [Multi-Day Evolution](multi_day_evolution.md)  
- [Symbolic Network](symbolic_network.md)  

---

## 🌐 Layered Rings Diagram

```mermaid
graph TD
    %% === TITLE ===
    A[Layered Rings: Core SCL Circulation]:::title

    %% === CORE SCLS ===
    subgraph Core[Core Loops]
        C1[Creation 🌱]:::creation
        C2[Effort/Adaptation ⚙️]:::effort
        C3[Reflection 💭]:::reflection
        C4[Influence 🌊]:::influence
        C1 --> C2 --> C3 --> C4 --> C1
    end

    %% === OUTWARD RIPPLE ===
    subgraph Ripple[Emergent SCLs]
        E1[Secondary Symbol: Clarion]:::emergent
        E2[Secondary Symbol: Stratus]:::emergent
        E3[Secondary Symbol: Harmonia]:::emergent
        C1 --> E1
        C2 --> E2
        C3 --> E3
    end

    %% === STYLE CLASSES ===
    classDef title fill:#222,color:#fff,stroke:#555,stroke-width:2px,font-size:16px,font-weight:bold;
    classDef creation fill:#1abc9c,color:#fff,stroke:#0e7c66,stroke-width:2px;
    classDef effort fill:#3498db,color:#fff,stroke:#1b5e91,stroke-width:2px;
    classDef reflection fill:#9b59b6,color:#fff,stroke:#5e3378,stroke-width:2px;
    classDef influence fill:#f1c40f,color:#000,stroke:#b38f00,stroke-width:2px;
    classDef emergent fill:#e67e22,color:#fff,stroke:#b35400,stroke-width:2px;
