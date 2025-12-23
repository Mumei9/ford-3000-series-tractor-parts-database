# Ford 3000 Tractor Parts Database

This project is a structured parts database developed for the Ford 3000 tractor.
All tractor components are classified by system and region, with each part assigned
a unique part code and region code to ensure unambiguous identification.

The database is designed to support maintenance, repair, and parts analysis by
organizing components into logical groups such as engine, transmission, hydraulics,
brake system, and electrical systems.

Each part record includes standardized codes, descriptive attributes, and technical
information that reflect real tractor components and correct mechanical structure.

## Database Structure
- Parts are grouped by system (e.g. Engine, Gearbox, Hydraulics, Brake)
- Each part has:
  - A unique full part code
  - Group code and part type code
  - System/region classification
  - Technical attributes related to the component

The relational structure is implemented using SQL, with clear relationships between
models, parts, part types, and sales tables.

## Data Analysis & Reporting
In addition to the database design, data analysis and visualization were performed
using KNIME. The analysis focuses on demonstrating analytical workflows and reporting
techniques.

⚠️ **Important Note on Data**
- Technical and structural data (parts, systems, codes, relationships) are accurate
  and based on real tractor components.
- Sales-related values such as prices, annual sales quantities, and revenue figures
  are **synthetic (assumed) data**, created solely for demonstration and analysis
  purposes.
- The analytical results should therefore be interpreted as examples of methodology
  rather than real commercial insights.

The analysis report and visualizations are documented in a PDF file.

## Language Note
The analysis report and documentation PDF are written in **Turkish**.  
The database structure, file naming, and code elements follow English conventions.

## Tools & Technologies
- SQL (relational database design)
- Microsoft Excel (data entry and validation)
- KNIME (data analysis, visualization, and reporting)

## Use Case
This project demonstrates practical database design, data organization, and
engineering-oriented analysis applied to a real mechanical system.
It is intended as a technical and educational reference rather than a commercial
sales analysis.
