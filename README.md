# SQL Lab Sheets 1–5

This folder contains five separate MySQL SQL scripts prepared from the provided lab-sheet PDF.

## Files

1. `Lab_Sheet_1_DDL.sql` — DDL commands: CREATE, ALTER, DROP, constraints, TRUNCATE.
2. `Lab_Sheet_2_DML.sql` — DML commands: INSERT, UPDATE, DELETE.
3. `Lab_Sheet_3_SQL_Functions.sql` — Number, aggregate, character, conversion, and date functions.
4. `Lab_Sheet_4_SQL_Operators.sql` — Arithmetic, logical, comparison, special, and set-operator examples.
5. `Lab_Sheet_5_SQL_Joins.sql` — INNER, LEFT, RIGHT, CROSS, NATURAL, SELF JOINs, and multi-table reports.

## How to run in MySQL Workbench

1. Download and extract the ZIP file.
2. Open MySQL Workbench and connect to your MySQL server.
3. Select **File → Open SQL Script** and choose one `.sql` file.
4. Review the script, then click the lightning-bolt **Execute** button.
5. Run one lab sheet at a time, from top to bottom.

## Important notes

- The scripts use the database `CollegeDB`.
- Some scripts drop and recreate tables to set up sample data. **Do not run them against a database containing important data unless you have backed it up.**
- Lab Sheet 1 includes `DROP TABLE` and `TRUNCATE` examples; these remove table data or table structures.
- Lab Sheet 4 notes MySQL version differences for `INTERSECT` and `EXCEPT`; workaround queries are included.
- These scripts use example names and sample values. Adjust them if your instructor requires different data.

## Requirements

- MySQL Server
- MySQL Workbench (recommended)

Prepared for practice using MySQL.
