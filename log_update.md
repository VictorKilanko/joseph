# Henceward — Build Log & Jump-Start Document

> Read this file at the start of every session. It tells you exactly where we are and what to do next.
> Last updated: 2026-04-19 (session 4)

---

## QUICK REFERENCE

| Item | Detail |
|------|--------|
| **Platform name** | HENCEWARD |
| **Tagline** | Stop figuring it out alone. |
| **Sub-tagline** | From here · Forward |
| **GitHub repo** | https://github.com/VictorKilanko/joseph |
| **Live site** | https://victorkilanko.github.io/joseph/ |
| **Domain to register** | henceward.com (check availability first) |
| **Mailchimp audience** | Henceward · ID: `00388b3ee6` · Server: `us9` |
| **Mailchimp tags** | `Henceward Mentees` / `Henceward Mentors` |
| **Tally form** | https://tally.so/r/gDNkWO (mentor application) |
| **Tally form fields** | See `Form.txt` in this folder |
| **Owner email** | victorkilanko@gmail.com |

---

## JUMP-START PROMPT (paste this into the next Claude session)

> "We are building Henceward — a mentorship platform for high schoolers and young adults. The brand, platform, and strategy are fully defined. The static site is live on GitHub Pages at https://victorkilanko.github.io/joseph/. Read Plan.md for full strategy and log_update.md for current status. Pick up from [CURRENT TASK]."

---

## WHAT HAS BEEN BUILT (complete)

### Strategy & Planning
- [x] Idea validated — concept, differentiation, risks (Plan.md §1)
- [x] Brand identity — HENCEWARD, visual system, tone, taglines (Plan.md §2)
- [x] Platform architecture — pages, app features, user flow (Plan.md §3)
- [x] Course curriculum — 101 Identity, 201 Frame, 301 Innovation, 401 Influence, Bonus (Plan.md §4)
- [x] Mentorship model — 3 tiers (Explorer/Builder/Founder), mentor vetting, revenue split (Plan.md §5)
- [x] Events strategy — Henceward Talks, Build Weekends, Innovation City Institute (Plan.md §6)
- [x] Tech stack selected — static HTML now → Next.js + Supabase + Stripe later (Plan.md §7)
- [x] Go-to-market — 3-phase plan over 12 months (Plan.md §8)
- [x] Revenue model — 6 streams (Plan.md §9)
- [x] Vision statement (Plan.md §10)
- [x] Dual funnel strategy — mentee journey + mentor journey, email sequences, content pillars (Plan.md §11)

### Brand & Design
- [x] Full rebrand: JOSEPH → **HENCEWARD** across all files
- [x] Logo designed: "H→ mark" — two pillars (purple/gold) + white forward arrow crossbar
- [x] `favicon.svg` — mark only, all 4 pages updated
- [x] `logo.svg` — full lockup: mark + HENCEWARD wordmark + "FROM HERE · FORWARD" tagline
- [x] Nav logo updated on all pages to H→ mark
- [x] Design system: #07070F bg · #8B5CF6 purple · #F59E0B gold · Syne + Outfit + JetBrains Mono

