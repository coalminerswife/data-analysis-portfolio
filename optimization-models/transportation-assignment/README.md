# Transportation & Assignment

Network-optimization models: move goods from sources to destinations at **least
cost** (transportation), and match agents to tasks one-to-one **optimally**
(assignment). Solved with Excel **Solver**.

**File:** [`transportation-assignment.xlsx`](transportation-assignment.xlsx)

## Models

| Problem | Type | Goal |
|---|---|---|
| Transportation Problem | Transportation | Minimize total shipping cost from factories to stores under supply/demand limits |
| Osbourne Concrete (Construction Projects) | Transportation | Allocate capacity across projects at minimum cost |
| New Hire Assignments | Assignment | Assign new hires to roles for best overall fit |
| Umpire Assignment | Assignment | Assign umpires to games minimizing travel |
| College Professors | Assignment | Assign professors to courses optimally |

## Techniques

- **Supply/demand balance** constraints for transportation networks
- **One-to-one matching** constraints for assignment problems
- Cost-minimization objective across a shipment/assignment matrix
- Handling balanced vs. unbalanced problems (dummy rows/columns)

## How to view

GitHub can't preview Excel files. **Download** the workbook and open in Excel
(enable Solver via *File → Options → Add-ins*), or import into Google Sheets.
