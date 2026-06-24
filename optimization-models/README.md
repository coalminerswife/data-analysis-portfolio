# Optimization Models

Prescriptive-analytics models built and solved with **Excel Solver**. Each
workbook contains multiple worked problems on separate sheets, covering one class
of mathematical programming.

| Folder | Technique | What it shows |
|---|---|---|
| [linear-programming](linear-programming/) | Linear programming (LP) | Maximizing profit / minimizing cost under linear constraints |
| [nonlinear-programming](nonlinear-programming/) | Nonlinear programming (NLP) | Optimizing when the objective or constraints are nonlinear (e.g. price × demand) |
| [integer-programming](integer-programming/) | Binary / integer programming | Discrete and yes/no decisions (project selection, capital budgeting) |
| [transportation-assignment](transportation-assignment/) | Network / assignment | Least-cost shipping and optimal one-to-one assignment |

### Approach used across all models
1. Define **decision variables** (the quantities Solver can change).
2. Build the **objective function** (the cell to maximize or minimize).
3. Encode **constraints** (capacity, demand, budget, non-negativity, binary, etc.).
4. Run **Solver** with the appropriate engine (Simplex LP, GRG Nonlinear, or Evolutionary).
5. Interpret the result and, where relevant, run **what-if / sensitivity analysis**.
