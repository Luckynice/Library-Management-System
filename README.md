# Library-Management-System
"A SQL Server project for managing library books, loans and fines."

## Features
Book Management: Add/Update books and track availability.
Member Management: Track active/inactive members.
Loan tracking: Record book borrow/return dates.
Fine Calculation: Automatically calculate overdue fines

## Prerequisites
SQL server
SQL server management studio (SSMS)

## Setup
Clone this repository:
  bash
git clone https://Luckynice/Library-Management-System.git

## Run Scripts in SSMS order:
Database_and_Tables.sql
sample_data.sql
Queries.sql
StoredProcedures_Triggers.sql

## Schema Design
[ER Diagram] (Documentation/ER_Diagram.png)

## Outputs:
Available Books:
Overdue Fine Report:

## Challenges & Solution
Automating Fines: Use a Trigger to calculate fines when books are returned late.
Data Integrity: Added foreign keys and constraints to enforce relationships.
