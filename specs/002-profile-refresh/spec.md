# Spec: Profile Refresh from CV + Visual Redesign

## Summary
Extend the landing page profile by extracting and summarizing content from
`assets/cv.pdf`, and redesign the page so it reads as a modern, recruiter-ready
profile rather than plain text.

## Goals
- Present a richer, structured profile (summary, strengths, experience highlights,
  projects, education/certifications if present).
- Use CV content only, with light summarization and no invented details.
- Deliver a visually polished, scannable layout that works on mobile and desktop.

## Non-goals
- Full resume replacement or multi-page site.
- Complex build tooling or new frameworks outside GitHub Pages/Jekyll.
- Automated CV parsing pipeline (manual extraction is acceptable).

## Requirements
- Extract key facts from `assets/cv.pdf` and update `index.md` accordingly.
- Keep the content concise and recruiter-friendly (short paragraphs + bullets).
- Add a lightweight visual system (typography, spacing, color accents, sections).
- Ensure contact and CV download are visible and accessible.
- Keep performance fast and compatible with GitHub Pages.

## Success criteria
- Page reads as a modern profile with clear hierarchy and scanability.
- Content matches the CV and does not introduce new claims.
- Layout looks intentional on mobile and desktop.

## Constraints
- Must remain in this repo and use Jekyll/GitHub Pages.
- Avoid external build steps or heavy dependencies.
