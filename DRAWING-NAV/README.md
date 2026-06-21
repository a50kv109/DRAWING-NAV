# DRAWING-NAV

Open protocol for transforming engineering drawings into human-readable and machine-readable semantic structures, graphs, and engineering passports.

## Overview
DRAWING-NAV is a specialized protocol designed to bridge the gap between static engineering drawings (PDF/IMG) and active engineering knowledge. It transforms drawings into structured data that AI agents, CAD systems, and engineers can navigate, query, and validate.

## Architecture
The protocol separates engineering drawings into three layers:
1. **Document Space:** Authority, revisions, standards, and responsibility.
2. **Geometry Space:** Dimensions, tolerances, views, and constraints.
3. **Semantic Space:** Functions, interfaces, load paths, and engineering meaning.

## Core Artifacts
- `INDEX.yaml` — The drawing passport.
- `NAV.md` — Human-readable navigation.
- `UTILITY.yaml` — Machine-readable API.
- `GRAPH.yaml` — Topological structure of the assembly.
- `SEMANTICS.yaml` — Functional meaning and critical links.

## License
Apache-2.0
