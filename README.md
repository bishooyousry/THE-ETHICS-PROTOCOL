# THE ETHICS PROTOCOL: Every Decision Has a Consequence — Skills Bank | GitHub Pages

One file (`index.html`), no build, no keys, no backend. English / العربية (RTL). Target: 10–12 minutes, individual (the classroom version is small groups of 3–4 discussing for about 5 minutes — a group can play on one screen and argue each choice).

## Publish (GitHub Pages)
1. Create a **public** repo. Upload `index.html` and `.nojekyll` to the root.
2. Settings → Pages → Deploy from branch `main` / root. Wait ~1 minute.
3. Open `https://<user>.github.io/<repo>/` → **Trainer** (top right) → PIN `2026`.
4. Always open the published link (not the file from your computer, not a preview window).

## About the source activity (please read)
- The course notes give: the goal (**recognize an ethical risk in an AI decision and choose a responsible next step**), the situation, the two questions (**What would you do next? Who would you tell about this?**), small groups of 3–4, about 5 minutes of discussion, each group shares its decision and reasoning, two debrief questions (*Was it easy or hard to agree as a group? Why? / What is your own company’s process for reporting a problem like this?*) and the facilitator tip: **“There is no single ‘correct’ answer to most ethics dilemmas — the goal is the discussion itself.”** The worksheet handout is **not in the deck**.
- The scenario is preserved **exactly**: “A company's AI hiring tool has been giving lower scores to graduates from certain universities, even though their skills and experience are similar to other applicants. No one designed it to do this on purpose.” An Arabic translation is shown in Arabic mode and the English original stays available.
- **Both original questions stay on screen the whole time** in the *Case Card* (with progress): ① *What would you do next?* is asked in scenes 1, 2 and 4; ② *Who would you tell about this?* is scene 3. The final reflection asks for both in your own words.
- **The company, people, numbers and events are FICTIONAL** training material written to expand the scenario (Meridian Talent Group; Rania, Tariq, Dr. Salma, Youssef, Mona, Adam; 212 applications, 61 vs 151 applicants, 17 of 20 matched pairs). The story notes say the pattern is “not proof”.
- Because the course says there is no single correct answer, the game scores a **transparent set of criteria** and shows trade-offs, not a single “right path”.

## The story (five scenes, an animated dialogue, a decision that changes what comes next)
1. **The discovery** — a confidential message arrives at night; Rania has noticed the pattern. *What would you do next?* Five realistic options (gather evidence and protect applicants · escalate now · keep using the tool · “it wasn’t intentional” · quietly adjust the scores).
2. **The deadline** — Tariq must hire 12 people by Friday. His lines **change depending on scene 1** (he reacts to the files on hold, to governance asking questions, to more rejections overnight, to adjusted scores…). Options trade off fair treatment, the deadline, the risk of continuing automated decisions and accountability.
3. **Who needs to know?** (question ②) — eight options, each with a **real responsibility** in the fictional organization: HR leadership · AI system owner · governance, risk & compliance · legal & privacy · the hiring manager · and three poor channels (the company-wide chat, contacting candidates alone, telling nobody yet). Tap in the order you would brief them. People already informed by a scene-1 escalation appear pre-checked.
4. **Protecting the candidates** — up to six corrective measures. A measure already in place from scene 2 is shown as such; a measure that **needs someone you did not tell** (e.g. investigating the model without the system owner) is flagged and loses half its points. A superficial fix (“remove the university names”) earns little; hand-adjusting scores or waiting for a complaint is called out. The game states that **no single fix guarantees fairness**.
5. **The consequences** — **five endings** decided by the *whole sequence*, then a decision timeline, a criteria breakdown that names where every point came from, an individual reflection (principles from the course’s AI-ethics slide + your own words) and the decision report.

