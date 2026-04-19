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
- **Platform Name**: **JOSEPH**
- **Domain**: `josephmovement.com` (available, no conflicts — register immediately)
- **Hero Headline**: *"Stop figuring it out alone."*
- **Sub-tagline**: *"A movement for the next generation of nation builders."*
- **Note**: Original tagline "Find Your Gift. Build Your World." retired from homepage — too abstract, no clear mechanism. Moved to inner pages / About.

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
- **Logo Mark**: Triangle of three dots — gold top (vision/dream), purple base left + right (community/foundation). Thin connecting lines. Clean, symbolic, non-religious.
- **Dark mode first**: Primary experience is dark. Light mode planned for later.
- **Imagery**: Real young people. Diverse. In action — building, creating, mentoring. Not stock-photo-generic.

### Mentor Filter Categories (Landing Page)
All · Tech · Business · Creative · Healthcare · Education · Finance · Law & Policy

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

### Phase 1 — Seed (Months 1–3)
- Launch landing page + waitlist
- Recruit 10–15 founding mentors (hand-picked)
- Run first Joseph Talk event (virtual or local)
- Enroll first 50 mentees (community outreach — churches, schools, youth orgs)

### Phase 2 — Launch (Months 4–6)
- Launch MVP website + mobile app
- Open course: Identity (free)
- Begin paid mentorship (Builder tier)
- Press: faith-based media, youth entrepreneurship blogs, LinkedIn

### Phase 3 — Scale (Months 7–12)
- Full course library live
- Partner with HBCUs, Christian universities, youth ministries
- Launch Innovation City Institute event
- Explore grant funding (education + youth development grants)

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

## 10. Vision Statement (Draft)

> *Joseph is a movement for the next generation of nation builders — young people who know who they are, understand how they're made, and use their gifts to solve the problems of their time. We believe every person carries divinity — creativity, purpose, and the capacity to change the world. Our job is to find that in you, frame it, and unleash it.*

---
