# Health First

A habit-formation app for kids: daily health goals (water, movement, sleep, fruit) bank screen-time minutes as they're completed, with a parent dashboard for review, goal setup, and emergency unlock.

Built for **Qutuhal InnovateX 2.0**.

**Live prototype:** https://claude.ai/code/artifact/dc777afc-bb3e-408c-aede-89ed91983bd3
Demo Parent PIN: `1234`

## What it does

- Kid checklist with four default goals — water (tap-per-glass counter), movement, sleep, fruit — each proven by photo or a note asking a parent, both landing in a parent review queue (with a bulk-approve option), and each banking a parent-configurable number of screen-time minutes.
- Sleep is checked each morning about *last night's* bedtime, so the reward isn't gated on something only verifiable after bedtime.
- Screen time is spent via a live countdown on Games/YouTube, with a low-time warning before it runs out; finishing every goal unlocks unlimited time for the day.
- Parent dashboard: review queue for photo submissions, PIN-gated emergency unlock, and a Goal Setup tab to add/remove goals and set each goal's reward minutes.
- Streak tracking with a 7-day history strip and milestone celebrations (3/7/14/30/60/100-day streaks).

## Files

| File | Description |
|---|---|
| `health_first.html` | The working prototype — a single self-contained HTML/CSS/JS file. |
| `Health_First_Solution_Blueprint.docx` | Original solution design doc (problem, MVP features, tech approach). |
| `Health_First_Week2_Submission.pdf` | Week 2 submission — prototype design & development. |
| `Health_First_Week3_Submission.docx` | Week 3 submission — build, integrate & mid-sprint review (AI/automation/data integration). |
| `Health_First_Week4_Submission.docx` | Week 4 submission — user testing & validation. |
| `Health_First_Week5_Submission.docx` | Week 5 submission — refinement & final prototype. |
| `Health_First_Week6_Submission.docx` | Week 6 submission — pitch preparation & final project documentation. |
| `Health_First_Week6_Pitch.pptx` | Week 6 pitch deck — 7 slides in simple, kid-friendly language: problem, solution + key features, app screen mockups, why it's different, try it, and a thank-you close. |
| `Health_First_Demo.mkv` | Recorded pitch/demo video. |

## Running it locally

`health_first.html` has no build step and no dependencies — open it directly in a browser, or serve the folder with any static file server:

```bash
python -m http.server 8000
```
