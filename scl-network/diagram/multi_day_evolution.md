# Multi-Day Evolution Diagram

**Back to README:** [Return to README](../README.md)  

**Related Simulations:**  
- [Symbolic Ecosystem](../simulations/symbolic_ecosystem.md)

```mermaid
%% Multi-Day Evolution Diagram
graph TD
    %% === TITLE ===
    A[Multi-Day Recursive Evolution of SCLs]:::title

    %% === DAYS ===
    subgraph D1[Day 1 – Initial Concept Loop]
        A1[Concept Birth 🌱]:::creation
        A2[Symbol Mapping 🧩]:::effort
        A3[Micro Reflection 🔍]:::reflection
        A4[Early Influence ↗️]:::influence
        A1 --> A2 --> A3 --> A4
    end

    subgraph D2[Day 2 – Adaptive Refinement]
        B1[Concept Re-Entry 🔁]:::creation
        B2[Adaptive Structuring ⚙️]:::effort
        B3[Expanded Reflection 💭]:::reflection
        B4[Network Influence 🌐]:::influence
        B1 --> B2 --> B3 --> B4
    end

    subgraph D3[Day 3 – Symbolic Integration]
        C1[Emergent Symbol Creation ✨]:::creation
        C2[Integration Effort 🔩]:::effort
        C3[Recursive Reflection 🔄]:::reflection
        C4[Influence Ripple 🌊]:::influence
        C1 --> C2 --> C3 --> C4
    end

    %% === INTERDAY LINKS ===
    A4 --> B1
    B4 --> C1
    C4 --> A1

    %% === STYLE CLASSES ===
    classDef title fill:#222,color:#fff,stroke:#555,stroke-width:2px,font-size:18px,font-weight:bold;
    classDef creation fill:#1abc9c,color:#fff,stroke:#0e7c66,stroke-width:2px;      %% Green–blue: Creation
    classDef effort fill:#3498db,color:#fff,stroke:#1b5e91,stroke-width:2px;         %% Blue: Effort/Adaptation
    classDef reflection fill:#9b59b6,color:#fff,stroke:#5e3378,stroke-width:2px;     %% Purple: Reflection
    classDef influence fill:#f1c40f,color:#000,stroke:#b38f00,stroke-width:2px;      %% Yellow: Influence
