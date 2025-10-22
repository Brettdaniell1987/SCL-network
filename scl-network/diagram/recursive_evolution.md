# Recursive Evolution Diagram

**Back to README:** [Return to README](../../README.md) 

**Related Simulations:**  
- [Day-in-the-Life](../simulations/day_in_the_life.md)  
- [Symbolic Ecosystem](../simulations/symbolic_ecosystem.md)

```mermaid
%% Recursive Evolution Diagram with Color Coding

%% Core SCLs (Blue)
graph TD
    Adaptation_D1[Adaptation D1]:::core
    Reflection_D1[Reflection D1]:::core
    Creation_D1[Creation D1]:::core
    Energy_D1[Energy D1]:::core
    Influence_D1[Influence D1]:::core
    Effort_D1[Effort D1]:::core

    %% Day 1 Secondary Symbols (Green)
    Lumen_D1[Lumen D1]:::secondary
    Prism_D1[Prism D1]:::secondary
    Fluxion_D1[Fluxion D1]:::secondary

    %% Day 1 Meta-SCLs (Orange)
    LuminaryFlow_D1[LuminaryFlow D1]:::meta
    ChaoticHarmony_D1[ChaoticHarmony D1]:::meta
    GuidedEmergence_D1[GuidedEmergence D1]:::meta

    %% Connections Day 1
    Adaptation_D1 --> Lumen_D1
    Reflection_D1 --> Lumen_D1
    Creation_D1 --> Fluxion_D1
    Energy_D1 --> Fluxion_D1
    Influence_D1 --> Prism_D1
    Effort_D1 --> Prism_D1

    Lumen_D1 --> LuminaryFlow_D1
    Prism_D1 --> ChaoticHarmony_D1
    Fluxion_D1 --> GuidedEmergence_D1

    LuminaryFlow_D1 --> ChaoticHarmony_D1
    ChaoticHarmony_D1 --> GuidedEmergence_D1
    GuidedEmergence_D1 --> LuminaryFlow_D1

    %% Day 2 Core SCLs (Blue)
    Adaptation_D2[Adaptation D2]:::core
    Reflection_D2[Reflection D2]:::core
    Creation_D2[Creation D2]:::core
    Energy_D2[Energy D2]:::core
    Influence_D2[Influence D2]:::core
    Effort_D2[Effort D2]:::core

    %% Day 2 Secondary Symbols (Green)
    Lumen_D2[Lumen D2]:::secondary
    Prism_D2[Prism D2]:::secondary
    Fluxion_D2[Fluxion D2]:::secondary

    %% Day 2 Meta-SCLs (Orange)
    LuminaryFlow_D2[LuminaryFlow D2]:::meta
    ChaoticHarmony_D2[ChaoticHarmony D2]:::meta
    GuidedEmergence_D2[GuidedEmergence D2]:::meta

    %% Connections Day 2
    LuminaryFlow_D1 --> Adaptation_D2
    ChaoticHarmony_D1 --> Reflection_D2
    GuidedEmergence_D1 --> Creation_D2
    Lumen_D1 --> Energy_D2
    Prism_D1 --> Influence_D2
    Fluxion_D1 --> Effort_D2

    Lumen_D2 --> LuminaryFlow_D2
    Prism_D2 --> ChaoticHarmony_D2
    Fluxion_D2 --> GuidedEmergence_D2

    %% Day 3 Core SCLs (Blue)
    Adaptation_D3[Adaptation D3]:::core
    Reflection_D3[Reflection D3]:::core
    Creation_D3[Creation D3]:::core

    %% Connections Day 3
    LuminaryFlow_D2 --> Adaptation_D3
    ChaoticHarmony_D2 --> Reflection_D3
    GuidedEmergence_D2 --> Creation_D3

%% Define Classes
classDef core fill:#a8d0e6,stroke:#333,stroke-width:1px;
classDef secondary fill:#b8e986,stroke:#333,stroke-width:1px;
classDef meta fill:#f6b26b,stroke:#333,stroke-width:1px;
