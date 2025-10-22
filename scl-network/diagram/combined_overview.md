```mermaid
%% Combined SCL Network Overview with Colors
graph TD
    %% Core SCLs
    Adaptation["Adaptation"]:::core
    Effort["Effort"]:::core
    Influence["Influence"]:::core
    Reflection["Reflection"]:::core
    Creation["Creation"]:::core
    Energy["Energy"]:::core

    %% Emergent Loops
    E1["Hybrid Adaptation-Reflection Loop"]:::emergent
    E2["Chaotic Creation-Energy Loop"]:::emergent
    E3["Influential Feedback Loop"]:::emergent
    E4["Interference Loop"]:::emergent

    %% Secondary Symbols
    Lumen["Lumen"]:::symbol
    Prism["Prism"]:::symbol
    Fluxion["Fluxion"]:::symbol
    Nebula["Nebula"]:::symbol
    Aurora["Aurora"]:::symbol
    Prismatica["Prismatica"]:::symbol
    Nebulatrix["Nebulatrix"]:::symbol
    PrismaticVortex["Prismatic Vortex"]:::symbol
    AuroralEcho["Auroral Echo"]:::symbol
    LatticeBloom["Lattice Bloom"]:::symbol

    %% Meta-SCLs
    LuminaryFlow["LuminaryFlow"]:::meta
    ChaoticHarmony["ChaoticHarmony"]:::meta
    GuidedEmergence["GuidedEmergence"]:::meta
    StellarFlow["StellarFlow"]:::meta
    ChaoticLuminescence["ChaoticLuminescence"]:::meta
    HarmonicConvergence["HarmonicConvergence"]:::meta
    StellarConvergence["Stellar Convergence"]:::meta
    TemporalFlow["Temporal Flow"]:::meta
    AuroralCascade["Auroral Cascade"]:::meta

    %% Core SCL interactions
    Adaptation --> E1
    Reflection --> E1
    Creation --> E2
    Energy --> E2
    Influence --> E3
    E1 --> Lumen
    E2 --> Fluxion
    E3 --> Prism
    E4 --> Nebulatrix
    E2 --> PrismaticVortex
    E3 --> AuroralEcho
    E1 --> LatticeBloom
    Lumen --> LuminaryFlow
    Prism --> ChaoticHarmony
    Fluxion --> GuidedEmergence
    Nebula --> StellarFlow
    Aurora --> ChaoticLuminescence
    Prismatica --> HarmonicConvergence
    Nebulatrix --> StellarConvergence
    PrismaticVortex --> ChaoticHarmony
    AuroralEcho --> TemporalFlow
    LatticeBloom --> AuroralCascade

    %% Recursive Feedback to Core
    LuminaryFlow --> Adaptation
    ChaoticHarmony --> Creation
    GuidedEmergence --> Reflection
    StellarFlow --> Adaptation
    ChaoticLuminescence --> Creation
    HarmonicConvergence --> Reflection
    StellarConvergence --> Adaptation
    TemporalFlow --> Reflection
    AuroralCascade --> Influence

    %% Style Classes
    classDef core fill:#f9d5e5,stroke:#e91e63,stroke-width:2px,color:#000;
    classDef emergent fill:#d5f4e6,stroke:#00b894,stroke-width:2px,color:#000;
    classDef symbol fill:#fff3b0,stroke:#ff9f1c,stroke-width:2px,color:#000;
    classDef meta fill:#c6d8ff,stroke:#3f51b5,stroke-width:2px,color:#000;
