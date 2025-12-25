# Multi-Day-Travel-Itinerary-Optimization

In this final course project, I formulated a mixed-integer optimization model to design a cost-efficient, well-balanced three-day travel itinerary to Sequoia National Park under realistic constraints.

The model integrates real-world considerations such as lodging selection, transportation costs, activity scheduling, time windows, and traveler fatigue. It demonstrates how decision analytics and optimization techniques can be applied to everyday planning problems.

## Modeling Approach

* Decision Variables: lodging and car selection, activity scheduling by day

* Constraints: time windows, activity dependencies, fatigue limits, and feasibility rules

* Objective: minimize total cost and fatigue penalties under worst-case pricing assumptions

The optimization is implemented in Pyomo and solved using the HiGHS solver.

## Results

The optimized itinerary selects:

* Wuksachi Lodge

* Chevrolet Beat

and produces a balanced activity schedule across all three days with a total objective value of $911.00.

## Tools

* Python

* Pyomo

* HiGHS Solver

* LaTeX

## Notes

This project was completed as part of a final project for INDENG 164: Introduction to Optimization Modeling at UC Berkeley.
