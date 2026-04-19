# The Joseph Project — Master Plan

---

## 1. Idea Assessment

**This is a strong, differentiated idea.** Here's why:

- **Timing**: Gen Z and Gen Alpha are deeply purpose-hungry. They don't just want jobs — they want meaning, mentorship, and belonging.
- **Gap in the market**: MentorCruise and similar platforms target professionals or career-switchers. Almost no one serves high schoolers and early college students with serious, project-based mentorship rooted in identity and calling.
- **Spiritual + Practical fusion**: Most faith-based platforms stop at inspiration. Joseph goes further — equipping young people with real skills, real mentors, and a real mission. That's rare.
- **The "Joseph" narrative is compelling**: Joseph in Genesis was a dreamer, a problem solver, a nation-preserver. He used his gift to serve beyond himself. That resonates deeply with the target audience.
- **Scalable model**: Courses, events, mentorship — three revenue/engagement streams that compound.

**Key risks to manage:**
- Mentor quality and retention (solution: vetting + stipend/recognition model)
- Keeping the spiritual identity without alienating secular users (solution: "humanity + divinity" framing — inclusive, not religious)
- Monetization without losing the mission (solution: freemium + premium tiers)

---

## 2. Brand Identity

### Name & Tagline
- **Platform Name**: **HENCEWARD** *(meaning: from this point, forward)*
- **Domain**: `henceward.com` — register immediately on Namecheap (~$12/yr)
- **Hero Headline**: *"Stop figuring it out alone."*
- **Mark tagline**: *"From here · Forward"*
- **Movement tagline**: *"A movement for the next generation of nation builders."*

### Core Values (Tenets) — Internal Use
These live on the About/inner pages, NOT the homepage. Homepage stays product-focused and universally accessible.
1. **Identity** — Know who you are before you build anything.
2. **Frame** — Your passion, personality, gifts, and experience are your blueprint.
3. **Innovation** — Creativity is your birthright. Solve real problems with what's in your hands.
4. **Influence** — Change the world with values, ideals, and your life.

### Tone & Voice
- Warm but direct. Inspiring but specific. Inclusive, not religious.
- Speak to the young person's actual pain — confusion, isolation, not knowing where to start.
- Write like a wise older sibling who's figured it out and wants to help — not a preacher, not a corporation.
- **Homepage rule**: Lead with outcomes, not philosophy. Philosophy lives on inner pages.

### Visual Identity — Resolved
- **Color Palette**: Near-black `#07070F` + deep violet `#8B5CF6` + electric amber `#F59E0B` + white
- **Accent**: Coral `#FB7185` for warmth; green `#4ADE80` for "Available" status
- **Typography**: *Syne* (brand/headings, 800 weight) + *Outfit* (body) + *JetBrains Mono* (labels/tags)
- **Logo Mark**: "The H→" — two geometric pillars (left: purple, right: gold — taller, suggesting ambition and forward lean) connected by a white forward arrow crossbar. Reads as both the letter H and as directional energy. Clean, Swiss-style geometry. Works at 16px favicon to billboard scale.
- **Wordmark**: HENCEWARD in Syne 800, letter-spaced, purple-to-gold gradient.
- **Tagline mark**: "FROM HERE · FORWARD" in small caps beneath the wordmark.
- **Files**: `logo.svg` (full lockup), `favicon.svg` (mark only).
- **Dark mode first**: Primary experience is dark. Light mode planned for later.
- **Imagery**: Real young people. Diverse. In action — building, creating, mentoring. Not stock-photo-generic.

### Mentor Filter Categories (Landing Page)
All · Tech · Business · Creative · Healthcare · Education · Finance · Law & Policy

---

## CURRENT BUILD STATUS (April 2026)

### Pages Live on GitHub Pages
| Page | File | Status |
|------|------|--------|
| Homepage | `index.html` | ✅ Live |
| About / Brand Story | `about.html` | ✅ Live |
| Course 101 — Identity | `Course.html` | ✅ Live · Mailchimp wired |
| Become a Mentor | `mentors.html` | ✅ Live · Tally form embedded |

