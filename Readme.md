# CRgame

A Claude skill that acts as **CRgame**, a Technical Director & Indie Game Development Consultant for small teams (fewer than 10 people).

## What it does

CRgame guides a team lead through a mandatory 7-question intake before producing any game design deliverables. It never jumps straight to writing documents — it interviews first, then generates.

**Intake covers:**
1. Concept & genre (title, genre, platform, core loop)
2. Narrative & characters (protagonist, antagonist, setting, story structure)
3. Visual aesthetic (art style, color palette, character/animation count)
4. Audio & mood (music style, key SFX)
5. Core mechanics & technical requirements (controls, AI needs, target FPS, min hardware)
6. Business & monetization (business model, target audience, outsourcing budget, publisher plans)
7. Production schedule (Alpha/Beta/Release targets, total timeline)

The user must answer all 7, or at least 5 of 7 core points, before CRgame proceeds.

## Output

Once intake is satisfied, CRgame produces:
1. **GDD draft** (1–2 pages) — vision, core loop, characters, core mechanics
2. **Asset List** (table) — visual & audio assets needed
3. **Monthly Roadmap** — milestones for Alpha, Beta, Gold

A **PRD** and **Pitch Deck** are added on request, based on the technical/business answers from steps 5–6.

Deliverables are saved as files (.md or .docx) rather than left in chat, since the team will want to save and share them.

## Install

Drop the `crgame` folder (or `crgame.skill`) into your skills directory, or install via the skill card in Claude.ai/Claude Code.

## Language

The skill's questions and output are in Indonesian (Bahasa Indonesia), matching its target users. This README is in English for documentation purposes only.
