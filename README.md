# Suhas Beemineni

High school student working on aerospace simulation, autonomy, and software. I like projects where the result can be checked against data, a reference implementation, or a frozen test set.

- [Portfolio](https://suhaslord.github.io/portfolio/)
- [LinkedIn](https://www.linkedin.com/in/suhas-beemineni-1984763b8/)

## What I am working on

### AegisLand

I built AegisLand to test a narrow question: **if a landing camera is confidently wrong, can an independent estimate expose the error before touchdown?**

An early synthetic experiment looked promising: unsafe touchdowns fell from **43% to 1%** with selective intervention. Later camera-based testing was less clean. On the Phase 10R frozen holdout, average error improved, but the system missed **20%** of truth-visible frames, failed both p95 tail-error targets, and under-covered its stated 95% uncertainty interval (**84.3% lateral / 79.7% altitude**). I kept that result frozen instead of tuning on the test set.

Repo: [uav-safety-research](https://github.com/suhaslord/uav-safety-research)

### Elodin / Voyager

I have been contributing to Elodin's Voyager example. My first merged contribution added position/velocity error telemetry against SPICE reference data. I then worked on a reconstructed Voyager 1 Jupiter validation case and on keeping the assumptions and limitations visible in the example instead of hiding them behind a large simulation stack.

Merged example contribution: [elodin-sys/elodin#769](https://github.com/elodin-sys/elodin/pull/769)

### Public spacecraft-model reproductions

I am also working through public spacecraft dynamics and controls results one at a time. For a Lockheed Martin HWO / disturbance-free-payload paper, I used a one-degree-of-freedom spring-mass model to check whether the reported modal-frequency shift is consistent with a 70% effective stiffness cancellation. The simple model gives the expected roughly **1.8x** frequency ratio. It does **not** reproduce the full 6-DOF controller, hardware, or flight design.

That kind of boundary matters to me: if I did not model it, I do not want the project page to imply that I did.

## Other projects

**AbstainBench** — a small browser benchmark for a simple question: when should a language model answer, and when should it say it does not know? It records correct answers, hallucinations, and false abstentions across a fixed set of prompts. [Repo](https://github.com/suhaslord/AbstainBench)

**TennisRank** — a private team ranking tool with spreadsheet import, singles/doubles rankings, and Supabase persistence. [Repo](https://github.com/suhaslord/tennisrank-ai)

**ECHO / FIELD** — a browser-based visual instrument where microphone input and motion alter a live generative field. [Repo](https://github.com/suhaslord/ECHO-FIELD)

## Experience

- **Seagulls / OpenStage — AI engineering intern.** Worked on model routing, memory boundaries, guardrails, tracing, QA, and production-path checks. Recent work included looking for inference paths that bypassed the intended routing layer and testing user-facing failure cases.
- **Open-source aerospace work.** Contributing to Elodin and exploring public NASA/Aviary work through reproducible examples and validation tasks.
- **Student research and engineering.** Independent simulation work plus school and community engineering projects.

## Background

River Islands High School · Delta College coursework

SkillsUSA regional champion in 3D Visualization & Animation; advanced to the California state competition. Also placed 2nd in a Python game jam and 5th of 25+ teams at an AI Collective hackathon.

I use Python and JavaScript most often. For simulation/research work I also use NumPy, Matplotlib, Git, and the surrounding domain tools as needed.

I would rather show a small result I can explain than a large system description I cannot defend.
