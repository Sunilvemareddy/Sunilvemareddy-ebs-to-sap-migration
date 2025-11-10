# Data Migration Strategy (Summary)

## Objectives
- Accurate transfer of master & transactional data to SAP
- Transparent reconciliation & audit trail

## Data types in scope
- Master data: Material, Business Partner, GL, Asset, BOM
- Open transactions: Open POs, open AR/AP, inventory on-hand, WIP
- Historical data policy: last X years or summarized balances

## Key activities
1. Profiling & inventory
2. Cleansing & standardization
3. Mapping & transformation
4. Staging & ETL design
5. Trial loads & reconciliation
6. Final cutover & validation

## Tools (examples)
- SAP Migration Cockpit / LSMW
- SAP BODS / Informatica / Custom ETL
