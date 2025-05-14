# abap-ddic-project
ABAP Dictionary : Create a basic Employee Management structure using ABAP Dictionary components to store and manage employee data in an organization.

# ABAP Dictionary Practice Project – Employee Master

This project demonstrates how to model a basic Employee Master in ABAP Dictionary using:

- Transparent Table: `ZEMPLOYEE`
- Domains and Data Elements
- Table Types and Structures

## Components

| Component Type | Name                 | Description                           |
|----------------|----------------------|---------------------------------------|
| Domain         | ZDOMAIN_DEPT         | Fixed values for department           |
| Data Elements  | ZDE_EID, ZDE_NAME... | For individual fields                 |
| Table          | ZEMPLOYEE            | Master employee storage               |
| Table Type     | ZTT_EMPLOYEE         | Internal table type for ZEMPLOYEE     |
| Structure      | ZS_EMPLOYEE_DISPLAY  | For report/display purposes           |

## Usage

Records can be created using transaction SE16N. This structure can be used in reports or interfaces.

## Screenshots

See `screenshots/` for reference steps performed in SAP GUI.
