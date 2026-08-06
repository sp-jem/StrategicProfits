# STIC for Team Training: What's Involved

> This document breaks down what teaching STIC to the SP team actually requires — the concepts in plain language, how they connect to what the team already knows, and an honest assessment of fit.

---

## The 10 STIC Dimensions in Plain Language

STIC has two halves. **Systemic Thinking** (can you see the whole picture?) and **Intent Clarity** (can you say exactly what you want?). Each half has 5 dimensions scored 0-5.

### SYSTEMIC THINKING — "Can you see the system?"

#### 1. Component Identification
**Plain language:** When you look at a problem, how many of the moving pieces can you name?

**Level 2 (where most of the team is):** "I answer support tickets" — names the obvious pieces.
**Level 4-5 (where you want them):** "Support tickets are a signal of upstream failures — onboarding gaps, unclear documentation, payment friction, program confusion, and a lack of self-service options that all feed into my inbox."

**Teachable?** YES — directly. You can teach people to ask "what else is connected to this?" Show them that Kat's support tickets are caused by 5 things upstream, and suddenly she sees components she never named.

---

#### 2. Relationship Mapping
**Plain language:** Can you see how the pieces affect each other? Not just A causes B, but A causes B which causes C which loops back and makes A worse.

**Level 2:** "When the onboarding is confusing, people ask me questions."
**Level 4-5:** "Confused onboarding → support tickets → Kat spends time answering basics → less time for proactive outreach → members feel ignored → churn goes up → revenue drops → less budget for better onboarding. It's a cycle."

**Teachable?** YES — with examples. Draw the loop on screen. Once they see one feedback loop in their own work, they start seeing them everywhere. Nicole and Ashley probably already think in loops. Kat and Anna probably don't.

---

#### 3. Constraint Awareness
**Plain language:** What's the ONE thing that, if you fixed it, would fix five other things?

**Level 2:** "I need more time." (surface symptom)
**Level 4-5:** "The real constraint is that information lives in 6 places and nobody can find anything — that's why I spend 2 hours a day answering questions that already have answers somewhere." (root constraint)

**Teachable?** YES — this is literally Theory of Constraints, which you've taught for decades. The team has heard you talk about bottlenecks. This dimension just formalizes it.

---

#### 4. Second-Order Thinking
**Plain language:** If we fix this problem, what ELSE changes — including things we didn't intend?

**Level 2:** "If we automate support responses, we'll save time."
**Level 4-5:** "If we automate support responses, we save time AND we lose the signal. Kat's tickets were telling us where our programs break. If the bot handles everything, we stop learning what's wrong. We need to automate the responses AND build a system that flags the patterns."

**Teachable?** PARTIALLY — you can teach people to ask "and then what?" but genuine second-order thinking takes practice. This is one where repeated exposure matters more than a single lesson.

---

#### 5. Leverage Identification
**Plain language:** Where's the smallest move that creates the biggest shift?

**Level 2:** "We should hire another support person." (brute force)
**Level 4-5:** "If we build one FAQ agent that answers the 5 most common questions, we eliminate 60% of Kat's ticket volume, free her to do proactive retention outreach, which reduces churn, which improves revenue. One agent, four outcomes."

**Teachable?** YES — especially for this team right now. They're literally building AI systems. The question "which system would create the most leverage?" is the most practical thing you could teach them.

---

### INTENT CLARITY — "Can you say what you want?"

#### 6. Outcome Definition
**Plain language:** Can you describe what success looks like — specifically, measurably, with a deadline?

**Level 2:** "I want to be better at my job with AI." (vague)
**Level 4-5:** "Within 30 days, I want 80% of routine support tickets handled without human intervention, measured by ticket volume per day and customer satisfaction score staying above 4.5."

**Teachable?** YES — directly. This is the "Vision" step from the Strategic Builder methodology they already have. You've been teaching this. STIC just scores how well they do it.

---

#### 7. Constraint Definition
**Plain language:** What CAN'T you change? What are the walls you're building inside?

**Level 2:** Doesn't mention constraints at all.
**Level 4-5:** "I can't change the CRM (GoHighLevel). I can't add headcount. I have 4 hours per week for this project. The solution must work for non-technical users."

**Teachable?** YES — simple prompt: "Before you build anything, write down what you can't change." Most people skip this and then waste time building things that violate constraints they never stated.

---

#### 8. Assumption Transparency
**Plain language:** What are you assuming is true that you haven't verified?

**Level 2:** Doesn't realize they're making assumptions.
**Level 4-5:** "I'm assuming members would USE a self-service FAQ. I'm assuming the questions are similar enough to template. I'm assuming Fireflies transcripts are accurate enough to extract answers from. I should test all three before building."

**Teachable?** PARTIALLY — you can teach the habit of listing assumptions, but actually CATCHING your own assumptions requires self-awareness that develops over time.

---

#### 9. Tradeoff Awareness
**Plain language:** What are you giving up to get what you want?

**Level 2:** "AI will make everything better." (no tradeoffs acknowledged)
**Level 4-5:** "Automating follow-ups saves me 5 hours a week, but I lose the personal touch that built my partner relationships. I need to keep the high-value relationships manual and only automate the re-engagement of dormant contacts."

**Teachable?** YES — directly. Ask: "What gets worse when this gets better?" That single question forces tradeoff thinking.

---

#### 10. Success Criteria Precision
**Plain language:** How will you KNOW it's working? And how will you know it's failing early enough to fix it?

**Level 2:** "I'll know it when I see it."
**Level 4-5:** "Leading indicator: response drafts requiring less than 2 edits before sending (measured weekly). Lagging indicator: ticket volume drops 40% in 30 days. Failure threshold: if satisfaction drops below 4.0, pause automation and investigate."

