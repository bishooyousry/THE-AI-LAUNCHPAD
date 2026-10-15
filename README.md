# THE AI LAUNCHPAD: Build Your Own Assistant — Skills Bank | GitHub Pages

One file (`index.html`), no build, no keys, no backend. English / العربية (RTL). Target: 15–20 minutes, individual, using a real AI tool the participant is allowed to use.

## Publish (GitHub Pages)
1. Create a **public** repo. Upload `index.html` and `.nojekyll` to the root.
2. Settings → Pages → Deploy from branch `main` / root. Wait ~1 minute.
3. Open `https://<user>.github.io/<repo>/` → **Trainer** (top right) → PIN `2026`.
4. Always open the published link (not the file from your computer, not a preview window).

## What this game is — and is not
- It is a **guided build-and-test environment**. It does **not** run an AI model and has no API keys. The participant pastes the instructions into **their own** AI tool (ChatGPT, Microsoft Copilot or Gemini — official links are provided) and records what happened.
- It builds on the previous activity (THE AI ARCHITECT). **Two GitHub Pages games do not share browser storage**, so the blueprint does not travel automatically: participants **paste** the copied blueprint, **import** the `.json`/`.txt` they downloaded, use a **sample**, or **type** it.
- Its result is a **tested prompt prototype**, never a formally deployed or production-ready enterprise assistant.

## Source in the course deck
- Slides 74–80: build steps (ChatGPT: Explore GPTs → Create GPT → name, description, system instructions → knowledge files → test and iterate; Gemini: create a Gem). Slide 77: the worked **Fraud Investigation Assistant** example → used as the first sample (fictional). Slide 79: test inputs (high-risk case, benign payroll case, unknown policy 19.4) → used as the sample test inputs. Slide 81 notes: “Participant will create through GPT” (no QR code, no debrief notes — the debrief questions are suggestions). Slide 82: governance (enterprise tools, mask PII, no customer data in public AI tools). Slides 85–88: why testing matters, the Test → Analyze → Refine → Re-Test cycle and what to verify.
- Samples, readiness rules, suggestions and all feedback texts are illustrative material written for this game.

## The six phases
1. **Blueprint arrival** — paste / import a file / sample / manual. Recognizes the JSON and the text exported by THE AI ARCHITECT (English or Arabic headers) and the course “Name / Description / Instructions” format; shows how many of 9 fields were recognized; everything stays editable.
2. **System configuration** — five systems (Role & purpose · Permitted & excluded tasks · Required inputs · Output structure · Human review & escalation). Each starts from the blueprint; edit it, switch on rules, confirm. The energy reactor powers up segment by segment.
3. **Launch readiness check** — six rule-based checks (purpose, scope, inputs, output format, explicit boundaries, human review). Each shows its rule, what was found and how to fix it. They are keyword/structure rules, **not** a judgment of wording quality — the game says so. At least 4/6 are needed for the countdown.
4. **Live AI test** — simulated countdown, then: copy instructions, open ChatGPT / Copilot / Gemini, copy a safe fictional test input (in-scope, edge case or unknown reference; optional boundary-push test), then record: tool used, stayed in scope, format matched, flagged human review, invented anything, what worked, what failed, optional sanitized evidence. A dry-run with a labelled sample response exists for anyone without access.
5. **Refine and relaunch** — rule-based suggestions from the test notes, an editable Version 2, a line-by-line **V1 vs V2 diff**, a required meaningful improvement (a new line of 6+ words) plus a written reason, then a re-test with a self-reported verdict (better / same / worse).
6. **Launch report** — liftoff, tests completed, improvements, readiness, hints, coins, score, final instructions; **Copy Final Instructions**, **Download Blueprint (.json)** (re-importable), **Download Launch Report (.txt)**.

## Scoring (rewards learning actions, not speed)
| Part | Points |
|---|---|
| Blueprint confirmed | 40 |
| Each of five systems | 30 for reviewing/confirming + 10 if you added a rule or line of your own (max 200) |
| Readiness | 10 per passing check + 20 if all six pass on the first run (max 80) |
| Live tests | 60 for a complete Test 1 record + 40 for the optional boundary test |
| Refinement | 60 meaningful improvement + 10 per extra improvement (max +20) + 20 for the written reason (max 100) |
| Re-test | 40 for a complete record + 20 for the verdict (no extra credit for “better” over “same”) |
Max **580**. Coins: 250 at start, hint = 50 (a model for a system · a model for the first failed check · the most useful change). Coins break ties. Ranks: ≥500 Mission Commander · ≥380 Flight Engineer · ≥250 Launch Technician · else Cadet.

## Trainer
5-character session code, **+ New session** (up to 6), **Reset**, **Close**, session name, copy EN/AR link, **Projector view**, live table (phase, assistant name and purpose, five system lights, readiness, V1 / boundary / V2 test chips, improvements, hints, coins, score, progress), expandable rows with **sanitized** test notes and the improvement note, **Debrief panel** (failed readiness checks, AI tools used, Version 1 → Version 2 scope and format rates, self-reported verdicts), Reveal/Hide leaderboard, CSV export, backup import. About **8 messages per player**.

## Privacy by design
- **Instructions and blueprints never leave the device** and are never sent to the relay. Only progress numbers, the assistant name and purpose, and short notes are sent — after automatic sanitizing (emails, links and long digit strings are replaced by `[removed]`; the player sees how many items will be removed).
- The `2026` PIN only hides the interface. The relay is public. Use **fictional or approved non-sensitive** examples only; use company-approved AI tools and never paste real customer or employee data.

## Honest limits
- **Not yet tested on real ntfy.sh, across real devices, or with the real ChatGPT / Copilot / Gemini.** Tested in a headless browser against a local relay that imitates ntfy (SSE, polling, retries, storage blocked, Arabic, an emulated touch phone using taps; 73 checks). Run the two-device checklist before a live class.
- ntfy.sh free limits are per IP (~250 publishes/day, ~30 live streams): ~30 players on one network is a safe size; use `?relay=` with your own server for more.
- The readiness checks and refinement suggestions are keyword/structure rules; the real evaluation is the participant's own reading of the AI tool's answer.

## Two-device test checklist
1. Laptop: published link → Trainer → PIN 2026. Note the 5-character code and `● LIVE`.
2. Phone: open the player link (or type the code) → enter a name → **Initiate launch sequence**.
3. Laptop: the participant appears in seconds. Phone: use a sample, paste a blueprint text and import a downloaded file (try both), edit a field, **Confirm blueprint**.
4. Phone: confirm the five systems (switch on a rule in each), **Run the checks**, then **Initiate countdown**. Laptop: system lights, readiness and score update.
5. Phone: copy the instructions, open an AI tool (or choose “No access”), record Test 1 (put an email address in the evidence to see it being removed). Laptop: expand the row — the notes appear sanitized, instructions do not.
6. Phone: refine (apply a suggestion, read the diff, write the reason), lock Version 2, re-test, **Launch report**; download the blueprint and the report; copy the final instructions.
7. Laptop: **Reveal leaderboard** → opens by itself on the phone; **Hide** closes it. Projector view shows the same.
8. Switch language on both; check RTL and that nothing is cut off on the phone.
9. Refresh the phone mid-build → **Resume build** continues (including edited instruction text).
10. Laptop: **Reset session** → new code. Check Sound ON/OFF and “reduce motion”.
