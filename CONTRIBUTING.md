# Contributing to Sunrise Atelier
 
Sunrise Atelier builds free, open-source tools for communities that can't afford enterprise software. All of our repositories are public — anyone can read the code, follow along, and learn from it. Active contribution (opening pull requests, pushing branches, reviewing code) requires joining a team first.
 
This document explains how that works for each program.
 
---
 
## How contribution works
 
### Two levels of involvement
 
**Reading and following along**
All repositories are public. No application needed — browse the code, read issues, follow progress.
 
**Active contributor (team member)**
To open pull requests, push branches, or review code, you need to be added as a collaborator on the relevant repository. This happens after you apply and are accepted onto a program team.
 
Pull requests are restricted to collaborators only. This isn't about gatekeeping — it's about maintaining quality and making sure every contributor has context, support, and a clear lane to work in.
 
---
 
### How to apply
 
Applications are handled directly through our Discord server via membership screening.
 
1. **Request to join the Discord** — [discord.gg/YOUR_INVITE_LINK](https://discord.gg/YOUR_INVITE_LINK)
2. **Complete the screening form** — you'll be asked for your GitHub, your LinkedIn, your desired team(s), and your relevant skills. If you're applying as a developer, list your familiarity with your target team's stack (see the per-program sections below for each team's stack). If you're not interested in any roles but still interested in joining the community, there is an option to be a guest in our community.
3. **We'll review and follow up** — typically within 3 days, maximum a week -- we'll never make you wait. We'll make sure to communicate if a role is limited on space, but we'll always try our best to accomodate everyone.
Once accepted, you'll be added to the relevant GitHub team and given access to your team's repository(s).
 
---
 
## Program-specific requirements
 
Each program needs different kinds of contributors. Read the section for the program you're applying to.
 
---
 
### 🔌 Plug & Play
 
**What it is:** Plug-and-play operational tools for underserved organizations. First focus is local U.S. cities; the scope expands from there. Each tool type lives as its own submodule with its own stack.
 
**Who we need:**
- **Developers** — frontend, backend, full-stack, or infrastructure. Expect to be comfortable with multiple languages if you intend to contribute to multiple tools. Most tools are built using React, TypeScript, and TailwindCSS.
- **Researchers** — context. context. context. researchers may participate in community needs assessment or user interviews with persons of interest.
- **Designers** — tool UI/UX, accessibility, documentation design. Should also be familiar with design tools like Canva, Figma, and concepts like A/B testing.
**Stack varies by submodule.** Check the README inside each submodule directory for its specific setup instructions.
 
---
 
### 🤝 Neighbor
 
**What it is:** OC volunteer matching — a curated directory of local organizations and an AI-assisted matching layer connecting volunteers to the right place.
 
**Stack:** Next.js, React, TypeScript, Tailwind CSS · Python / FastAPI backend via sunrise-api · Supabase
 
**Who we need:**
- **Frontend developers** — Next.js, React, TypeScript
- **Backend developers** — Python, FastAPI, PostgreSQL
- **Curators** — research and maintain the volunteer organization directory. Non-technical role. Strong writing and attention to detail required.
- **Researchers** — org outreach, volunteer user interviews, needs assessment
- **Designers** -- Should be familiar with A/B testing and tools like Canva and Figma.
---
 
### 🏮 Almanac
 
**What it is:** Free, bilingual business tools for AAPI businesses — POS, reservation, inventory. Built to be deployed on-site by volunteers, not just published on GitHub.
 
**Stack:** Next.js, React, TypeScript, Tailwind CSS · Backend TBD
 
**Who we need:**
- **Developers** — frontend, backend, full-stack
- **Bilingual contributors** — Mandarin, Cantonese, Vietnamese, Korean, and Japanese speakers for translation and cultural review. This is not a translation gig — we need people who understand the business context and can catch cultural mismatches, not just language errors.
- **Deployment volunteers** — willing to go on-site to small businesses, install tools, configure settings, and train staff. Non-technical but requires patience, communication skills, and ideally some language overlap with the business owner. CURRENTLY NOT ACCEPTING APPLICANTS UNTIL FURTHER NOTICE.
- **Designers** — UI/UX with sensitivity to multilingual interfaces and non-technical users. Should be familiar with A/B testing and tools like Canva and Figma.
  
**What to include in your application:**
- For bilingual contributors: which language(s) 
- For deployment volunteers: location (we need people who can physically reach OC and Bay Area business corridors) and availability
**Note:** Almanac has the most human-facing deployment work of any program. If you're applying as a deployment volunteer, the most important thing is showing up reliably. That matters more than any technical skill.
 
---
 
### 🔭 Aperture
 
**What it is:** A plain-language database of research, internship, and fellowship opportunities for first-generation and non-target students. Every opportunity described honestly, in plain language, in one place.
 
**Stack:** Next.js, React, TypeScript, Tailwind CSS · Supabase
 
**Who we need:**
- **Curators** — the most important role on this program. Research opportunities (REUs, fellowships, internships, research programs), write plain-language descriptions, verify eligibility details, keep entries current. Strong writing required. First-hand experience navigating these programs as a first-gen or non-target student is a genuine asset.
- **Engineers** — frontend, backend, full-stack
- **Researchers** — systematic sourcing of new opportunities, outreach to program administrators, gap analysis

---
 
### 🌐 Website
 
**What it is:** The public Sunrise Atelier website — program information, volunteer interest form, organization front door.
 
**Stack:** React, TypeScript, Tailwind CSS · Supabase
 
**Who we need:**
- **Frontend engineers** — React, TypeScript
- **Designers** — UI/UX, visual design

---
 
 
## Code standards
 
- Follow the existing style in each repo — check for an `.eslintrc`, `pyproject.toml`, or style notes in the repo README
- Write tests for new functionality where tests already exist in the repo
- Document non-obvious decisions in comments, not obvious ones
- Commit messages: present tense, imperative mood — `Add volunteer matching endpoint` not `Added` or `Adding`
---
 
## Pull request process
 
1. Branch from `main` with a descriptive name — `feat/volunteer-matching-api` or `fix/org-directory-search`
2. Keep PRs focused — one feature or fix per PR
3. Fill out the PR template — it exists for a reason
4. Request review from at least one team member
5. Address review comments before re-requesting review
6. A team lead with Maintain access will merge once approved
---
 
## Questions
 
Ask in the relevant program channel in Discord before opening an issue. Chances are someone has context that will save you time.
 
---
 
*Sunrise Atelier is based in the Bay Area. Open source.*
