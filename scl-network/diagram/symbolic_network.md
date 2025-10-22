# Symbolic Network Diagram

**Back to README:** [Return to README](../README.md)  

**Related Simulations:**  
- [Day-in-the-Life](../simulations/day_in_the_life.md)  
- [Symbolic Ecosystem](../simulations/symbolic_ecosystem.md)

```mermaid
%% Symbolic Network Diagram with Color Coding

%% Define nodes with colors directly
graph TD
    %% Core SCLs (Blue)
    Adaptation[Adaptation]:::core
    Reflection[Reflection]:::core
    Creation[Creation]:::core
    Energy[Energy]:::core
    Influence[Influence]:::core
    Effort[Effort]:::core

    %% Secondary Symbols (Green)
    Lumen[Lumen]:::secondary
    Prism[Prism]:::secondary
    Fluxion[Fluxion]:::secondary

    %% Meta-SCLs (Orange)
    LuminaryFlow[LuminaryFlow]:::meta
    ChaoticHarmony[ChaoticHarmony]:::meta
    GuidedEmergence[GuidedEmergence]:::meta

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

%% Define classes
classDef core fill:#a8d0e6,stroke:#333,stroke-width:1px;
classDef secondary fill:#b8e986,stroke:#333,stroke-width:1px;
classDef meta fill:#f6b26b,stroke:#333,stroke-width:1px;
