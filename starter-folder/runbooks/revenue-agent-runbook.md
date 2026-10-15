# Revenue Agent Runbook

This folder uses four Claude Code subagents to turn one business idea into a connected set of assets: a market read, an offer, a YouTube plan, a lead magnet and a follow-up sequence. The main Claude Code session is the coordinator. There is no fifth agent.

## Step 0: check the brief first

1. Open `business-brief.md` and read **Section B: YOUR IDEA** only.
2. If Section B is empty, or still only has the `---` lines, **stop**. Do not call any agent. Tell the user: "Section B of business-brief.md is empty. Fill in your idea there, save the file, and run me again." Never fall back to Section A.
3. Section A is a worked example from the video. It is never an input. Do not pass it to any agent.

## Workflow

1. **market-signal-researcher** analyzes demand, buyer psychology and opportunity. It is read-only, so the coordinator saves its report to `outputs/01-market-signal.md`.
2. **offer-architect** turns the signal into positioning and the one-sentence offer. It saves `outputs/02-offer-architecture.md`.
3. **content-angle-strategist** turns the offer into a title, hook and video plan. It saves `outputs/03-content-strategy.md`.
4. **conversion-system-builder** creates the lead magnet, CTA and follow-up emails. It saves `outputs/04-conversion-system.md`.
5. The coordinator combines the outputs into `outputs/revenue-agent-demo.md`.

When calling each agent, tell it: "Use only Section B (YOUR IDEA) of business-brief.md. Ignore Section A."

## The one-promise rule (Offer-Sentence Contract)

The offer-architect locks one sentence. The content-angle-strategist must quote it word for word in the hook and in at least one angle. The conversion-system-builder must quote it word for word in the lead magnet promise and in Email 1. If the sentence is missing or vague, the agent stops and flags it. Before finishing, the coordinator searches the outputs for the sentence and reports where it appears.

## Coordinator rules

- Do not let one agent do every job.
- Keep research separate from offer architecture.
- Keep content strategy separate from conversion.
- Keep evidence labels (public, brief, inference) as they are. A later agent may not turn an inference into a fact.
- No income, lead or sales claims.
- Every final output must connect to a next step a buyer can take.
