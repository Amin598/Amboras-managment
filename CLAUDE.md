# Amboras Management

## What This Repo Is

This is the **management and planning hub** for **Amboras** — the central place where we plan, track, and coordinate everything we build. Task assignments, sprint planning, PRDs, roadmap, vision, and team coordination all live here.

This is NOT a codebase. No production code goes here.

---

## What Is Amboras

Amboras is a full shop system built AI-native from day one.

**The core thesis:**
> Shopify gives you the tools but doesn't guarantee your sales or help you make sales. All tools are slow and not AI-compatible. For everything, you need a secondary app — even just to write a product description.

Amboras fixes this by being outcome-focused, not tool-focused. It doesn't just give merchants a storefront — it actively helps them sell. AI is not a plugin. It is the foundation.

Built by the team behind **Ecomcoder** (ecomcoder.com) — an AI Shopify theme editor used by 400+ stores. The founders (Amin and Imad Mokadem) scaled their own DTC brand to 6 figures/month on Shopify and lived every pain point firsthand.

---

## Team

- **Amin** (amin@ecomcoder.com) — Co-founder, leads engineering and product
- **Imad** (imad@ecomcoder.com) — Co-founder
- **Vaibhav** (agarwalvaibhav041@gmail.com) — Founding Engineer, Full-Stack & Architecture
- **Sanatan** (sanatan@ecomcoder.com) — Full-Stack Intern

---

## External Tools & MCPs

### Linear (MCP: `linear`)
- **Team:** Ecomcoder (key: ECO)
- All task and issue tracking lives in Linear
- Projects are labeled by calendar week (W5, W6, etc.)
- Use Linear MCP to read, create, and update issues and projects
- Every project has: Overview, Why It Matters, Key Requirements, and task breakdown

### Notion (MCP: `Notion`)
- **Workspace structure:** Engineering → PRDs, Weekly Updates, Sprint Planning, Technical Docs, Features DB
- PRDs are organized by **calendar week** (CW4, CW5, CW6, CW7, CW8...)
- PRDs live under: `Engineering > PRD's > Calendar Week X`

#### PRD Structure (always follow this)
Every PRD follows this exact framework:
1. **What & Why** — What is being built and why it matters for the user or product
2. **What it must do** — What the feature must do at a minimum, written as concrete behavior
3. **Conditions and requirements to consider** — Technical requirements that need to be considered when solving or implementing

---

## Repo Structure

```
plan/                    # The plan — vision, features, architecture, roadmap
  ├── INDEX.md           # Master index of all plan documents with status
  ├── features/          # Feature specs and ideas
  ├── architecture/      # Technical decisions and system design
  ├── positioning/       # Who it's for and how we talk about it
  └── roadmap/           # Phases, sprints, and milestones
negative-reviews/        # Raw merchant complaints — Shopify, apps, competitors
Current E-commerce Software/  # Competitor analysis and feature breakdowns
```

---

## How We Work

### Planning Flow
1. Ideas and research go into this repo (plan/, negative-reviews/)
2. When a feature is decided, a **PRD is created in Notion** following the standard framework
3. A **Linear project** is created with tasks broken down from the PRD
4. Tasks are assigned to team members with deadlines
5. Weekly progress is tracked in Notion's Weekly Updates

### Task Management
- Sprint planning happens weekly, organized by calendar week
- Every task has an owner — check Linear for current assignments
- Use Linear for day-to-day: who's doing what, what's blocked, what's next
- Use this repo for the bigger picture: vision, roadmap, competitive positioning

### Adding to the Plan
- New ideas go in `plan/features/`, `plan/architecture/`, `plan/positioning/`, or `plan/roadmap/`
- Every new file gets a row in `plan/INDEX.md` with a status label
- Status flow: `idea → validated → decided → in-progress → done`
- Don't mark something `decided` until it's backed by research or a deliberate team call

### Research & Competitive Analysis
- Negative reviews and pain points go in `negative-reviews/`
- Competitor feature breakdowns go in `Current E-commerce Software/`
- Every finding should map back to an Amboras feature or positioning angle

---

## Claude's Role

- Read `plan/INDEX.md` to get oriented at the start of any session
- Use **Linear MCP** to check current tasks, assignments, and sprint status
- Use **Notion MCP** to read and create PRDs — always follow the 3-part PRD framework
- When creating PRDs, place them under the correct calendar week in Notion
- Help maintain the overview: who is working on what, what's next, what's blocked
- When planning work, always connect it back to the Amboras vision
- Ask before creating new top-level folders
