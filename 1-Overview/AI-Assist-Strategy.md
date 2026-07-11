🏠 [Home](../README.md) · ⬆ [Phase 1 · Overview](README.md)

# AI-Assist Strategy

How we can use **AI to speed up building and running** this training program — and, just as
important for a government contractor, **how to do it safely**. Each phase's README has a short
**🤖 AI Assist** box pointing back here.

> **Read the guardrails first.** In a govcon environment the *how* matters more than the *what*.
> Used wrong, AI creates compliance, security, and export-control risk. Used right, it removes
> weeks of drafting work.

---

## Guardrails (non-negotiable — read before using any AI)

1. **Data-classification gate.** **Never** put **CUI, ITAR/EAR-controlled technical data,
   classified information, or PII** into a public or commercial AI tool. Those only go into an
   environment **accredited for that data level** (e.g., FedRAMP/DoD IL-accredited, GovCloud, or
   a self-hosted/on-prem model). Public-domain content (the standards catalog, public regs,
   generic job descriptions) is fine in commercial tools.
2. **Human-in-the-loop.** AI **drafts**; a **qualified SME reviews and signs off**. AI never
   makes the final "**Required**" determination and never approves compliance-critical content.
3. **Source-grounding + citation check.** Ground AI on the authoritative
   [governing-standards catalog](../3-Requirements/Governing-Standards-Reference.md) and the
   real standard/contract text. **Verify every citation and requirement against the source** —
   AI can confidently invent regulation numbers, revisions, and requirements.
4. **Version control + audit trail.** AI-assisted content goes through the **same Git review**
   as everything else. Note in the commit or record where AI assisted — transparency, and some
   contracts require disclosure of AI use.
5. **Policy alignment.** Check the **customer/agency AI-use policy** and Tyonek's own before
   adopting; some contracts restrict or prohibit AI. Align first.

---

## Where AI helps, by phase

| Phase | High-value AI uses | Risk level |
| --- | --- | --- |
| **2 · The Jobs** | Draft a new job's three files (training doc, certifications, trade-progression) from a short description + the catalog; refresh/standardize existing docs to the template | Low (public content) |
| **3 · Requirements** | Extract flowed-down training/cert requirements from a contract/SOW/PWS; monitor & summarize standard/regulation changes and flag affected jobs | **High** (may involve CUI/contract data — use an accredited tool; verify every citation) |
| **4 · Discover & Analyze** | Ingest current-state training records and map them to the required list; suggest RAG ratings; draft the Initial Findings Report; assist 5-Whys root cause | Medium (records may contain PII — accredited tool) |
| **5 · Develop · Deliver · Assess** | **Generate courseware** (learning objectives, lesson plans, job aids, scenarios); generate **knowledge-check questions** and practical-demonstration checklists; draft 508-accessible eLearning scripts | Low–Medium (public standards → commercial OK; verify technical accuracy with SME) |
| **6 · Sustain & Improve** | Summarize audit findings; draft CAPA/A3s; analyze KPI trends and draft management-review summaries; monitor cert expirations & standard changes to auto-flag affected training | Medium (audit/records data — accredited tool) |

**The biggest single win is Phase 5 — "future training generation."** Turning an approved
training document + its standards into draft courseware and assessment items is exactly what
modern AI is good at, and the source material is largely public. That's where I'd start.

---

## How to go about it (crawl → walk → run)

**Crawl (start here — low risk, fast value)**
- Use AI on **public-domain content only**: draft new job files, refresh existing docs to the
  template, and generate first-draft courseware and quiz questions for **one pilot discipline**
  (Welding is a good candidate — its example is already built).
- Build a **prompt library** (saved, reviewed prompts) so output is consistent and grounded in
  our templates and catalog. Keep it in the repo.
- **Measure**: time-to-draft before vs. after, and SME edit effort. Prove the value on one job.

**Walk (after the pilot proves out)**
- Stand up an **accredited AI environment** (GovCloud/FedRAMP or on-prem) for anything touching
  contract data, records, or CUI — then extend to requirement-extraction (Phase 3) and
  current-state ingestion (Phase 4).
- Formalize the **SME review workflow** (draft → SME → commit) and the AI-use disclosure note.

**Run (mature state)**
- An **assistant grounded in this repo** (retrieval-augmented generation over the standards
  catalog, job files, and requirements) that answers "what training does role X need?" and
  drafts new material on request — always SME-verified.
- **Automated change-monitoring**: watch for standard/regulation revisions and auto-open a
  flagged item against the affected jobs (feeds the Phase 6 re-trigger).

## Tooling (illustrative — validate against policy)
- **Public content:** commercial enterprise AI (with data-retention off) for drafting/summarizing.
- **Sensitive content (CUI/contract/records):** Azure OpenAI or AWS Bedrock **GovCloud**,
  or a **self-hosted open model** — never a consumer tool.
- **Repo assistant:** RAG over this repository as the knowledge base.

## What AI should *not* do here
- Decide what is **Required** (that's verification against the actual source).
- Approve or sign off training, competency, or audit findings.
- Touch controlled data in an unaccredited tool.
- Be trusted on a citation or requirement without a human checking the source.

---
◀ [Back to Phase 1 · Overview](README.md)
