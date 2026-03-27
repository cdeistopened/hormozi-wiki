---
name: value-equation-scorer
description: "Score your offer across all 4 variables of Hormozi's Value Equation and identify the single highest-leverage improvement. Use when you've completed the sub-skills (dream outcome, likelihood, time delay, effort) or when you want a quick diagnostic of any offer. Also use when someone says 'is my offer good enough,' 'why aren't people buying,' 'how do I justify a higher price,' or 'audit my offer.'"
argument-hint: "[your offer details or outputs from sub-skills 1.1-1.4]"
---

# Value Equation Scorer

Score each of the 4 variables in Hormozi's Value Equation, compute a composite value score, identify the weakest link, and prescribe the single highest-leverage improvement to increase price, conversion, or both.

Read `references/frameworks/value-equation-explained.md` for the full framework with all nuances.

## The Value Equation

This is Hormozi's signature framework — the foundation of everything in $100M Offers:

```
              Dream Outcome  x  Perceived Likelihood of Achievement
Value = ──────────────────────────────────────────────────────────────
              Time Delay  x  Effort & Sacrifice
```

> "We boiled down value into four variables. There's things that enhance value, but like, core variables. One is the overall dream outcome of the customer. Two is the perceived likelihood of achievement. On the bottom, time delay — how far between when they buy and when they get. And effort and sacrifice."
> — Alex Hormozi, "The $100M Offer Formula"

The numerator (Dream Outcome x Perceived Likelihood) is what you want to MAXIMIZE.
The denominator (Time Delay x Effort & Sacrifice) is what you want to MINIMIZE.

> "In a perfect world, the moment someone says 'I want that thing, that beautiful dream outcome,' they'd be virtually guaranteed they would get it, it would happen immediately, and it would be effortless. That is the perfect ideal we look at in terms of value."
> — Alex Hormozi, "The $100M Offer Formula"

## The Consultation

### Step 1: Gather Inputs

If the user has already run the sub-skills (`/dream-outcome-definer`, `/likelihood-booster`, `/time-delay-compressor`, `/effort-reducer`), pull their outputs. If not, ask these diagnostic questions:

**Dream Outcome:**
1. What specific end-state does your customer achieve?
2. Is it tied to a deep driver (money, appearance, relationships, health)?
3. Can you express it in one sentence?

**Perceived Likelihood:**
4. What proof do you have that customers achieve this result? (Data, testimonials, case studies, credentials)
5. How many customers have achieved the full result?
6. Do you have a guarantee? What kind?

**Time Delay:**
7. How long from purchase to first visible result?
8. How long from purchase to full dream outcome?
9. What's the longest single wait period?

**Effort & Sacrifice:**
10. How many things must the customer START doing?
11. How many things must they STOP doing?
12. What's the single most painful requirement?

### Step 2: Score Each Variable

Rate each variable 1-10 using these benchmarks:

**Dream Outcome (DO):**
| Score | Meaning |
|-------|---------|
| 1-3 | Vague, incremental, no clear before/after |
| 4-6 | Clear result but not tied to deep status driver |
| 7-8 | Specific, measurable, tied to status/identity |
| 9-10 | Life-changing transformation, strong emotional pull, impossible to say no to the category |

**Perceived Likelihood (PL):**
| Score | Meaning |
|-------|---------|
| 1-3 | No proof, self-claims only, no guarantee |
| 4-6 | Some testimonials, basic credentials, conditional guarantee |
| 7-8 | Aggregate data, strong case studies, performance guarantee |
| 9-10 | Overwhelming evidence, "10,000 surgeries," unconditional guarantee backed by track record |

**Time Delay (TD) — INVERTED (lower time = higher score):**
| Score | Meaning |
|-------|---------|
| 1-3 | Result takes 6+ months, long wait between steps |
| 4-6 | Result in 1-3 months, some quick wins along the way |
| 7-8 | First result in days/weeks, full outcome in 1-2 months |
| 9-10 | Instant or near-instant result (liposuction model) |

