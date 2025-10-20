# 01 — Concept Overview

**Context.** HackaHealth 2025 @ EPFL. Goal: restore natural, alternating arm swing and improve stability for a walker user (cerebellar ataxia) using **pure mechanics** (no electronics). Quiet operation preferred.

---

## Scope / Non-Goals
- **In scope:** opposing handle motion linked to gait; stable/safe integration on an existing walker; reproducible build.
- **Non-goals:** motors, sensors, software.

---

## Concepts (2 paths)

### A) GoFast — Gear-Based Transmission ✅ (kept)
- **Principle:** bevel-gear (*engrenage conique*) box generates **counter-rotation** of left/right shafts → opposing handle swing.
- **Core parts:** two coaxial shafts + 90° intermediate bevel pair; PETG 3D-printed gears; transparent PMMA gearbox; wooden supports; metal tubes; 3D-printed L-joints; original handles with brakes.
- **Why this:** compact, clear phase relation, didactic (visible), low noise when aligned.
- **Status:** implemented prototype. See `02_Structural_Design.md` and `03_Transmission_Mechanism.md`.

### B) Other Concept — placeholder (to be documented by the parallel team) ⏳
> This section is intentionally minimal and will be completed by the teammate responsible for the second approach.  
> **Do not edit unless you are the assigned author.**

**Fill later:**
- Principle:
- Main parts:
- Pros / Risks:
- Status:
- Links: `/docs/...`, `/design/...`

---

## Needs · Constraints · Objectives (concise)

**Needs**
- Natural alternating arm–leg coordination
- Low effort; **low noise** (quiet operation)

**Constraints**
- Purely mechanical (no electronics)
- Build with available hackathon materials; mount on existing frame
- Safety: enclosed gears, dependable brakes, stable base
- Reasonable weight/bulk

**Objectives**
1. Asynchronous / alternating handle motion  
2. Stability during push/pull cycles

---

## System at a Glance (GoFast)
- **Input:** user hands at handles  
- **Transmission:** bevel gears → counter-rotating shafts → metal tubes → 3D-printed L-joints → handles  
- **Structure:** PMMA gearbox on wooden columns/base; screws + zip ties for test stability  
- **Brakes:** manual lever brakes (details pending in `04_Brake_and_Control_System.md`)  
- *(Diagram to add: `/media/diagrams/concept_overview.svg`)*

---

## References to Detailed Docs
- `02_Transmission_Mechanism.md`
- `03_Brake_and_Control_System.md`
- `04_Ergonomics_Safety.md`
- `05_Material_Specifications.md` 
- `06_Assembly_Guide.md` 
- `07_Testing_and_Validation.md` 
- See also: `00_Summary.md` for team, notes, and brainstorming log.

---

## Status
- **GoFast** documented and shown.  
- **Other concept**: placeholder; to be updated by the assigned teammate.
