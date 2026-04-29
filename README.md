# 🌿 Life Cycle Assessment — Wooden Chair (Cradle to Gate)

**Escuela Colombiana de Ingeniería Julio Garavito · May 2022**

*Jahily Andrea Morales Fonseca & Carlos Andrés Pino Hernández*
---

## 📋 Overview

This project presents a full **Life Cycle Assessment (LCA)** of a wooden chair 
manufactured in a non-technified workshop in Bogotá, Colombia, following the 
**ISO 14040** standard methodology.

The study quantifies greenhouse gas (GHG) emissions across all stages of the 
product lifecycle — from raw material extraction in the Caquetá rainforest to 
the finished chair leaving the workshop gate.

---

## 🎯 Objective

Determine the **carbon footprint** of a wooden chair produced in informal 
manufacturing conditions in Bogotá, identifying the lifecycle stages with the 
greatest environmental impact and proposing improvement opportunities.

---

## 🔬 Methodology

| Item | Detail |
|------|--------|
| Standard | ISO 14040 |
| System boundary | Cradle to gate |
| Functional unit | 1 wooden chair (15-year useful life) |
| Impact category | Global Warming (GWP100) |
| Characterization method | ReCiPe Hierarchist |
| GHG boundary | Kyoto Protocol gases (CO₂, CH₄, N₂O) |
| Inventory tool | Matrix calculation in Excel |
| Data quality assessment | Pedigree Matrix |

---

## 🌲 System Boundary — Lifecycle Stages

```
┌─────────────────┐    ┌───────────┐    ┌────────────────┐    ┌─────────────────┐
│  RAW MATERIAL   │    │  SAWMILL  │    │  DISTRIBUTION  │    │  MANUFACTURING  │
│   EXTRACTION    │───▶│           │───▶  Caquetá–Bogotá│ ───▶    Workshop    │
└─────────────────┘    └───────────┘    └────────────────┘    └─────────────────┘
  • Felling              • Debarking      • 480 km truck         • Cutting
  • Delimbing            • Sawing         • Diesel semi-truck     • Turning
  • Skidding             • Drying                                 • Sanding
  • Transport            • Planing                                • Assembly
    to sawmill                                                    • Varnishing
```
---

## 📊 Key Results

| Lifecycle Stage | kg CO₂ | % of Total |
|----------------|--------|------------|
| Distribution | 1.718 | 30.4% |
| Sawmill | 1.507 | 26.6% |
| Raw Material Extraction | 1.099 | 19.4% |
| Manufacturing | 0.550 | 9.7% |
| Adhesive Production | 0.519 | 9.2% |
| Transport to Sawmill | 0.440 | 7.8% |
| Varnishing | 0.012 | 0.2% |
| Assembly | 0.000 | 0.0% |
| Felling & Delimbing | -0.303 | negative (CO₂ absorption) |

### 🏁 Total Carbon Footprint: **5.66 kg CO₂eq per chair**

> Over **80% of the total impact** is concentrated in distribution, 
> the sawmill and raw material extraction.

---

## 💡 Key Findings

- **Distribution is the largest contributor** — the 480 km fossil-fuel truck 
  route from Caquetá to Bogotá generates ~30% of total emissions.
- **Tree carbon absorption offsets** felling emissions, resulting in a 
  net negative value for that stage.
- **Assembly produces zero emissions** — it is entirely manual with no 
  electricity consumption.
- **Adhesive (Colbón) has a disproportionate impact** — representing only 
  2.5% of product mass, its production generates nearly as much GHG as the 
  entire manufacturing stage.
  
---
## 📁 Repository Contents

## 📁 Repository Contents

```
📄 LCA_Wooden_Chair_Report.pdf     → Full study report (ISO 14040)
📊 Inventory_Matrix.xlsx           → Excel matrix with all unit process 
                                     calculations (A & B matrices)
```
