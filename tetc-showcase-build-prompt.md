# Build Prompt — TETC Program Tooling Showcase (Leadership-Facing)

## What you're building
A single, self-contained HTML page that showcases the suite of digital tools built for the TETC engineering program. **Audience: upper leadership.** Purpose: make the body of work legible at a glance and demonstrate the program's capability. It must communicate value in a **60-second scan**, even if the viewer never clicks a single link.

## Core principles (non-negotiable)
- **Outcomes first, tool second.** Every item leads with the problem it solves and who it helps — not what it's built with. Do not mention implementation details (HTML, React, Firebase, etc.) unless it is genuinely the point.
- **Program's tooling, not personal projects.** Voice is "we built / the program now has" — capability, not a personal portfolio.
- **Scannable.** A leader should grasp scope and value without clicking anything. Every card reads fully on its own.
- **Honest but forward-looking.** Open problems appear as *direction and momentum* — a roadmap — never as loose ends or a bug list.
- **Plain language only.** No internal pedagogy jargon, framework names, or insider terminology anywhere on the page.

## Structure
1. **Header** — program name, one-line statement of what the toolset is and why it exists. Optional scope line (e.g., "12 tools across 6 units"). Use real numbers or omit — never invent.
2. **Three audience sections**, in this order:
   - **For Students** — tools students use directly
   - **For Teachers** — tools that support planning, delivery, and coaching
   - **For Leadership** — tools built for program oversight and decisions
3. **What's Next** — forward-looking section. Open questions and upcoming builds, framed as roadmap and direction.

## Card anatomy (every tool)
- Plain-language title
- One line: what it does / who it helps
- One sentence: the problem it solves
- Status badge: **Shipped** / **In Progress** / **Exploring**
- Link button if live; omit the button if not

## Visual design (TETC brand)
- Primary Teal `#186172`, Accent Magenta `#BD2F7F`, Calibri (with system sans fallback)
- Card grid, generous whitespace, strong section headers, color-coded status badges
- Responsive / mobile-friendly
- Should feel designed and credible — this is a demonstration artifact, not a links page

## Content to populate (fill before running)
Replace the example below with the real inventory. One bullet per tool, pipe-separated:
`**Title** | what it does / who it helps | Problem it solves. | Status | link`

### For Students
- **Stadium Logistics Rover — Companion** | Self-paced guide for the VEX AIM rover coding challenge; students pick their own entry level, from drag-and-drop blocks up to real Python | Lets a mixed-experience class each start where they are and pull just-in-time hints, instead of everyone stalling at the same wall waiting on the teacher. | Shipped | https://tetc-edu.github.io/Stadium-Rover-Companion/
- **River Crossing — Companion** | The same self-paced robot-coding companion, built around the classic wolf–goat–cabbage logic puzzle | Pairs a reasoning puzzle with the code so students debug their thinking before their program; tiered hints keep them moving without hand-holding. | Shipped | https://tetc-edu.github.io/River-Crossing-Companion/
- **Engineering Skills & Careers** | A reflection tool where students star the lessons and careers that hooked them, rank a top three, and name a dream job | Connects hands-on work to real career paths, and captures interest as anonymous totals — no names — so the program can see what lands without surveilling anyone. | Shipped | https://tetc-skills-careers.web.app/

### For Teachers
- **Hydraulic Machines / JudoBot — Teacher Guide** | Full interactive guide for the 2-day JudoBot hydraulics build: phase-by-phase timing, prep checklist, materials, talking points | Replaces a long static document with a paced, in-class reference a teacher can run the room from. | Shipped | https://tetc-edu.github.io/hydraulic-machines-guide/
- **Hydraulic Rescue Arm — Teacher Guide** | Teacher guide for the 3-day Hydraulic Rescue Arm challenge — force ratios, build, and the relay competition | One structured, navigable guide in place of a sprawling multi-page doc. | Shipped | https://tetc-edu.github.io/Hydraulic-Arm-Teacher-Guide/

### For Leadership
- **Engineering Skills & Careers — Results Dashboard** | A live, anonymous rollup of which lessons and careers students gravitate toward | Gives leadership a real signal on what's resonating across the program — aggregate only, no personal data. | Shipped | https://tetc-skills-careers.web.app/dashboard.html

> **TWO MORE TOOLS** live on local storage — add them in Claude Code. Slot each into the correct audience section above using the same `Title | what it does / who it helps | Problem | Status | link` format.

### What's Next
- **One shared unit template.** Every unit's materials look and work the same way no matter who builds them — so consistency and quality stop depending on which teacher authored it.
- **A single source of truth.** A published, canonical version of each unit that can't be quietly edited out from under the team.
- **Quiet, exam-free insight into student thinking.** Building on what the Skills & Careers tool already proves possible — capturing the texture of how students reason as a byproduct of the work, never a test, never surveillance.

## Constraints
- Single self-contained HTML file; no external dependencies beyond fonts.
- No `localStorage` / `sessionStorage`.
- Include only tools that are provided here — do not invent tools, links, or metrics.
