# Layered Rings Diagram

**Back to README:** [Return to README](../README.md)  

**Related Simulations:**  
- [Day-in-the-Life](../simulations/day_in_the_life.md)
- 
```mermaid
%% Layered Ring SCL Flow
graph TD
    subgraph Inner Loop
        A[Adaptation]
        B[Reflection]
        C[Creation]
        D[Effort]
        E[Influence]
        F[Energy]
    end

    %% Internal circular flow
    A --> B --> C --> D --> E --> F --> A

    %% Outward ripple flow
    A --> G[Emergent SCLs]
    B --> G
    C --> G
    D --> G
    E --> G
    F --> G

    %% Emergent SCLs loop back
    G --> A