### Assets
| Asset | File | Status |
|-------|------|--------|
| Logo (full lockup) | `logo.svg` | ✅ Done |
| Favicon | `favicon.svg` | ✅ Live on all pages |
| Course content (markdown) | `Courses/` folder | ✅ 4 courses + quizzes |
| Mentor application form fields | `Form.txt` | ✅ Reference doc ready |

### Integrations
| Integration | Status | Notes |
|-------------|--------|-------|
| Mailchimp | ✅ Wired | JSONP from Course gate + homepage waitlist |
| Tally (mentor form) | ⏳ Partial | Published but needs 12 questions added (see Form.txt) |
| Tally → Mailchimp | ❌ Not connected | 5-click setup in Tally → Integrations |

---

## 3. Platform Architecture

### Website (josephproject.co — suggested domain)

#### Pages
| Page | Purpose |
|------|---------|
| `/` | Hero — vision statement, CTA to join or explore |
| `/about` | Story, tenets, mission, who we are |
| `/mentors` | Browse mentors by field, filter by career/project type |
| `/courses` | Self-paced courses: Identity, Frame, Innovation, Influence |
| `/events` | Upcoming talks, workshops, community gatherings |
| `/apply` | Apply as a mentee or mentor |
| `/blog` | Articles, stories, reflections |
| `/dashboard` | Logged-in user hub (sessions, progress, messages) |

#### Key Website Features
- Mentor discovery + filter (by industry, interest, project type)
- Session booking (calendar integration — Calendly or custom)
- Mentee profile + goal-setting
- Course player (video + readings + reflection prompts)
- Community forum or group threads
- Events calendar + RSVP

---

### Mobile App

#### Platform: React Native (iOS + Android from one codebase)

#### Core App Features
| Feature | Description |
|---------|-------------|
| Onboarding | Identity assessment — personality, gifts, passions |
| Mentor Match | AI-assisted matching based on goals + profile |
| Sessions | Schedule, join (video call), and review mentorship sessions |
| Courses | Mobile-first course content (Identity, Frame, Innovation, Influence) |
| Journal | Daily reflection prompts + personal goal tracking |
| Community | Feed of posts, wins, and challenges from peers |
| Notifications | Session reminders, new mentor matches, course nudges |

#### App Flow (First-Time User)
1. Sign up → Choose role (Mentee / Mentor / Explorer)
2. Complete Identity Profile (5-min assessment)
3. Get matched with 3 mentor suggestions
4. Unlock "Identity" course (free)
5. Book first session

---

## 4. Courses Offered

### Course 101 — Identity
*"Who are you before you do anything?"*
- The Master Creator and what it means that you're made in His image
- Understanding your God-given worth
- Overcoming limiting beliefs about yourself

### Course 201 — Frame
*"How were you made?"*
- Passion mapping
- Personality and strengths discovery (StrengthsFinder / Enneagram integration)
- Aligning gifts with purpose

### Course 301 — Innovation
*"What problem are you called to solve?"*
- Creative problem solving
- Design thinking for young leaders
- Project-based learning: build something that matters

### Course 401 — Influence
*"How do you change the world?"*
- Leading with values
- Community and civic impact
- Building a life that is your message

### Bonus Course — American Dream Reimagined
*"America as we see it — our past, our future, and our role."*
- History through the lens of justice, hope, and calling
- What it means to be a nation builder today

---

## 5. Mentorship Model

### Mentee Tiers
- **Explorer (Free)**: Access to Identity course, community feed, 1 free session/month
- **Builder ($29/mo)**: Full course library, 2 sessions/month, journal + goal tracker
- **Founder ($79/mo)**: Unlimited sessions (from mentor pool), priority matching, events access

### Mentor Model
- Apply + vet (background check + mission alignment interview)
- Set availability + rate (platform takes 15% cut)
- Top mentors featured, earn badges, speaking invitations to events
- Volunteer mentor option for mission-aligned professionals

---

## 6. Events Strategy

- **Joseph Talks** — Speaker series (quarterly, local then national)
- **Build Weekends** — Project-based hackathons for young innovators
- **Innovation City Institute** — Annual 3-day immersive for serious builders
- **Online Live Sessions** — Monthly community webinars with featured mentors

---

## 7. Tech Stack

