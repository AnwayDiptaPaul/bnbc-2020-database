# BNBC 2020 MASTER NAVIGATION MAP

This is the central routing map for the Bangladesh National Building Code (BNBC) 2020 virtual file system.

## Operational Routing Logic for Downstream AI

When interpreting a user query, determine the primary engineering domain or intent, and route to the corresponding Part folder using the rules below.

| Part Directory | Domain / Intent Description | Routing Rules |
| :--- | :--- | :--- |
| **`Part_01_Scope_and_Definitions`** | General definitions, scope, application, and units. | Route here for terminology definitions, overall scope of the code, and standard abbreviations. |
| **`Part_02_Administration_and_Enforcement`** | Legal, permits, inspections, authority. | Route here for questions about building permits, site inspections, enforcement authority, and administrative penalties. |
| **`Part_03_General_Building_Requirements`** | Occupancy classification, fire resistance types, space requirements. | Route here for building occupancy classes (e.g., residential, commercial), floor area requirements, setbacks, and basic energy efficiency rules. |
| **`Part_04_Fire_Protection`** | Fire safety, egress, detection, extinguishing. | Route here for egress/exit widths, fire alarms, sprinkler systems, fire doors, and general fire safety precautions. |
| **`Part_05_Building_Materials`** | Standards for construction materials. | Route here for specifications on cement, steel, masonry, timber, concrete mixes, and other material quality standards. |
| **`Part_06_Structural_Design`** | Loads, structural engineering, foundations, RC, steel, masonry. | Route here for **ALL structural engineering** queries: dead/live loads, wind speed/loads, seismic/earthquake loads (base shear, Response Spectrum), foundation design, concrete detailing, steel design, and retaining walls. |
| **`Part_07_Construction_Practices_and_Safety`** | Site safety, construction management. | Route here for site safety protocols, scaffolding, demolition rules, and quality control during construction. |
| **`Part_08_Building_Services`** | MEP (Mechanical, Electrical, Plumbing), HVAC, Lifts. | Route here for electrical wiring, plumbing, drainage, HVAC calculations, elevator/lift specs, and gas supply. |
| **`Part_09_Alteration_and_Addition`** | Modifying existing structures, conservation. | Route here for rules regarding altering existing buildings, additions, and conservation of historical structures. |
| **`Part_10_Signs_and_Outdoor_Display`** | Billboards, signs. | Route here for structural and placement rules regarding outdoor signs, billboards, and neon displays. |

## Sub-Directory Structure

Inside each `Part_XX` folder, the AI will find:
- `CLAUSE_ROUTER.md`: An index file mapping real-world engineering scenarios and keywords to specific Markdown clause files.
- `/clauses/`: Contains individual `.md` files for every section/clause.
- `/json/`: Contains structured tabular data extracted from the text.
- `/mmd/`: Contains Mermaid.js flowcharts for procedural logic.
- `/webp/`: Contains extracted diagrams and images in WebP format.
