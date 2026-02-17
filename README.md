# Daimon

**The Personal AI Conscience for the Agentic Era**

> *Socrates described his daimon as an inner voice — a personal spirit that warned him when he was about to make a mistake. Not a god. Not a demon. A quiet, persistent guide that knew him well enough to say: "Stop. Think. That's not who you are."*

> *That's what's missing from the AI agent revolution.*

---

## The Problem No One Is Solving

Personal AI agents are here. They book your flights, draft your emails, manage your calendar, trade on your behalf, and speak in your voice across social media. They're fast, capable, and increasingly autonomous.

They also have no idea who you are.

When you tell an agent "go find me a good deal on bitcoin," it doesn't know that you're risk-averse with money. It doesn't know you'd be horrified if it scraped public records to find an edge. It doesn't know that your employer has a social media policy, or that your mother follows you on Twitter, or that you're three months into a plan to get out of debt.

The agent just executes. And the downstream consequences — financial exposure, PII leakage, reputational damage, legal risk — cascade silently until the damage is done.

This isn't a story about rogue AI. This is about *perfectly functioning* agents operating without conscience. The agent did exactly what you asked. The problem is that no one — not you, not the agent — thought through what that request actually meant in the full context of your life.

The prevailing response is "slow AI down." We think the better response is: **give AI a conscience.**

## What Is Daimon?

Daimon is an open-source framework for building a **personal AI conscience** — a dedicated agent whose sole purpose is to understand you deeply enough to protect you from the agents acting on your behalf, from your own blind spots, and from the increasingly complex digital landscape that no individual can fully comprehend alone.

Think of it as the digital equivalent of a celebrity's inner circle: personal assistant, security detail, public affairs advisor, and reputation manager — rolled into a single AI layer that sits between you and every agent, communication, and decision in your digital life.

Daimon doesn't replace your agents. It doesn't slow them down unnecessarily. It provides the *contextual understanding* they lack — your values, your boundaries, your goals, your risk tolerances — and intervenes only when something doesn't fit.

## The Optimal Character Framework

At the core of Daimon is a model we call your **Optimal Character** — a living, evolving representation of who you are and who you're working to become.

### Two Baselines

Most people don't fully know themselves. They have a rough sense of their values and a vague aspiration toward someone they'd like to be. Daimon makes both of these concrete and trackable:

- **Descriptive Self** — Who you actually are, derived from behavioral observation, communication patterns, decision history, and honest self-assessment. This isn't a judgment. It's a mirror.

- **Aspirational Self** — Who you say you want to be. Your stated values, goals, risk tolerances, and ideals. The person you'd describe if someone asked "what kind of person are you?"

The *gap* between these two is where Daimon operates. Not to judge either version of you, but to make the gap visible — so you can consciously decide how to close it.

### Calibrated Onboarding

Daimon starts with a structured questionnaire designed to establish a **conservative baseline**. The principle: start restrictive, let the user loosen deliberately. This is safer than the alternative — starting open and hoping the user thinks to tighten.

The questions are scenario-based, not abstract. They force the user to confront permissions and boundaries they'd never consider until an agent just *does something*:

- *"Would you trust AI to predict your needs and make purchases on your behalf?"*
- *"Do you believe AI currently understands your values well enough to communicate with your employer? Your family? Your social media followers?"*
- *"On a scale of 1-10, how concerned are you about your location being publicly discoverable?"*

Each question is designed to reveal a boundary the user hasn't thought about. The cumulative result is an initial risk profile that errs toward caution — a foundation that Daimon refines over time through observation and ongoing dialogue.

### Conflict Resolution: The Analogy Engine

People change their minds. People are also inconsistent. Daimon needs to handle both without being preachy, paternalistic, or annoying.

When Daimon detects an incongruence — between your stated values and your behavior, between what you asked your agent to do and what your profile says you'd actually want — it follows a simple protocol:

1. **Surface the incongruence** through an analogy that characterizes the conflict in plain, relatable terms. Not a warning. Not a lecture. A mirror held up clearly.

2. **Present a Model A / Model B choice.** Two concrete framings of how to resolve the conflict. The user picks one.

3. **Update the Optimal Character.** The user's choice feeds directly back into the profile, refining Daimon's understanding for next time.

This mechanism keeps the user in control at all times. They're never overridden — just asked to be intentional. And every interaction makes the model smarter.

The same mechanism handles the "changing your mind" problem. If you genuinely want to update your values, Daimon surfaces the change, confirms it's deliberate, and adapts. No friction. But if you're acting against your own stated goals without realizing it, Daimon catches that too — and asks you to choose consciously.

## Three Tiers of Protection

### Tier 1: Agent Conscience
The most urgent layer. Daimon monitors the agents acting on your behalf — reviewing their intended actions against your Optimal Character before execution. Like a live broadcast delay, where the producer can catch something harmful before it airs.

An agent drafting an email in your name that doesn't match your communication style? Flagged. An agent about to execute a financial transaction that conflicts with your debt-reduction goal? Paused for your review. An agent querying public records in ways that expose your PII? Blocked.

