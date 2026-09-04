# 1KB_SRAM
<div align="center">

# 🧠 1KB SRAM — RTL to GDSII Physical Design

**A complete RTL-to-GDSII physical design implementation of a 1Kb single-port synchronous SRAM**

![Node](https://img.shields.io/badge/Technology-45nm-blue)
![Tool](https://img.shields.io/badge/Tool-Cadence%20Innovus%2023.16--s070__1-informational)
![Status](https://img.shields.io/badge/Setup%20WNS-1.167ns-brightgreen)
![Status](https://img.shields.io/badge/Hold%20WNS-0.000ns-brightgreen)
![DRC](https://img.shields.io/badge/DRC%20Violations-0-brightgreen)
![Freq](https://img.shields.io/badge/Frequency-285.714MHz-orange)

</div>

## 🔍 Overview

| | |
|---|---|
| **Project** | 1KB SRAM — Full RTL-to-GDSII Physical Design |
| **Technology Node** | 45nm |
| **Tool Flow** | RTL → Genus (Synthesis) → Innovus (PnR) → GDSII |
| **Innovus Version** | 23.16-s070_1 |

---

## 🧩 Design Specification

| Parameter | Value |
|---|---|
| **Type** | Single-port synchronous SRAM (valid/ready handshake) |
| **Size** | 1Kb (1024 bits) = 64 × 16 |
| **Depth** | 64 words |
| **Width** | 16 bits/word |
| **Address Width** | 6 bits |
| **Reset** | Synchronous, active-high |

---

## 🏗️ Floorplan & Physical Metrics

| Metric | Value |
|---|---|
| **Chip Area** | 8145.072 µm² |
| **Core Area** | 6418.656 µm² |
| **Standard Cell Area** (excl. physical-only cells) | 3609.810 µm² |
| **Utilization** | 57.24% |
| **Cell Count** | 1173 |

---

## ⏱️ Timing Closure Summary

### Setup
| WNS | TNS | Violating Paths |
|---|---|---|
| **1.167 ns** | 0.000 ns | 0 / 562 |

### Hold
| WNS | TNS | Violating Paths |
|---|---|---|
| **0.000 ns** | 0.000 ns | 0 |

### Design Rule Checks (DRC)
| max_cap | max_tran | max_fanout | max_length |
|---|---|---|---|
| ✅ 0 | ✅ 0 | ✅ 0 | ✅ 0 |

> ✅ Design is **fully timing clean** — zero setup, hold, and DRC violations.

---

## ⚡ Power Summary

**Operating Frequency:** 285.714 MHz (Clock Period = 3.5 ns)

| Power Type | Value | % of Total |
|---|---|---|
| **Internal Power** | 0.221 mW | 70.25% |
| **Switching Power** | 0.093 mW | 29.70% |
| **Leakage Power** | 0.00017 mW | 0.05% |
| **Total Power** | **0.314 mW** | 100% |

### Power by Category
| Category | Share |
|---|---|
| Sequential (flops) | 58.69% |
| Clock network | 21.79% |
| Combinational | 19.53% |

---

## 🖼️ Visuals

### Floorplan
<img width="1920" height="1080" alt="floorplan" src="https://github.com/user-attachments/assets/6d8f4d71-4676-4143-b3e9-fb9504271aee" />

### Port Placement
<img width="1920" height="1080" alt="port_placement" src="https://github.com/user-attachments/assets/8d4c2236-aa32-4087-bf9b-e79a442ac674" />

### Power Plan
<img width="1920" height="1080" alt="power_plan" src="https://github.com/user-attachments/assets/51fc6dcd-2bad-4680-9a5d-5aa9c3f38607" />

### Standard Cells Placed
<img width="1920" height="1080" alt="standard_cells_placed" src="https://github.com/user-attachments/assets/ef71d86a-4cac-4c6c-ab3b-b65425ec4911" />

### Metal Layers (M9 → M1)
<img width="1920" height="1080" alt="layer9" src="https://github.com/user-attachments/assets/3f8e7873-c058-46e2-9e12-c667107e8c80" />
<img width="1920" height="1080" alt="layer8" src="https://github.com/user-attachments/assets/734e750c-1eff-46a6-a982-2b9b61660c34" />
<img width="1920" height="1080" alt="layer6" src="https://github.com/user-attachments/assets/6071a323-2aa3-46af-9c50-f5303637a259" />
<img width="1920" height="1080" alt="layer5" src="https://github.com/user-attachments/assets/a7e73291-ed43-4959-bebe-82baec6110ef" />
<img width="1920" height="1080" alt="layer4" src="https://github.com/user-attachments/assets/556b759f-6b2b-4877-a94f-cfd9fd29f75f" />
<img width="1920" height="1080" alt="layer3" src="https://github.com/user-attachments/assets/6a8355bc-e4bb-4066-84d1-bb90da78963f" />
<img width="1920" height="1080" alt="layer2" src="https://github.com/user-attachments/assets/94b885dc-c99d-4b41-ba42-9ac502d5f055" />
<img width="1920" height="1080" alt="layer2" src="https://github.com/user-attachments/assets/7f143544-e027-45e3-bd3f-4b353da2a627" />

### Pre-CTS
<img width="1920" height="1080" alt="pre_cts" src="https://github.com/user-attachments/assets/45fc096e-3edd-4f55-a163-167bcc45b611" />

### Post-CTS
<img width="1920" height="1080" alt="post_cts" src="https://github.com/user-attachments/assets/a2395760-0ddb-4358-a48d-67031bf13313" />

### Clock Tree
<img width="1920" height="1080" alt="clocktree" src="https://github.com/user-attachments/assets/e2886077-1b8c-41e9-b0c3-297077b713c0" />

---

<div align="center">

**Built using the Cadence RTL-to-GDSII flow — Genus (Synthesis) → Innovus (Place & Route)**

</div>