| Layer | Choice | Reason |
|-------|--------|--------|
| Frontend (Web) | Next.js (React) | SEO, performance, full-stack capability |
| Mobile App | React Native (Expo) | One codebase, iOS + Android |
| Backend/API | Node.js + Express or Next.js API routes | Familiar, fast to build |
| Database | PostgreSQL (via Supabase) | Relational data, auth built-in, free tier |
| Auth | Supabase Auth | Email, Google, Apple login |
| Video Sessions | Daily.co or Whereby embed | Simple API, no infrastructure overhead |
| Courses | Custom LMS or Teachable embed | Start with Teachable, migrate to custom later |
| Payments | Stripe | Industry standard, easy subscription billing |
| Hosting | Vercel (web) + Expo EAS (mobile) | Fast deployment, free tiers |
| Email | Resend or SendGrid | Transactional + marketing emails |
| CMS (blog/content) | Sanity.io | Flexible content modeling |

---

## 8. Go-To-Market Strategy

### Phase 1 — Seed (Months 1–3) ← WE ARE HERE
- [x] Launch landing page (index.html, about.html)
- [x] Course 101 live with email capture
- [x] Mentor application page live (mentors.html + Tally form)
- [ ] Add Tally form questions (Form.txt) — URGENT
- [ ] Register henceward.com — URGENT
- [ ] Recruit 10–15 founding mentors (personal outreach)
- [ ] Write + load 7-part mentee email sequence into Mailchimp
- [ ] Run first Henceward Talk event (virtual, 1 speaker)
- [ ] Claim @henceward social handles

### Phase 2 — Launch (Months 4–6)
- [ ] Course 201 — Frame (interactive, with FRAME assessment)
- [ ] Build join.html — dedicated mentee onboarding
- [ ] Mentors browse page (real profiles, Calendly booking)
- [ ] Begin paid mentorship — Builder tier (Stripe)
- [ ] 50+ mentees enrolled via community outreach
- [ ] Discord community server live

### Phase 3 — Scale (Months 7–12)
- [ ] Migrate to Next.js + Supabase (when triggers are met — see log_update.md)
- [ ] Full course library live (301, 401, Bonus)
- [ ] Partner with HBCUs, youth ministries, schools
- [ ] Launch Innovation City Institute event
- [ ] Apply for education + youth development grants
- [ ] Mobile app (React Native) development begins

---

## 9. Revenue Model Summary

| Stream | Source |
|--------|--------|
| Subscriptions | Mentee monthly plans |
| Mentor commissions | 15% of session fees |
| Course sales | One-time or bundle purchases |
| Events | Ticket sales + sponsorships |
| Grants/Donations | Mission-aligned foundations |
| Corporate partnerships | Companies sponsoring mentee seats |

---

## 11. User Journeys & Marketing Funnels

### The Core Principle (Seth Godin)
> *"Find the smallest viable audience. Make something remarkable for them. Let them spread it."*

Joseph has two distinct users — mentees and mentors — each with their own emotional journey, entry point, and reasons to stay. The website must be designed to serve BOTH simultaneously without confusing either. Every page should know who it's talking to.

---

### MENTEE JOURNEY — "Stop Figuring It Out Alone"

The emotional truth: *"I know I'm made for something, but I don't know what it is, and I feel behind."*

| Stage | What They Feel | What Joseph Does | Touch Point |
|-------|---------------|-----------------|-------------|
| **Awareness** | Lost, comparing, confused | Speak to the feeling — not the product | Social content, blog, word of mouth |
| **First Touch** | Curious but skeptical | Prove we understand them — fast | Homepage hero copy |
| **Hook** | "This is for me" | Give them something free and valuable | Course 101 (email gate) |
| **Nurture** | Engaged but uncommitted | Deliver value before asking for anything | Email sequence (7-part) |
| **Convert** | Ready to invest | Make the next step obvious and low-risk | Book free session / upgrade to Builder |
| **Retain** | Growing | Keep the momentum going | Weekly dispatch, journal prompts |
| **Advocate** | Transformed | Give them a story to tell | Shareable certificate, refer-a-friend |

