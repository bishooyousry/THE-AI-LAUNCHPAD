# Facilitator guide — THE AI LAUNCHPAD: Build Your Own Assistant (online)

**Goal:** participants turn the assistant blueprint from the previous activity into usable instructions, test them with a real AI tool, evaluate the result and refine the instructions.
**Format:** individual, 15–20 minutes of play + 5–7 minutes of debrief. Participants need an AI tool they are allowed to use (ChatGPT, Copilot or Gemini); a dry-run mode exists for anyone without access.

## Know the source before you present
- In the course deck the build step is “add a name, description and system instructions, upload knowledge files, test and iterate before sharing”, with a worked Fraud Investigation Assistant (slide 77) and test inputs (slide 79). The slide for this activity has no debrief notes, so the debrief questions below are **suggestions**.
- This game does **not** run an AI model. The AI work happens in the participant’s own tool. The result is a **tested prompt prototype**, not a deployed enterprise assistant.

## Before the session (5 min)
- Open the link → Trainer (PIN 2026). One session per group (**+ New session**). Put the **player link** (or the 5-character code) in the chat.
- Ask everyone to have their blueprint ready: **copy the text** from the previous activity, or the **downloaded .json/.txt file**. (The two games do not share browser storage, so nothing travels automatically.) Anyone without it can use a sample.
- Governance reminder (course slide 82): company-approved AI tools only, mask PII, no customer data in public AI tools. All test inputs here are fictional — keep it that way.

## Run (timing)
| Time | What you do |
|---|---|
| 0:00 | Say: “Design first, prompt second. Take the blueprint you designed, turn it into instructions, test it with a real AI tool, then improve it.” Share link/code. |
| 0:02 | Everyone is in. Optionally open **Projector view**. |
| 0:02–0:20 | Watch the table: assistant names, the five system lights, readiness (x/6), test chips (✓ = stayed in scope and matched format), improvements. Expand a row (⌄) to read the sanitized test notes. |
| ~0:20 | Ask 2–3 volunteers to show their final instructions on screen. Then **Reveal leaderboard**. |
| 0:20–0:27 | Debrief (below). |

## What happens (for narration)
1. **Blueprint arrival** — paste, import, sample or type; fields are recognized and editable.
2. **Five systems** — each starts from the blueprint; edit it, switch on rules, confirm.
3. **Readiness check** — six transparent rules (keyword/structure only — not a quality verdict).
4. **Live AI test** — copy instructions, paste into the AI tool, send a fictional test input, come back and record what happened.
5. **Refine** — fix what the test exposed (Version 2, shown against Version 1), then test again.
6. **Launch report** — final instructions, blueprint and report downloads; a reminder that this is a prototype.

## Privacy note for you
Instructions and blueprints never reach your dashboard. You only see progress, assistant names and purposes, and short **sanitized** notes (emails, links and long numbers are removed automatically).

## Debrief questions (suggested)
1. What did the live test show that your design did not? Which readiness check was hardest to satisfy? (Debrief panel → failed checks.)
2. What was the one change that improved Version 2 the most — and how do you know? Did anything get worse?
3. Did your assistant follow every instruction, keep the output structure, flag the risky case for a human, refuse to cross a boundary and avoid inventing? (course slide on functional testing)
4. Which test would you add before sharing this with a team: an edge case, a boundary push, an unknown reference?
5. What would you monitor after a real release, and who stays accountable? (course slides on monitoring)
6. What is missing between this prototype and a real enterprise deployment? (enterprise tools, access control, audit logging, a controlled-group release)

## Notes
- Scoring rewards learning actions (reviewing, adding your own rules, recording honest observations, improving, re-testing) — not speed. Use it for feedback, not for grading people.
- A participant may look idle while testing in another tab — progress is sent when a phase or step is completed.
- If the live connection drops: **Refresh** on the dashboard rebuilds from the relay history; otherwise collect the launch-report files and use **Import**.
- Export CSV at the end if you want the sanitized results.
