# GENEVIEVE App™ — Growing Up

**Canonical repository for the Growing Up child/puberty education prototype.**

This is a standalone, offline-capable educational prototype covering puberty, personal care, emotional safety, consent, online safety, health escalation and parent/carer guidance.

## Product boundary

Growing Up is **not** part of Health Navigator, Life Companion, LISTENS, the psychology command centre, or the adult personal-support apps. Its child-safeguarding, age-appropriate content, privacy and professional-review requirements are separate and must remain explicit.

## Current prototype boundary

- No account system
- No analytics or advertising
- No camera, microphone or location access
- No cloud database
- No personal-information upload
- No public chat/profile
- No claim of legal or clinical approval

The existing `README.txt` is retained as the original prototype quick-start note.

## Public-release gate

Before any public release, the content and product should undergo appropriate Australian child-safeguarding, privacy, clinical/health-content, cybersecurity, accessibility and insurance review. A privacy impact assessment and governed content-review process are also required.

## Platform direction

The current app is static HTML/CSS/JavaScript. If published for controlled review, use the ON TRACK by TRACE platform direction:

- GitHub source control
- Cloudflare Pages for static hosting
- no Neon database unless a later governed design genuinely requires persistent server-side data
- no Vercel deployment dependency

## Files

- `index.html` — application shell
- `app.js` — educational modules and prototype interaction logic
- `styles.css` — presentation
- `README.txt` — original prototype note
- `Letter-to-Irene-Psychologist.docx` — historical/review correspondence artifact

Ordinary repository cleanup must not merge this prototype into an adult health, clinical, or command-centre repository merely because health and wellbeing topics overlap.
