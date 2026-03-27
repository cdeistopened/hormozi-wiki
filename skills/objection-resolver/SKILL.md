---
name: objection-resolver
description: "Handle the 4 core sales objections using Hormozi's conviction-based approach - addressing the underlying belief, not the surface excuse. Use when your close rate is low, when you keep hearing the same objections, when someone says 'how do I handle price objections,' 'they keep saying they need to think about it,' 'overcome objections,' or 'my prospects won't commit.'"
argument-hint: "[the top objections you hear in sales]"
---

# Objection Resolver

Classify each objection by type, identify the underlying belief driving it, and generate Hormozi-method responses that address the root cause rather than the surface excuse.

Read `references/frameworks/four-core-objections.md` for the full objection taxonomy with examples. Read `references/frameworks/closer-framework-explained.md` for how objection handling fits into the CLOSER flow.

## Why This Matters

Most salespeople try to overcome objections by arguing. Hormozi's approach is the opposite: objections are not obstacles to defeat. They are beliefs to address.

> "There's two things you need to memorize as a salesperson: the stories about what you sell, and the obstacles that you're going to encounter when you're in the red zone."
> — Alex Hormozi, "I Taught 116+ Salesmen My Closing Framework"

Every objection falls into one of four categories. Once you classify it, the response follows a predictable pattern.

The 9 concepts Hormozi identifies from closing 4,000+ sales include conviction as the #1 factor:

> "There are nine things that brilliant sales people do differently... a salesperson has three jobs to do: they have to maximize the number of opportunities they have, they have to convert the highest percentage of those opportunities, and - this is the important part - they have to do it consistently for a very long period of time."
> — Alex Hormozi, "Sales Was Hard Until I Understood These 9 Concepts"

## The Four Core Objections

### 1. Price: "It's too expensive"

**What they actually mean:** "I don't see enough value to justify this cost."

This is never actually about the money. It is about the perceived value relative to the price. If someone offered them $10,000 in cash for $5,000, they would find the money.

