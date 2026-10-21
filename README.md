# Nitrogen Fitness & Wellness — website

Multi-page site for Nitrogen Fitness & Wellness, Karachi (Block F North Nazimabad + Nazimabad No. 3). Built by [Nexlyr Solutions](https://nexlyr.solutions).

Every page is one self-contained HTML file (styles and scripts inline). Media sits flat next to the pages — no subfolders, no build step.

## Deploy
Import this repo on Vercel (Framework preset: **Other**, no build command). `vercel.json` turns on clean URLs and long caching for media.

## Pages
| File | What's on it |
| --- | --- |
| `index.html` | Lightning preloader (Nitrogen fills with charge, bolt strikes, screen splits on the N angle) · slanted triptych video hero · **Element 07** — a 3D nitrogen atom: 7 electrons, each one a real fact (2 branches + 5 ways to train) · packages · reels rail · proud moments (Mr. Universe 2026, Ayesha Hassan gold, Nasir Khan) · 5-check form teaser · Google reviews · branches |
| `training.html` | 3D lat-pulldown lab (scroll runs Nitrogen's 5-point checklist) · 4 pulldown mistakes · exercise library filmed at Nitrogen · shoulder & chest guides · training-days picker · myth/fact flip cards · pre-workout fuel · feed wall |
| `team.html` | Nasir Khan, Farhana, the Mr. Universe athlete, coaches named in reviews/timetable, OSM Fitness, PT steps, hiring |
| `membership.html` | Gold Rs. 4,000 · Early Bird Rs. 6,999 · PT · ladies-only slots (live) · OSM Body Shred Boot Camp · WhatsApp enquiry form · FAQ |
| `visit.html` | Both branches with live open/closed, weekly hours, map switcher, ladies slots, first-visit steps |
| `404.html` | "This page skipped its warm-up." |

Shared on every page: dark/light theme (dark default), sound toggle, smooth scroll, page curtain, lightbox, and a **Front desk** chatbot (timings with live status, fees, ladies classes, location, trainers, boot camp, hiring — understands Roman Urdu, hands anything else to WhatsApp with the question pre-typed).

## Editing data
All phone numbers, timings, branches and ladies slots live in the `NG` object at the top of the inline script in each page (search `const NG`). The page text is plain HTML.

## To confirm with the owner
- [ ] WhatsApp number — using **0370 084 3151** (from their posters).
- [ ] Instagram — newest posters say **@nitrogen.pk**, older ones **@nitrogenfitnesspk**. Site links to @nitrogen.pk.
- [ ] Nazimabad No. 3 hours — using Mon–Sat 6 AM–1 AM (Google listing), closed Sunday.
- [ ] Which branch the ladies-only classes run at (the site doesn't name one).
- [ ] Name of the athlete who represented Pakistan at Mr. Universe 2026 (shown unnamed).
- [ ] Ayesha Hassan (World Cup Powerlifting gold) — confirm she trains at Nitrogen.
- [ ] Which interior belongs to which branch — black/gold = Block F, green neon = Nazimabad is assumed.
- [ ] Domain — canonical tags and sitemap use `https://nitrogen.nexlyr.solutions`.

Facts on the site come from Nitrogen's own posts and reels and their Google listings (Oct 2026). Nothing is invented — no fake member counts; coaches are only those named in reviews, posts or the timetable.
