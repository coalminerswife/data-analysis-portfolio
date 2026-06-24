# Binary & Integer Programming

Optimization with **discrete** decisions — variables constrained to integers or to
binary (0/1) yes-no choices. Solved with Excel **Solver**.

**File:** [`binary-integer-programming.xlsx`](binary-integer-programming.xlsx)

## Models

| Problem | Type | Decision |
|---|---|---|
| Princess Brides | Integer | Peak vs. off-peak quantities (whole units) |
| Bolsa de Café | Integer | How many bags / pounds to produce |
| Art Posters | Integer | Large vs. small poster production mix |
| Binary Investment Decision | Binary (0/1) | Which projects to fund — capital budgeting |
| Horizon Wireless | Binary (0/1) | Select among mutually exclusive options |

## Techniques

- **Binary (0/1) variables** for select / don't-select capital-budgeting decisions
- **Integer constraints** where fractional answers are meaningless (you can't ship
  3.4 units)
- Modeling mutually-exclusive and dependency constraints between choices
- Solver `int` and `bin` constraint types with the Simplex LP / Branch-and-Bound engine

## How to view

GitHub can't preview Excel files. **Download** the workbook and open in Excel
(enable Solver via *File → Options → Add-ins*), or import into Google Sheets.
