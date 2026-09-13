# Sprint 1 Playback — UX Contribution

**Prepared by:** Harneet Kaur
**Role:** UX Designer
**Sprint:** Sprint 1 — Design & Bootstrap, Week 3 Playback
**Team:** 05-IBM-RCS Infrastructure — Team 1

---

## Introduction

I am Harneet Kaur, on Team 5's UX design team, mainly responsible for translating the BA's requirements and Core MVP scope into user personas, user flows, and the Sprint 1 digital prototype, with technical implementation handled by our Developers. This sprint, I was tasked with defining the personas, mapping high-level and detailed user flows for the Auditor and Manager, and building the four-screen Sprint 1 prototype in Figma, then validating all of it against the confirmed requirements and the Sprint 1 BA playback review.

---

## What I Contributed This Sprint

- Defined the three user personas — Public User, Auditor, and Manager/Supervisor — with the Auditor as primary persona.
- Mapped high-level user flows and UX direction across all three personas.
- Converted the high-level flows into detailed step-by-step Auditor and Manager flow diagrams (eight steps for the Auditor, six for the Manager).
- Built the four-screen Sprint 1 digital prototype in Figma: Dashboard, Case Preview, Analysis & Decision, and Manager Overview.
- Validated the flows and prototype against the Core MVP requirements, covering all thirteen confirmed UX checklist items.
- Re-validated everything against a mid-sprint requirements refinement, correcting the classification of Manager oversight, wellbeing controls, and Auditor decline from "out of scope" to "confirmed, parameters open."
- Responded to a BA review round: added draft/TBC markers on unconfirmed decision options, clarified the exposure-time unit, and made the decline-to-Manager-escalation outcome visible on the relevant screen.

---

## UX / Prototype Explanation

**How it reduces exposure:** Severity, summary, and incident timestamps are shown before any raw media. Raw content stays hidden until the Auditor explicitly selects a flagged moment — nothing plays automatically.

**How it keeps the human in control:** Every decision path — Approve, Reject, or Decline — ends with the Auditor, never the AI. This is enforced visually by keeping AI-generated output and the Auditor's decision bar clearly separate on screen.

**How it handles uncertainty:** Any requirement not yet confirmed by the client — the severity scale, the exact decision options, exposure and cooldown thresholds — is marked as draft or tagged to a specific open-decision number, rather than guessed at or presented as final.

**How it supports Manager oversight:** A separate Manager Overview screen shows team workload and exposure information, without duplicating or interfering with the Auditor's own review and decision screen.

**Transparency:** Every screen carries annotations tying its key elements back to a specific requirement or acceptance criterion, so BA and Developers can trace any design choice back to its source.

---

## One Honest Blocker or Learning

Primary blocker for the spoken script: mid-sprint, the BA sent through refined requirements, and several things I'd already built as "out of scope" — Manager oversight, the wellbeing controls — turned out to be confirmed requirements, with only the exact thresholds and permissions still open. I had to go back and relabel a meaningful amount of already-completed work.

Additional learnings on record, for supporting Q&A if asked:
- "Not yet built" and "not yet confirmed" are two different problems, and it's easy to blur them together.
- A few specific fixes — a banner's text spacing, a table row's colour flag — took several review rounds to actually land, which taught me to check frame-by-frame rather than assume a change went through after making it.
- Different BA documents used different numbering schemes for the same open items, which meant cross-referencing carefully rather than assuming consistency across documents.

---

## Spoken Script (~1 minute)

*Use this version for the live playback slot — the sections above are the full supporting detail.*

> Hi, I'm Harneet Kaur, UX Designer on the team.
>
> This sprint I built the detailed Auditor and Manager flow diagrams, and then the four-screen Sprint 1 prototype in Figma — the dashboard, case preview, analysis and decision screen, and manager overview. Together, those cover all thirteen of our confirmed UX requirements, from severity visibility through to the final decision step.
>
> My honest learning came mid-sprint, when the BA sent through refined requirements. A few things I'd treated as out of scope — manager oversight, the wellbeing controls — turned out to actually be confirmed requirements. The specific thresholds and permissions were still open, but the features themselves weren't optional anymore. So I went back and relabeled a fair amount of work, from "not built yet" to "confirmed, details pending." That's stuck with me — assuming something isn't decided is a different mistake than assuming it isn't happening at all.
