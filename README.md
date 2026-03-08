# Process Safety Study — Risk-Based Analysis of Hazardous Chemical Storage

> **Independent Chemical Engineering Project**
> Process Safety · HAZID · Risk-Based Process Safety (RBPS)
> *Chemistry and Engineering of Organic Compounds | Petrochemistry and Carbochemistry*

---

## What This Project Does

Applies **Risk-Based Process Safety (RBPS)** principles from AIChE ELA 950–952 training to analyze a hypothetical bulk ammonia storage facility. Identifies credible hazard scenarios, maps them against a structured risk matrix, and documents safeguard recommendations — following the AIChE CCPS methodology used in real industrial practice.

---

## Why Ammonia Storage?

Ammonia (NH₃) is a critical intermediate in **organic chemical and petrochemical industries:**
- Feedstock for nitric acid, urea, and fertilizer production
- Refrigerant in industrial cooling systems
- Building block for numerous organic nitrogen compounds

It is also a **high-consequence hazard** — toxic (IDLH: 300 ppm), flammable (15–28% in air), and stored in bulk quantities. It is a standard case study in professional process safety training worldwide.

---

## Facility Studied (Hypothetical)

| Parameter | Value |
|-----------|-------|
| Storage type | Atmospheric refrigerated tank |
| Capacity | 1,000 tonnes liquid ammonia |
| Operating temperature | −33°C (atmospheric boiling point) |
| Operating pressure | ~1.013 bar |

---

## HAZID Results — 4 Nodes Analyzed

### Node 1: Tank Overpressure
| | |
|--|--|
| **Hazard** | Tank rupture from blocked relief path under heat ingress |
| **Causes** | Solar radiation, fire exposure, PRV blocked or undersized |
| **Consequence** | Catastrophic vapor cloud release |
| **Risk level** | HIGH |
| **Safeguards** | PRV, high-pressure alarm, insulation |
| **Recommendation** | Secondary relief valve; SIS high-pressure shutdown; MOC-controlled PRV testing |

### Node 2: Liquid Leak — Transfer Line
| | |
|--|--|
| **Hazard** | Flange leak → flash vaporization → toxic cloud |
| **Causes** | Flange degradation, vibration fatigue, improper installation |
| **Consequence** | Downwind LC50 exposure zone |
| **Risk level** | MEDIUM–HIGH |
| **Safeguards** | Gas detectors, deluge system, PPE |
| **Recommendation** | Double-block-and-bleed isolation; enhanced leak detection coverage |

### Node 3: Loading/Unloading Interface
| | |
|--|--|
| **Hazard** | Hose rupture from premature vehicle departure |
| **Causes** | Operator error, missing interlock |
| **Consequence** | Liquid ammonia spill at grade |
| **Risk level** | MEDIUM |
| **Recommendation** | Automated wheel-lock interlock tied to loading arm connection |

### Node 4: Loss of Refrigeration
| | |
|--|--|
| **Hazard** | Temperature rise → boil-off → PRV venting |
| **Causes** | Power failure, compressor trip |
| **Risk level** | MEDIUM |
| **Recommendation** | UPS backup for refrigeration controls; automatic switchover |

---

## Risk Matrix

```
                    CONSEQUENCE
                 Minor  | Moderate |  Major  | Catastrophic
              ──────────────────────────────────────────────
 Frequent     | Medium |   High   |  High   |  CRITICAL
 Probable     |  Low   |  Medium  |  High   |  CRITICAL
 Occasional   |  Low   |   Low    | Medium  |   High
 Remote       |  Low   |   Low    |  Low    |   Medium

 Node 1: Remote    × Catastrophic = HIGH
 Node 2: Occasional × Major       = MEDIUM–HIGH
 Node 3: Probable  × Moderate     = MEDIUM
 Node 4: Probable  × Major        = HIGH
```

---

## RBPS Framework — Elements Applied

| RBPS Element | Application in This Study |
|-------------|--------------------------|
| Understand Hazards & Risks | HAZID nodes 1–4; severity estimation |
| Manage Risk | Safeguard identification per node |
| Management of Change | PRV testing flagged as MOC-controlled |
| Conduct Operations | Loading interlock recommendation |
| Emergency Management | Evacuation zone considerations |

---

## Certifications That Informed This Study

| Certification | Issuer | Content |
|--------------|--------|---------|
| AIChE ELA 950 | American Institute of Chemical Engineers | Introduction to Process Safety |
| AIChE ELA 951 | AIChE CCPS | Risk-Based Process Safety (RBPS) |
| AIChE ELA 952 | AIChE CCPS | Management of Change (MOC) |

---

## Key Findings

1. Overpressure and refrigeration failure are the **highest-priority risks** — require layered protection (BPCS + SIS)
2. Human factors at loading interfaces are **underappreciated** — engineered interlocks substantially reduce risk
3. All safeguards must be subject to **MOC control** — modifications without review are a leading cause of incidents

---

## References

- AIChE CCPS, *Guidelines for Risk-Based Process Safety* (2007)
- AIChE CCPS, *Guidelines for Hazard Evaluation Procedures* (3rd Ed.)
- IEC 61511 — Functional Safety for the Process Industry Sector
- OSHA 29 CFR 1910.119 — Process Safety Management Standard

---

*Zidanur Rahman | Independent Chemical Engineering Study | 2025*
*Based on AIChE ELA 950–952 certified training | Prepared as part of Romanian Government Scholarship application*
