# BrowseBlock Report

This repository contains the Phase I report for **BrowseBlock**, an AI/ML-powered
browser security platform for real-time browser-based attack detection and prevention.

# BrowseBlock SRS

> [!TIP]
> 📑 [Click here to view the Full Literature Review (`thesis.pdf`)](./thesis.pdf)

## Project contents

- `thesis.tex` - Main LaTeX document.
- `chapter/` - Chapters 1 through 6.
- `images/` - Figures and institutional logo used by the report.
- `frontpage.tex` - Title page, declaration, certificate, acknowledgement, and abstract.
- `format.tex` - LaTeX packages and document formatting.
- `dmathesis.cls` - Thesis document class.
- `ref.tex` - Bibliography.
- `SRS.pdf` - Software Requirements Specification.
- `Literature Review Complete.pdf` - Literature review source document.

## Building the report

Install a LaTeX distribution with the packages used by `format.tex`, then run:

```bash
pdflatex -interaction=nonstopmode -halt-on-error thesis.tex
pdflatex -interaction=nonstopmode -halt-on-error thesis.tex
```

The second run updates the table of contents and figure references.

## Scope

BrowseBlock combines a Manifest V3 Chromium extension, React dashboard, FastAPI
backend, Firebase Authentication, MongoDB, machine-learning models, static analysis,
and AI-assisted email analysis. The report covers URL and QR phishing, XSS,
credential harvesting, redirects, clickjacking, cryptojacking, malicious downloads,
email phishing, notification scams, and browser-extension abuse.
