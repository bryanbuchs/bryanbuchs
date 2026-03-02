# CLAUDE.md

## Repository Overview

This is **Bryan Buchs' personal GitHub profile repository** (`bryanbuchs/bryanbuchs`). It contains a single `README.md` that serves as a professional portfolio and resume, displayed on Bryan's GitHub profile page.

This is **not** a software project — there is no source code, build system, dependencies, or test suite. The repository is purely a version-controlled professional document.

## Repository Structure

```
bryanbuchs/
├── CLAUDE.md       # AI assistant guidelines (this file)
└── README.md       # Professional portfolio / resume (the sole content)
```

## Content Details

**README.md** contains:
- Professional summary (Senior Web Developer & Accessibility Specialist)
- Technical skills (HTML, CSS, JavaScript/Vue.js, Drupal, Node.js, accessibility/WCAG)
- Work experience at Kapow, Inc. (2007–present) and earlier career history (1996–2007)
- Highlighted projects (Stanford University, HHMI BioInteractive, PBS, cultural institutions)
- Contact information

## Key Conventions

### Editing Guidelines

- The README.md uses standard GitHub-flavored Markdown
- Professional tone throughout — this is a public-facing resume
- External links point to live client websites and LinkedIn; verify links still resolve before adding or changing them
- Project descriptions emphasize accessibility (WCAG 2.1), performance, and user experience
- Work history is organized reverse-chronologically with year ranges as section headers

### Formatting Patterns

- H1 (`#`) for name only
- H2 (`##`) for major sections (Professional Summary, Technical Skills, Professional Experience, etc.)
- H3 (`###`) for individual roles or project groups
- Bullet lists for skills, responsibilities, and project details
- Inline links `[text](url)` for external references

### Content Style

- Concise, achievement-oriented bullet points
- Quantifiable results where possible (e.g., "reduced page load time", "reduced development time")
- Technical specifics included (frameworks, tools, standards)
- Accessibility expertise is a recurring theme — preserve this emphasis in any edits

## Git Workflow

- **Primary branch:** `master`
- **Commit style:** Short messages like `Update README.md`
- No CI/CD, no branch protection, no `.gitignore`
- All historical commits are README content updates

## What NOT to Do

- Do not add build tooling, package.json, or other project scaffolding — this is a document repo
- Do not restructure into a static site or add HTML/CSS unless explicitly requested
- Do not remove or alter contact information without explicit instruction
- Do not fabricate or embellish professional experience, project details, or credentials
