# IDEO Design Method Cards for Claude Code

A Claude Code skill that brings IDEO's 51 Design Method Cards to your terminal. Get smart, context-aware method recommendations, step-by-step facilitation guides, and workshop planning — all without leaving your workflow.

## What It Does

- **Quick Recommendation** — Describe your challenge, get 3-5 methods with rationale
- **Deep Dive** — Pick a method, get a complete facilitation playbook
- **Workshop Planning** — Build a timed agenda with method sequences and materials lists
- **Random Inspiration** — Draw a card for a fresh perspective on your current work

## Install

### Option 1: Symlink (recommended for development)

```bash
ln -s /path/to/idea-method-cards ~/.claude/skills/idea-method-cards
```

### Option 2: Copy

```bash
cp -r /path/to/idea-method-cards ~/.claude/skills/idea-method-cards
```

### Option 3: Install from GitHub

```bash
git clone https://github.com/bayramannakov/idea-method-cards.git ~/.claude/skills/idea-method-cards
```

## Usage

### Slash Command

```
/idea-method-cards
```

### Natural Language (Auto-Trigger)

The skill activates when you mention design methods, user research, workshop planning, design sprints, or related topics:

- "I need to plan user research for our new feature"
- "What design method should I use to understand our users?"
- "Help me plan a 3-hour workshop for my team"
- "Draw a random design method card"

## The 51 Methods

Organized across four categories:

| Category | Count | Focus |
|----------|-------|-------|
| **LEARN** | 12 | Analysis and synthesis of existing information |
| **LOOK** | 11 | Observation of people and contexts |
| **ASK** | 14 | Engaging with people directly |
| **TRY** | 14 | Prototyping and simulation |

## Examples

See the `examples/` directory for sample outputs:

- `discovery-sprint.md` — A 3-day discovery sprint plan
- `quick-validation-session.md` — A 2-hour validation session

## License

MIT