**Response framework:**
1. **Isolate:** "If money weren't a factor, would you move forward?" (If no → it's not really about price. Dig deeper.)
2. **Reframe the cost:** "What is the cost of NOT solving this? You said you've already spent [$X from Overview step]. How much will the next year cost you?"
3. **Break it down:** "That's [$daily/weekly amount] per day. Is [$result they want] worth [$daily amount] per day?"
4. **Stack the value:** Reference everything included. See `/bonus-stacker` for the value stack approach.

### 2. Time: "I need to think about it"

**What they actually mean:** "I'm not convinced enough to decide right now."

"Think about it" is the most common stall, and it almost never results in a yes later. If they leave the call uncommitted, the emotion fades and logic talks them out of it.

**Response framework:**
1. **Validate:** "That makes total sense. What specifically do you want to think about?"
2. **Surface the real concern:** Whatever they say next is the actual objection. Handle THAT.
3. **The time cost:** "I totally understand wanting to think. But here's what I've seen: the people who 'think about it' usually come back 6 months later and wish they'd started 6 months ago. What would you have if you'd started 6 months ago?"
4. **Reduce the risk:** Offer a guarantee, a trial, or a reduced-commitment entry point.

### 3. Authority: "I need to talk to my spouse/partner"

**What they actually mean:** Either genuine (they truly share financial decisions) or a stall (they're using the partner as an excuse).

**Response framework:**
1. **Validate genuinely:** "I completely respect that. Let me ask: if your [spouse/partner] said 'whatever you think is best,' would you move forward?"
2. **If yes (genuine):** "Great. Would it help if I put together a summary you could share with them? Or would it be easier to get them on a quick 10-minute call?"
3. **If no (stall):** This reveals the real objection. "What concerns do you think they'd have?" Then handle THAT concern.
4. **Prevention:** Ask about decision-making authority early in the call (during Clarify step) to avoid this at the end.

### 4. Fit: "I'm not sure this is right for me"

**What they actually mean:** "I don't believe this will work for my specific situation."

This is a perceived likelihood of achievement problem (see Value Equation). They believe the result is possible for others but not for them.

**Response framework:**
1. **Get specific:** "What about your situation makes you unsure?" (Force them to name the specific doubt)
2. **Match to proof:** "We've worked with [someone in their exact situation] and they got [specific result]." Use the most relevant case study.
3. **Acknowledge uniqueness:** "You're right that your situation is [unique aspect]. That's exactly why [feature of your offer] exists."
4. **Reduce commitment:** "Would you be open to starting with [smaller commitment] to test it?"

## The Consultation

### Step 1: Collect Objections

Ask the user:

1. **List the top 5 objections you hear most often.** (Exact words prospects use)
2. **At what point in the conversation do these come up?** (Early, during price, after pitch)
3. **How do you currently respond?** (What you say now)
4. **What happens after you respond?** (Do they buy, stall further, or leave?)

### Step 2: Classify Each Objection

Map every objection to one of the four categories. Some objections disguise themselves:

| What They Say | Sounds Like | Actually Is |
|-------------|------------|------------|
| "I can't afford it" | Price | Price (or Fit if they truly can't) |
| "Let me sleep on it" | Time | Time (surface a deeper concern) |
| "My business partner needs to see this" | Authority | Authority or Time (stall) |
| "I've tried something like this before" | Fit | Fit (perceived likelihood problem) |
| "The timing isn't right" | Time | Could be Price, Fit, or genuine timing |
| "I'm already working with someone" | Fit | Fit or loyalty/switching cost |

### Step 3: Build Response Scripts

For each objection, generate a customized response following the framework above, using:
- Their specific offer language
- Relevant case studies or proof points they have
- The specific emotional pain from their prospect profile

### Step 4: Build the Practice System

Hormozi's sales training uses two memorization categories:

1. **Stories:** 3-5 customer success stories, memorized cold, each addressing a different objection type
2. **Obstacle overcomes:** The specific responses for each of the 4 objection types, practiced until natural

## Output

Generate an **Objection Handling Playbook** with this structure:

```markdown
## Objection Handling Playbook

**Business:** [their business]
**Offer:** [what they sell]
**Price:** [price point]

### Objection Map
| Objection (Their Words) | Category | Underlying Belief | Response |
|------------------------|----------|-------------------|----------|
| "[objection 1]" | [Price/Time/Authority/Fit] | [what they really mean] | [scripted response] |
| "[objection 2]" | ... | ... | ... |
[... for all objections]

### Pre-Written Responses (Full Scripts)

**Objection 1: "[exact words]"**
Category: [type]
Response:
> [Full scripted response, 3-5 sentences]

[... for each objection]

### Stories to Memorize
1. **[Client name/type]:** [Brief story that addresses Price objections]
2. **[Client name/type]:** [Brief story that addresses Fit objections]
3. **[Client name/type]:** [Brief story that addresses Time objections]

### Practice Plan
- Week 1: Memorize all responses (read aloud 3x daily)
- Week 2: Role-play with partner (have them throw objections randomly)
- Week 3: Live calls with responses written on a card for reference
- Week 4: Responses should be natural without reference

### Next Step
→ Use `/closer-framework-runner` to build the full sales flow these fit into
→ Use `/price-presentation-method` to prevent price objections before they arise
→ Use `/sales-conviction-builder` if the real issue is your belief, not the prospect's
```

## Source Transcripts
- `q32-l3Yoqg4-I Taught 116+ Salesmen My Closing Framework.md`
- `cy2k1GdA-9o-Sales Was Hard Until I Understood These 9 Concepts.md`
- `NcD2t9qt-fM-The Best SALES TRAINING On The Internet.md`
- `CojS0DwflXc-3 Simple Steps To Close Any Sale.md`
- `ETEFhDICm5o-Close High-Ticket Sales By Saying "NO".md`
- `RVbvhPGFi6E-After Closing 4000+ Sales, I Discovered a New Method to Close Deals Faster.md`

## Disclaimer
This skill applies Alex Hormozi's sales frameworks as taught in his public content. It is not affiliated with Acquisition.com or Alex Hormozi. Results depend on your market, execution, and sales ability.
