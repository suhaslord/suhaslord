# Suhas Beemineni

High-school student working on aerospace software, autonomy, simulation, and ML evaluation.

I like projects where the result can be measured, reproduced, and proven wrong.

[Portfolio](https://suhaslord.github.io/portfolio/) · [LinkedIn](https://www.linkedin.com/in/suhas-beemineni-1984763b8/)

## Selected work

### [AegisLand](https://github.com/suhaslord/uav-safety-research)

**Question:** when UAV landing perception is confidently wrong, can an independent estimate catch the error without creating too many unnecessary interventions?

**What I did:** built the simulation/evaluation pipeline, tested redundant estimation and abstention, moved from synthetic failures to PX4/Gazebo camera evidence, and froze holdouts before final evaluation.

**Current result:** Phase 10R reduced mean error on ambiguous views but failed the overall frozen evaluation because p95 tail error, miss rate, and uncertainty coverage did not meet the preregistered gates. The failed result is preserved in the repo.

**Scope:** simulation only. No physical-flight validation.

### [Elodin / Voyager](https://github.com/elodin-sys/elodin)

Contributed to the Voyager example and validation work in Elodin. My merged work added position/velocity error telemetry against SPICE truth so propagation changes can be measured instead of judged visually.

### [AbstainBench](https://github.com/suhaslord/AbstainBench)

A benchmark for a simple question: **when should a language model refuse to answer?** It tracks accuracy, hallucinations, and false abstentions so different refusal strategies can be compared with numbers instead of demos.

### [TennisRank](https://github.com/suhaslord/tennisrank-ai)

Built a ranking app for school tennis with spreadsheet import, singles/doubles rankings, and Supabase persistence.

## Experience

- **Seagulls / OpenStage — AI Engineer Intern:** worked on model routing, guardrails, memory boundaries, observability, and QA for assistant/workout flows.
- **Learn To Be — Math Tutor:** volunteer math and English tutoring.
- **Cruze — Fleet Outreach Intern:** fleet-partner and pilot outreach.
- **exovista.org — Market Research Intern:** STEM market research and outreach.

## What I am working on now

- UAV perception reliability and uncertainty under distribution shift
- spacecraft / flight-dynamics simulation and validation
- open-source aerospace software contributions
- tools that make ML behavior easier to measure and inspect

## Tools I actually use

Python · JavaScript · NumPy · Matplotlib · Git/GitHub · Supabase · Vercel · Blender

## A few results I care about

- AegisLand Phase 10R: strong mean-error improvements on ambiguous views, but **failed overall** on frozen holdout because tail error, availability, and uncertainty coverage did not all transfer.
- Earlier AegisLand synthetic benchmark: unsafe simulated touchdowns `43% → 1%`, with a 3% low-light timeout cost.
- Elodin: merged Voyager validation telemetry contribution against SPICE truth.
- SkillsUSA: regional champion in 3D Visualization & Animation; 16th at California state.

I would rather show a failed, well-measured experiment than hide it behind a polished demo.