**Mentee Email Sequence (7 emails after Course 101 sign-up):**
1. Day 0 — Welcome + Course 101 link: *"Your journey starts here."*
2. Day 2 — "Here's what Module 1 says about why you feel stuck."
3. Day 5 — Mid-course check-in + one insight from the course
4. Day 8 — "You've finished Identity. Here's what comes next — Frame."
5. Day 12 — Mentor spotlight: a real story of transformation
6. Day 16 — Soft pitch: "You're ready for a mentor. Here's how it works."
7. Day 21 — "Book your first free session. No commitment. Just a conversation."

---

### MENTOR JOURNEY — "Be the Mentor You Wish You Had"

The emotional truth: *"I've built something real. I know what it took. I want to give someone else a shorter path."*

| Stage | What They Feel | What Joseph Does | Touch Point |
|-------|---------------|-----------------|-------------|
| **Awareness** | Successful, want to give back | Tell them their story matters to the next generation | LinkedIn content, existing mentor referrals |
| **First Touch** | Intrigued, slightly uncertain | Show them the vision clearly and quickly | mentors.html landing page |
| **Application** | Committed, want to be vetted | Make the process feel intentional, not bureaucratic | Clean application form (Tally.so) |
| **Onboarding** | Excited, want to feel prepared | Equip them with tools + context | Welcome kit, onboarding call |
| **First Session** | Slightly nervous | Make booking seamless and well-supported | Calendly integration |
| **Active** | Energized, building a reputation | Feature them, celebrate them | Mentor spotlight emails, "Founding Mentor" badge |
| **Advocate** | Proud and invested | Give them something to recruit with | Referral program, speaking invitations |

---

### THE HOMEPAGE — Dual Audience Design

The homepage must serve two people at once: the confused 19-year-old and the 35-year-old VP who wants to give back.

**Current problem:** Homepage only has ONE CTA direction (browse mentors / join waitlist).
**Fix:** Add a clear fork — two paths, two identities:

```
Primary CTA:    [ Find a Mentor — Free ]
Secondary CTA:  [ Become a Mentor → ]
```

The "Become a Mentor" link goes to `mentors.html` — a dedicated landing page with its own value proposition, social proof, and application form.

---

### PAGES NEEDED FOR COMPLETE FUNNELS

| Page | Audience | Purpose | Priority |
|------|---------|---------|----------|
| `mentors.html` | Mentor prospects | Convert professionals into applicants | 🔴 High |
| `join.html` | Mentees | Dedicated sign-up + onboarding flow | 🔴 High |
| `blog/` | Both | Organic traffic + trust building | 🟡 Medium |
| `pricing.html` | Mentees | Transparent tiers, reduce friction | 🟡 Medium |
| `dashboard.html` | Logged-in users | Hub for sessions, courses, progress | 🟢 Later |

---

### LEAD CAPTURE STRATEGY

**For Mentees:**
- Course 101 email gate (primary lead capture — already live)
- Homepage waitlist form (secondary)
- Blog post CTAs ("Get the free Identity guide")
- Event RSVP (captures name + email + interest level)

**For Mentors:**
- mentors.html application form (primary)
- "Know someone who'd make a great mentor?" referral link
- LinkedIn outreach → profile page → apply

**Email is the asset. Social media is the amplifier.**
Every piece of content should drive back to an email capture. The email list is the business. Social followers are borrowed audiences; email subscribers are owned.

---

### CONTENT PILLARS (Organic Growth Engine)

Three content themes that attract both audiences:

1. **Identity & Purpose** — "Why Most People Never Discover Who They Are" (attracts mentees)
2. **Generational Impact** — "What It Means to Be a Nation Builder in 2026" (attracts both)
3. **Mentor Stories** — "I Gave 2 Hours a Month for a Year. Here's What It Built." (attracts mentors)

Post formats: Instagram carousels, TikTok short-form, LinkedIn long-form, email newsletter.

---

## 10. Vision Statement (Draft)

> *Joseph is a movement for the next generation of nation builders — young people who know who they are, understand how they're made, and use their gifts to solve the problems of their time. We believe every person carries divinity — creativity, purpose, and the capacity to change the world. Our job is to find that in you, frame it, and unleash it.*

---
