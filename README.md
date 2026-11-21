# Ubuntu Terminal Learning Lab

I use this repository to turn Ubuntu terminal study into practical administration skills. I keep my study plan, exercise design, review notes and learning checkpoints together so I can revisit both successful approaches and mistakes.

> **Unofficial certification preparation.** I am preparing for Canonical Academy's Ubuntu Using Linux Terminal certification. This is my personal learning project, not an official Canonical course, examination, endorsed study guide or certification result. My practice tasks and timing do not claim to reproduce the examination.

## Start here

- [Project origins](docs/project-origins.md): why I started and how I organise the work.
- [Lab environment](docs/lab-environment.md): CLIENT, SERVER and safety boundaries.
- [Practice methodology](docs/practice-methodology.md): assignments, assistance, evidence and reviews.
- [Six-block roadmap](docs/roadmap.md): the complete practice plan and current learning status.
- [Study-material inventory](study-material/README.md): my starting notes and their publication status.
- [Practice blocks](blocks/README.md): what is available in this repository.
- [Sources and attribution](docs/sources-and-attribution.md): authorship, AI assistance and reference limitations.
- [Publication checklist](docs/publication-checklist.md): what to check before sharing or contributing material.

## How I learn

```text
Study -> prepare fixtures -> attempt a complete block -> review -> remediate -> record lessons
```

I work through realistic task batches rather than isolated command quizzes. I separate the assignment from hints and solutions, use local documentation, and record what I actually observed instead of replacing unsuccessful commands with ideal answers.

## Learning and publication status

| Block | Focus | My learning checkpoint | This repository |
|---|---|---|---|
| 1 | Files and navigation | Closed as guided practice with remediation; final verification gaps recorded | Checkpoint summary available; complete exercise pack and transcripts not yet imported |
| 2 | Text and pipelines | Planned | Roadmap only |
| 3 | Logs and scheduling | Planned | Roadmap only |
| 4 | Storage | Planned | Roadmap only |
| 5 | Accounts and access | Planned | Roadmap only |
| 6 | SSH and sudo | Planned | Roadmap only |

A completed learning checkpoint is not automatically a fully verified task pass. My [Block 1 checkpoint](blocks/block-01-files-and-navigation/README.md) explains the distinction.

## Repository structure

```text
.
├── .editorconfig
├── .gitignore
├── README.md
├── docs/
│   ├── lab-environment.md
│   ├── practice-methodology.md
│   ├── project-origins.md
│   ├── publication-checklist.md
│   ├── roadmap.md
│   └── sources-and-attribution.md
├── study-material/
│   └── README.md
└── blocks/
    ├── README.md
    └── block-01-files-and-navigation/
        └── README.md
```

This describes the published repository, not a VM filesystem or a claim that future exercise files already exist. I keep generated lab workspaces separate, beneath `~/terminal-lab/exam/` inside the relevant VM.

## Publication boundaries

I wrote the starting study notes while preparing for the certification. Full notes and original terminal submissions are not included in this initial publication.

I use AI assistance for exercise design, explanations, review and repository drafting. I distinguish generated reference examples from observed terminal evidence.
