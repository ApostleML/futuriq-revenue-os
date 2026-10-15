# FuturIQ Revenue Operating System

A four-agent Claude Code team ("The Revenue Chain") that turns one business idea into positioning, an offer, a YouTube video plan, a lead magnet and a 5-email follow-up.

## What's here
- `SETUP-GUIDE.md`: one-page, click-by-click Windows setup for non-developers. Start here.
- `business-brief.md`: who FuturIQ serves, the voice and the rules. Every agent reads it.
- `.claude/agents/`: the four specialist agents:
  1. `market-signal-researcher`: demand, buyer psychology, opportunity score
  2. `offer-architect`: positioning and the one-sentence offer
  3. `content-angle-strategist`: title, hook, 14-minute video plan
  4. `conversion-system-builder`: lead magnet, CTA, emails
- `runbooks/revenue-agent-runbook.md`: the order the agents run in, and the coordinator rules.
- `outputs/`: the results.
  - `final-video-brief.md`: **the one to film from**
  - `revenue-agent-demo.md`: first-pass combined plan
  - `01`–`04`: each agent's raw output

## How to run it
1. Open this folder in Claude Code. Restart Claude Code if it was already open, so the agents load.
2. Edit `business-brief.md` for your idea.
3. Tell Claude Code: "Run the Revenue Agent runbook on business-brief.md."

## Offer-Sentence Contract
Agents 3 and 4 must quote the offer-architect's one-sentence offer word for word, and flag it if it's missing. Search for that sentence in the outputs. If it's missing anywhere, the chain broke at that agent.
