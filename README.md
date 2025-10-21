## Blind Docking of Catechin Gallate vs SARS-CoV-2 Main Protease (6LU7)

## Author: Sahil Khan • Date: 12 Sep 2025 • OS: Windows 11  
**Keywords:** molecular docking, CB-Dock2, PyMOL, ADMET, SwissADME, pkCSM, ProTox-II

## Overview
One-day blind docking mini-project against **Mpro (6LU7)** with **catechin gallate (CID 6419835)**.  
**Top pose:** Vina **−7.6 kcal/mol** in **Pocket 1** near **His41–Cys145**, with contacts to **Met49/Met165/Glu166**.  
**ADMET (snapshot):** SwissADME **low GI**; pkCSM **~62.1% absorption** with **hERG II** flag; ProTox-II **Class 4**, **LD50 ~1000 mg/kg**.  
**Note:** Educational; predictions require wet-lab validation.

## Repo map
- `input/` → cleaned receptor (`MproA_clean.pdb`), raw PDB, ligand SDF (+ optional N3).  
- `docking/` → best pose `top.pdb` (+ optional CB-Dock2 ZIP).  
- `report/` → 3 PyMOL figures, ADMET screenshots, `pocket_residues.csv`, `mini_report.pdf`.

## Quick reproduce (PyMOL 3.x trial, Windows)
1. **Load receptor + pose**
