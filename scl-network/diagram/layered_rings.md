# Layered Rings Diagram

**Back to README:** [Return to README](../README.md)  

**Related Simulations:**  
- [Day-in-the-Life](../simulations/day_in_the_life.md)

```mermaid
%% Layered Rings Diagram with Color Coding
graph TD
    %% Core SCLs (Blue)
    classDef core fill:#a8d0e6,stroke:#333,stroke-width:1px;
    Adaptation:::core
    Reflection:::core
    Creation:::core
    Energy:::core
    Influence:::core
    Effort:::core

    Adaptation --> Creation
    Reflection --> Effort
    Influence --> Energy
    Creation --> Influence
    Effort --> Reflection

    %% Secondary Symbols (Green)
    classDef secondary fill:#b8e986,stroke:#333,stroke-width:1px;

    %% Meta-SCLs (Orange)
    classDef meta fill:#f6b26b,stroke:#333,stroke-width:1px;
