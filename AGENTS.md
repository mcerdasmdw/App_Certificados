# App_Certificados — Data Repository

This repository stores input data for a certificate generation pipeline. **No application code lives here.**

## Contents

| File | Purpose |
|------|---------|
| `Insumos/Maestro_Estudiantes.xlsx` | Student master data (names, IDs, emails, etc.) |
| `Insumos/Registro_Evaluaciones.xlsx` | Evaluation records (scores, dates, course info) |

## Working with this repo

- **Read-only for agents** — Treat as a data source. Do not commit generated certificates or output files here.
- **Schema changes** — If column names/types change, update the consuming application (not in this repo).
- **No build/test/lint commands** — This is not a code project.

## Related

The certificate generation application that consumes these files lives in a separate repository.