# HASMA Project — Health & Wellness App (WBS & Documentation) 💚

[![Project Status](https://img.shields.io/badge/status-Planning%20%2F%20WBS-blue)](https://github.com/42seconds/HASMA_Project)
[![Owner](https://img.shields.io/badge/owner-42seconds-lightgrey)](https://github.com/42seconds)
[![License](https://img.shields.io/badge/license-See%20LICENSE-lightgrey)]()

Welcome to the HASMA Project repository — a curated collection of planning artifacts, Work Breakdown Structure (WBS) deliverables, and documentation for the Health & Wellness App initiative. This repository stores original project files (LibreOffice/ODF), exported PDFs and images, meeting notes, and project management artifacts used for planning and stakeholder communication.

Quick links
- Repository: https://github.com/42seconds/HASMA_Project
- Owner: 42seconds

---

Table of contents
- Project overview
- What’s in this repo
- Repo structure
- How the WBS is organised
- Opening & editing project files (tips)
- Versioning & file naming conventions
- Contribution guidelines
- Maintainer checklist & PR guidance
- Roadmap & status
- License, credits & contact

---

Project overview
---------------
HASMA (Health & Wellness App) is a planning-level project to design and deliver a cross-platform application to help users track well-being, healthy habits, and basic health metrics. This repository contains the planning artifacts and WBS used to scope the project and create a baseline schedule.

Goals
- Produce a clear, actionable WBS linked to deliverables and owners
- Prepare a baseline schedule and risk register
- Deliver a documented plan ready for handover to design/development teams

Audience
- Project managers and planners
- Stakeholders & sponsors
- Designers and technical leads reviewing scope & schedule

---

What you will find in this repo
-------------------------------
- Original project files (LibreOffice Writer/Calc/Draw) and exported PDFs
- WBS (hierarchical tasks) and Gantt chart exports
- Requirements and scope notes
- Risk log and assumptions
- Meeting minutes and decisions
- Design sketches and reference assets (images)
- CHANGELOG.md (if present) and LICENSE (if present)

---

Repository structure (example)
------------------------------
- /.project-files/        — Original LibreOffice files (.odt, .ods, .odg) and project sources  
- /docs/                  — Exported PDFs, reports and read-only documents  
- /assets/                — Images, diagrams, mockups, and exported charts  
- /templates/             — Project templates (meeting notes, risk log, WBS template)  
- /CHANGELOG.md           — Project change log  
- /LICENSE                — Repository license (if present)  
- /README.md              — This file

Note: Some directories may be empty placeholders for future artifacts.

---

How the WBS is organised
-----------------------
The WBS in this repo uses a hierarchical decomposition approach so tasks are grouped into logical, manageable packages. Example WBS top-level divisions:

1. Initiation
   - Project charter
   - Stakeholder register
2. Planning
   - Requirements gathering
   - WBS & schedule creation
   - Risk analysis
3. Design
   - UX research
   - Wireframes & prototypes
4. Development
   - Core features (onboarding, tracking, analytics)
   - Integrations (APIs, third-party services)
5. Testing & QA
   - Test planning
   - UAT
6. Deployment & Handover
   - Release & deployment plan
   - Training & documentation

Each task in the source files should include:
- Deliverable name
- Description / acceptance criteria
- Owner / responsible party
- Estimated duration
- Dependencies (if known)

If tasks are exported to a spreadsheet or CSV, each row should map to the fields above for easy import into scheduling tools.

---

Opening & editing project files (tips)
-------------------------------------
Preferred tools:
- LibreOffice (Writer/Calc/Draw) for original ODF files — recommended to preserve formatting and structure.
- PDF viewers (Adobe Reader, Evince, Preview) for read-only exports.

Tips:
- Always keep a copy of the original file before editing. Use versioned filenames (see Versioning section).
- Export to PDF before opening in other editors to make sure formatting looks correct.
- When updating diagrams, keep source vector files (.odg / .svg) in /assets/ to allow clean edits.
- If you don't have LibreOffice, tools like Collabora Online or Google Drive may show the content (rendering may differ).

---

Versioning & file naming conventions
-----------------------------------
To keep planning artifacts traceable, adopt a simple naming convention:

filename-version_editor-YYYYMMDD.ext

Examples:
- project-wbs-v1.0_ajones-20250901.odt
- gantt-baseline-v1.0_42seconds-20250904.pdf

Versioning rules:
- Increment the version for major changes (v1.0 → v1.1 for minor; v2.0 for major rebaselines)
- Include an editor/author short handle and ISO date
- Preserve previous versions in the repository (do not overwrite without justification)

---

Contribution guidelines
-----------------------
We welcome improvements to planning artifacts and documentation. For meaningful contributions:

1. Fork the repo.
2. Create a branch: git checkout -b feature/update-wbs
3. Make changes; commit with clear messages describing the change.
   - Example: "Update WBS: split Development/Integrations into mobile & backend"
4. Open a Pull Request describing intent and impacted files.

When editing original ODF files:
- Prefer adding a versioned copy (e.g., project-wbs-v1.1.odt) instead of editing in place for major changes.
- In PR description, include a short summary of the diff and reason for change.
- If a file is large, include exported PDF artifacts to simplify review.

PR checklist for contributors:
- [ ] Changes are documented in the PR description
- [ ] Major file updates include a PDF export for reviewers
- [ ] Versioned filename used if the change is not trivial
- [ ] Any new assets placed under /assets/ with appropriate naming

---

Maintainer checklist
---------------------
When accepting a PR that updates planning documents:
- Confirm file naming/versioning is followed
- Verify a PDF export is present for reviewers
- Update CHANGELOG.md with a brief entry summarising the change
- Confirm risks/assumptions updated if scope changed

Suggested PR labels:
- documentation
- planning
- wbs
- needs-review

---

Roadmap & current status
------------------------
Status: Planning / WBS

Short-term (next milestones)
- Finalize and baseline WBS (v1.0)
- Produce baseline schedule & resource plan
- Review risks and assumptions with stakeholders

Long-term goals
- Deliver v1.0 scope to design & development teams
- Iterate based on early user feedback and metrics

---

Examples & handy commands
-------------------------
Clone the repo:
git clone https://github.com/42seconds/HASMA_Project.git

Create a feature branch:
git checkout -b feature/update-docs

Commit and push:
git add .
git commit -m "Update WBS: clarify dependencies"
git push --set-upstream origin feature/update-docs

---

License, credits & acknowledgements
-----------------------------------
- Please consult the LICENSE file in this repository for licensing details. If no LICENSE file exists, assume the materials are proprietary to the project owner (42seconds) and request permission before reuse.
- Acknowledgements: project templates and artifacts prepared using LibreOffice and standard PM templates.

---

Contact
-------
If you have questions about the WBS, artifacts, or contribution process:
- Open an issue in this repository
- Or contact the repository owner: 42seconds — https://github.com/42seconds

---

Next suggestions (things I can add for you)
- A CONTRIBUTING.md with the contributor flow and PR templates
- ISSUE_TEMPLATE.md and PULL_REQUEST_TEMPLATE.md to standardise contributions
- Export key ODF files to PDF and add them to /docs/ for easier reviewing
- Generate a machine-readable WBS CSV/JSON summary for import into scheduling tools

Thank you for checking out the HASMA Project. If you’d like, I can prepare those additional files (CONTRIBUTING, templates, and PDF exports) and provide them here for review.
