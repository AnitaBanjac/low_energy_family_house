# Low-Energy Family House — Thermal Modelling Package

Thermal modelling package for a representative low-energy single-family house including:

- a high-fidelity IDA ICE building model,
- a reduced-order state-space thermal model,
- matching Zagreb Typical Meteorological Year (TMY) weather data.

The repository is intended for:
- building thermal dynamics research,
- HVAC control design,
- model predictive control (MPC),
- thermal comfort analysis,
- student projects and teaching.

---

# Repository Structure

```text
docs/                   Exported documentation (PDF)
model_ida_ice/          IDA ICE project and weather files
model_state_space/      Reduced-order state-space model
```

---

# Included Models

## IDA ICE High-Fidelity Model

The repository contains a detailed multi-zone IDA ICE building energy model of a low-energy detached single-family house designed for the continental climate of the Zagreb region, Croatia.

The IDA ICE model includes:
- full 3-D geometry,
- layer-by-layer envelope constructions,
- HVAC system configuration,
- occupancy and internal gains,
- integrated TMY weather data.

---

## Reduced-Order State-Space Model

A semi-physical linear state-space model identified from IDA ICE simulation data is included for:
- fast simulation,
- control design,
- MPC/PID applications,
- thermal dynamics studies.

The model contains:
- air-temperature states,
- thermal-mass states,
- weather and solar irradiation inputs,
- per-zone heating/cooling inputs.

---

# Weather Data

The repository includes Typical Meteorological Year (TMY) weather data for the Zagreb region, Croatia.

The weather data are provided in formats suitable for:
- IDA ICE,
- MATLAB / Simulink workflows.

---

# Requirements

## IDA ICE Model
- IDA ICE 4.8 or newer

## State-Space Model
- MATLAB / Simulink

---

# Citation

If you use this repository in academic work, please cite:

1. A. Banjac and D. Prvonožec,  
   *Optimizing Insulation Thickness for Energy and Cost Efficiency in Residential Buildings: A Case Study*,  
   Proc. 11th International Conference on Control, Decision and Information Technologies (CoDIT), 2025.

2. D. Prvonožec and A. Banjac,  
   *Thermal Comfort-Based vs Temperature-Based Control in a Single-Family House: Impacts on Energy Use and Occupant Comfort*,  
   SpliTech 2026.

---

# License

This repository is licensed under the CC BY 4.0 License.

https://creativecommons.org/licenses/by/4.0/