The agent still does the work. Daimon just makes sure the work is *yours*.

### Tier 2: User Self-Awareness
The digital landscape is too complex for any person to fully grasp their own exposure. Daimon monitors the user's own behavior — across email, social media, text, financial transactions, and application usage — and flags patterns the user can't see from inside their own life.

This isn't surveillance. It's the mirror function of the Optimal Character. You told Daimon you want to be financially disciplined, but you've made three impulse purchases this week. You said reputation matters, but your last five tweets were increasingly combative. Daimon surfaces these patterns — not to scold, but to make the invisible visible.

### Tier 3: Extended Authority
Many users manage others — employees, family members, contractors — and bear responsibility for their actions. They may also manage multiple AI agents across different platforms.

Daimon allows the user to extend their Optimal Character as a governance framework across their sphere of responsibility. A parent can establish a "Safe Explorer" profile for family devices and agents. A manager can propagate brand-aligned communication standards to team-managed bots. The responsible party's values become a guardrail — not a cage — for those under their authority.

## The Full Stack: What Daimon Watches

Daimon's value comes from **correlation across domains**. A phishing email combined with an unusual network probe looks different than either event in isolation. An agent's financial transaction looks different when cross-referenced against the user's stated goals.

The full scope of Daimon's awareness:

- **Communications** — Email, text, social media (inbound and outbound), screened through the Optimal Character before transmission or response
- **Agent Activity** — All directives issued to personal AI agents and their downstream actions
- **Financial Behavior** — Transactions, subscriptions, and spending patterns evaluated against stated financial goals
- **Network Presence** — Public data exposure, social graph activity, mentions and references across the web
- **Device and Infrastructure** — Network activity, application behavior, and IoT device status for anomaly detection

The key insight: threats and risks don't respect domain boundaries. Neither should your defense.

## Future Vision

Daimon's architecture opens possibilities that extend well beyond personal use.

### Optimal Character Libraries
If an Optimal Character profile can be built, it can be shared. Imagine open-source repositories of curated character profiles — archetypes that represent different value systems, risk postures, and ethical frameworks.

A user who isn't sure where to start could adopt a baseline profile and tailor it. Communities could publish shared standards. Organizations could distribute compliance-aligned profiles. The Optimal Character becomes a portable, composable, human-defined governance layer for AI behavior.

### Infrastructure-Level Defense
Today's operating systems and applications weren't designed for a world where AI agents act autonomously on behalf of users. Future systems could be.

Consider dynamic port management — where applications and the OS collaborate to shift network attack surfaces in real time, keeping exposure windows minimal and unpredictable. Application frameworks could be built with dynamic defense engines as a first-class concept, not bolted on after the fact.

Daimon envisions a future where the defensive posture of a user's entire hardware and software stack is continuously shaped by AI that understands the user's actual risk profile. Port monitoring, anomaly detection, and adaptive configuration management — driven not by static rules but by a living model of what the user needs, when they need it, and what threats are relevant to them specifically.

These are not features of today's MVP. They are the direction of travel — and they become possible when you start with a deep model of the user rather than a generic threat database.

## The Argument for Building, Not Braking

The public conversation after every AI scare follows a predictable pattern: "slow this down." It's understandable. It's also the wrong response.

AI agents aren't going away. They're going to get more capable, more autonomous, and more deeply embedded in daily life. The question isn't whether people will use them — it's whether people will use them *without protection*.

Daimon's position is pro-acceleration with a conscience. Build the agents. Make them powerful. But also build the layer that ensures they serve the person they're supposed to serve — in a way that person would actually choose if they had the full picture.

That's what's missing. Not capability. Not regulation. *Conscience.*

## Project Status

Daimon is in active development. The concept and architectural foundations are established, and the first practical implementation layer is live.

**[openclaw-diamon](https://github.com/spanklitch/openclaw-diamon)** — The Diamon (Decision Diamond) framework is the practical infrastructure that makes Daimon possible. It provides a human-readable, machine-executable file format (DIAMON.md) for encoding values, decision heuristics, and prohibitions that any AI agent can reference. The OpenClaw reference implementation includes a parser, decision engine, memory curator, and validation workflow.

- **Daimon** describes *what* a personal AI conscience should do
- **Diamon** specifies *how* to encode the decision-making framework
- **openclaw-diamon** is the first working implementation

What comes next:
- Threat taxonomy: a structured catalog of specific harms that personal AI agents can cause
- Optimal Character specification: the data model, questionnaire framework, and conflict resolution protocol
- Interception architecture: how Daimon sits between agents and execution on a real system

## Get Involved

Daimon is an open-source project because the problem it addresses affects everyone. If this resonates with you — whether you're a security researcher, a behavioral scientist, an AI engineer, or just someone who's thought deeply about what it means to have AI agents acting in your name — we want your input.

See [CONTRIBUTING.md](CONTRIBUTING.md) for how to participate.

---

*Daimon is not a product of fear. It's a product of the recognition that the most powerful AI agents in the world are about to act on behalf of people who haven't fully thought through what that means — and that the answer isn't to stop building, but to build the conscience that's missing.*
