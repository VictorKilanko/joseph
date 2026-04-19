# Joseph Project — Log & Jump-Start Document

> This file is your jump-start document. Pick up exactly where we left off.
> Last updated: 2026-04-19 (session 2)

---

## STATUS: Landing Page Live — Refining & Building Out

GitHub repo: https://github.com/VictorKilanko/joseph
Live site: https://victorkilanko.github.io/joseph/
Domain to register: `josephmovement.com` (confirmed available)

---

## What Has Been Done

- [x] **Idea validated** — Concept assessed, differentiation confirmed, risks identified (see Plan.md §1)
- [x] **Brand identity defined** — Name (JOSEPH), tagline revised, tenets, tone, visual direction updated (Plan.md §2)
- [x] **Platform architecture planned** — Website pages, app features, user flow (Plan.md §3)
- [x] **Course curriculum outlined** — 101 Identity, 201 Frame, 301 Innovation, 401 Influence, Bonus (Plan.md §4)
- [x] **Mentorship model designed** — Tiers, mentor vetting, pricing (Plan.md §5)
- [x] **Events strategy mapped** — Joseph Talks, Build Weekends, Innovation City Institute (Plan.md §6)
- [x] **Tech stack selected** — Static HTML/CSS/JS for landing page; Next.js + React Native planned for full platform (Plan.md §7)
- [x] **Go-to-market strategy written** — 3 phases over 12 months (Plan.md §8)
- [x] **Revenue model defined** — 6 revenue streams (Plan.md §9)
- [x] **Vision statement drafted** (Plan.md §10)
- [x] **GitHub repo created** — `VictorKilanko/joseph`, GitHub Pages enabled
- [x] **Landing page v1 built & deployed** — Dark theme, animated hero, orbs, marquee, pillars, courses, waitlist
- [x] **Landing page v2 redesigned & deployed** — Full messaging and structural overhaul:
  - New hero: "Stop figuring it out alone." — mentorship-first copy
  - Mentors section promoted to primary product section
  - Working filter tabs: All, Tech, Business, Creative, Healthcare, Education, Finance, Law & Policy
  - 9 sample mentor profiles with hover-reveal booking button
  - Value props reframed: Get Mentored / Discover Yourself / Build Your Future
  - Courses repositioned as self-discovery layer (not entry gate)
  - Religious/spiritual language removed from homepage — kept inclusive
  - Custom cursor, page loader, scroll reveal animations, mentor filter, count-up stats
- [x] **About page built & deployed** (`about.html`) — World-class editorial copy covering:
  - The Problem: why most people never discover who they are
  - The Archetype: who a Joseph is (posture, not personality — women and men)
  - Three Stages: Discover → Deploy → Build
  - Five Beliefs: convictions that drive the platform
  - Who This Is For: six self-identifying cards
  - Closing manifesto: "Joseph exists to make sure you're one of them."
- [x] **About nav link** wired from homepage to `about.html`
- [x] **SVG favicon** added — matches the brand mark (gold top dot, purple base)

---

## What Is Left To Do

### Immediate Next Steps (Start Here — In Priority Order)

- [ ] **1. Register `josephmovement.com`** — ~$12/yr on Namecheap or GoDaddy. Most urgent — makes the site shareable and professional.
- [ ] **2. Connect domain to GitHub Pages** — Repo → Settings → Pages → Custom domain → enter `josephmovement.com`. Add CNAME record at registrar pointing to `victorkilanko.github.io`.
- [ ] **3. Wire up waitlist email form** — Sign up for Mailchimp (free up to 500 contacts). Replace the form's `onsubmit` handler with a Mailchimp embed or API call. Starts capturing real leads immediately.
- [ ] **4. Build mentor application form** — Use Tally.so (free, beautiful, no-code). Fields: name, role, company, expertise areas, why Joseph, availability. Share the link to start recruiting.
- [ ] **5. Recruit 10–15 founding mentors** — Hand-pick professionals you know or can reach. Send them the about page + application form. Real mentors = real product.
- [ ] **6. Build `mentors.html`** — Dedicated mentors browse page with real profiles, full bios, expertise tags, and booking links (Calendly per mentor).
- [x] **7. Build `Course.html`** — Full interactive Course 101 (Identity) experience built as standalone HTML/CSS/JS:
  - Email + name gate (localStorage, blocks all content until submitted)
  - 6 fully written modules with animated content reveals
  - Pull quotes, insight boxes, CORE framework displays, pressure test grids
  - 3 reflection/journal questions per module (auto-save to localStorage)
  - 2 multiple-choice quiz questions per module with animated feedback
  - Module locking system — complete quiz to unlock next module
  - Confetti celebration on each module completion
  - Course complete screen with certificate (personalized with user name)
  - Personal Journal modal (accessible from nav — shows all reflection answers)
  - Top progress bar + sidebar progress tracker
  - Mobile-responsive with hamburger menu
  - Matches index.html design language (same fonts, colors, cursor, animations)
