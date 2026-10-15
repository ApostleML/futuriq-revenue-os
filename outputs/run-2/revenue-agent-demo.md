# Revenue Agent Demo (run-2)

Coordinator: the main Claude Code session. This combines the four specialist outputs in this folder into one plan. Each agent ran separately, in runbook order, and worked only from `business-brief.md` and the run-2 files written before it. No earlier-run files were used.

| Phase | Agent | Output |
|---|---|---|
| 1 | market-signal-researcher (read-only, so the coordinator saved its brief) | `01-market-signal.md` |
| 2 | offer-architect | `02-offer-architecture.md` |
| 3 | content-angle-strategist | `03-content-strategy.md` |
| 4 | conversion-system-builder | `04-conversion-system.md` |

## The One-Sentence Offer (locked in phase 2)

I help solo coaches and consultants turn one business idea into a positioned offer, YouTube angles, a lead magnet, and a follow-up sequence in a single working session, without paying a strategist and copywriter or stitching together a dozen AI tools, by building a four-agent Claude Code revenue team.

### Offer-Sentence Contract check

Each location below was checked with an exact, character-for-character string match against the line under "### One-Sentence Offer" in `02-offer-architecture.md`.

| Where | File | Result |
|---|---|---|
| Hook, the whole hook at [0:00] | `03-content-strategy.md` | Exact match |
| Angle A (primary) rationale | `03-content-strategy.md` | Exact match |
| Lead magnet Promise | `04-conversion-system.md` | Exact match |
| Email 1 body | `04-conversion-system.md` | Exact match |

The chain held. Nothing broke between agents.

## 1. Market Signal (evidence and score)

- **Category:** AI-for-business-owners education that leads to a systems or template offer. Claude Code is the vehicle and the product is the revenue pipeline.
- **Strongest evidence [PUBLIC]:**
  - Subagents are an official, documented Claude Code feature.
  - The tutorials found are developer-oriented, and one search found none aimed at coaches or consultants. That is a gap signal from a single search, not proof.
  - A small paid Maven course suggests business owners will pay for this framing. This is a weak signal.
- **Audience:** skeptical-intermediate. They have chatted with AI, are tired of tool videos, and fear the terminal. They secretly hope someone hands them the system.
- **Opportunity score: 26 / 35**

| Category | Score |
|---|---|
| Urgency | 3 |
| Willingness to pay | 4 |
| Searchability | 3 |
| Clickability | 3 |
| Credibility | 4 |
| Business fit | 5 |
| Under-15-minute viability | 4 |

- **Top risks:**
  - Generic output.
  - Drifting into a tool tutorial.
  - Unproven revenue claims.
  - A wall of jargon.
  - A template that doesn't match what was shown.

## 2. Offer Architecture

- **Narrowed buyer:** solo coaches and consultants who sell their own expertise and want leads from YouTube.
- **Positioning:** not an AI tools tutorial. A four-agent Claude Code team, the Revenue Chain, run by the main session as coordinator. It turns one idea into a market read, an offer, YouTube angles, a lead magnet, a CTA and a follow-up sequence. The money is in the system, not the tool.
- **Mechanism guardrails shown on screen:**
  - One shared brief with written handoffs between agents.
  - Evidence labels that later agents can't upgrade from inference to fact.
  - The Offer-Sentence Contract.
- **Promised:** the asset pack. **Not promised:** leads, sales or revenue.

## 3. Content Strategy

- **Best title:** One Business Idea In, Full Offer System Out (Claude Code)
- **Backup titles:**
  - Build This AI Agent Team Before You Build Anything Else
  - Stop Using AI Like a Chatbot: Build a Revenue Team Instead
  - I Built a 4-Agent Claude Code Team So You Can Copy It
  - The AI System That Turns Your Expertise Into an Offer
  - You're Not Behind Yet: Your First AI Business System
- **Thumbnail:** ONE IDEA IN / 4 AGENTS, 1 SYSTEM / BUILD THIS FIRST / NOT ANOTHER TOOL / IDEA TO OFFER
- **Hook (word for word, about 20 seconds, the offer sentence alone):**
  > [0:00] I help solo coaches and consultants turn one business idea into a positioned offer, YouTube angles, a lead magnet, and a follow-up sequence in a single working session, without paying a strategist and copywriter or stitching together a dozen AI tools, by building a four-agent Claude Code revenue team.
- **Retention map, about 14:30:**

| Time | Segment |
|---|---|
| 0:00 | Hook |
| 0:20 | The idea and the problem ("the money is in the system" said here) |
| 1:30 | A subagent is a role file (folder shown once) |
| 3:00 | The brief and the chain |
| 4:00–11:30 | The four agents run in order, each output on screen |
| 10:45 | Split screen of the sentence in all four places |
| 11:30 | Honest limits, timer stopped |
| 12:30 | Template shown side by side with the demo folder |
| 13:30 | CTA |
| 14:15 | Close |

## 4. Conversion System

- **Lead magnet:** the Revenue Agent Template. It is the exact folder from the video, seven files:
  - the four agent files (market-signal-researcher, offer-architect, content-angle-strategist, conversion-system-builder)
  - a blank `business-brief.md`
  - the Revenue Agent runbook
  - a separate one-page setup guide for non-developers

  The offer file, the conversion file and the 12:30 shot all list these same seven files. Nothing held back and no fifth agent.
- **In-video CTA (13:30):** one link, a plain statement of the limits, and one conditional workshop mention ("if you would rather build this with me live").
- **Emails (days 0, 2, 4, 6, 9):**
  1. Deliver the folder and restate the promise.
  2. Run the chain in this order.
  3. How to tell if your output is generic.
  4. Why four specialists beat one big prompt.
  5. Build it with me live, including who it is not for, with a "reply build" option.
- **Sales path:**
  - Video
  - Template (email captured)
  - Activation emails
  - Workshop. Price band is a hypothesis to test: low-to-mid hundreds of USD.
  - Done-with-you build. High-ticket; offered by reply only until 2 to 3 real builds exist.

## Monetization Path

Video → free Revenue Agent Template → activation emails → live build workshop → done-with-you AI revenue systems build. Each rung extends the same system the viewer watched run, and none depends on an income claim.

## Coordinator Flags (fix before filming or sending)

1. **Agent count was corrected in phase 2.** The first offer draft said "five-agent" and invented two roles. The coordinator sent it back, and the locked sentence now says "four-agent", which matches `.claude/agents/`.
2. **Resolved: hook length.** The hook is now the offer sentence alone, about 20 seconds. The outcome line, the "here's what I do" lead-in and the closing line were cut. The "money is in the system" line moved to the 0:20 problem segment.
3. **Resolved: template contents.** The standard is seven files, including a separate one-page setup guide, and it is now the same in `02`, `04` and the 12:30 shot in `03`. The setup guide still has to be written before the template ships.
4. **The demo idea is a placeholder.** "A coach who helps first-time agency owners hire their first account manager" has not been run yet. Run it, and if the output reads generic, change the idea, not the claims.
5. **"Single working session" is unmeasured.** The estimate of about 60 to 90 minutes is a hypothesis. State only the elapsed time the on-screen timer actually shows.
6. **Workshop placeholders.** Emails 4 and 5 have [bracketed] title, date and link fields. Don't send them until the page exists, or switch Email 5 to a waitlist.
7. **Runbook and setup guide readiness.** Before giving the runbook away, check that it contains nothing internal. Write the one-page setup guide for non-developers, including the coordinator note that the main session saves the read-only researcher's output.
8. **Unvalidated demand data.** Search volume and competing videos were not checked. Validate the title against real search terms before locking it.
