# jaiydn-website

Personal brand website for Jaidyn Green — technology consultant and AI-enabled builder.

Live at: [jaiydn.com](https://jaiydn.com) *(domain pending)*

---

## What's in this repo

| File | Purpose |
|------|---------|
| `index.html` | Full website — single file, no dependencies |
| `vercel.json` | Vercel deploy configuration |

---

## Stack

- Pure HTML, CSS, JavaScript — no frameworks, no build step
- Fonts loaded from Google Fonts (Space Grotesk, DM Serif Display)
- Headshot embedded as base64 — no external image hosting required
- Deploys as a static site

---

## Deploying to Vercel

1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click **Add New Project** → import `jaiydn-website`
3. Vercel auto-detects the static config — click **Deploy**
4. Once live, go to **Settings → Domains** → add `jaiydn.com`
5. Follow Vercel's DNS instructions at your domain registrar

---

## Making updates

All content lives in `index.html`. Common updates:

**Swap the Calendly link**
Find the two `mailto:` links and replace with your Calendly URL:
```
href="mailto:Jagreen2024@gmail.com"
→
href="https://calendly.com/your-username"
```

**Add a new case study**
Copy an existing `<div class="case-card">` block in the `#work` section, update the content, and increment the project number.

**Update contact email**
Search for `Jagreen2024@gmail.com` — appears in the contact section and footer. Replace both.

**Add the gallery project**
When the African art gallery engagement reaches a deliverable milestone, add it as Project 04 in the `#work` section with real outcomes.

---

## Site sections

| Section | ID | Notes |
|---------|----|-------|
| Hero | `#hero` | Headline + CTA |
| Why Work With Me | `#why` | 4-point credibility strip |
| Services | `#services` | 3 service rows |
| Selected Work | `#work` | 3 case studies |
| Process | `#process` | 4-phase methodology |
| Experience | `#experience` | Background + credentials |
| Contact | `#contact` | CTA + email |

---

## Background

Built in June 2025 in preparation for a June 18 client meeting.

Design direction: Metalab-inspired dark editorial — near-black background, warm cream typography, DM Serif Display headlines, Space Grotesk for UI text.

Case studies reflect verified work:
- AT&T Executive Scheduling Applications (2023)
- AT&T Legislative Intelligence Dashboard (2022) — still in active executive use
- OpportuNet — Senior Engineering Capstone, UNT (2025)

---

*For questions about the build, reach out at Jagreen2024@gmail.com*

