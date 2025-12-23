# Ford 3000 Tractor Parts Database

This project is a structured parts database developed for the Ford 3000 tractor.
All tractor components are classified by system and region, with each part assigned
a unique part code and region code to ensure unambiguous identification.

The database is designed to support maintenance, repair, and parts analysis by
organizing components into logical groups such as engine, transmission, hydraulics,
brake system, and electrical systems.

Each part record includes standardized codes, descriptive attributes, pricing data,
and sales-related information, allowing consistent tracking and comparison across
different tractor systems.

## Database Structure
- Parts are grouped by system (e.g. Engine, Gearbox, Hydraulics, Brake)
- Each part has:
  - Unique full part code
  - Group code and part type code
  - System/region classification
  - Pricing and annual sales data

The relational structure is implemented using SQL, with clear relationships between
models, parts, part types, and sales tables.

## Data Analysis & Reporting
In addition to the database design, data analysis and visualization were performed
using KNIME. Analytical outputs include:
- Revenue and price distribution by system
- Identification of high-revenue and low-revenue components
- Comparative charts and statistical summaries

All analysis results, charts, and reports are documented in the accompanying PDF file.

## Tools & Technologies
- SQL (relational database design)
- Microsoft Excel (data entry and validation)
- KNIME (data analysis, visualization, and reporting)

## Use Case
This project demonstrates practical database design, data organization, and
engineering-oriented analysis applied to a real mechanical system.
It can be used as a reference for parts management, maintenance planning,
and data-driven decision support in engineering contexts.
