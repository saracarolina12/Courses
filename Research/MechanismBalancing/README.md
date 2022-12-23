# Mechanism Balancing 

## Objective
1. Optimize the following:
    - ShF: Shaking Force equations
    - ShM: Shaking Moment equations
2. Six Bar Mechanism

## Tasks
1. Investigate about Multi-objective Optimization:
    -   Multiple objective functions are considered

## [First article](https://www.mdpi.com/2076-3417/9/19/4115)
### __Goal__ 
Balance a four-bar mechanism

### **Proposed Algorithm**
Simplified version of Projected Gradient Descent, a deterministic and iterative algorithm based on the gradient vector direction.

A weighted sum was used for defining the objective function:

$f(X) = \gamma*\beta_{ShM}(X)+(1-\gamma)*\beta_{ShF}(X)$

where $\gamma$ is a scalar value that determines the importance given to each of the objectives of the optimization.


### **Pareto Front**
In multi-objective optimization, Pareto front/frontier/curve is the set of all efficient solutions.

### **Firefly algorithm**
Is a metaheuristic inspired by the flashing behavior of fireflies