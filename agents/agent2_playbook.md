Agent 2 — Playbook Editor
Input: inputs/playbook_v3.md
Output: outputs/playbook_v3.1.md
Run when: Agent 1 is complete (Playbook must reference Scorecard category names exactly)
Task
Edit the existing v3.0 playbook into a reference companion for the bundle. The playbook is no longer the hero of the product — it is the operating manual. Apply four directives exactly.
Directive 1 — Kill Unsubstantiated Claims
Search for and address every specific statistic, percentage, or benchmark in the document. Apply one of two treatments:
Treatment A — Reframe: If the claim reflects a genuine observed pattern, rewrite it as: "In launches we've documented, [observation] — though results vary significantly by product category and audience size."
Treatment B — Cut: If tto craft an icebreaker based on their actual recent work rather than a template]
Do not include any placeholder data tables. A methodology beats fake data every time.
Directive 4 — Add Launch Rescue Protocol
After the 11:59 PM PST entry in Module 4, insert a new section:
markdown## When Things Go Wrong — Launch Rescue Protocol
Write three scenarios. Each gets 150–200 words of specific, actionable guidance:

Scenario A: It's noon. You're at #8. Momentum has stalled. What do you do in the next 3 hours?
Scenario B: Upvotes are coming in but there are fewer than 5 comments. The algorithm isn't boosting you. What do you do?
Scenario C: A competitor launched the same day with a similar product and is outranking you. What do you do?

For each scenario: lead with the diagnosis (why this is happening), then give 3–4 specific actions in priority order.
Format Requirements

Preserve all existing checklist formatting exactly
After every significant edit, add: <!-- EDITOR'S NOTE: [brief rationale for the change] -->
Output the complete document — not a diff, not a summary, the full edited filehe claim cannot be defended at all, remove it entirely.
Specific strings that must be found and treated:

"mathematically maximize" → cut the word "mathematically"
"guarantee" (any usage promising outcomes) → reframe as "maximize your chances of"
Any percentage stated without a source (e.g., "40%+ response rate", "30–50% of engaged users") → Treatment A or B
"94% of traffic disappears" → Treatment A with explicit uncertainty framing

Directive 2 — Reposition the Introduction
Replace the existing introduction with a maximum 150-word version that positions the playbook as a reference document. The first paragraph must begin with a variant of: "You've completed the Readiness Scorecard and identified your gaps. This playbook is your execution reference."
Immediately after the introduction, insert this navigation block verbatim:
markdown## Jump to Your Gap

| Low Score In | Go To |
|---|---|
| Audience Infrastructure | Module 1, Phase 1 |
| Asset Quality | Module 2 + Appendix B |
| Network Activation | Module 1, Phase 3 |
| Timing & Positioning | Module 1, Phase 2 |
| Retention Infrastructure | Module 5 |
Directive 3 — Replace Appendix A
Remove the existing Appendix A (Top Hunters Database with placeholder rows). Replace it entirely with:
markdown## Appendix A: How to Research Your Hunter in 20 Minutes

[300-word methodology guide covering: where to find active hunters on PH, how to evaluate hunter-product fit by reviewing their last 10 hunts, what signals indicate a hunter is likely to respond to outreach, and how 
