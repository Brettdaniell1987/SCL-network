# Full SCL Ecosystem Diagram

**Back to README:** [Return to README](../README.md)  

**Related Simulations:**  
- [Day-of-Anomalies](../simulations/day_of_anomalies.md)

```mermaid
%% Full SCL Ecosystem Diagram with Color Coding
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
    Aurora[Aurora]:::secondary
    Fluxion[Fluxion]:::secondary
    Prismatica[Prismatica]:::secondary
    Prism[Prism]:::secondary
    Nebula[Nebula]:::secondary

    %% Meta-SCLs (Orange)
    LuminaryFlow[LuminaryFlow]:::meta
    ChaoticLuminescence[ChaoticLuminescence]:::meta
    GuidedEmergence[GuidedEmergence]:::meta
    StellarFlow[StellarFlow]:::meta
    ChaoticHarmony[ChaoticHarmony]:::meta
    AuroralCascade[AuroralCascade]:::meta

    %% Connections Core -> Secondary
    Adaptation --> Lumen
    Reflection --> Aurora
    Creation --> Fluxion
    Energy --> Prismatica
    Influence --> Prism
    Effort --> Nebula

    %% Secondary -> Meta
    Lumen --> LuminaryFlow
    Aurora --> ChaoticLuminescence
    Fluxion --> GuidedEmergence
    Prismatica --> StellarFlow
    Prism --> ChaoticHarmony
    Nebula --> AuroralCascade

    %% Meta Interactions
    LuminaryFlow --> ChaoticHarmony
    ChaoticLuminescence --> GuidedEmergence
    StellarFlow --> AuroralCascade
    AuroralCascade --> LuminaryFlow
    ChaoticHarmony --> StellarFlow
    GuidedEmergence --> ChaoticLuminescence

%% Define Classes
classDef core fill:#a8d0e6,stroke:#333,stroke-width:1px;
classDef secondary fill:#b8e986,stroke:#333,stroke-width:1px;
classDef meta fill:#f6b26b,stroke:#333,stroke-width:1px;
