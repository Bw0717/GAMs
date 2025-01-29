# Production Line Workstation Optimization Model

## Introduction
This GAMS model is designed to optimize workstation task allocation in production lines by balancing fixed and flexible tasks across workstations.

## Model Structure
### Sets
- T: Fixed tasks, mandatory operations for each workstation
- S: Workstations
- R: Flexible tasks, operations that can be flexibly allocated

### Main Features
- Minimizes work time differences between workstations
- Ensures proper allocation of fixed tasks
- Optimizes flexible task distribution for workstation balance
