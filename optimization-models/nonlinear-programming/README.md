# Nonlinear Programming

Optimization problems where the objective or constraints are **nonlinear** —
solved with Excel **Solver** using the GRG Nonlinear engine.

**File:** [`nonlinear-programming.xlsx`](nonlinear-programming.xlsx)

## Models

| Problem | Focus |
|---|---|
| PB&J | Two-variable nonlinear optimization |
| Motorcross of Wisconsin (Snowmobiles) | Output mix with nonlinear demand/cost relationships |
| Baseball Stadium | **Price/demand optimization** — set price to maximize concession revenue (demand falls as price rises) |

## Techniques

- Modeling nonlinear relationships (e.g. `demand = a − b·price`) directly in cells
- **GRG Nonlinear** Solver engine, with attention to starting values and local vs.
  global optima
- Revenue/profit maximization where the optimum is an interior point, not a corner
- Showing the elasticity-style trade-off between price and quantity sold

## How to view

GitHub can't preview Excel files. **Download** the workbook and open in Excel
(enable Solver via *File → Options → Add-ins*), or import into Google Sheets.
