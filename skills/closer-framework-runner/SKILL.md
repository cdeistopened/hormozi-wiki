---
name: closer-framework-runner
description: "Walk through a sales conversation using Hormozi's C.L.O.S.E.R. framework - his signature 6-step sales process refined from training 116+ salespeople and closing 4,000+ sales personally. Use when you need a sales script, when you're preparing for a sales call, when someone says 'how do I close more sales,' 'write me a sales script,' 'teach me the CLOSER framework,' or 'I have a sales call tomorrow.'"
argument-hint: "[your offer and the type of sales conversation]"
---

# CLOSER Framework Runner

Build a customized sales conversation flow using Hormozi's C.L.O.S.E.R. framework. Output a step-by-step script skeleton tailored to your specific offer and sales situation.

Read `references/frameworks/closer-framework-explained.md` for the full framework with examples. Read `references/frameworks/four-core-objections.md` for handling objections within the CLOSER flow.

## Why This Matters

Hormozi developed the CLOSER framework from training over 116 salespeople and personally closing 4,000+ deals. It is the backbone of every sales team across his portfolio:

> "So let's rock and roll. CLOSER framework. The C is clarify why the person is on the phone with you. I'm going to label you with a problem. After that we overview their past paid. And then finally, step before finally, we explain away their concerns. So they say yes, and then once they say yes, we reinforce the decision."
> — Alex Hormozi, "I Taught 116+ Salesmen My Closing Framework"

The framework works because it follows the natural psychology of a buying decision. You don't pitch first. You diagnose first - just like a doctor.

## The Framework

### C - Clarify Why They're Here

The first step is understanding why the prospect showed up. If they don't clarify the problem themselves, any solution you offer will feel like a pitch instead of a prescription.

> "If someone does not clarify why they need a solution, you do not ask for the sale."
> — Alex Hormozi, "I Taught 116+ Salesmen My Closing Framework"

**Questions to ask:**
- "What brought you here today?"
- "What's going on that made you reach out?"
- "What made now the right time?"

**What you're listening for:** The specific pain, the triggering event, the emotional weight. Do NOT rush past this step. Sit in the pain.

### L - Label the Problem

After they describe their situation, you label it. Labeling does two things: it proves you understand, and it positions you as the expert who has seen this before.

> "I'm going to label you with a problem. Right, we got to give it to you before we can cure it."
> — Alex Hormozi, "I Taught 116+ Salesmen My Closing Framework"

**How to label:**
- "So it sounds like [restate their problem in clearer terms]."
- "What I'm hearing is [diagnosis]. Is that right?"
- "Based on what you're telling me, the real issue is [root cause, not symptom]."

The label must be MORE specific than what they said. If they said "I can't get clients," your label is "You don't have a predictable system for generating leads, so you're stuck in feast-or-famine mode."

### O - Overview Past Experience

Before prescribing a solution, understand what they've already tried. This prevents them from thinking "I already tried that" when you present your offer.

**Questions to ask:**
- "What have you tried so far to solve this?"
- "How did that work out?"
- "What do you think went wrong?"
- "How much have you invested in solving this already?"

**What you're listening for:** Past failures (your solution must be differentiated), money already spent (builds cost-of-inaction case), and what they believe works vs. doesn't.

### S - Sell the Vacation (Not the Flight)

Now you paint the picture of the outcome. You are NOT describing your product features. You are describing what their life looks like after the problem is solved.

**Structure:**
1. "Based on what you've told me, here's what I think is possible for you..."
2. Paint the specific outcome in their language (use their words from step C)
3. Connect it to what they've tried (from step O) - explain why this is different
4. Show the gap between where they are and where they could be

The "sell the vacation, not the flight" metaphor: nobody wants to hear about airplane seat configurations. They want to hear about the beach.

### E - Explain Away Concerns

After painting the picture, you ask for the decision. If they say anything other than yes, you explain away their concerns.

> "There's two things you need to memorize as a salesperson: the stories about what you sell, and the obstacles that you're going to encounter when you're in the red zone."
> — Alex Hormozi, "I Taught 116+ Salesmen My Closing Framework"

The four core objections (see `/objection-resolver` for deep handling):

| Objection | What They Say | What They Mean |
|-----------|-------------|----------------|
| **Price** | "It's too expensive" | "I don't see enough value" |
| **Time** | "I need to think about it" | "I'm not convinced enough" |
| **Authority** | "I need to talk to my spouse/partner" | "I can't decide alone" or stalling |
| **Fit** | "I'm not sure this is right for me" | "I don't trust that this works for my situation" |

