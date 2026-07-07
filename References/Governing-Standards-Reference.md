🏠 [Home](../README.md) · ⬆ [References](README.md)

---

# Governing Standards — The Catalog of What Requires Training

**This is the single, canonical list** of the outside rules — safety law, environmental law,
quality standards, and contract/security mandates — that *require* training across Tyonek.
Because Tyonek is a **government contractor**, anything a regulation, statute, or contract flows
down is **Required**.

Both the [Gap Analysis worksheet](../Program-Management/templates/Training-Needs-Gap-Analysis.md)
and the [Requirements Verification process](../Program-Management/01-Requirements-Verification-Process.md)
draw their "required" list from **this** catalog. For the official website to obtain or review
each item, see the [Link Directory](Training-and-Certification-Links.md).

> **How to read this catalog:**
> - **Applies to** — which companies a rule affects: **MFG** (Manufacturing), **MRO** (Aviation
>   Services), **MS** (Mission Support), **CON** (Construction), **ALL** (every subsidiary).
> - **🟢 public-domain** = free to read/copy · **🔒 copyrighted** = buy from the publisher (full
>   text is not stored in this repo).
> - Editions/frequencies are the general baseline — **verify the current revision** at the source.
> - A citation like `29 CFR 1910.147` means *Title 29, Code of Federal Regulations, Part 1910,
>   Section 147* — you can look up any rule by its citation.

---

## A. Workplace Safety — OSHA 🟢
**Issuer:** U.S. DOL / OSHA · **Master index:** OSHA Publication 2254, *Training Requirements in OSHA Standards* · **Where:** osha.gov · ecfr.gov (29 CFR)

OSHA has no single "safety class" — *each hazard* has its own training rule.

| Standard | What it requires (plain) | Applies to | Recurrence |
|---|---|---|---|
| 1910.1200 Hazard Communication | Know the chemicals you work with (labels, safety data sheets) | ALL | Initial + on new hazard |
| 1910.147 Lockout/Tagout | Safely shut off machine energy before service | MFG, MRO, CON | Initial + on change |
| 1910.132/.133 PPE / eye & face | Correct selection and use of protective equipment | ALL | Initial + on change |
| 1910.134 Respiratory Protection | Proper respirator use + medical clearance | MFG (paint/weld), MRO | **Annual** fit test/training |
| 1910.95 Hearing Conservation | Protect hearing in high-noise areas | MFG, MRO | **Annual** (over action level) |
| 1910.1026 / .1025 / .1053 Hex chrome / Lead / Silica | Handle weld fume, lead, and silica dust safely | MFG (weld, coatings) | Per exposure |
| 1910.178 Powered Industrial Trucks | Certified to operate forklifts | MFG, MRO, CON | Eval **every 3 yrs** |
| 1910.146 Confined Space | Safe entry into tanks/booths/vaults | MFG, MRO, CON | Initial + on change |
| 1910.120 HAZWOPER | Hazardous-material / emergency response | MRO, CON | 24–40 hr + **8 hr annual** |
| 1910.157 / .38 Fire Extinguisher / Emergency Action Plan | Respond to fire and evacuate | ALL | Initial + **annual** |
| 1910.252 Welding / Cutting / Hot Work | Safe hot-work practices, fire watch | MFG, MRO | Initial |
| 1910.331–.335 Electrical safe work | Safe work around energized systems | MFG, MRO, MS | Initial |
| 1910.1030 Bloodborne Pathogens | Exposure control (first-aid responders) | ALL (first-aid teams) | **Annual** |

## B. Environmental & Hazardous Material Handling / Shipping
| Standard | What it requires (plain) | Applies to | Recurrence | Where |
|---|---|---|---|---|
| 49 CFR 172.704 (DOT Hazmat) 🟢 | Anyone who ships/handles dangerous goods must be trained | MFG, MRO, MS, CON | **Every 3 yrs** | ecfr.gov · phmsa.dot.gov |
| IATA Dangerous Goods 🔒 | Air-shipment-specific dangerous-goods training | MFG, MRO, MS | ~**24 months** | iata.org |
| 40 CFR 262.17 (RCRA generator) 🟢 | Manage/store hazardous waste properly | MFG, MRO | Initial + **annual** (LQG) | ecfr.gov · epa.gov/hw |
| EPA NESHAP 6H (coatings) 🟢 | Painter training for spray coatings | MFG (coatings) | Per rule | ecfr.gov |

## C. Quality Management Systems 🔒 (copyrighted — purchase from publisher)
These require the company to *prove* its people are competent and aware — training is how you meet them.

| Standard | What it requires (plain) | Applies to | Where to obtain |
|---|---|---|---|
| ISO 9001:2015 (cl. 7.2 / 7.3) | Ensure & document competence; awareness of one's role in quality | ALL | iso.org |
| AS9100 Rev D (aerospace) | Adds product **safety**, ethics, and **Human Factors** awareness | MFG | sae.org |
| AS9110 Rev C (aviation maintenance) | Competence + human factors tailored to MRO | MRO | sae.org |
| Nadcap special-process checklists (AC71xx) | Operator qualification/training for weld, coatings, NDT, etc. | MFG | p-r-i.org |

