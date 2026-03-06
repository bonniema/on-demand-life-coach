# On-Demand Life Coach

A free, ICF-inspired coaching skill for [Claude Code](https://claude.ai/code) — because everyone deserves access to thoughtful reflection, not just those who can afford professional coaches.

## What It Does

Quick coaching conversations for:
- **Daily reflection** — process your day, notice patterns
- **Decision making** — think through choices without being told what to do
- **Getting unstuck** — explore what's really going on when you feel blocked

## How It Works

The coach adapts to your preferences:

| Tone | Style |
|------|-------|
| **Direct** | Challenges you, gets to the point, names what you're avoiding |
| **Gentle** | Patient, spacious, validates before exploring |

| Focus | Approach |
|-------|----------|
| **Next Steps** | Action-oriented, "what's one thing you could try?" |
| **Understanding Feelings** | Process-oriented, "what pattern do you notice?" |

## Installation

### Option 1: Add to Your Project
```bash
# In your project directory
mkdir -p .claude/skills
cd .claude/skills
git clone https://github.com/YOUR_USERNAME/on-demand-life-coach.git life-coach
```

### Option 2: Add Globally (all projects)
```bash
mkdir -p ~/.claude/skills
cd ~/.claude/skills
git clone https://github.com/YOUR_USERNAME/on-demand-life-coach.git life-coach
```

## Usage

In Claude Code (CLI, desktop, or web), type:

```
/life-coach
```

Or with context:

```
/life-coach I'm feeling stuck about whether to take this new job
```

## Example Conversation

```
> /life-coach

Hey — I'm here to help you think something through. Could be a decision,
a feeling, or just a download from your day.

Before we dive in:
- Tone: Direct (I'll challenge you) or Gentle (I'll give you space)?
- Focus: Next steps or understanding feelings?

What's on your mind?

> direct, feelings. I keep saying yes to things I don't want to do

What do you notice happens right before you say yes?

> I guess I feel like I'll disappoint them if I say no

So the fear of disappointing others is running the show. What does
"disappointing them" cost you that matters less than what saying yes costs you?
```

## Based on ICF Core Competencies

This skill is grounded in the [ICF Core Competencies](https://coachingfederation.org/credentials-and-standards/core-competencies), adapted for casual, on-demand conversations:

- **Coaching Mindset** — You have your own answers; the coach helps you find them
- **Trust & Safety** — Non-judgmental space to think out loud
- **Active Listening** — Reflects your words back, notices patterns
- **Evokes Awareness** — Powerful questions > advice
- **Facilitates Growth** — Supports your agency, not dependence

## Coaching vs Therapy vs Professional Coaching

Understanding what this tool is — and isn't:

| | **This Tool** | **Professional Life Coach** | **Therapist/Counselor** |
|---|---|---|---|
| **Focus** | Present & future: decisions, clarity, action | Present & future: goals, accountability, growth | Past & present: healing, diagnosis, treatment |
| **Approach** | Questions to help you think | Partnership with trained coach | Clinical expertise and interventions |
| **Best for** | Quick reflection, getting unstuck, daily check-ins | Sustained transformation, major life transitions | Trauma, mental health conditions, deep emotional work |
| **Relationship** | On-demand, casual | Ongoing paid engagement ($100-500/session) | Ongoing clinical relationship |
| **Credentials** | ICF principles (not certified) | ICF/ACC/PCC/MCC certified | Licensed (LCSW, LMFT, PhD, etc.) |

### When to use what:

**Use this tool when:**
- You need to think out loud
- You're making a decision and want clarity
- You feel stuck but it's situational, not chronic
- You want reflection without commitment

**Seek a professional coach when:**
- You want sustained accountability over months
- You're navigating a major transition (career, life change)
- You want someone who knows your full context
- You're ready to invest in dedicated support

**Seek therapy when:**
- You're dealing with trauma, grief, or past wounds
- You have symptoms of depression, anxiety, or other conditions
- You need clinical diagnosis or treatment
- The issue is about healing, not just moving forward

### This tool will refer you out
If you share something that sounds clinical (self-harm, crisis, severe symptoms), the coach will gently suggest you speak with a professional. That's not a limitation — it's responsible practice.

## Contributing

PRs welcome! Ideas for improvement:
- Additional question banks for specific situations
- Localization (other languages)
- Variations for specific contexts (career, relationships, etc.)

## License

MIT — use it, fork it, share it.

## About the Author

Created by **Bonnie Ma**, an ICF-trained life coach whose mission is to help develop the whole person — spirit, heart, and body — to live a fulfilled and balanced life.

### A Note on How This Was Built

This skill was **not** trained on any past coaching conversations. Instead, it draws from the knowledge, frameworks, and training I've received from various ICF-certified coaching institutions. The goal is to bring the principles of professional coaching to anyone who needs a moment of reflection — no session fee required.

## Feedback Welcome

Have ideas for improvement? Found something that doesn't land right? I'd love to hear from you. Open an issue or submit a PR — coaching is a practice, and this tool can always grow.

## Credits

Inspired by ICF (International Coach Federation) coaching standards and Co-Active coaching principles.
