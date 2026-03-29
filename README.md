# Sports Scheduling Optimization

Optimization-based scheduling for the Worldwide Softball League (WSL) using Mixed-Integer Linear Programming (MILP) in Python with Gurobi.

## Overview
This project builds a 9-week schedule for a 12-team league while satisfying hard constraints on divisional play, home/away balance, bye weeks, and travel patterns. The model also improves travel fairness and separates marquee TV matchups across different weeks.

## Business Problem
Sports leagues face trade-offs between travel cost, schedule fairness, and broadcast value. This project converts those rules into a solvable MILP and generates a validated schedule.

## Approach
- Formulated the problem as a MILP with binary game-week-location variables
- Enforced league structure, home/away balance, and travel-pattern constraints
- Added fairness and broadcast considerations in the optimization
- Solved the model in Python using Gurobi

## Results
- Total away-team travel: 35,125 miles
- Travel spread: 1,050 miles
- Zero back-to-back away sequences
- All marquee matchups scheduled in distinct weeks

## Tech Stack
Python, Gurobi, MILP, Optimization, Scheduling

## Repository Structure
- `src/` -> optimization code
- `outputs/` -> final schedule text file
- `reports/` -> full project report
- `slides/` -> presentation deck

## How to Run
1. Install dependencies
2. Run the scheduler script
3. Review the generated schedule output

## Author
Ashutosh Srivastava
