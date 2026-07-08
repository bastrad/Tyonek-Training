# Requirements Verification Process

**Purpose:** Replace the industry-informed *defaults* currently in each `CERTIFICATIONS.md`
and `TRADE-PROGRESSION.md` with **verified, actual requirements** for every work process —
so the training program is built on truth, not assumption. This is the **Plan** phase and
the foundation ("true north") for the continuous-improvement loop.

> This is a U.S. Government contract environment. When a contract, regulation, or statute
> flows a requirement, it is **Required** — no exceptions. Verification proves *which*
> requirements apply, to *whom*, at what *revision*, and with what *evidence*.

---

## 1. Source-of-Truth Hierarchy
Verify each requirement against the highest applicable authority. When sources conflict, the
higher tier governs (and contract-specific terms can only add to, not waive, regulation).

1. **Active contracts / task orders / SOW / PWS** — flowed-down clauses (FAR/DFARS), DID/CDRLs,
   Quality Assurance Surveillance Plans (QASPs), customer-specific training mandates.
2. **Regulation & statute** — OSHA (29 CFR 1910/1926), EPA (RCRA/NESHAP), FAA (14 CFR 65/120/145),
   DoD (8570.01-M / 8140), DCMA 8210.1C, USACE EM 385-1-1, NISPOM (32 CFR 117), ITAR/EAR.
3. **Quality system & accreditation** — ISO 9001, AS9100/AS9110, NADCAP, FAA Part 145 RSQM,
   IPC/J-STD program requirements.
4. **Certifying / standards bodies** — AWS, IPC, ASQ, FAA, BCSP, NFPA, DoL Registered
   Apprenticeship standards, O*NET occupation data.
5. **Customer / OEM specifications** — drawing-called specs, source-control drawings, build-to-print.
6. **State / local & business** — state licensing (e.g., Alaska GC), bonding/insurance, AHJ codes.

> **Starting reference:** the [governing-standards catalog](Governing-Standards-Reference.md)
> is a ready-made, plain-language list of the regulatory sources that mandate training
> (OSHA, EPA/DOT, ISO 9001 / AS9100 / AS9110, FAA Part 145, IPC/AWS, NISPOM / DoD 8570,
> EM 385-1-1). Use it as the starting checklist when building each Requirements Register —
> then confirm the exact citation and current revision here.

## 2. Process Steps
Run this per work process (all 46), owned by the assigned Process Owner/SME with the Training
Manager coordinating.

1. **Assign ownership** — name a Process Owner/SME and supporting functions (Contracts, QA,
   Security, HR) using the RACI in the area README.
2. **Build the Requirements Register** — seed it from the current `CERTIFICATIONS.md` and
   `TRADE-PROGRESSION.md` line items (use the template). One row per requirement.
3. **Identify the authoritative source** for each row using the hierarchy above; record the
   exact citation (regulation section, contract clause, standard + revision, cert-body page).
4. **Verify applicability** — does it apply to this work, to which roles, and under which
   contracts? Distinguish always-on (regulatory) vs. contract-conditional requirements.
5. **Verify currency** — confirm the standard/cert is at the current revision and note the
   next known revision or expiration driver.
6. **Confirm classification** — Required / Recommended / Nice-to-have, per this environment
   (regulatory/contract-flowed = **Required**).
7. **Reconcile** — mark each row **Confirmed / Revised / Added / Removed**, with rationale.
8. **Update the repo** — apply approved changes to the subsidiary `CERTIFICATIONS.md` /
   `TRADE-PROGRESSION.md` via normal Git change control (commit = the audit trail).
9. **Baseline & schedule re-verification** — record the verification date, verifier, and the
   next re-verification trigger/date (see §5).

## 3. Verification Methods
- **Document review** — read the actual contract/SOW, regulation text, and standard (not a summary).
- **Structured interviews** — Contracts/PM for flow-downs; QA for standards; Security for
  clearance/COMSEC; the certifying body for current cert rules.
- **Gemba walk** — go to the floor/line and confirm the documented requirement matches the
  work actually performed and the tools/materials in use.
- **Cross-reference** — trace each requirement from the person → cert → requirement →
  contract clause so nothing is orphaned or unsupported.

## 4. Definition of Done (per work process)
- Every requirement has a named authoritative source + citation + revision.
- Applicability (roles, contracts) and classification are confirmed.
- Register reconciled; repo docs updated via commit.
- Verification date, verifier, and next re-verification trigger recorded.
- Open questions logged as actions (do not leave "unknown" requirements unmanaged).

## 5. Re-Verification Cadence (triggers)
Requirements are not static — re-verify when any trigger fires, and at minimum annually.
| Trigger | Action |
| --- | --- |
| New contract award or modification | Re-verify affected processes within 30 days |
| Regulation or standard revision (e.g., new EM 385, IPC rev) | Re-verify impacted rows |
| Certification body updates requirements | Update cert rows + affected training |
| Audit finding (from the loop) | Re-verify the cited requirement + root cause |
| Annual program review | Full re-verification sweep + management review |

## 6. Output
A **verified Requirements Register** per process that becomes the backbone of the training
matrix (people × requirements) and the entry point to the continuous-improvement loop. Any
requirement with **no existing training/assessment** is flagged and routed to **Develop**
(see [`Continuous-Improvement-Loop.md`](../6-Sustain-and-Improve/Continuous-Improvement-Loop.md)).
