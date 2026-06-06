# 🚆 Aurora Express Wheel Assembly — Industrial Engineering Internship

> **Siemens Mobility Virtual Experience Programme | Forage**
> Industrial Engineering · Time Study Analysis · Lean Manufacturing · Facility Layout Optimisation

---

## 🏆 Business Impact First — Why This Work Matters

> *The gap between an assembly line that barely meets targets and one that consistently exceeds them is rarely a technology problem. It is almost always a process visibility problem.*

This project tackled exactly that.

The Aurora Express wheel assembly line was operating with **hidden inefficiencies** — not visible to the naked eye, not flagged by daily output numbers alone, but silently draining throughput, inflating cycle times, and exposing the operation to safety risk. The work delivered here surfaces those inefficiencies, quantifies them, and prescribes targeted interventions backed by data.

### 📊 Headline Business Impact

| Outcome | Detail |
|---|---|
| **Root Cause Identified** | Step 6 (Lubrication) carries **32.19% variability** — the highest of any step — indicating a process running almost entirely on operator intuition, with no standardisation. A single SOP intervention here is projected to recover 10–15% of wasted cycle time. |
| **Crane Bottleneck Exposed** | Step 14 (Wheel Mounting) is crane-dependent and accounts for a disproportionate share of total cycle time. Idle crane wait is pure non-value-added time. Pre-scheduling crane usage eliminates this without any capital expenditure. |
| **Safety & Liability Risk Quantified** | Step 15 (Torque Locking) shows 21.98% variability on a safety-critical fastening operation. In a rail vehicle, under-torqued wheel locks are not an operational inconvenience — they are a potential incident. This project flags that exposure and proposes concrete controls. |
| **Layout Redesign Proposed** | The facility layout proposal redesigns the assembly floor to eliminate fragmented crane travel paths, establish a closed-loop material flow circuit, and embed a worker wellbeing zone — projected to cut wheel press cycle time by **30–50%**. |
| **Total Cycle Time Reduction Target** | Full implementation of the recommendations targets a **20–35% reduction** in total assembly cycle time, directly improving on-time delivery performance and reducing per-unit labour cost. |

This is the difference between an assembly process that *works* and one that *performs*.

---

## 📁 Project Structure

```
 aurora-express-wheel-assembly/
├──  Aurora_Express_Time_Study_Professional.xlsx   ← Time study dataset + findings
│   ├── Sheet 1: Time Study Data                     (20 steps × 10 observations, colour-coded risk)
│   ├── Sheet 2: Findings & Recommendations          (structured bottleneck analysis)
│   └── Sheet 3: Variability Summary + Chart         (visual overview for quick review)
│
├──  Task_2_Proposal.pptx                          ← Facility layout redesign proposal
│   ├── Current layout with measured cycle times
│   ├── Proposed optimised layout (circuit flow)
│   ├── Justification, benefits & implementation strategy
│   └── Risk mitigation plan
│
└── 📄 README.md                                     ← You are here
```

---

##  The Problem

The Aurora Express wheel assembly station at Siemens Mobility exhibited three interlocking problems:

**1. Process Inconsistency Without Visibility**
No systematic time data existed at the element level. Supervisors could see that some shifts ran longer than others — but *why* and *where* was invisible. Without element-level observation data, targeting improvement efforts was guesswork.

**2. Crane-Constrained Material Flow**
The wheel press, the most capital-intensive station on the floor, was positioned far from the warehouse. Every single component entered and exited the wheel press via crane, traversing the full width of the facility. The crane had become the invisible gatekeeper throttling the entire line's throughput.

**3. Safety-Critical Steps Operating Without SOPs**
Several high-consequence operations — torque fastening, bearing installation, sensor placement — showed variability levels that indicated operators were self-directing technique rather than following documented standards. In rail manufacturing, that is unacceptable.

---

##  Methodology

### Task 1 — Time Study

A structured **direct time observation study** was conducted across the full 20-element wheel assembly sequence.

- **10 observations per element** — sufficient sample size to calculate statistical range and variability
- **Metrics captured:** Observed times (hrs), Average time, Range, and **Coefficient of Variation** (Range / Average × 100%)
- **Risk classification:** Each element was classified as `CRITICAL`, `High`, or `Normal` based on variability thresholds and operational consequences

```
CRITICAL  →  Variability > 25%  (immediate SOP action required)
High      →  Variability 15–25% OR safety-critical operation
Normal    →  Variability < 15%  (within acceptable control limits)
```

**Total measured cycle time: ~2.586 hours (155.2 minutes)**
The top 4 time-consuming steps represent **~30% of total cycle time**, confirming Pareto concentration of improvement opportunity.

### Task 2 — Facility Layout Analysis & Proposal

Using the time study data alongside direct facility observation, a **current-state layout analysis** was conducted to identify structural (non-process) contributors to inefficiency.