### Website (GitHub Pages — static HTML/CSS/JS)
- [x] `index.html` — Homepage v2: hero, mentor grid + filter, how it works, courses, waitlist, footer
- [x] `about.html` — Brand story: "Why Henceward?", archetype (Joseph of Egypt inspiration), beliefs, who it's for, manifesto
- [x] `Course.html` — Full interactive Course 101 (Identity):
  - Email + name gate → auto-submits to Mailchimp
  - 6 modules (full content, animations, pull quotes, insight boxes)
  - 3 reflection journal questions per module (auto-save to localStorage)
  - 2 quiz questions per module with animated feedback
  - Module locking — complete quiz to unlock next
  - Confetti celebration per module + course complete screen
  - Personalized certificate (shows user's name)
  - Personal journal modal (view all reflections in one place)
  - Top progress bar + sidebar module tracker
  - Mobile-responsive
- [x] `mentors.html` — "Become a Mentor" landing page:
  - Hero: "Be the mentor you wish you had."
  - Why mentor (4 value props), who qualifies (5 criteria), 3-step process
  - Founding mentor spotlight profiles
  - Tally application form embedded in modal
- [x] `Course.html` linked from homepage Course 101 card (LIVE badge)
- [x] `mentors.html` linked in homepage nav ("Become a Mentor")

### Email & Forms
- [x] Mailchimp account — audience "Henceward" created with tags
- [x] Course 101 gate → submits email + first name to Mailchimp via JSONP (safe, no API key exposed)
- [x] Homepage waitlist form → submits to Mailchimp via JSONP
- [x] Tally mentor application form created — ID: gDNkWO — PUBLISHED but needs questions added
- [x] `Form.txt` — all 12 Tally field definitions + Mailchimp integration instructions saved

### Courses Content (markdown — not yet interactive)
- [x] `Courses/101_Identity.md` — 6-module course content (full)
- [x] `Courses/101_Identity_Quiz.md` — 20-question reflective assessment
- [x] `Courses/201_Frame.md` — FRAME framework course content
- [x] `Courses/201_Frame_Quiz.md`
- [x] `Courses/301_Innovation.md`
- [x] `Courses/401_Influence.md`
- [x] `Courses/README.md` — curriculum overview + FRAME acronym explained

---

## WHAT IS LEFT — IN PRIORITY ORDER

### 🔴 DO THIS NOW (blocks everything else)

**1. Add questions to Tally form** ← USER TASK (takes 15 min)
   - Go to tally.so → open form gDNkWO → Edit
   - Add all 12 fields from `Form.txt`
   - Republish when done
   - Then connect: Tally → Integrations → Mailchimp → tag "Henceward Mentors"

**2. Register henceward.com** ← USER TASK (takes 5 min)
   - Go to namecheap.com → search henceward.com → register (~$12/yr)
   - If taken: henceward.co or henceward.app
   - This makes the site shareable and professional

**3. Connect domain to GitHub Pages** ← USER TASK (takes 10 min)
   - GitHub → repo → Settings → Pages → Custom domain → type henceward.com → Save
   - At registrar: add CNAME record → `victorkilanko.github.io`

---

### 🟡 BUILD NEXT (Claude can do these)

**4. Write 7-part mentee email sequence**
   - Triggers when someone submits Course 101 gate
   - Loaded into Mailchimp as an automation
   - See Plan.md §11 for the full email-by-email outline
   - Output: 7 emails written, ready to paste into Mailchimp

**5. Build Course 201 — Frame (interactive)**
   - Same structure as Course.html but for Course 201
   - The FRAME quiz is the centrepiece: a real personality/gifts assessment
   - F = Fire (passion) · R = Roots (experience) · A = Abilities · M = Makeup (personality) · E = Expression
   - Content already exists in Courses/201_Frame.md

**6. Homepage improvements**
   - Add "Become a Mentor" as a more prominent second CTA in the hero (not just nav)
   - Add a social proof section (real testimonial or quote)
   - Update mentor count + stats to feel real

**7. Build join.html — dedicated mentee onboarding**
   - Captures: name, email, age range, area of interest, what they want from a mentor
   - Goes into Mailchimp with tag "Henceward Mentees"
   - Triggers the 7-part email sequence

**8. Set up social media handles** ← USER TASK
   - Check @henceward on Instagram, LinkedIn, TikTok, X
   - Claim them all even if you don't post yet

---

### 🟢 SHORT-TERM (next 30 days)

- [ ] Recruit 10–15 founding mentors — send: about.html + mentors.html + tally.so/r/gDNkWO
- [ ] Build mentors-browse.html — public mentor directory (once real profiles exist)
- [ ] Build pricing.html — clear tier breakdown (Explorer free / Builder $29 / Founder $79)
- [ ] Integrate Calendly per mentor (for session booking)
- [ ] Plan first Henceward Talk event (virtual, 1 speaker, 1 hour)
- [ ] Build Course 301 — Innovation (interactive)
- [ ] Start blog: 3 foundational articles (identity, purpose, mentorship)

---

### 🔵 MEDIUM-TERM (30–90 days)

- [ ] Onboard first 50 mentees — outreach via churches, schools, youth orgs
- [ ] Set up Discord community server
- [ ] Apply for education/youth development grants
- [ ] Build Course 401 — Influence (interactive)
- [ ] Launch Bonus Course — American Dream Reimagined

---

### ⚫ WHEN TO MIGRATE TO NEXT.JS

Trigger conditions (all must be true before migrating):
- [ ] henceward.com registered and live
- [ ] 15+ real mentors recruited and confirmed
- [ ] 100+ real emails on the waitlist
- [ ] 3 courses live (101, 201, 301)

Migration scope: Next.js + Supabase (auth + DB) + Stripe (payments) + Calendly/Daily.co (sessions)
Timeline once triggered: ~10 weeks to full MVP

---

## KEY DECISIONS LOG

| Decision | Status | Resolution |
|----------|--------|------------|
| Platform name | ✅ Resolved | **HENCEWARD** |
| Homepage tagline | ✅ Resolved | "Stop figuring it out alone." |
| Domain | ⏳ Pending | henceward.com — register ASAP |
| Mentor entry | ✅ Resolved | Browse freely, no gate |
| Spiritual language | ✅ Resolved | Inclusive on homepage; philosophy on inner pages |
| Course delivery | ✅ In progress | Custom HTML (built). Next.js LMS at scale. |
| Email platform | ✅ Resolved | Mailchimp (Henceward audience, tags for segmentation) |
| Mentor applications | ✅ Resolved | Tally form (gDNkWO) — needs questions added |
| Community | ⏳ Pending | Discord to start → custom at scale |
| Mobile app | ⏳ Pending | Build after web MVP is validated |
| Monetization | ⏳ Pending | Free tier live. Paid tiers when Stripe is integrated. |

---

## ACCOUNTS & CREDENTIALS

| Service | Status | Notes |
|---------|--------|-------|
| GitHub | ✅ Live | github.com/VictorKilanko/joseph |
| GitHub Pages | ✅ Live | victorkilanko.github.io/joseph |
| Mailchimp | ✅ Live | Audience: Henceward · ID: 00388b3ee6 |
| Tally | ✅ Live | Form: gDNkWO · needs questions added |
| Domain (henceward.com) | ❌ Not registered | Register on Namecheap |
| Vercel | ❌ Not set up | Needed for Next.js migration |
| Supabase | ❌ Not set up | Needed for auth + database |
| Stripe | ❌ Not set up | Needed for paid tiers |
| Discord | ❌ Not set up | Community — set up when first 25 members |
| Social media @henceward | ❌ Not claimed | Instagram, LinkedIn, TikTok, X |

---

## PEOPLE / ROLES STILL NEEDED

| Role | Priority | Why |
|------|----------|-----|
| 10–15 Founding Mentors | 🔴 High | Core product doesn't work without real mentors |
| UI/UX Designer | 🟡 Medium | Polish brand, build design system in Figma |
| Full-stack Developer | 🟡 Medium | Next.js migration when triggers are met |
| Community Manager | 🟢 Later | Run Discord, events, social |
| Content Writer | 🟢 Later | Blog, email sequences, course refinement |
