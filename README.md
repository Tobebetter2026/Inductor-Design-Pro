# Inductor Design Pro

[![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20iPadOS%20%7C%20macOS-blue)]()
[![Offline](https://img.shields.io/badge/offline-local%20workflow-green)]()
[![App Store](https://img.shields.io/badge/App%20Store-Download-black)](https://apps.apple.com/us/app/inductor-design-pro/id6758878884)

Engineering workflow tool for magnetic component design with Pareto optimization, multi-loss analysis, and offline database support.

<img width="1536" height="1024" alt="image1" src="https://github.com/user-attachments/assets/6a170a58-6065-46bf-9f21-ca149b748d96" />

---

## Why This Tool Exists

While reorganizing Buck inductor design workflows, one thing became increasingly obvious:

The real time-consuming part is usually not the first calculation.

It is:

- changing cores
- changing wire gauges
- thermal iteration
- copper/core loss trade-offs
- repeated parameter linkage

Traditional spreadsheet workflows work well at the beginning.

But once projects become more complex:

- multiple cores
- multiple materials
- multiple winding options
- thermal optimization
- loss optimization

the workflow becomes difficult to maintain.

---

## Typical Engineering Problem

For the same 24μH target:

Different core and winding combinations may lead to:

- 0.7W vs 2W+ total loss
- 50°C vs 130°C hotspot temperature
- completely different copper/core loss ratios
- different window utilization
- different skin-effect behavior

The difficult part is often not:

> "Can it be calculated?"

but:

> "Can dozens of engineering trade-offs be compared efficiently?"

---

## Main Features

## Key Engineering Capabilities

- AP-method assisted core selection
- LI²-based toroid optimization
- Steinmetz / iGSE core-loss estimation
- AC copper-loss analysis
- Thermal co-estimation
- Pareto-front multi-solution comparison
- Core-winding joint iteration
- Offline engineering database

---

### Core × Winding Co-Optimization

Instead of selecting cores and windings separately,
the workflow jointly iterates:

- core selection
- winding selection
- thermal estimation
- copper loss
- core loss
- fill factor
- current density

---

### Pareto-Front Multi-Solution Comparison

Compare multiple candidate solutions simultaneously.

Useful for balancing:

- efficiency
- temperature
- size
- manufacturability

<p align="center">
  <img src="https://github.com/user-attachments/assets/4721ccc8-18a3-43fd-b63b-fd59afb3da72" width="980">
</p>

---

### Local Offline Workflow

All calculations run locally.

Design data is not uploaded to external servers.

Useful for:

- factory environments
- confidential projects
- offline engineering workflows

---

### Custom Local Database

Build your own reusable engineering database:

- core materials
- core models
- bobbins
- winding data

The database becomes part of accumulated engineering experience.

<p align="center">
  <img src="https://github.com/user-attachments/assets/12819f51-e873-4660-bff6-167df081d24b" width="900">
</p>

---

## Supported Topologies

- Buck
- Boost
- Forward
- Interleaved Buck (multi-phase)

### Operating Modes

- CCM
- DCM
- BCM

---

## Workflow

### Step 1 — Specifications & Constraints

Input:

- Vin range
- Vout
- Iout
- ripple target
- switching frequency
- thermal constraints

---

### Step 2 — Core & Winding Optimization

Joint iteration of:

- magnetic cores
- winding structures
- losses
- thermal estimation

with multi-solution comparison.

---

### Step 3 — Summary & Export

Generate:

- design summary
- loss analysis
- thermal results
- export files

---

## Why Not Just Excel?

Spreadsheets are flexible.

But once solution counts increase,
maintaining engineering trade-offs becomes increasingly difficult.

The goal of this workflow is not simply:

> "automatic calculation"

but rather:

> reducing repetitive engineering iteration.

---

## Availability

Available on the Apple App Store.

- iPhone
- iPad
- macOS

### App Store

[Download on the App Store](https://apps.apple.com/us/app/inductor-design-pro/id6758878884)

---

## Technical Support

Please use GitHub Issues for:

- bug reports
- feature requests
- workflow discussion

---

## License

All rights reserved.

This repository is used for:

- product introduction
- documentation
- issue tracking
- workflow discussion

Source code is not included.
