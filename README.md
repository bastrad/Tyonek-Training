# Tyonek Training

Training documentation for the subsidiary companies operating under the **Tyonek**
umbrella. Each subsidiary has its own folder; within it, each work process has a
folder containing a training document.

## Organization
Work processes within each subsidiary are organized with **lean principles**:
value-adding processes are grouped in flow order under `Value-Stream/`, and enabling
functions are grouped under `Support-Processes/`.

```
Tyonek-Training/
└── <Subsidiary>/
    ├── README.md                     (subsidiary overview)
    ├── Value-Stream/
    │   └── NN-<Work-Process>/
    │       ├── README.md             (training document, in flow order)
    │       ├── CERTIFICATIONS.md     (Required / Recommended / Nice-to-have certs)
    │       └── TRADE-PROGRESSION.md  (trade classification & Apprentice→Journeyman→Master path)
    └── Support-Processes/
        └── <Work-Process>/
            ├── README.md
            ├── CERTIFICATIONS.md
            └── TRADE-PROGRESSION.md
```

Every one of the **46 work-process folders** carries the same three documents, so any
role in the organization has a consistent training record, compliance checklist, and
career-progression map in one place.

**➡ See the [Trade & Progression Index](TRADE-INDEX.md) for all 46 trades on one page.**

## How I'd use this as a Training Manager
This repository is the working model I'd bring into the role — a single, version-controlled
source of truth for workforce development across every Tyonek subsidiary. Concretely:

- **Standardize training.** Every work process uses the same training-document template
  (purpose, procedure, safety/compliance, competency sign-off), so onboarding and
  cross-training are consistent from the shop floor to the flight line to the SOC.
- **Manage certification compliance for a govcon environment.** Each process lists its
  certifications grouped **Required / Recommended / Nice-to-have**, with every regulatory,
  statutory, and contract-flowed requirement marked **Required** (OSHA, EM 385-1-1, FAA
  Part 145, DCMA 8210.1C, IPC/J-STD, DoD 8570/8140, NISPOM, and more). This becomes the
  backbone of a training matrix that maps people → certs → contract requirements.
- **Build real progression pathways.** Each process is mapped to its recognized DOL /
  O*NET-SOC trade with an **Apprentice → Journeyman → Master** ladder, showing where the
  company could **register a U.S. DOL Apprenticeship** (a retention, recruiting, and
  workforce-pipeline win) versus where a certification/licensure ladder fits better.
- **Organize with lean thinking.** Grouping each subsidiary into a flow-ordered value
  stream plus support processes keeps training focused on what delivers customer value —
  and makes it obvious where quality is built in as a value-stream station.
- **Scale and hand off cleanly.** Because it's in Git, changes are tracked, reviewable,
  and auditable — the same discipline I'd apply to keeping a training program current as
  contracts, standards, and certifications evolve.

> Content is derived from Tyonek's public capability statements plus U.S. DOL/O*NET,
> OSHA, FAA, DoD, and industry-standard certification frameworks. It is a demonstration
> of approach — exact requirements would be validated against each active contract/SOW.

## Subsidiaries
| Folder | Subsidiary | Sector |
| --- | --- | --- |
| `Tyonek-Manufacturing-Group` | Tyonek Manufacturing Group, Inc. | Manufacturing |
| `Tyonek-Services-Group` | Tyonek Services Group, Inc. | Services (MRO) |
| `Tyonek-Mission-Support` | Tyonek Services Group, Inc. | Mission Support |
| `Tyonek-Contractor-Services` | Tyonek Contractor Services, LLC | Construction |

_More subsidiaries will be added as they are provided._

## Maintained by
Training Manager, Tyonek.