For each objection, the response follows the same structure:
1. Acknowledge ("I totally understand...")
2. Reframe (connect back to their pain from step C)
3. Address the underlying belief
4. Re-ask

### R - Reinforce the Decision

After they say yes, the sale is NOT over. Buyer's remorse starts immediately. The reinforce step prevents cancellations and chargebacks.

> "The sale just continues throughout the entire customer relationship."
> — Alex Hormozi, "I Taught 116+ Salesmen My Closing Framework"

**Reinforce actions:**
1. Congratulate the decision (not the purchase - the decision to invest in themselves)
2. Set expectations for what happens next (onboarding, first steps, timeline)
3. Ask them to tell someone about the decision (creates public commitment)
4. Follow up within 24 hours with a welcome message or quick win

## The Consultation

### Step 1: Understand the Sales Context

Ask the user:

1. **What do you sell?** (Product, service, price point)
2. **How does the sales conversation happen?** (Phone, Zoom, in-person, DM)
3. **How long is a typical sales conversation?** (15 min, 30 min, 60 min)
4. **Who is the typical prospect?** (Demographics, where they came from)
5. **What are the top 3 objections you hear?**
6. **Do you have a current script or process?** (If yes, share it)

### Step 2: Build the Script Skeleton

Using their answers, build a customized CLOSER flow with:
- Specific opening questions for their prospect type
- Labels relevant to their industry
- Past experience questions that surface the right information
- Vacation language specific to their dream outcome
- Pre-written responses to their top 3 objections
- Reinforcement sequence appropriate to their delivery model

## Output

Generate a **CLOSER Sales Script** with this structure:

```markdown
## CLOSER Sales Script

**Offer:** [their offer]
**Price:** [price point]
**Call Type:** [phone / Zoom / in-person]
**Estimated Duration:** [X minutes]

### C - Clarify (Minutes 0-5)
**Opening:** "[Exact opening line]"
**Diagnostic Questions:**
1. "[Question 1]"
2. "[Question 2]"
3. "[Question 3]"
**Listen for:** [what signals to pick up on]

### L - Label (Minutes 5-8)
**Template:** "Based on what you're telling me, [label]. Is that right?"
**Industry-specific labels:**
- If they say [X] → Label as [Y]
- If they say [A] → Label as [B]

### O - Overview (Minutes 8-12)
**Questions:**
1. "[Past attempt question]"
2. "[Investment question]"
3. "[What went wrong question]"
**Transition:** "OK so you've tried [X, Y, Z] and [summary of results]. Here's why I think what we do is different..."

### S - Sell the Vacation (Minutes 12-18)
**Paint the picture:** "[Customized vision of their life after the problem is solved]"
**Differentiation:** "[Why your approach is different from what they've tried]"
**Bridge to offer:** "[How your specific offer delivers this outcome]"

### E - Explain Away Concerns (Minutes 18-25)
**Ask:** "So what do you think? Should we get started?"
**If Price:** "[Response]"
**If Time:** "[Response]"
**If Authority:** "[Response]"
**If Fit:** "[Response]"

### R - Reinforce (Minutes 25-30)
**Congratulate:** "[Exact words]"
**Next steps:** "[What happens immediately after they say yes]"
**Public commitment:** "Who's the first person you're going to tell about this?"
**Follow-up plan:** [24-hour follow-up message template]

### Next Step
→ Use `/objection-resolver` to deepen your objection handling for all 4 types
→ Use `/price-presentation-method` to refine how you present the price
→ Use `/sales-conviction-builder` if your team struggles with conviction
```

## Source Transcripts
- `q32-l3Yoqg4-I Taught 116+ Salesmen My Closing Framework.md`
- `NcD2t9qt-fM-The Best SALES TRAINING On The Internet.md`
- `RVbvhPGFi6E-After Closing 4000+ Sales, I Discovered a New Method to Close Deals Faster.md`
- `cy2k1GdA-9o-Sales Was Hard Until I Understood These 9 Concepts.md`
- `CojS0DwflXc-3 Simple Steps To Close Any Sale.md`
- `ZIJAuw64nY4-The Secret To Alex Hormozi's Sales Success.md`
- `GABddwChDtA-Alex Hormozi's C.L.O.S.E.R. Framework Explained By Sales Rep.md`

## Disclaimer
This skill applies Alex Hormozi's sales frameworks as taught in his public content. It is not affiliated with Acquisition.com or Alex Hormozi. Results depend on your market, execution, and sales ability.