- [ ] **8. Design final logo file** — Export the SVG brand mark as a proper logo file for use across social media, print, and app. Figma or work with a designer.
- [ ] **9. Set up social media handles** — Instagram, LinkedIn, TikTok: @josephmovement (check availability). Start posting before the full platform is built.

### Short-Term (Next 30 Days)

- [ ] **Recruit founding mentors** — 10–15 professionals, hand-picked, mission-aligned
- [ ] **Build mentor profile pages** — name, bio, expertise, availability, book session
- [ ] **Integrate Stripe** — subscription billing for Builder + Founder tiers
- [ ] **Integrate Calendly or Daily.co** — session scheduling + video
- [ ] **Build course player** — start with Teachable or build custom in Next.js
- [ ] **Community feature** — Discord server (short-term) → custom feed (long-term)
- [ ] **Plan first Joseph Talk** — date, speaker, venue (virtual first)

### Medium-Term (30–90 Days)

- [ ] **Launch MVP publicly** — website + app beta
- [ ] **Onboard first 50 mentees** — via churches, schools, youth orgs
- [ ] **Launch Frame (201) and Innovation (301) courses**
- [ ] **Set up email sequences** — welcome flow, course nudges, session reminders
- [ ] **Apply for youth development / education grants**
- [ ] **Build out blog/content section** — 5–10 foundational articles

### Long-Term (90+ Days)

- [ ] Launch Innovation City Institute (annual event)
- [ ] Partner with HBCUs + Christian universities
- [ ] Build full mobile app (React Native)
- [ ] Explore corporate sponsorship program
- [ ] Launch Influence (401) + American Dream courses
- [ ] International expansion planning

---

## Key Decisions Still Open

| Decision | Options | Recommendation |
|----------|---------|----------------|
| Platform name | "Joseph", "Joseph Movement" | **Resolved: JOSEPH** (brand name). Domain: josephmovement.com |
| Homepage tagline | Multiple options tested | **Resolved: "Stop figuring it out alone."** |
| Mentor entry | Course/quiz first vs. browse freely | **Resolved: Browse freely, no gate** |
| Spiritual language on homepage | Faith-forward vs. inclusive | **Resolved: Inclusive — philosophy on inner pages** |
| Course delivery | Teachable vs. custom LMS | Start Teachable, migrate later |
| Community platform | Discord vs. Circle vs. custom | Start Discord, build custom at scale |
| Mobile app timing | Build now vs. after web launch | Build web first, app at 6 months |
| Monetization start | Free only vs. charge from day 1 | Free tier + paid at launch |
| Mentor filter categories | Individual niches vs. grouped | **Resolved: All/Tech/Business/Creative/Healthcare/Education/Finance/Law & Policy** |

---

## Tech Repos / Assets to Create

```
joseph-project/
├── web/          ← Next.js website
├── app/          ← React Native mobile app
├── backend/      ← API (if separate from Next.js)
├── content/      ← Course scripts, blog posts
└── design/       ← Brand assets, logos, mockups
```

---

## People / Roles Needed

| Role | Priority | Notes |
|------|----------|-------|
| Designer (UI/UX + brand) | High | Logo, site, app |
| Developer (Full-stack) | High | Next.js + React Native |
| Content writer | Medium | Courses + blog |
| Community manager | Medium | Discord / events |
| Mentor relations lead | Medium | Recruit + vet mentors |

---

## Contact / Accounts to Set Up

- [ ] Domain registration
- [ ] GitHub organization
- [ ] Supabase project
- [ ] Stripe account
- [ ] Vercel account
- [ ] Resend (email) account
- [ ] Sanity.io (CMS)
- [ ] Social media handles: Instagram, LinkedIn, TikTok — @josephproject or @josephgeneration

---

## Migration: Static Site → Full Platform

The current site (GitHub Pages, static HTML/CSS/JS) is a landing page only — no backend, no auth, no database, no payments. The full platform requires a proper stack.

**Full stack planned:**
- Frontend: Next.js on Vercel
- Database + Auth: Supabase
- Payments: Stripe
- Video sessions: Daily.co or Whereby
- Courses: Teachable (start) → custom LMS (scale)
- Mobile: React Native (Expo) — Phase 2

**The design, copy, and brand carry directly into Next.js — migration, not a rebuild.**

**Green light to migrate when:**
- [ ] `josephmovement.com` registered and live
- [ ] 15+ real mentors recruited and confirmed
- [ ] 100+ real emails on the waitlist
- [ ] At least one course content outline ready

**Rough timeline once green light is hit:**
- Week 1–4: Next.js app — auth, real mentor profiles, Calendly booking, Supabase DB
- Week 5–10: Stripe payments, course player, mentee + mentor dashboards
- Month 4–6: React Native mobile app, events system, community features

**Note:** Can start scaffolding the Next.js project in parallel while the static site collects interest — so the skeleton is ready when trigger conditions are met. Pick this up next session if ready.

---

## Jump-Start Prompt (for next Claude session)

> "We're building the Joseph Project — a mentorship platform for high schoolers and young adults. The plan is in Plan.md and the status log is in log_update.md. Pick up from [CURRENT TASK] and continue building."

---
