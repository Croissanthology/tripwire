# tripwire

Helping our future selves avert or mitigate catastrophic risks since 2026.

## What this is

For each catastrophic risk identified in [Sentinel's probability estimates](https://blog.sentinel-team.org/p/how-likely-are-various-precursors), this repo contains a plan for spending up to $300K with one month of advance warning to avoid or mitigate it.

Research was done using Claude Opus 4.5. None of the writing here was produced by an LLM, but most of the sourcing was.

## Risks covered

| Risk | Folder | P(>1M deaths in any year, next decade) |
|------|--------|----------------------------------------|
| War | [`risks/war/`](risks/war/) | 23% |
| War (regime crackdown) | [`risks/war-regime-crackdown/`](risks/war-regime-crackdown/) | (subset of above) |
| Natural pandemic | [`risks/pandemic-covid-like/`](risks/pandemic-covid-like/) | 22% |
| Extreme pandemic | [`risks/pandemic-extreme/`](risks/pandemic-extreme/) | (worst-case subset) |
| The unexpected | [`risks/the-unexpected/`](risks/the-unexpected/) | 21% |
| WW3 | [`risks/ww3/`](risks/ww3/) | 12% |
| AI | [`risks/ai/`](risks/ai/) | 10% |
| Climate change | [`risks/climate-change/`](risks/climate-change/) | 2.5% |
| Unintentional biochem | [`risks/biochem/`](risks/biochem/) | 2.4% |
| Biological weapons | [`risks/bioweapons/`](risks/bioweapons/) | 2.2% |
| Volcanoes | [`risks/volcanoes/`](risks/volcanoes/) | 1% |
| US civil war | [`risks/us-civil-war/`](risks/us-civil-war/) | 0.92% |
| Financial crisis | [`risks/financial-crisis/`](risks/financial-crisis/) | 0.59% |
| Solar flare / CME | [`risks/solar-flare/`](risks/solar-flare/) | 0.2% |
| Asteroids | [`risks/asteroids/`](risks/asteroids/) | (low) |

## LLM tooling

Reusable prompts and workflows for generating and evaluating mitigation plans live in [`tools/prompts/`](tools/prompts/). The goal is not just plans but a *system for generating plans*—so that when Sentinel identifies an emerging threat, bespoke mitigation plans can be produced rapidly.

## Structure

```
tripwire/
├── README.md
├── risks/
│   ├── war/
│   │   └── PLAN.md
│   ├── war-regime-crackdown/
│   │   └── PLAN.md
│   ├── ww3/
│   │   └── PLAN.md
│   ├── pandemic-covid-like/
│   │   └── PLAN.md
│   ├── pandemic-extreme/
│   │   └── PLAN.md
│   ├── solar-flare/
│   │   └── PLAN.md
│   ├── asteroids/
│   │   └── PLAN.md
│   ├── volcanoes/
│   │   └── PLAN.md
│   └── the-unexpected/
│       └── PLAN.md
├── tools/
│   └── prompts/
│       └── generate-plan.md
└── meta/
    └── methodology.md
```
