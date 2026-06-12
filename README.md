# Poetic Naming Creator

**An agent skill for generating original, brand-quality names** — for companies, products, features, campaigns, and everything in between.

[![Install with Skills CLI](https://img.shields.io/badge/skills.sh-install-black?style=flat-square)](https://skills.sh) [![License: MIT](https://img.shields.io/badge/License-MIT-gray?style=flat-square)](LICENSE)

---

## What it does

Most AI-generated names are forgettable. This skill isn't.

It teaches AI agents to think like a brand strategist, naming consultant, and poet at once — producing names with metaphor, emotional depth, and real strategic value instead of defaults like *CloudPilot*, *DataFlow*, or *GrowthOps*.

**Output looks like this:**

> Black Lantern · Glass Oracle · Stonecloud · Signal Garden · Moss Engine · Human Atlas · Velvet Cart · Dream Circuit · Clause & Compass · Concrete Swan

---

## Installation

**Via Skills CLI (recommended)**
```bash
npx skills add radityprtama/poetic-naming-creator
```

**Manual**
```bash
# Claude Code
git clone https://github.com/radityprtama/poetic-naming-creator.git ~/.claude/skills/poetic-naming-creator
```

---

## Usage

Just ask naturally — no special syntax required.

```
"I need a name for my AI-powered legal contract analyzer"
"Help me name my climate tech startup"
"Give me feature names for my project management tool"
"Name my design agency — something premium and mythic"
```

**Example output:**

```markdown
## Direction 1: Industrial Intelligence
- Clause & Compass — navigation through legal complexity
- White Gavel — authority with clarity and fairness

## Direction 2: Organic Systems
- Contract Garden — agreements that grow and evolve
- Policy Harbor — safe port for regulatory navigation

## Direction 3: Mythic Clarity
- Glass Oracle — transparent foresight
- Legal Lantern — light in legal darkness
```

Each name comes with: rationale, domain suggestions, and expandability ideas.

---

## When it triggers

The skill activates for naming requests across any context:

| Target | Examples |
|---|---|
| Companies & Startups | Founding names, holding companies |
| SaaS Products & Apps | B2B tools, consumer apps, AI agents |
| Agencies & Studios | Creative shops, consultancies, dev studios |
| Developer Tools | CLIs, libraries, platforms, frameworks |
| Product Features | In-app modules, modes, settings, tiers |
| Campaigns & Communities | Marketing campaigns, community names |

Even casual prompts like *"help me name this thing"* will trigger it.

---

## How it works

### Quality criteria

Every name is evaluated against 10 criteria. A name needs at least 3 to make the cut.

| Criteria | What it means |
|---|---|
| Memorable | Easy to recall after hearing once |
| Meaningful | Has a story, metaphor, or emotional anchor |
| Flexible | Survives product pivots and business evolution |
| Distinctive | Doesn't sound like every other SaaS or agency |
| Philosophical | Suggests a deeper worldview |
| Visual | Creates an image in the mind |
| Strategic | Supports positioning and trust |
| Speakable | Easy to say in conversation |
| Domain-friendly | Works as `.com`, `.app`, `.dev`, `.ai`, `.studio` |
| Expandable | Can become a system of sub-brands |

### Naming styles

| Style | Feel | Best for |
|---|---|---|
| Poetic Tech | Nature + philosophy + systems | AI, data, climate, creative tools |
| Mythic / Archetypal | Guardians, oracles, ancient roles | Security, legal, AI, enterprise |
| Warm Humanist | Care, softness, trust | Healthtech, edtech, HR, wellness |
| Industrial Elegant | Strong, premium, architectural | DevOps, infra, logistics, B2B |
| Strategic Minimal | Clear positioning with character | SaaS, fintech, AI productivity |
| Editorial / Studio | Agency, bureau, creative house | Agencies, studios, consultancies |
| Feature Naming | Useful, delightful, integrated | App features, modules, modes |

### Industry coverage

Specialized naming guidance for 16 sectors:

Security · Healthtech · AI/Automation · Infrastructure/DevOps · Finance · Education · Legal · Real Estate · Logistics · Ecommerce · HR/Recruitment · Marketing · Data/Analytics · Construction · Agriculture/Climate · Developer Tools · Agency/Studio

---

## File structure

```
poetic-naming-creator/
├── SKILL.md                  # Core skill instructions
├── references/
│   ├── word-banks.md         # 300+ curated words across 12 clusters
│   ├── patterns.md           # 10 repeatable name construction patterns
│   └── sectors.md            # Sector-specific naming guidance
├── README.md
└── LICENSE
```

---

## Compatibility

Works with any agent that supports the [Agent Skills open standard](https://skills.sh):

- Claude Code
- Cursor
- Windsurf
- OpenAI Codex
- Antigravity CLI (Gemini)

---

## Contributing

Contributions welcome. High-value additions:

- New sectors in `references/sectors.md`
- Expanded word banks in `references/word-banks.md`
- New construction patterns in `references/patterns.md`

```bash
git checkout -b add-new-sector
# make changes
# submit pull request
```

---

## Credits

Created by [@radityprtama](https://github.com/radityprtama). Built for the [skills.sh](https://skills.sh) ecosystem.

*Great names aren't labels — they create a mental world.*
