---
name: core-four-channel-selector
description: "Choose the right advertising channel using Hormozi's Core Four framework from $100M Leads. Use when you're spread too thin across marketing channels, when you don't know where to focus your time, when someone says 'where should I advertise,' 'how do I get customers,' 'should I run ads or do outreach,' or 'I only have 4 hours a day for marketing.'"
argument-hint: "[your business, time available, and current customer acquisition method]"
---

# Core Four Channel Selector

Diagnose which of Hormozi's four core advertising channels to prioritize based on your resources, stage, and business model. Output a channel recommendation with weekly time allocation.

Read `references/frameworks/100m-leads-core-four.md` for the full Core Four framework explained.

## Why This Matters

Hormozi breaks all advertising down to a 2x2 matrix: you either do it yourself or get others to do it, and you either reach people you know (warm) or people you don't (cold). That gives exactly four channels. Most businesses dabble in all four and master none.

> "You can talk to people one-on-one, you can make content, you can run ads, or you can get affiliates and referrals."
> — Alex Hormozi, "I Helped Business Owners Overcome Their Fear of Failure"

The Core Four become eight ways when you split warm vs. cold:

| | **You Do It** | **Others Do It** |
|---|---|---|
| **Warm (people who know you)** | 1. Warm outreach | 3. Customer referrals |
| **Cold (people who don't know you)** | 2. Cold outreach | 4. Paid ads |
| **Warm** | 5. Post content (existing audience) | 7. Affiliates promote you |
| **Cold** | 6. Make content (new audience) | 8. Agency/employee sales |

> "There's really only eight ways to let other people know about the stuff you sell. Four of those ways, you do yourself. Four of those ways, other people do for you."
> — Alex Hormozi, "8 Ways To Get Customers"

## The Consultation

### Step 1: Business Assessment

Ask the user:

1. **What do you sell?** (Product, service, price point)
2. **How many customers do you have now?** (0-10, 10-100, 100+)
3. **How much time can you dedicate to marketing daily?** (1 hour, 2-4 hours, full-time)
4. **What's your monthly marketing budget?** ($0, $500-2K, $2K-10K, $10K+)
5. **How are you currently getting customers?** (List all channels)

### Step 2: Stage Diagnosis

Map their answers to Hormozi's progression:

| Stage | Customers | Revenue | Primary Channel |
|-------|-----------|---------|-----------------|
| **Pre-revenue** | 0 | $0 | Warm outreach (always start here) |
| **First customers** | 1-10 | <$10K/mo | Warm outreach + one content platform |
| **Proof of concept** | 10-50 | $10-50K/mo | Cold outreach + content ramping |
| **Scaling** | 50-200 | $50-200K/mo | Paid ads + referral system |
| **Mature** | 200+ | $200K+/mo | All four, with team on each |

Hormozi's advice for people starting out is unambiguous:

> "Content, you reach out to people, and you do that for four straight hours every day. You reach out to 10,000 people, you'll have the business you want."
> — Alex Hormozi, "I Helped Business Owners Overcome Their Fear of Failure"

### Step 3: Resource-Channel Match

For each potential channel, assess fit:

**Warm Outreach:**
- Requires: existing network (contacts, past customers, social connections)
- Time investment: 1-4 hours/day
- Cost: $0
- Best for: first 5-20 customers, service businesses, high-ticket offers
- Hormozi's benchmark: 100 reach-outs/day, 10,000 total in first 6 months

**Cold Outreach:**
- Requires: target list, messaging templates, tracking system
- Time investment: 2-4 hours/day (or hire)
- Cost: $0-500/mo for tools
- Best for: B2B, agency, consulting, defined target market

**Content Creation:**
- Requires: one platform commitment, consistent posting
- Time investment: 1-2 hours/day to create, more to distribute
- Cost: $0
- Best for: anyone, but especially thought leadership, education, personal brands

> "The purpose of having the organic content is lead nurture, not lead generation. Phase one and phase two, if you're in one of those camps, you don't need to do anything else."
> — Alex Hormozi, "1.2M Followers in 6 Months"

**Paid Ads:**
- Requires: proven offer (tested via organic first), budget, tracking
- Time investment: 2-5 hours/week to manage
- Cost: $1K+/mo minimum to test
- Best for: businesses with proven unit economics and a scalable offer

**Referrals/Affiliates:**
- Requires: happy customers (you need customers first)
- Time investment: setup + ongoing management
- Cost: commission/incentive structure
- Best for: businesses with high customer satisfaction and clear measurable results

### Step 4: The Priority Decision

Apply the decision tree:

1. **Do you have customers yet?** No → Warm outreach. Period.
2. **Do you have budget?** No → Outreach + content. Skip paid ads.
3. **Do you have a proven offer?** No → Don't run paid ads yet. Test via outreach first.
4. **Do you have happy customers?** Yes → Build a referral system immediately.
5. **Are you doing 100+ reach-outs per day?** No → Increase volume before adding channels.

Hormozi's rule: do NOT add a second channel until the first one is working. "Spreading thin" is the most common mistake.

### Step 5: Weekly Time Allocation

Based on the selected primary channel, build a weekly schedule:

| Block | Monday-Friday |
|-------|--------------|
| **Morning (2 hrs)** | Primary channel activity |
| **Midday (1 hr)** | Content creation (even if content isn't primary) |
| **Afternoon (1 hr)** | Follow-up, nurture, admin |

Adjust blocks based on available time. If only 1 hour/day, ALL of it goes to the primary channel.

## Output

Generate a **Channel Strategy Brief** with this structure:

```markdown
## Channel Strategy Brief

**Business:** [their business]
**Stage:** [pre-revenue / first customers / proof of concept / scaling / mature]
**Available Time:** [hours/day]
**Budget:** [monthly marketing budget]

### Primary Channel: [channel name]
**Why:** [1-2 sentences on why this channel fits their stage and resources]
**Daily Activity Target:** [specific volume — e.g., "100 warm reach-outs" or "1 post + 20 comments"]
**Expected Timeline to Results:** [realistic timeframe]

### Secondary Channel: [channel name] (start after primary is working)
**Trigger to Add:** [what milestone to hit before adding this channel]

### Channels to Skip (for now)
- [Channel]: [why it doesn't fit their current stage]

### Weekly Schedule
| Day | Block 1 (X hrs) | Block 2 (X hrs) |
|-----|-----------------|-----------------|
| Mon | [activity] | [activity] |
| Tue | [activity] | [activity] |
[...]

### Volume Targets
- **Week 1-4:** [ramp-up targets]
- **Month 2-3:** [steady-state targets]
- **Month 4-6:** [scaling targets]

### Next Step
→ If warm outreach: use `/warm-outreach-system` to build scripts and sequences
→ If cold outreach: use `/cold-outreach-system` to build targeting and templates
→ If content: use `/content-engine-blueprint` to build your content machine
→ If paid ads: use `/paid-ads-launcher` to design your first campaign
→ If referrals: use `/affiliate-referral-designer` to build your program
```

## Source Transcripts
- `40GVk9hoIYU-8 Ways To Get Customers - Lesson from Alex Hormozi.md`
- `I Helped Business Owners Overcome Their Fear of Failure-0_Gf5v8DEMY.md`
- `P-PSAD-w4Og-8 Proven Ways to Get New Leads: Alex Hormozi's Core Four Explained.md`
- `MD5-HByRxoA-1.2M Followers in 6 Months… My Content Marketing Strategy REVEALED.md`
- `oZ18-kMrmKw-Alex Hormozi's Lead Generation Strategy for 2026.md`

## Disclaimer
This skill applies Alex Hormozi's lead generation frameworks as taught in his public content. It is not affiliated with Acquisition.com or Alex Hormozi. Results depend on your market, execution, and delivery capability.
