Agent 1 — Scorecard Architect
Input: None (build from scratch)
Output: outputs/scorecard.md
Run when: Starting the project
Task
Build a Pre-Launch Readiness Scorecard. This is a diagnostic tool, not a quiz. Every question must map to a concrete, defensible risk or advantage on launch day.
Scorecard Structure
40 questions across 5 weighted categories. Build each question in this exact format:
markdown### Q[N]. [Question text]

**Category**: [Category Name]
**Points Available**: [X]

| Option | Answer | Points |
|--------|--------|--------|
| A | [Specific, measurable answer] | [X] |
| B | [Specific, measurable answer] | [X] |
| C | [Specific, measurable answer] | [X] |
| D | [Specific, measurable answer] | [X] |

**Why This Matters**: [1–2 sentences expy it predicts launch outcomes, what a high score looks like in practice, and what a low score means on launch day. This becomes its own PDF section.
Constraints

No vague answer options. "Somewhat prepared" is never an option. Every answer must be specific and measurable: "I have an email list of 100–500 subscribers" not "I have a small list."
Every point allocation must be internally consistent. A 4-point question must be demonstrably higher-stakes than a 2-point question. Add a <!-- SCORING RATIONALE: [explanation] --> HTML comment after each question if the weighting isn't self-evident.
Do not include questions the founder cannot answer with certainty before launch.
The full scorecard must be completable in under 15 minutes. category and explain its specific launch day consequence]

**Your Next Action**: [Specific sprint plan. Name exact modules from the playbook. Give a timeline. Example: "Delay launch by 2 weeks. Execute the Ship follower-building sprint in Playbook Module 1, Phase 1. Target: 150+ Ship followers before rescheduling."]
Tiers:

0–49: Not Ready — Stop
50–69: Caution — Specific Gaps
70–84: Ready — Execute the Plan
85–100: Strong — Go for Top 3

For the 85–100 tier specifically, include a "Top 3 Push" — the 3 highest-leverage actions available in the final 48 hours to push from Top 5 to Top 3.
Companion Section
After all questions and tiers, write a ## Understanding Your Score section. For each category, write 200–300 words covering: what the category measures, whlaining what this predicts about launch day outcome. Be specific.]
Category Specs
Category 1 — Audience Infrastructure (8 questions, max 25 points)
Cover: email list size and engagement rate, Twitter/X following quality (engaged vs. passive), Ship page follower count, number of people who will engage within the first hour of launch, and activity in PH communities in the last 30 days.
Weight this category highest. Audience-less launches are the single biggest predictor of failure. Make the scoring reflect this.
Category 2 — Asset Quality (8 questions, max 20 points)
Cover: whether the thumbnail is animated and under 3MB, whether the tagline passes the 5-second comprehension test, whether gallery image 1 communicates the product without text, whether the demo video shows the "aha moment" in the first 15 seconds, and whether the description is under 500 characters and outcome-first.
Category 3 — Network Activation Plan (8 questions, max 20 points)
Cover: whether a top hunter in their niche has been identified and contacted, whether they have a distributed 24-hour engagement schedule prepared (not a spike), whether they have 3+ communities where they are a genuine active member, and whether their DM list is prepared and personalized.
Category 4 — Timing & Strategic Positioning (8 questions, max 20 points)
Cover: whether they've checked the competitive launch calendar for their target day, whether their product category is correctly selected on PH, whether they know their primary competitor's PH presence, and whether they have a clear answer to "why should the PH community care about this today specifically?"
Category 5 — Retention Infrastructure (8 questions, max 15 points)
Cover: whether onboarding converts in under 60 seconds, whether a post-launch email sequence is prepared, whether a PH-exclusive discount code is ready, and whether the checkout/signup flow has been tested end-to-end in the last 48 hours.
Scoring Output Tiers
After the questions, write four output tier blocks in this format:
markdown## Score Tier: [Name]
**Range**: [X–Y]
**Headline**: [One sentence verdict]

**What This Means**: [2–3 sentences explaining what this score indicates about their specific launch readiness situation]

**Your Highest-Risk Gap**: [Instruction to identify the lowest-scoring