**Effort & Sacrifice (E&S) — INVERTED (lower effort = higher score):**
| Score | Meaning |
|-------|---------|
| 1-3 | Customer must do most of the work, significant lifestyle changes required |
| 4-6 | Moderate effort, some done-for-you components, manageable sacrifices |
| 7-8 | Mostly done-for-you, minimal customer effort, few sacrifices |
| 9-10 | Completely effortless, push-button, no lifestyle change required |

### Step 3: Compute Composite Score

```
Value Score = (DO x PL) / (TD_inverted x ES_inverted)
```

Where TD_inverted and ES_inverted use the inverted scale above (already accounting for the fact that lower time/effort = higher value).

For a simpler read: **Composite = (DO + PL + TD + ES) / 4** gives the average across all four.

### Step 4: Identify the Weakest Link

The variable with the lowest score is the highest-leverage improvement target. Hormozi's insight:

> "And so when you itemize all the things... and then you create solutions for each of those categories, then you create an incredibly valuable offer. And that's when these crazy lava-palooza effects occur in the business where they go from 2 million to 10 in a year, changing nothing but what the core offer said."
> — Alex Hormozi, "How To Craft A $100M Offer In 6 Minutes"

The fix is almost always in the denominator. Most people try to make their dream outcome bigger (harder, requires real innovation) when they should be making their delivery faster and easier (execution, not innovation).

### Step 5: Prescribe the Fix

Route to the appropriate sub-skill based on the weakest variable:

| Weakest Variable | Route To | Quick Fix |
|-----------------|----------|-----------|
| Dream Outcome | `/dream-outcome-definer` | Niche down to a specific avatar with a specific status driver |
| Perceived Likelihood | `/likelihood-booster` | Collect 5 specific-result testimonials this week |
| Time Delay | `/time-delay-compressor` | Add an instant-win deliverable in the first 24 hours |
| Effort & Sacrifice | `/effort-reducer` | Convert the highest-resistance task to done-for-you |

## Output

Generate a **Value Equation Scorecard**:

```markdown
## Value Equation Scorecard

**Offer:** [their offer]
**Price:** [current or target price]

### The Equation

```
         DO ([X]) x PL ([X])        [numerator]
Value = ─────────────────────── = ─────────────── = [composite]
         TD ([X]) x ES ([X])        [denominator]
```

### Variable Scores

| Variable | Score | Key Evidence | Benchmark Comparison |
|----------|-------|-------------|---------------------|
| Dream Outcome | [X/10] | [why this score] | [what a 10 looks like in their industry] |
| Perceived Likelihood | [X/10] | [why this score] | [what a 10 looks like] |
| Time Delay | [X/10] | [why this score] | [what a 10 looks like] |
| Effort & Sacrifice | [X/10] | [why this score] | [what a 10 looks like] |

### Composite Score: [X/10]

### Weakest Link: [Variable Name] at [X/10]

**Why this matters:** [Explanation of how this one variable is dragging down the entire offer]

### The #1 Fix
[Specific, actionable prescription to improve the weakest variable by 2+ points]

### Price Implications
- **Current justified price:** $[X] (based on current value score)
- **After fixing weakest link:** $[Y] (estimated based on improved score)
- **Hormozi benchmark:** "We were able to 10x our prices" — happens when all 4 variables are optimized for a narrow niche

### Next Steps
1. [Immediate action — this week]
2. [Short-term action — this month]
3. [Long-term action — this quarter]

→ Design a guarantee: `/guarantee-designer`
→ Stack bonuses to handle objections: `/bonus-stacker`
→ Add scarcity/urgency: `/scarcity-urgency-builder`
→ Name and package the offer: `/offer-namer`
```

## Source Transcripts
- `9htyfIZ9iPk-How To Craft A $100M Offer In 6 Minutes.md`
- `p5u28z1FAsI-The $100M Offer Formula.md`
- `80tRGf_nL0g-How To Create Grand Slam Offers with Alex Hormozi.md`
- `6c5WJA0TH3g-How To Create A GRAND SLAM Offer with Alex Hormozi (Not What You Think).md`
- `aETs5vL4H-w-Making irresistible offers - Alex Hormozi.md`

## Disclaimer
This skill applies Alex Hormozi's offer design frameworks as taught in his public content. It is not affiliated with Acquisition.com or Alex Hormozi. Results depend on your market, execution, and delivery capability.
