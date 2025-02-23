# JumpSystem

## System Constructors

```@docs
JumpSystem
```

## Composition and Accessor Functions

  - `get_eqs(sys)` or `equations(sys)`: The equations that define the jump system.
  - `get_states(sys)` or `states(sys)`: The set of states in the jump system.
  - `get_ps(sys)` or `parameters(sys)`: The parameters of the jump system.
  - `get_iv(sys)`: The independent variable of the jump system.

## Transformations

```@docs; canonical=false
structural_simplify
```

## Analyses

## Problem Constructors

```@docs; canonical=false
DiscreteProblem(sys::ModelingToolkit.DiscreteSystem, u0map, tspan)
```
```@docs
JumpProblem(sys::JumpSystem, prob, aggregator)
```
