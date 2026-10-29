# Visayas State University AI Policy Framework

This repository documents the development of a proposed Visayas State University (VSU) AI Policy Framework—from planning and proposal drafting through consultation, panel deliberations, revisions, and formal approval.

The repository is a process record and collaboration space. It does not itself constitute an approved university policy. Only an authorized university body can approve and issue the final framework.

## Start here

- [Development process](docs/development-process.md) describes the working stages and how to record progress.
- [Proposal outline](templates/proposal-outline.md) provides a structure for drafting the initial proposal.
- [Panel feedback template](templates/panel-feedback.md) captures comments and dispositions consistently.
- [Decision log](docs/decision-log.md) records significant decisions and their status.

## Draft framework (LaTeX)

- [`framework/`](framework/) contains the modular LaTeX draft of the VSU AI Policy Framework (`main.tex`, `sections/`, `references.bib`). It is a **draft for panel review, not approved policy**; its Appendix D lists the sources consulted.
- Build with `cd framework`, then `latexmk -pdf main.tex` (or `pdflatex`, `bibtex`, `pdflatex` twice).

## Working principles

- Keep drafts, deliberations, feedback, and decisions traceable; identify the document version under review.
- Distinguish proposals and recommendations from decisions made by an authorized panel or university body.
- Record feedback faithfully and document how each comment was addressed or why it remains open.
- Respect university records, privacy, and confidentiality requirements. This repository is public: do not publish personal, sensitive, restricted, or confidential material, or attribute comments without appropriate authorization. Use approved university channels for material that must not be public.
- Mark the framework as approved only after the competent university authority has formally approved it; record the approving body, date, and public reference where available.

## Changelog

Entries are clustered by date (YYYY-MM-DD), in chronological order. Update this section with every change to the repository or the policy framework document.

### 2026-10-29

- Repository created and scaffolded (initial commit): README, CONTRIBUTING, `docs/` (development process, decision log), `templates/` (proposal outline, panel feedback).
- Added the draft LaTeX policy framework in `framework/` (`main.tex`, `sections/`, `references.bib`): sections on purpose and scope, principles, governance, faculty enablement, student learning, academic integrity, data privacy, equity, research ethics, tool approval, implementation; appendices for declaration templates, quick guides, glossary, and verification status. Marked as a draft for panel review.
- Added `.gitignore` for LaTeX build artifacts and a README link to the framework.
- Revised the draft for precision: softened or marked unverified claims as `[CITATION NEEDED]`, clarified the AI-use level scale and default, expanded abbreviations.
- Added this Changelog section.
- Recorded the Technical Working Group for AI Policy and Governance, led by Dr. Magdalene C. Unajan, as the policy owner in the framework's title block, authority section, roles table, and document control.
- Resolved all open items in the framework: checked CHED Memorandum Order No. 21, s. 2026 and CHED Regional Memorandum No. 318, s. 2026 (scanned PDFs) and the cited journal PDFs; added both memoranda to `references.bib` and replaced the pending alignment table with a provision-by-provision map to CMO No. 21.
- Removed unverified claims and citations (Kasneci, Liang, Weber-Wulff, Perkins, Dwivedi 2023, UNESCO, Feuerriegel) because the sources are not in the reference folder; added verified sources (Yu 2023, Morales-García 2024, Holden 2021, Tarafdar 2014) and confirmed Chan 2023, Chan and Hu 2023, and Belanger and Crossler 2011.
- Removed all `[Verify]`/`[CITATION NEEDED]` markers and the `\todoverify` macro; rewrote Appendix D as a short "Sources Consulted" note.
- Settled with the policy owner: approval route (University Academic Council and University Administrative Council concurrently, then Office of the President to the Board of Regents); no separate Steering Committee (duties rest with the TWG); Level 2 remains the default and an AI Use Declaration is mandatory with every submission; review targets set to 25 working days (Tier B) and 50 working days (Tier C), excluding holidays, special non-working days, and work-suspension days.
- Aligned Tier C examples, thesis disclosure, assessment-redesign, detector, and transition provisions with CMO No. 21 (Sec. 8, 9, 11, 12, 15--18, 30).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for suggested contribution and review practices. Use pull requests for substantive edits so reviewers can comment on changes and the decision trail remains visible.
