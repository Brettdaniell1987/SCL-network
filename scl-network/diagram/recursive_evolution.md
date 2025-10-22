# Recursive Evolution Diagram

**Back to README:** [Return to README](../README.md)  

**Related Simulations:**  
- [Day-in-the-Life](../simulations/day_in_the_life.md)  
- [Symbolic Ecosystem](../simulations/symbolic_ecosystem.md)

```mermaid
%% Recursive Evolution Diagram
graph TD
    %% Day 1 Core SCLs
    Adaptation_D1 --> Lumen_D1
    Reflection_D1 --> Lumen_D1
    Creation_D1 --> Fluxion_D1
    Energy_D1 --> Fluxion_D1
    Influence_D1 --> Prism_D1
    Effort_D1 --> Prism_D1

    %% Day 1 Secondary Symbols to Meta-SCLs
    Lumen_D1 --> LuminaryFlow_D1
    Prism_D1 --> ChaoticHarmony_D1
    Fluxion_D1 --> GuidedEmergence_D1

    %% Day 2 Core SCLs inherit feedback from Day 1
    LuminaryFlow_D1 --> Adaptation_D2
    ChaoticHarmony_D1 --> Reflection_D2
    GuidedEmergence_D1 --> Creation_D2
    Lumen_D1 --> Energy_D2
    Prism_D1 --> Influence_D2
    Fluxion_D1 --> Effort_D2

    %% Day 2 Secondary Symbols to Meta-SCLs
    Lumen_D2 --> LuminaryFlow_D2
    Prism_D2 --> ChaoticHarmony_D2
    Fluxion_D2 --> GuidedEmergence_D2

    %% Day 3 Core SCLs inherit feedback from Day 2
    LuminaryFlow_D2 --> Adaptation_D3
    ChaoticHarmony_D2 --> Reflection_D3
    GuidedEmergence_D2 --> Creation_D3