## D. Aviation Maintenance — FAA & Defense 🟢
| Standard | What it requires (plain) | Applies to | Recurrence | Where |
|---|---|---|---|---|
| 14 CFR 145.163 (Repair Station Training) | FAA-**approved** employee training program; each person capable of the task | MRO | Initial + recurrent; records ≥2 yrs | ecfr.gov · AC 145-10 |
| 14 CFR Part 65 (A&P) | Airframe & Powerplant mechanic certificate | MRO | Certificate + IA renewal | faa.gov |
| 14 CFR Part 120 (Drug & Alcohol) | Program training for safety-sensitive staff | MRO | Initial + recurrent | faa.gov |
| DCMA 8210.1C (Flight & Ground Ops) | Qualify personnel to approved flight/ground procedures | MRO | Per program | dcma.mil |
| MIL-HDBK-516 (Airworthiness) | Airworthiness certification criteria (reference) | MRO | Reference | DoD |

## E. Electronics & Welding Workmanship 🔒
| Standard | What it requires (plain) | Applies to | Where |
|---|---|---|---|
| IPC J-STD-001 / A-610 / A-620 / 7711-7721 | Certified soldering / assembly / harness / rework workmanship (~2-yr recert) | MFG | ipc.org |
| ANSI/ESD S20.20 | Protect electronics from static damage | MFG, MS | esda.org |
| AWS D17.1 (aerospace welding) | Welders tested/qualified to the code | MFG | aws.org |

## F. Defense Security & Cybersecurity 🟢 (government)
| Standard | What it requires (plain) | Applies to | Recurrence | Where |
|---|---|---|---|---|
| NISPOM — 32 CFR Part 117 | Security briefings + insider-threat awareness for cleared staff | MRO, MS | Initial + **annual** | dcsa.mil · ecfr.gov |
| DoD 8570.01-M / DoDM 8140 | Baseline certification for cyber roles + annual cyber awareness | MS | Cert + **annual** | public.cyber.mil |
| ITAR / EAR (export control) | Handle controlled technical data lawfully | MFG, MRO, MS | Initial + **annual** | pmddtc.state.gov / bis.doc.gov |
| COMSEC | Handle communications-security material | MRO, MS | Per custodian program | (agency) |
| CDSE curricula (free training) | FSO, COMSEC, insider-threat, CUI courses | MRO, MS | Per course | cdse.edu |

## G. Construction Safety & Quality (federal) 🟢
| Standard | What it requires (plain) | Applies to | Recurrence | Where |
|---|---|---|---|---|
| OSHA 29 CFR 1926 | Fall (.503), excavation (.651), scaffold (.454), crane (.1427) + competent persons | CON | Initial + designations | osha.gov |
| USACE EM 385-1-1 | Site Safety & Health Officer (40-hr + refresher); activity hazard analyses | CON | 40-hr + **8-hr annual** | usace.army.mil |
| CQM-C (Construction Quality Mgmt for Contractors) | QC manager qualification on federal jobs | CON | Course (renewal) | USACE/NAVFAC |

## H. Workforce / Apprenticeship 🟢 (government)
| Resource | What it provides | Applies to | Where |
|---|---|---|---|
| Registered Apprenticeship (29 CFR 29 & 30) | Apprentice → Journeyworker standards; sponsor programs | ALL | apprenticeship.gov |
| O*NET-SOC occupation data | Trade classification codes used in each `TRADE-PROGRESSION.md` | ALL | onetonline.org |

---

## How to use this catalog
1. When building a work process's **Requirements Register** or **Gap Analysis**, pull the rows
   whose **Applies to** tag matches the subsidiary, then add the process's own `CERTIFICATIONS.md`.
2. Confirm the **current revision** at the source (see the [Link Directory](Training-and-Certification-Links.md)).
3. For **copyrighted** standards, work from a **licensed current copy** — never a summary or reprint — for compliance decisions.

## Official sources
- [OSHA 2254 — Training Requirements in OSHA Standards](https://www.osha.gov/sites/default/files/publications/OSHA2254.pdf) · [OSHA training by topic](https://www.osha.gov/publications/bytopic/training)
- [49 CFR 172.704 — DOT Hazmat Training](https://www.ecfr.gov/current/title-49/subtitle-B/chapter-I/subchapter-C/part-172/subpart-H/section-172.704) · [40 CFR 262.17 — RCRA training](https://www.ecfr.gov/current/title-40/chapter-I/subchapter-I/part-262)
- [14 CFR 145.163 — Repair Station Training](https://www.ecfr.gov/current/title-14/chapter-I/subchapter-H/part-145/subpart-D/section-145.163) · [FAA AC 145-10](https://www.faa.gov/documentLibrary/media/Advisory_Circular/AC_145-10.pdf)
- AS9100 Rev D / AS9110 Rev C (SAE); ISO 9001:2015 (ISO); NISPOM 32 CFR Part 117; DoD 8570.01-M / 8140; USACE EM 385-1-1
- Full official-site directory: [Training-and-Certification-Links.md](Training-and-Certification-Links.md)

> **Note:** Frequencies and applicability here are the general regulatory baseline. Confirm the
> exact interval and applicability against the current standard text and each active
> contract/SOW during requirements verification.
