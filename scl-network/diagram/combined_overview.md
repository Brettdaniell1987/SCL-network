# Combined Overview Diagram

**Back to README:** [Return to README](../../README.md)
 

**Related Diagrams:**  
- [Experimental Collisions](diagram/experimental_collisions.md)  
- [Full SCL Ecosystem](diagram/full_scl_ecosystem.md)
- [Layered Rings](diagram/layered_rings.md) 
- [Recursive Evolution](diagram/recursive_evolution.md) 
- [Symbolic Network](diagram/symbolic_network.md)  
- [Multi-Day Evolution](diagram/multi_day_evolution.md)


```mermaid
%% Combined Overview Diagram with Color Coding
graph TD
    %% Core SCLs (Blue)
    classDef core fill:#a8d0e6,stroke:#333,stroke-width:1px;
    Adaptation:::core
    Reflection:::core
    Creation:::core
    Energy:::core
    Influence:::core
    Effort:::core

    Adaptation --> Lumen
    Reflection --> Aurora
    Creation --> Fluxion
    Energy --> Prismatica
    Influence --> Prism
    Effort --> Nebula

    %% Secondary Symbols (Green)
    classDef secondary fill:#b8e986,stroke:#333,stroke-width:1px;
    Lumen:::secondary
    Aurora:::secondary
    Fluxion:::secondary
    Prismatica:::secondary
    Prism:::secondary
    Nebula:::secondary

    Lumen --> LuminaryFlow
    Aurora --> ChaoticLuminescence
    Fluxion --> GuidedEmergence
    Prismatica --> StellarFlow
    Prism --> ChaoticHarmony
    Nebula --> AuroralCascade

    %% Meta-SCLs (Orange)
    classDef meta fill:#f6b26b,stroke:#333,stroke-width:1px;
    LuminaryFlow:::meta
    ChaoticLuminescence:::meta
    GuidedEmergence:::meta
    StellarFlow:::meta
    ChaoticHarmony:::meta
    AuroralCascade:::meta

    %% Meta-SCL Interactions
    LuminaryFlow --> ChaoticHarmony
    ChaoticLuminescence --> GuidedEmergence
    StellarFlow --> AuroralCascade
    AuroralCascade --> LuminaryFlow
    ChaoticHarmony --> StellarFlow
    GuidedEmergence --> ChaoticLuminescence