**Teachable?** YES — but requires discipline. Most people set goals but not failure thresholds. Teaching "what number tells you to stop?" is valuable.

---

## How STIC Maps to What They Already Know

| STIC Dimension | Strategic Builder Equivalent | Gap |
|---|---|---|
| Component Identification | Architecture (mapping pieces) | Team is doing this loosely — not formally |
| Relationship Mapping | — | NOT covered in Strategic Builder |
| Constraint Awareness | — | NOT covered (this is the big gap) |
| Second-Order Thinking | — | NOT covered |
| Leverage Identification | Phased Delivery (what to build first) | Loosely covered but not as "leverage" |
| Outcome Definition | Vision statement | COVERED — they've been doing this |
| Constraint Definition | — | NOT covered explicitly |
| Assumption Transparency | — | NOT covered |
| Tradeoff Awareness | — | NOT covered |
| Success Criteria Precision | Validation Gates (pass/fail) | Partially covered — but Rich-facing, not team-facing |

**The honest assessment:** 6 of the 10 dimensions are NOT covered by the Strategic Builder methodology. The team has been taught Vision + Build. They have NOT been taught: see the system, find the constraint, think about what breaks, state your assumptions, name your tradeoffs. Those are the thinking skills underneath the building skills.

---

## The Connection to Agents and Skills

Here's why STIC matters for Session 3 specifically:

The team has been building one-shot prototypes (Session 1-2). Now they need to build permanent systems (agents and skills). The difference between a prototype and a permanent system is:

- A prototype handles one task.
- A permanent system handles a task WITHIN a system — it knows what feeds into it, what depends on it, what can go wrong, and when to escalate.

**Example — Michelle's follow-up automation:**
- **Prototype (what she built):** Claude reads Fireflies transcripts and drafts follow-up emails. Works 95% of the time.
- **Permanent system (what she needs):** An agent that knows the partner lifecycle, knows which follow-ups are time-sensitive vs. nurture, knows when to escalate to Michelle vs. handle autonomously, tracks what worked and what didn't, and improves over time.

The gap between prototype and system IS the gap STIC measures. Can she see the full system (not just the task)? Can she define what success looks like? Can she name the constraints and assumptions?

If you teach STIC before agents and skills, they'll build BETTER agents and skills — because they'll think systemically about what those agents need to know.

---

## My Honest Assessment: Does This Fit Tomorrow?

### The case FOR teaching STIC tomorrow:
- It fills the thinking gap between prototypes and permanent systems
- It gives them a framework for WHAT to build, not just HOW to build
- It directly improves the quality of agents and skills they'll create
- Nicole's session 2 moment ("Tom's project shifted from a spreadsheet to retention") is EXACTLY what STIC produces — systemic reframing
- Every person's Opportunity Map answer could be scored on STIC right now — and most would score 10-15 out of 50 (surface thinking, vague intent)

### The case AGAINST teaching STIC tomorrow:
- You promised agents and skills. The team is expecting that. Pivoting may feel like you're always teaching something new instead of going deeper on what they already have
- Session 1 you over-taught and they didn't build. Session 2 the demo ran long and building time got squeezed again. If you add STIC concepts + agents/skills, you're packing even more into 2 hours
- The team ranges from "I have no idea what I'm doing" (Harry, Kate) to "I built 13 agents" (Tom). STIC is going to hit very differently across that range — the advanced people will get it, the beginners might feel even more overwhelmed
- STIC is abstract. The team has responded best to CONCRETE (build this thing, see it work). Pure systems thinking training may not land the way a "here's your first skill, watch it work" would

### My recommendation:
Don't teach STIC as a framework tomorrow. Instead, teach ONE STIC concept — **Constraint Awareness** — as the bridge to agents and skills. Here's why:

- It's the most immediately useful dimension for this team
- It connects to your TOC background (they've heard you talk about bottlenecks)
- It directly answers the question: "What should my first agent or skill be?" → "The one that removes your biggest constraint"
- It's concrete enough to apply in the session
- It doesn't require learning a whole new framework — it's one question: "What's the one thing that, if you fixed it, would fix five other things?"

Then use the full STIC framework as a later session (Session 4 or 5) once they've built their first agents and have something real to score against.

---

## What a "Constraint-First" Session 3 Could Look Like

| Time | What |
|------|------|
| 0:00 | Open: Recap what they built. One distinction: "You've been building tools. Today we build systems." |
| 0:10 | Teach the ONE concept: Constraint Awareness. "What's the one thing that, if fixed, fixes five things?" Walk through Nicole or Tom's example from Session 2 showing how the project shifted from task to system. |
| 0:25 | Each person identifies their #1 constraint from their Opportunity Map. Not the annoying task — the ROOT of why the annoying task exists. 5 minutes, written. |
| 0:35 | Rich demos: Build a SKILL live. Take one team member's constraint and turn it into a permanent skill (not a one-shot prompt). Show the difference: prototype vs. skill. |
| 1:00 | Hands-on: Everyone builds their first skill targeting their constraint. Rich and Ben circulate. |
| 1:40 | Show and tell: Who built what? Score their constraint identification informally — did they find the root or the symptom? |
| 1:50 | Close: Preview STIC as the full framework coming later. "Today you learned one dimension — constraint awareness. There are 9 more. When you can score high on all 10, you'll be building systems that don't just work — they work within the whole picture of your role." |

This keeps the agents/skills promise, introduces one STIC concept as the frame, and sets up the full STIC training for a future session where it'll land better because they'll have real systems to evaluate.

---

*Created: February 16, 2026*
*For Rich's review before Session 3 planning*
