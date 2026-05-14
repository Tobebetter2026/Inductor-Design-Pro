# Inductor Design Pro

Engineering workflow tool for magnetic component design with Pareto optimization, multi-loss analysis, and offline database support.

<p align="center">
  <img src="https://github.com/user-attachments/assets/652fcd57-b9da-487e-b771-ab0c3d4be0c4" width="720">
</p>

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
  <img src="https://github.com/user-attachments/assets/5754c925-3f07-4491-82cc-cb5a2b2a4281" width="780">
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
  <img src="https://github.com/user-attachments/assets/20c2a53b-d821-4d89-a76b-70829bc3bf8c" width="900">
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

## Screenshots

### Workflow Overview

![Workflow](screenshots/workflow-overview.png)

---

### Multi-Solution Pareto Comparison

![Pareto](screenshots/pareto-comparison.png)

---

### Database Management

![Database](screenshots/database-management.png)

---

## Availability

Available on the Apple App Store.

- iPhone
- iPad
- macOS

### App Store

[Download on the App Store](https://apps.apple.com/us/app/inductor-design-pro/id6758878884）

> Replace this link with your actual App Store URL.

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
