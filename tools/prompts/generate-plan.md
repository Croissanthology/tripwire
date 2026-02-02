# Prompt: Generate Mitigation Plan

Use this prompt with Claude Opus 4.5 (or equivalent) to generate a first-draft mitigation plan for a given catastrophic risk.

## Prompt

```
You are helping a small nonprofit (Sentinel) that monitors catastrophic risks. Given the following parameters, generate a prioritized mitigation plan.

**Catastrophe:** {catastrophe}
**Warning time:** {warning_time} (default: 1 month)
**Budget:** {budget} (default: $300,000)
**Actor:** A small nonprofit with connections to the EA community, academic researchers, and some policy contacts. Not a government.
**Location focus:** {location} (default: global, with emphasis on the US)

Generate a plan that includes:
1. A ranked list of interventions, each with estimated cost and expected impact
2. For each intervention: who to contact, what to buy/fund, and what the theory of change is
3. An explicit "dead ends" section listing plausible-sounding interventions that DON'T work and why
4. Key uncertainties and what would change the plan

Constraints:
- Be concrete. "Fund researchers" is not a plan. "Email the 12 people on the Fast Grants evaluator list and offer $25K micro-grants for {specific research}" is a plan.
- Distinguish between interventions that require advance preparation (buying PPE now) vs. interventions that can only happen after the alarm is pulled.
- Consider what existing infrastructure (Fast Grants, Manifund, EA orgs) can be leveraged rather than built from scratch.
```

## Usage notes

- Works best when you provide specific scenario details rather than generic catastrophe types
- Follow up by asking the model to steelman the weakest intervention and attack the strongest one
- Save interesting outputs as drafts in the relevant `risks/` folder
