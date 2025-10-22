# Layered Rings Diagram

**Back to README:** [Return to README](../README.md)  

**Related Simulations:**  
- [Day-in-the-Life](../simulations/day_in_the_life.md)

```mermaid
%% Layered Rings Diagram with Color Coding
graph TD
    %% Core SCLs (Blue)
    classDef core fill:#a8d0e6,stroke:#333,stroke-width:1px;
    Adaptation[Adaptation]:::core
    Reflection[Reflection]:::core
    Creation[Creation]:::core
    Energy[Energy]:::core
    Influence[Influence]:::core
    Effort[Effort]:::core

    %% Secondary Symbols (Green)
    classDef secondary fill:#b8e986,stroke:#333,stroke-width:1px;
    Lumen[Lumen]:::secondary
    Prism[Prism]:::secondary
    Fluxion[Fluxion]:::secondary

    %% Meta-SCLs (Orange)
    classDef meta fill:#f6b26b,stroke:#333,stroke-width:1px;
    LuminaryFlow[LuminaryFlow]:::meta
    ChaoticHarmony[ChaoticHarmony]:::meta
    GuidedEmergence[GuidedEmergence]:::meta

    %% Connections Core -> Secondary
    Adaptation --> Lumen
    Reflection --> Lumen
    Creation --> Fluxion
    Energy --> Fluxion
    Influence --> Prism
    Effort --> Prism

    %% Secondary -> Meta
    Lumen --> LuminaryFlow
    Prism --> ChaoticHarmony
    Fluxion --> GuidedEmergence

    %% Meta Interactions (optional)
    LuminaryFlow --> ChaoticHarmony
    ChaoticHarmony --> GuidedEmergence
    GuidedEmergence --> LuminaryFlow
