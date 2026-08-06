The Runbook Evolution: From Skills to Execution Scripts

Skills are powerful. They embed methodology, frameworks, and patterns into reusable instructions. But skills have a vulnerability: they require interpretation.

When a skill says "invoke the deutsch skill with the brief," the AI must decide:
- How to invoke it (which tool?)
- What to pass (which parts of the brief?)
- What to do with the output (where to save it?)

Most of the time, interpretation works fine. But in high-stakes situations -- when millions of dollars ride on the outcome, when you're asleep and the system runs autonomously, when you can't afford inconsistency -- interpretation becomes risk.

**The next evolution: Runbooks.**

A runbook is a linear execution script generated FROM a skill. It removes all interpretation:

| Skill Says | Runbook Says |
|------------|--------------|
| "Invoke the deutsch skill" | "Use Task tool with subagent_type='general-purpose', prompt=[exact 500-word prompt including persona, brief, instructions]" |
| "Save the draft" | "Write to [exact file path] with filename [exact name]" |
| "Update the dashboard" | "Write this exact JSON to [exact path]" |

**The relationship:**
- **Skill** = Documentation + Decision Trees + Flexible Guidance (the "why" and "what")
- **Runbook** = Exact Commands + Zero Interpretation + Linear Steps (the "how" precisely)

**When to use which:**
- **Skill:** Normal operations, exploration, iterative work where flexibility helps
- **Runbook:** Production runs, high-stakes situations, overnight automation, anything where consistency matters more than flexibility

**The generation pattern:**
Runbooks are GENERATED from skills, not written separately. This prevents drift:

```
SKILL.md (source of truth)
    ↓ [runbook generator]
RUNBOOK.md (executable version)
```

When the skill evolves, regenerate the runbook. The skill is the methodology; the runbook is one specific execution path through that methodology.

**What makes a good runbook:**
1. **No interpretation required** -- Every step is exact
2. **No decisions required** -- All choices pre-made
3. **Resumable at any step** -- If interrupted, can restart from any phase
4. **Failure handling explicit** -- What to do when something breaks
5. **Validation built in** -- How to verify each phase completed

**The tradeoff:**
Runbooks sacrifice flexibility for reliability. A skill can adapt to unexpected situations. A runbook cannot -- it does exactly what it says, no more. For production work where you've validated the approach, this is a feature. For exploration, it's a limitation.

**Current experiment status:**
This is an active experiment in the methodology. The pattern is being tested with complex multi-agent orchestrations (copywriting arenas, webinar arenas) where execution consistency is critical. The hypothesis: for validated workflows, runbooks will outperform skills in reliability while maintaining the same output quality.

The skill remains the source of truth. The runbook is a deployment artifact.