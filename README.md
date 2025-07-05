# Equality-Score-Audit
his Excel-based project evaluates workplace compensation fairness using a classification model.

## Data

- Source file: Equality Table.xlsx
- Columns:
  - Factory
  - Job Role
  - Equality Score (ranging from -100 to +100)
  - Equality Class (added using Excel formula logic)

## Classification Rules

- **Fair**: Score between -10 and 10  
- **Unfair**: Score beyond ±10  
- **Highly Discriminative**: Score beyond ±20

## Outcome

Enabled HR analysis of bias patterns across factories and roles.
