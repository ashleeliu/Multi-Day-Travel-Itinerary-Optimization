# Multi-Day-Travel-Itinerary-Optimization

In this final course project, I formulated a mixed-integer optimization model to design a cost-efficient, well-balanced three-day travel itinerary to Sequoia National Park under realistic constraints.

The model integrates real-world considerations such as lodging selection, transportation costs, activity scheduling, time windows, and traveler fatigue. It demonstrates how decision analytics and optimization techniques can be applied to everyday planning problems.

## What It Does

* Computes an optimal travel plan including lodging, transportation, and activity schedule

* Balances cost, time availability, and fatigue penalties

* Handles activity dependencies and eligibility constraints

* Outputs a structured itinerary that satisfies all constraints

## Modeling Approach

The problem is modeled as a mixed-integer optimization using Pyomo, and solved with HiGHS.

Key components:

* Decision variables: lodging selection, car rental choice, activity scheduling by day

* Constraints: time windows, activity dependencies, non-overlapping activities, fatigue limits

* Objective: minimize total cost + weighted fatigue penalties

## Results

The optimized itinerary selects:

* Wuksachi Lodge

* Chevrolet Beat

and produces a balanced activity schedule across all three days with a total objective value of $911.00.

## Tools

* Python

* Pyomo

* HiGHS Solver

* LaTeX (for the final project report)

## Notes

This project was completed as part of a final project for INDENG 164: Introduction to Optimization Modeling at UC Berkeley.
