# 🪶 Poetic Naming Creator

> **An AI agent skill that generates original, meaningful, and memorable names** — for companies, products, features, campaigns, and everything in between.

[![Install with Skills CLI](https://img.shields.io/badge/skills.sh-install-blue?style=flat-square)](https://skills.sh)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

---

## ✨ What Is This?

**Poetic Naming Creator** is an [Agent Skill](https://skills.sh) — a structured set of instructions that teaches AI agents (Claude Code, Cursor, Windsurf, Codex, etc.) how to generate **brand-quality names** with strong metaphor, emotional depth, and real strategic value.

Instead of generic names like _CloudPilot_, _DataFlow_, or _GrowthOps_, this skill produces names like:

> **Black Lantern** · **Glass Oracle** · **Stonecloud** · **Signal Garden** · **Moss Engine** · **Human Atlas** · **Velvet Cart** · **Dream Circuit** · **Clause & Compass** · **Concrete Swan**

---

## 🎯 When Does It Trigger?

The skill activates when the user needs creative, brandable, or meaningful names for:

- 🏢 **Companies & Startups** — Founding names, holding companies
- 🚀 **SaaS Products & Apps** — B2B tools, consumer products, AI agents
- 🏗️ **Agencies & Studios** — Creative shops, consultancies, dev studios
- 🔧 **Developer Tools & Frameworks** — CLIs, libraries, platforms
- 📦 **Product Features & Modules** — In-app features, modes, settings
- 📣 **Campaigns & Communities** — Marketing campaigns, community names
- 💎 **Pricing Plans & Product Lines** — Tier names, sub-brands

Even casual requests like _"help me name this thing"_ or _"I need a name for my startup"_ will trigger the skill.

---

## 📦 Installation

### Using the Skills CLI (Recommended)

```bash
npx skills add radityprtama/poetic-naming-creator
```

### Manual Installation

Clone or download this repository into your agent's skills directory:

```bash
# Claude Code
git clone https://github.com/radityprtama/poetic-naming-creator.git ~/.claude/skills/poetic-naming-creator

# Or copy SKILL.md and references/ to your agent's skill folder
```

---

## 📁 Skill Structure

```
poetic-naming-creator/
├── SKILL.md                    # Core skill instructions (required)
├── references/
│   ├── word-banks.md           # 300+ curated words across 12 clusters
│   ├── patterns.md             # 10 repeatable name construction patterns
│   └── sectors.md              # Sector-specific naming guidance (16 industries)
├── README.md                   # This file
└── LICENSE                     # MIT License
```

| File | Purpose |
|---|---|
| `SKILL.md` | Main instructions — loaded every time the skill is invoked |
| `references/word-banks.md` | Core vocabulary organized by theme (light, nature, industrial, etc.) |
| `references/patterns.md` | 10 proven naming formulas with examples and usage guidance |
| `references/sectors.md` | Industry-specific metaphors, themes, and example names for 16 sectors |

---

## 🧠 How It Works

### Core Philosophy

The skill teaches AI agents to think like a hybrid of: **brand strategist**, **naming consultant**, **poet**, **product designer**, **startup founder**, **UX writer**, and **systems thinker**.

Every generated name is evaluated against **10 quality criteria**:

1. **Memorable** — Easy to recall after hearing once
2. **Meaningful** — Has a story, metaphor, or emotional anchor
3. **Flexible** — Survives product pivots and business evolution
4. **Distinctive** — Doesn't sound like every other SaaS or agency
5. **Philosophical** — Suggests a deeper worldview
6. **Visual** — Creates an image in the mind
7. **Strategic** — Supports positioning and trust
8. **Speakable** — Easy to say in conversation
9. **Domain-friendly** — Works as `.com`, `.app`, `.dev`, `.ai`, `.studio`
10. **Expandable** — Can become a system of sub-brands

A name must satisfy **at least 3 of these 10** to be included.

### Naming Styles

| Style | Feel | Best For |
|---|---|---|
| **Poetic Tech** | Nature + philosophy + systems | AI, data, climate, creative tools |
| **Mythic / Archetypal** | Guardians, oracles, ancient roles | Security, legal, AI, enterprise |
| **Warm Humanist** | Care, softness, trust | Healthtech, edtech, HR, wellness |
| **Industrial Elegant** | Strong, premium, architectural | DevOps, infra, logistics, B2B |
| **Strategic Minimal** | Clear positioning with character | SaaS, fintech, AI productivity |
| **Editorial / Studio** | Agency, bureau, creative house | Agencies, studios, consultancies |
| **Feature Naming** | Useful, delightful, integrated | App features, modules, modes |

### Industry Coverage

The skill includes specialized naming guidance for **16 sectors**:

Security · Healthtech · AI/Automation · Infrastructure/DevOps · Finance · Education · Legal · Real Estate · Logistics · Ecommerce · HR/Recruitment · Marketing · Data/Analytics · Construction · Agriculture/Climate · Developer Tools · Agency/Studio

---

## 💬 Example Usage

Just ask your AI agent naturally:

```
"I need a name for my AI-powered legal contract analyzer"

"Help me name my climate tech startup"

"Give me feature names for my project management tool"

"I'm building a developer CLI tool, suggest some cool names"

"Name my design agency — something that feels premium and mythic"
```

### Example Output

The skill generates names grouped by **creative direction**:

```markdown
## Direction 1: Industrial Intelligence
- **Clause & Compass** — Navigation through legal complexity
- **White Gavel** — Authority with clarity and fairness

## Direction 2: Organic Systems  
- **Contract Garden** — Agreements that grow and evolve
- **Policy Harbor** — Safe port for regulatory navigation

## Direction 3: Mythic Clarity
- **Glass Oracle** — Transparent foresight
- **Legal Lantern** — Light in legal darkness
```

Each name includes: rationale, domain suggestions, and expandability ideas.

---

## 🔧 Compatibility

This skill follows the [Agent Skills open standard](https://skills.sh) and works with:

- ✅ [Claude Code](https://claude.ai) (Anthropic)
- ✅ [Cursor](https://cursor.sh)
- ✅ [Windsurf](https://codeium.com/windsurf)
- ✅ [OpenAI Codex](https://openai.com)
- ✅ Any agent that supports the Agent Skills standard
- ✅ [Antigravity CLI](https://deepmind.google) (Gemini)

---

## 🤝 Contributing

Contributions are welcome! Some ways to help:

- **Add new sectors** to `references/sectors.md`
- **Expand word banks** in `references/word-banks.md`
- **Create new patterns** in `references/patterns.md`
- **Share names** you've generated using this skill

### How to Contribute

1. Fork this repository
2. Create a feature branch (`git checkout -b add-new-sector`)
3. Make your changes
4. Submit a pull request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🌟 Credits

Created by [@radityprtama](https://github.com/radityprtama).

Built for the [skills.sh](https://skills.sh) ecosystem — giving AI agents the power of poetic, strategic naming.

---

<p align="center">
  <i>Great names are not labels. They create a <b>mental world</b>.</i>
</p>