The redesign applied **lean manufacturing principles**:
- Proximity optimisation (warehouse ↔ wheel press adjacency)
- Circuit / closed-loop material flow elimination of backtracking
- Separation of worker recovery zones from hazardous operational areas
- Phased implementation to minimise production downtime during transition

---

##  Key Findings

### 🔴 Critical — Step 6: Lubricate Wheel Bearings

| Metric | Value |
|---|---|
| Average Time | ~1.5 hrs |
| Variability | **32.19%** |
| Risk Level | ⚠️ CRITICAL |

This is the most inconsistent step in the entire process. A standardised process running at 32% variability is a contradiction in terms — the standardisation has not been implemented effectively. Root causes include technique variation between operators, inconsistent tool usage, and absence of a documented procedure.

**Recommendations:**
- Develop and enforce detailed SOP (technique, tool, lubricant volume)
- Targeted operator training with competency sign-off
- Periodic technique audits

---

### 🟠 High Impact — Step 14: Mount Wheel to Axle

| Metric | Value |
|---|---|
| Average Time | ~5.4 hrs (max observed) |
| Variability | 7.09% |
| Root Cause | Crane availability dependency |

Low variability here does *not* mean this step is under control — it means the delay is structural and repeatable. The crane is always slow. Pre-scheduling and fixed staging positions are the interventions.

---

### 🟠 High Impact — Step 15: Secure Wheel with Locking Mechanism

| Metric | Value |
|---|---|
| Variability | **21.98%** |
| Risk Level | ⚠️ High — Safety Critical |
| Consequence | Under-torque = rail safety incident risk |

No other finding in this study carries higher real-world consequence. A torque operation that varies by 22% is not a process — it's a prayer. Mandatory torque verification, daily calibration checks, and operator rotation are non-negotiable controls.

<img width="1615" height="641" alt="Screenshot 2026-06-06 at 9 07 06 PM" src="https://github.com/user-attachments/assets/ead51c28-6a29-4d32-8882-ce05c1d3ba64" />

---

###  Layout Inefficiency — Wheel Press Position

The original layout places the wheel press at maximum distance from the warehouse, requiring full-facility crane traversals for every single component movement. The proposed layout relocates the wheel press adjacent to the warehouse, converting long-haul crane operations into short pick-and-drop movements.

**Projected impact:** 30–50% reduction in cycle time at the wheel press station.

<img width="1232" height="665" alt="Screenshot 2026-06-06 at 9 09 12 PM" src="https://github.com/user-attachments/assets/787d754e-1fa8-4136-a9d3-889af2284b5a" />
<img width="1223" height="668" alt="Screenshot 2026-06-06 at 9 09 39 PM" src="https://github.com/user-attachments/assets/98c81131-2b64-4b2e-a48a-e13649937482" />

---

## 💡 Recommendations Summary

| Priority | Step | Issue | Recommendation |
|---|---|---|---|
| 🔴 Immediate | Step 6 | 32.19% variability | Develop SOP, training programme, tool standardisation |
| 🟠 High | Step 14 | Crane wait time | Pre-schedule crane, fixed staging positions |
| 🟠 High | Step 15 | Safety-critical, 21.98% var | Torque SOP, PPE protocol, operator rotation |
| 🟠 High | Step 4 | Fatigue-driven variability | Job rotation, ergonomic workstation, pneumatic assists |
| 🟡 Medium | Steps 19–20 | Documentation & transport | Digitise docs, standardise transport route |
| 🏗️ Strategic | Facility layout | Crane-dependent bottleneck | Implement proposed circuit-flow layout redesign |

---

## 🛠️ Tools & Skills Applied

| Domain | Tools / Techniques |
|---|---|
| Industrial Engineering | Time and Motion Study, Elemental Time Analysis |
| Process Analysis | Bottleneck Identification, Coefficient of Variation, Pareto Analysis |
| Lean Manufacturing | 5S, SOP Development, Waste Elimination (Muda) |
| Facility Design | Layout Optimisation, Circuit Flow Design, Proximity Analysis |
| Data Analysis | Microsoft Excel (statistical modelling, conditional formatting, charting) |
| Communication | Executive findings report, stakeholder presentation (PowerPoint) |



---

##  About This Project

This project was completed as part of the **Siemens Mobility Virtual Experience Programme** hosted on [Forage](https://www.theforage.com/), an online platform offering real-world job simulations from leading global companies.

The programme simulates the work of an **Industrial Engineering intern** at Siemens Mobility, one of the world's leading providers of integrated transport technology.

> **Disclaimer:** This is a virtual internship simulation. Data and scenarios are representative of real industrial engineering work but are provided by Forage/Siemens Mobility for educational purposes.
>
<img width="1126" height="830" alt="Screenshot 2026-06-06 at 9 10 58 PM" src="https://github.com/user-attachments/assets/07394cf9-f29e-4b3d-b63e-ba957fab7ef6" />


---

##  Contact

Feel free to connect or reach out if you'd like to discuss the methodology, findings, or applications of industrial engineering in manufacturing environments.

---

*Built with rigour. Designed to inform decisions.*
