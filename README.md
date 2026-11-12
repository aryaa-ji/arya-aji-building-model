# Arya Aji – Building Information Model (IFC)

IFC export of a multi-storey building model, kept under version control so every revision is tracked.

## Model file

| | |
|---|---|
| **File** | `Arya_Aji_IFC.ifc` |
| **Schema** | IFC4 – Reference View 1.2 |
| **Authoring tool** | Autodesk Revit 2021 (IFC Exporter 21.0.0.383) |
| **Exported** | 4 June 2025 |
| **Units** | Millimetres (length), m² (area), m³ (volume) |
| **Size** | ~4.9 MB |

## Building levels

| Level | Elevation |
|---|---|
| Level 4 | +11.50 m |
| Level 3 | +9.00 m |
| Level 2 | +4.50 m |
| Level 1 | ±0.00 m |
| Level 5 | −0.53 m |
| Level 9 | −7.43 m |

## Elements in the model

| Element | Count | Element | Count |
|---|---|---|---|
| Members (mullions / framing) | 699 | Doors | 35 |
| Plates (curtain panels) | 194 | Curtain walls | 34 |
| Furniture | 136 | Spaces / rooms | 30 |
| Walls | 132 | Windows | 24 |
| Slabs | 74 | Plumbing fixtures | 22 |
| Columns | 64 | Railings | 8 |
| Beams | 46 | Stairs | 4 |
| Roofs | 2 | Coverings | 6 |

**Main materials:** cast-in-situ concrete, sand/cement screed, glass, aluminium, damp-proofing, ceiling tiles (600×600), cherry, pine, laminates.

## How to view the model

GitHub cannot preview IFC files. Download `Arya_Aji_IFC.ifc` and open it in any free IFC viewer, for example:

- **BIMvision** (Windows)
- **Open IFC Viewer** (Windows)
- **BlenderBIM / Bonsai** (Windows, macOS, Linux)
- **IfcOpenShell** (Python)

## Versions

Every update to the model is committed with the **same file name**, so GitHub keeps the full history.
- See all past versions: open `Arya_Aji_IFC.ifc` → **History**.
- Official versions are published under **Releases** (v1.0, v1.1, …).
- What changed in each version is listed in [CHANGELOG.md](CHANGELOG.md).

## Known issues (to fix in a future export)

- Project name / status still use Revit defaults ("Project Name", "Project Status").
- Site location is Revit's default (Boston, USA), not the real project site.
- Some materials are unnamed ("Default New Material (1–3)").

## Author

Arya Aji
