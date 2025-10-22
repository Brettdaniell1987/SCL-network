
---

### **2. Symbolic Network (`symbolic_network.md`)**

```markdown
# Symbolic Network Diagram

**Back to README:** [Return to README](../README.md)  

**Related Simulations:**  
- [Day-in-the-Life](../simulations/day_in_the_life.md)  
- [Symbolic Ecosystem](../simulations/symbolic_ecosystem.md)

```mermaid
%% Symbolic Network Diagram with Color Coding
graph TD
    %% Core SCLs (Blue)
    classDef core fill:#a8d0e6,stroke:#333,stroke-width:1px;
    Adaptation:::core
    Reflection:::core
    Creation:::core
    Energy:::core
    Influence:::core
    Effort:::core

    %% Secondary Symbols (Green)
    classDef secondary fill:#b8e986,stroke:#333,stroke-width:1px;
    Lumen:::secondary
    Prism:::secondary
    Fluxion:::secondary

    %% Meta-SCLs (Orange)
    classDef meta fill:#f6b26b,stroke:#333,stroke-width:1px;
    LuminaryFlow:::meta
    ChaoticHarmony:::meta
    GuidedEmergence:::meta

    %% Connections
    Adaptation --> Lumen
    Reflection --> Lumen
    Creation --> Fluxion
    Energy --> Fluxion
    Influence --> Prism
    Effort --> Prism

    Lumen --> LuminaryFlow
    Prism --> ChaoticHarmony
    Fluxion --> GuidedEmergence

    LuminaryFlow --> ChaoticHarmony
    ChaoticHarmony --> GuidedEmergence
    GuidedEmergence --> LuminaryFlow
