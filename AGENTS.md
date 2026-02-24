# PH Top 5 Launch Audit System

## Project Brief
[paste the brief section only — ~150 words]

## Execution Order
1. Agent 1 — @agents/agent1_scorecard.md
2. Agent 2 — @agents/agent2_playbook.md  
3. Agent 3 — @agents/agent3_teardown.md
4. Agent 4 — @agents/agent4_packager.md

## Quality Gates
# Run after each agent completes
# Check 1: No unsubstantiated guarantee language
grep -n "guarantee\|mathematically\|100% actionable" outputs/*.md

# Check 2: No placeholder data (unfilled brackets)
grep -n "\[Hunter Name\]\|\[Add more\]\|\[TBD\]" outputs/*.md

# Check 3: Minimum word counts
wc -w outputs/scorecard.md    # expect 3000+
wc -w outputs/teardown.md     # expect 2500+
wc -w outputs/playbook_v3.1.md # expect 4000+

# Check 4: All required sections present in teardown
grep -n "## Score Tier\|## Section [1-6]\|## Post-Mortem\|## Scorecard Retrospective" outputs/teardown.md

# Check 5: Cross-reference — Scorecard category names match Playbook Jump table
grep "Audience Infrastructure\|Asset Quality\|Network Activation\|Timing.*Positioning\|Retention Infrastructure" outputs/playbook_v3.1.md
```

Any `grep` hit on Check 1 or Check 2 is a blocker. Fix before moving forward.

---

## Execution Order
```
Agent 1 → Agent 2 → Agent 3 → Agent 4
