---
name: effort-reducer
description: "Reduce the effort and sacrifice your customer must endure after purchasing. Use when customers complain the process is too hard, when completion rates are low, when you hear 'I just don't have time for this,' or when someone says 'my customers aren't doing the work,' 'how do I make my program easier to follow,' or 'people buy but don't implement.'"
argument-hint: "[your offer + what customers must do after buying]"
---

# Effort & Sacrifice Reducer

Map every action your customer must take after purchasing, separate effort (new things they must start) from sacrifice (things they must stop), rank each by customer resistance, and generate solutions that make the path to the result as frictionless as possible.

Read `references/frameworks/value-equation-explained.md` for how effort & sacrifice fits into the Value Equation as the second denominator variable.

## Why This Matters

Effort and sacrifice are two sides of the same coin, and they live in the denominator of the Value Equation — meaning they divide the value of your offer. Every additional thing your customer has to do reduces what they're willing to pay.

> "Effort are the things that you have to begin doing that you don't want to do as a result of a purchase. So in the personal training example, you got to wake up early, you got to be sore. Sacrifices are the things you have to stop doing that you want to keep doing — you got to stop Taco Tuesday, you got to stop sleeping in."
> — Alex Hormozi, "How To Craft A $100M Offer In 6 Minutes"

Hormozi's method is to get granular about every single micro-step a customer must take, then systematically find ways to remove, automate, or do each one for them:

> "When you itemize all the things that a customer has to do as a result of a purchase — what are the things that increase their risk, what are the things that make it take longer, what are the things that make them start doing things they hate, and what are the things that we have them stop doing that they love — and then you create solutions for each of those categories, then you create an incredibly valuable offer."
> — Alex Hormozi, "How To Craft A $100M Offer In 6 Minutes"

## The Consultation

### Step 1: List Every Post-Purchase Action

Ask the user to describe everything a customer must do after buying:

1. **What must they start doing immediately?** (Fill out forms, attend calls, learn software, change habits)
2. **What must they keep doing consistently?** (Weekly sessions, daily tasks, ongoing practices)
3. **What must they stop doing?** (Old habits, current routines, things they enjoy)
4. **What decisions must they make along the way?** (Choosing options, prioritizing, self-assessing)
5. **What skills must they learn?** (New software, new techniques, new knowledge)

Get specific. The weight loss example illustrates the level of granularity needed:

- Go grocery shopping (differently)
- Learn how to prep food
- Wake up earlier
- Exercise (be sore)
- Stop eating Taco Tuesday
- Stop sleeping in
- Track meals
- Weigh themselves regularly

### Step 2: Classify Each Item

Separate into two categories and rank by resistance (how much the customer hates doing this):

**EFFORT (things they must START doing):**

| Action | Resistance (1-10) | Frequency | Impact on Result |
|--------|-------------------|-----------|-----------------|
| [action] | [score] | [daily/weekly/once] | [critical/helpful/minor] |

**SACRIFICE (things they must STOP doing):**

| Action | Resistance (1-10) | Current Frequency | Impact on Result |
|--------|-------------------|-------------------|-----------------|
| [action] | [score] | [how often they do it now] | [critical/helpful/minor] |

### Step 3: Apply the 5 Friction Reduction Strategies

For each high-resistance item (7+), identify which strategy applies:

| Strategy | What It Does | Example |
|----------|-------------|---------|
| **Done-for-you** | You do it entirely | Meal prep service instead of teaching cooking |
| **Done-with-you** | You do it together | Co-working session instead of "go figure it out" |
| **Templates/Swipe files** | Pre-built starting point | Grocery list instead of "plan your meals" |
| **Automation** | Software does it | Auto-tracking instead of manual food diary |
| **Elimination** | Remove the step entirely | Intermittent fasting (skip breakfast = one fewer meal to plan) |

**The key insight:** Moving from "teach them to do it" to "do it for them" is how you justify 10x price increases. This is why Hormozi says you probably need a less scalable business model in the beginning:

> "You probably need to have some sort of done-for-you component where you're going to provide more than you normally would, and just go above and beyond."
> — Alex Hormozi, "How To Create A GRAND SLAM Offer"

### Step 4: Redesign the Customer Journey

Create a new post-purchase flow where high-resistance items have been reduced, automated, or eliminated.

## Output

Generate an **Effort & Sacrifice Friction Map**:

```markdown
## Effort & Sacrifice Friction Map

**Offer:** [their offer]
**Total effort items:** [count]
**Total sacrifice items:** [count]
**Highest-resistance item:** [the #1 thing customers hate doing]

### Effort Inventory (Things They Must Start)

| # | Action | Resistance | Solution | New Resistance |
|---|--------|-----------|----------|---------------|
| 1 | [action] | [X/10] | [DFY/DWY/template/automate/eliminate] | [Y/10] |
| 2 | [action] | [X/10] | [solution] | [Y/10] |
| ... | ... | ... | ... | ... |

### Sacrifice Inventory (Things They Must Stop)

| # | Action | Resistance | Solution | New Resistance |
|---|--------|-----------|----------|---------------|
| 1 | [action] | [X/10] | [substitute/gradual/reframe] | [Y/10] |
| 2 | [action] | [X/10] | [solution] | [Y/10] |
| ... | ... | ... | ... | ... |

### Friction Score
- **Before:** [average resistance across all items]
- **After:** [average resistance with solutions applied]
- **Reduction:** [percentage]

### Top 3 High-Impact Reductions
1. [The single change that removes the most friction]
2. [Second-highest impact]
3. [Third-highest impact]

### Done-For-You Opportunities
[List any items where you could do the work for the customer, enabling a premium price tier]

### Next Step
→ Score the full offer with `/value-equation-scorer`
→ Or compress the timeline with `/time-delay-compressor`
```

## Source Transcripts
- `9htyfIZ9iPk-How To Craft A $100M Offer In 6 Minutes.md`
- `p5u28z1FAsI-The $100M Offer Formula.md`
- `6c5WJA0TH3g-How To Create A GRAND SLAM Offer with Alex Hormozi (Not What You Think).md`

## Disclaimer
This skill applies Alex Hormozi's offer design frameworks as taught in his public content. It is not affiliated with Acquisition.com or Alex Hormozi. Results depend on your market, execution, and delivery capability.