### Endings (rules, in order)
Superficial fix without investigation or human review → **Superficial fix, risk unresolved** · nobody who can act was told and no human review → **Silence, unaddressed harm** · harm points ≥ 2 from early choices (continuing the tool, dismissing, leaving it to the manager…) → **Delayed response, preventable harm** (a strong follow-up cannot erase early harm) · at least 2 of 3 key people told including the system owner, human review, ≥ 4 responsible measures effectively in place and the model investigated → **Responsible intervention** · otherwise → **Contained, but incomplete**.

## Scoring (transparent, max 113)
| Criterion | Max | Earned by |
|---|---|---|
| Recognition of possible harm | 8 | taking the signal seriously in scene 1 |
| Evidence-based investigation | 16 | gathering evidence (scene 1), investigating the model (scene 4) |
| Appropriate escalation | 20 | telling the people empowered to act (HR 6 · owner 6 · governance 6 · legal 4); penalties for premature channels |
| Protection of affected people | 18 | holding rejections for human review, reviewing decisions, offering a review path |
| Effective human oversight | 16 | human review in scene 2, a standing review step in scene 4 |
| Responsible corrective action | 13 | documenting, monitoring, finding the cause; nothing for superficial fixes |
| Reflection | 22 | up to 3 sound principles (4 each, −4 per unsound one) + 10 for your own words |
Nothing is awarded for the most dramatic or the fastest option. Coins: 250 at start, hint = 50, one per scene (guidance only). Coins break ties. Ranks: ≥100 Ethics Lead · ≥78 Responsible Practitioner · ≥52 Aware Colleague · else Learning Colleague.

## Trainer
5-character session code, **+ New session** (up to 6), **Reset**, **Close**, session name, copy EN/AR link, **Projector view**, live table (scene reached, the scene-1 and scene-2 choices as colour-coded chips, who was told (four chips), measures x/6, ending, hints, coins, score, progress), expandable rows (decision timeline in order, criteria scores, sanitized reflection, harm points), **Debrief panel** (distribution of every choice, who participants would tell with premature channels in red, measures, endings reached), a collapsible **ANSWER KEY (trainer only)** (every option with its harm points, consequence and reasoning, each stakeholder’s responsibility, each measure and its dependencies, ending rules, criteria — English and Arabic, never shown to players), Reveal/Hide leaderboard, CSV export, backup import. About **7 messages per player**.

## Honest limits
- It is an authored story with rule-based scoring: it cannot judge the quality of your own words, and it does not model a real organization — in real life consequences are messier and rules differ.
- Only fictional-story decisions, the ending and a short sanitized reflection are sent (emails, links and long numbers are removed). The `2026` PIN only hides the interface; the relay is public.
- **Not yet tested on real ntfy.sh or across real devices.** Tested in a headless browser against a local relay that imitates ntfy (all five endings, branching dialogue, scoring, SSE, polling, storage blocked, Arabic, an emulated touch phone using taps; 68 checks). Run the two-device checklist before a live class. ntfy.sh free limits are per IP (~250 publishes/day): ~35 players on one network is a safe size.

## Two-device test checklist
1. Laptop: published link → Trainer → PIN 2026. Note the 5-character code and `● LIVE`.
2. Phone: open the player link (or type the code) → enter a name → **Open confidential case** (the message on the wall screen opens).
3. Laptop: the participant appears in seconds. Phone: step through scene 1 (try **Continue** and **Skip**), choose and commit; read the consequence.
4. Phone: scenes 2–4 (notice how scene 2’s dialogue depends on scene 1). Laptop: the decision chips, people told and measures update after each scene.
5. Phone: reach an ending, pick principles, write the reflection, **Close the case**. Laptop: ending chip, score and the sanitized reflection appear; expand the row for the timeline and criteria.
6. Laptop: **Reveal leaderboard** → opens by itself on the phone; **Hide** closes it. Projector view shows the same.
7. Switch language on both; check RTL and that nothing is cut off on the phone.
8. Refresh the phone mid-story → **Resume the case** continues at the same scene.
9. Replay with a very different set of choices to see another ending. Laptop: **Reset session** → new code. Check Sound ON/OFF and “reduce motion”.
