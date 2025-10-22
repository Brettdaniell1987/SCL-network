### **2. Symbolic Network (`symbolic_network.md`)**

```markdown
# Symbolic Network Diagram

**Back to README:** [Return to README](../README.md)  

**Related Simulations:**  
- [Day-in-the-Life](../simulations/day_in_the_life.md)  
- [Symbolic Ecosystem](../simulations/symbolic_ecosystem.md)

```mermaid
%% Symbolic Network: Core SCLs to Secondary Symbols to Meta-SCLs
graph TD
    %% Core SCLs
    Adaptation["Adaptation"]
    Reflection["Reflection"]
    Creation["Creation"]
    Effort["Effort"]
    Influence["Influence"]
    Energy["Energy"]

    %% Secondary Symbols
    Lumen["Lumen"]
    Prism["Prism"]
    Fluxion["Fluxion"]
    Nebula["Nebula"]
    Aurora["Aurora"]
    Prismatica["Prismatica"]

    %% Meta-SCLs
    LuminaryFlow["LuminaryFlow"]
    ChaoticHarmony["ChaoticHarmony"]
    GuidedEmergence["GuidedEmergence"]

    %% Core SCL → Secondary Symbol Links
    Adaptation --> Lumen
    Reflection --> Lumen
    Creation --> Fluxion
    Energy --> Fluxion
    Influence --> Prism
    Effort --> Prism
    Adaptation --> Nebula
    Reflection --> Aurora
    Creation --> Prismatica

    %% Secondary Symbol → Meta-SCL Links
    Lumen --> LuminaryFlow
    Prism --> ChaoticHarmony
    Fluxion --> GuidedEmergence
    Nebula --> LuminaryFlow
    Aurora --> ChaoticHarmony
    Prismatica --> GuidedEmergence
