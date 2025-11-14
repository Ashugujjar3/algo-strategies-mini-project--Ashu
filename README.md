# algo-strategies-mini-project--Ashu
Algorithms Report –

This repository contains detailed explanations, analyses, and code snippets for four essential algorithmic problems.
Each section includes problem descriptions, algorithm logic, time/space complexity, and (where applicable) visualizations and real-world considerations.

📘 Contents
## Problem 1 — Scheduling TV Commercials to Maximize Impact (Greedy Job Sequencing)

Objective:
Schedule commercials into available time slots to maximize revenue, ensuring each slot contains at most one ad.

Method:

Uses Greedy Job Sequencing

Sorts ads by descending profit

Assigns each ad to the latest available slot ≤ its deadline

Complexity:

Sorting: O(n log n)

Scheduling: O(n * d)

Optimized with DSU: O(n log n)

Space: O(d + n)

Notes:
Visualizations included in the document simulate ads vs. revenue.

## Problem 2 — Maximizing Profit with Limited Budget (0/1 Knapsack)

Objective:
Pick items such that:

Total cost ≤ budget

Profit is maximized

Method:

Classic 0/1 Dynamic Programming Knapsack

Builds DP table dp[i][w]

Complexity:

Time: O(n * budget)

Space: O(n * budget) → Optimizable to O(budget)

Real-World Constraints:

Project dependencies

Fractional funding (→ Fractional Knapsack)

Changing budgets requiring re-optimization

## Problem 3 — Solving Sudoku Puzzle (Backtracking)

Objective:
Fill a 9×9 Sudoku board by checking validity in rows, columns, and 3×3 subgrids.

Method:

Recursive backtracking search

Prunes paths using constraint checks

Complexity:

Time: worst-case ≈ O(9^m) (m = number of empty cells)

Space: O(m) recursion depth

Notes:
Optional performance visualizations measure solver time vs. number of empty cells.

## Problem 4 — Brute-force: Safe Simulation & Analysis

Objective:
Provide a non-invasive, safe computation-only simulation of brute-force attack time estimates.

Method:

Calculates:

Number of possible combinations

Estimations based on attempts/second

No network access or real attacking behavior

Use Cases:

Educational understanding of brute-force complexity

Demonstrations for cybersecurity awareness

Visualizations of time growth as password length/charset increases

🧰 Tools & Technologies

Python (DP, backtracking, brute-force simulation)

Greedy algorithms

Data structures (arrays, disjoint sets)

Complexity analysis

Optional computational visualizations (plots)

📄 Files

algorithms_report.docx — Main report containing explanations, code samples, outputs, and visuals.

README.md — Overview of all problems and results.

🧠 Purpose

This report is ideal for students, educators, and developers wanting practical exposure to:

Optimization techniques

Greedy, dynamic programming, and backtracking algorithms

Complexity behavior in real-world and simulated scenarios
