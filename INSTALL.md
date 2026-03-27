# Installing Ask Hormozi

## Prerequisites

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) installed and working

## Installation

```bash
claude install-plugin github:cdeistopened/hormozi-wiki
```

Or add the plugin directory manually:

```bash
# From your project directory
claude plugin add /path/to/hormozi-wiki/plugin
```

## First Question to Try

```
Is my offer good enough?
```

This routes to the Value Equation Scorer — Hormozi's most diagnostic tool — and scores your offer across Dream Outcome, Perceived Likelihood, Time Delay, and Effort & Sacrifice.

## Other Good Starting Questions

- "How do I get my first customers?"
- "Write me a sales script using the CLOSER framework"
- "Design a lead magnet for my business"
- "How do I raise my prices?"
- "What bonuses should I include in my offer?"

## Playbook Sequences

For a full build, run skills in playbook order:

1. **Grand Slam Offer** (9 skills) — Build a complete offer from dream outcome to packaging
2. **$100M Leads** (7 skills) — Build a lead gen engine from warm outreach to paid scale
3. **Sales & CLOSER** (5 skills) — Close more deals at higher prices

## Troubleshooting

- **Skills not showing:** Make sure the plugin path is correct and Claude Code has been restarted
- **Generic answers:** Try invoking a specific skill directly: `/ask-hormozi:value-equation-scorer`
- **Want a full offer build?** Start with `/ask-hormozi:dream-outcome-definer` and work through the Grand Slam Offer playbook in order

## Learn More

Visit [creativeintel.agency](https://creativeintel.agency) for more Ask [Creator] plugins.
