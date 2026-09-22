# Commercial Office Electrical Model | Autodesk Revit

An educational electrical BIM project for a two-storey office. I built the electrical model in Autodesk Revit 2027 using a linked architectural model as the building reference. The project covers electrical device placement, branch circuits, panel organization, and a Dynamo device audit.

## Project overview

| Item | Description |
|---|---|
| Software | Autodesk Revit 2027, Dynamo |
| Building | Two-storey commercial office |
| Model | `Office_Electrical.rvt` |
| Architectural reference | `Office_Architecture_2027.rvt` |
| Focus | Electrical distribution, receptacles, lighting, circuits, and model data |

## What I worked on

- Linked and pinned the architectural model in a separate electrical Revit project.
- Placed electrical equipment, receptacles, and lighting devices in the office model.
- Organized receptacles into branch circuits and assigned them to a panel.
- Added electrical annotations to communicate the intended distribution layout.
- Created a Dynamo graph for auditing device marks and circuit information.

## Model workflow

1. Open `Office_Electrical.rvt` in Revit 2027.
2. If Revit reports a missing architectural link, reload `Office_Architecture_2027.rvt` from its location on your computer.
3. Review the electrical views, equipment, devices, and circuits in the model.
4. Open the Dynamo `.dyn` file in Revit to inspect the device mark and circuit audit.

## Project scope

This is a portfolio model demonstrating my Revit MEP workflow. The six-sheet drawing set proposed in the original project plan was not produced. The model has not been issued for construction or reviewed as a code-compliant electrical design.

## Files

The Revit model contains the electrical work. The architectural model provides the building geometry; keep both files available so the link can be reloaded if needed. Any included `.dyn` file contains the Dynamo audit graph.

## Note

This project is for education and portfolio presentation only. Equipment selection, circuit loading, protection, conductor sizing, and code compliance would require further engineering review before use in a real installation.
