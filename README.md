# Enterprise AI Architecture-to-Production

Interactive practitioner showcase demonstrating an end-to-end enterprise AI architecture and delivery lifecycle.

## Live Demo

https://danvzla.github.io/ai-architecture-to-production/

## What the showcase contains

- **Architecture-to-Production Methodology** — 6 phases and 22 practitioner steps.
- **22 methodology templates** — customer-ready blank artifacts associated with each step.
- **Methodology in Practice** — 15 illustrative enterprise AI scenarios.
- **330 completed scenario deliverables** — 22 artifacts for each scenario.
- All visual artifacts are stored as external image files; the HTML contains no Base64-embedded deliverables.

## Repository structure

```text
/
├── index.html
├── Enterprise-AI.jpeg
└── images/
    ├── templates/
    │   ├── step-01-template.png
    │   └── ... step-22-template.png
    └── scenarios/
        ├── scenario-01/
        │   ├── step-01.png
        │   └── ... step-22.png
        └── ... scenario-15/
```

## GitHub Pages deployment

1. Create a new public GitHub repository, recommended name:
   `ai-architecture-to-production`
2. Upload **the contents of this folder to the repository root**.
   `index.html` must be at the top level of the repository.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/(root)`
6. Click **Save**.
7. After GitHub publishes the site, the expected URL is:
   `https://<username>.github.io/ai-architecture-to-production/`

## Important

Do not rename or move the `images` directories unless the relative paths in `index.html` are updated.

The scenarios are illustrative, non-client examples designed to demonstrate methodology application and customer-style deliverables.
