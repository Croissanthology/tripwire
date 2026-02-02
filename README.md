# tripwire

Helping our future selves avert or mitigate catastrophic risks since 2026.

## What this is

For each catastrophic risk identified in [Sentinel's probability estimates](https://blog.sentinel-team.org/p/how-likely-are-various-precursors) from Oct 2024, this repo contains a plan for spending up to $300K with one month of advance warning to avoid or mitigate it. If we need to move within days, as e.g. [Fast Grants](https://future.com/what-we-learned-doing-fast-grants/) had to do at the beginning of 2020, it may be helpful to have some strategy at the ready. Heavy use of LLMs throughout. Email me at croissanthology@gmail.com if you have suggestions/thoughts/info, project will be indefinitely maintained. 

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

## Meta work 

[On the lacunae](https://x.com/croissanthology/status/2014071957692531107?s=20) of solar flare research / intuiting from an LLM's response-shape how competent our civilization is as addressing this specific issue. [Bis.](https://x.com/croissanthology/status/2014101664182026668?s=20)

On the vulnerability in the world in general and a slight update toward "we have any preparation at all for most risks": https://croissanthology.substack.com/p/is-the-world-actually-that-vulnerable

On future "Moltbook events", i.e. networked artificial intelligence running in the wild and its potential consequences in the short term future, assessment of total risk in the long term (the majority of all compute is run on individual computers at home, not in AI lab servers! Hence worth keeping an eye on anything that could capture a significant portion of that compute, as Moltbook has done in miniature): https://croissanthology.substack.com/p/how-relevant-is-wild-intelligence 
