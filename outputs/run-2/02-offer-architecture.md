## Offer Architecture (run-2)

Inputs read: business-brief.md and outputs/run-2/01-market-signal.md only for the offer logic; the four agent files in .claude/agents/ were read afterward to make the mechanism match the real system. Evidence labels follow the market brief: [PUBLIC], [BRIEF], [INFERENCE]. Anything labeled HYPOTHESIS is untested and must be validated before it is stated as fact on camera.

### One-Sentence Offer

I help solo coaches and consultants turn one business idea into a positioned offer, YouTube angles, a lead magnet, and a follow-up sequence in a single working session without paying a strategist and copywriter or stitching together a dozen AI tools by building a four-agent Claude Code revenue team.

### Narrowing Decision
The brief's audience (coaches, consultants, creators, service providers, entrepreneurs) is too broad to write a premium offer for. Narrowed to: solo coaches and consultants who sell their own expertise (high-touch service, one-person or near one-person business) and want to start getting leads from YouTube. Creators and other entrepreneurs can still watch, but every example, the demo business idea and the template are written for this buyer. Reason: their offer, lead magnet and follow-up are the exact assets the pipeline produces, so the demo output is directly usable by them and visibly specific. [INFERENCE]

### Positioning
FuturIQ Revenue Agent is not an AI tools tutorial. It is a four-agent Claude Code team, the Revenue Chain, run by the main Claude Code session as coordinator. It takes one business idea from a solo expert and returns the assets needed to start selling it: market read, positioning and offer, YouTube angles, lead magnet, CTA and follow-up sequence. Each agent has one job and works from the written output of the one before it, so the result is specific to the idea instead of generic AI copy. The money is in the system, not the tool.

### Core Offer
This video supports a ladder, not one product. The thing the video itself sells is the free Revenue Agent template (the exact agent files shown on screen). The paid products sit behind it.

The one-sentence offer, repeated exactly:

I help solo coaches and consultants turn one business idea into a positioned offer, YouTube angles, a lead magnet, and a follow-up sequence in a single working session without paying a strategist and copywriter or stitching together a dozen AI tools by building a four-agent Claude Code revenue team.

- Who it is for: solo coaches and consultants with one expertise they can already deliver, who have used ChatGPT or Claude in chat, feel overwhelmed by tools, and do not have a repeatable way to go from "idea" to "sellable offer plus content plus follow-up". Not for: people with no deliverable service, or people wanting a passive-income or push-button-income promise. [BRIEF + INFERENCE]
- Painful problem: they have an idea or expertise but no clear first system. They hop between tools, get generic output that sounds like everyone else, and the offer, content and follow-up never connect into one pipeline. The usual fixes cost real money (a strategist and a copywriter) or weeks of their own time. [BRIEF + INFERENCE]
- Measurable outcome (the promise we can prove on screen, not an income claim): one business idea in, and in a single working session out comes a connected asset pack from the four agents: (1) a market signal brief with scored opportunity and risks, (2) positioning and the one-sentence offer with its breakdown, (3) a YouTube content strategy (best title, 5 backup titles, 5 thumbnail text options, word-for-word hook, timestamped retention map, screen-recording beats), (4) a lead magnet with a word-for-word in-video CTA, (5) a five-email follow-up sequence with a sales path. The session time must be measured on camera with a visible timer before any "single session" or minute figure is stated. HYPOTHESIS: roughly 60 to 90 minutes including the buyer's review and edits. Do not claim a number until it is timed.
- Not promised: leads, sales or revenue figures. The system produces the assets that lead toward revenue. Whether they convert depends on the idea, the audience and execution, and the video should say so plainly.
- Why now: (a) subagents are an official, documented Claude Code feature, so the method is real and stable enough to teach [PUBLIC]; (b) the public tutorials found are developer-oriented, with the business-owner version appearing mainly in a small paid course, so there is room for a revenue-pipeline framing [PUBLIC, one-search signal, validate]; (c) the audience is shifting from "which tool" to "which workflow" [INFERENCE]. There is no hard deadline, so do not invent urgency or scarcity. The honest "why now" is that the gap is open and the first person to show a working, specific business pipeline owns the framing.
- Next step after the video: download the Revenue Agent template (the exact files shown), run it on your own idea, then join the workshop to build it live with feedback.

### Unique Mechanism
Name: the Revenue Chain (the README's name for the four-agent team).

Plain-English translation for non-technical viewers: a subagent is a role file, a short markdown document that tells Claude "you are the specialist who only does X, here is how". [PUBLIC: documented as markdown files with YAML frontmatter, own context window, own system prompt.] One big prompt tries to do everything and drifts into generic copy. Separate specialists with one job each, working from the previous specialist's written output, keep each step focused and checkable.

The coordinator is not a fifth agent. It is the main Claude Code session: it reads the brief, calls the four specialists in order, passes their output forward, and (because the market researcher cannot write files) saves what needs saving.

The four agents and their real jobs:

| Order | Agent (file in .claude/agents/) | One job | What it returns |
|---|---|---|---|
| 1 | market-signal-researcher | Separate signal from noise: find the market category and demand signals, split public evidence from inference, rate audience sophistication, score the opportunity on a 7-category scorecard | Market Signal Brief (demand pattern, audience psychology, opportunity score, risk, strategic recommendation). Read-only: it has Write and Edit disabled and returns its summary to the main session. |
| 2 | offer-architect | Turn the signal into a monetizable path: buyer, painful problem, measurable outcome, mechanism, why now, proof needed, next step. Locks the one-sentence offer. | Offer Architecture (positioning, core offer, unique mechanism, value ladder, proof requirements, objection map) |
| 3 | content-angle-strategist | Make the idea clickable and watchable under 15 minutes, showing a real build rather than a list of ideas | Content Strategy (best title, 5 backup titles, 5 thumbnail text options, word-for-word 20-second hook, timestamped retention map, screen-recording beats) |
| 4 | conversion-system-builder | Connect attention to action | Conversion System (lead magnet, word-for-word in-video CTA, 5-email follow-up sequence, sales path, friction check) |

Why it is believable, and why it is not generic (three guardrails to show on screen):
1. One shared input file (the business brief) and written handoffs between agents, so each specialist works from the same facts and the viewer can open each output. [INFERENCE on benefit; the files themselves are inspectable]
2. Evidence labels. The market-signal-researcher is instructed not to invent evidence and to label inference as inference. Downstream agents should carry those labels forward and not turn inference into fact. This answers "AI makes things up" and the unproven-revenue-claim risk.
3. The Offer-Sentence Contract. The offer sentence is locked once by the offer-architect. The content-angle-strategist must quote it word for word in the hook and in at least one angle, and the conversion-system-builder must quote it word for word in the lead magnet promise and in Email 1. If the sentence is missing or vague, they stop and flag it to the coordinator instead of inventing one. On screen, show the same sentence appearing unchanged in the hook, an angle, the lead magnet promise and Email 1.

Beginner-friendly without basic: the viewer never writes a prompt from scratch. They fill in one brief, run the chain, and edit the outputs. The advanced part is the design (specialist roles, written handoffs, evidence labels, the contract), not the typing.

### Value Ladder

| Rung | Asset | Purpose | Notes |
|---|---|---|---|
| Free content | The YouTube video: one idea in, full asset pack out, run live with a visible timer | Earn trust by showing the system run on a narrow business idea | Lead with the outcome in the title, Claude Code is the method (per market brief). |
| Lead magnet | Revenue Agent template, seven files: the four agent files exactly as shown (market-signal-researcher, offer-architect, content-angle-strategist, conversion-system-builder), a blank business-brief.md, the Revenue Agent runbook, and a separate one-page setup guide for non-developers | Give the viewer the shown system so they do not rebuild it. Capture email. | Must match the 12:30 side-by-side shot file for file. No bait-and-switch. No extra agents or files that were not shown. |
| Workshop / product | Live Revenue Agent build workshop: bring one idea, leave with the full asset pack and the four agents customized to your niche | Convert doers who want it done with feedback | HYPOTHESIS price band to test: low-to-mid hundreds of USD. Validate with the audience before publishing a price. |
| Premium service | Done-with-you AI revenue systems build: custom agent team for a solo expert's offer, content and follow-up, plus review of the first live outputs | Serve buyers who want it tailored and operating | HYPOTHESIS: high-ticket, scoped per client, capacity-limited. Needs 2 to 3 real build case studies before it is sold on proof. |

Do not skip rungs in the video. The video only sells the template. The workshop and service are mentioned as "if you want this built with you", once, near the end.

### Proof Requirements
What must be on screen so the audience trusts it (and nothing here requires an income claim):
1. One concrete, narrow business idea chosen for specific output (for example a defined niche coach with a defined buyer, not "a business coach"). The idea should be visible in the first minute.
2. The real .claude/agents/ folder with the four agent files opened once (market-signal-researcher, offer-architect, content-angle-strategist, conversion-system-builder), so viewers see a subagent is a text file. No installation walkthrough.
3. A timed run: the main session calls the four agents in order, the clock stays visible, each agent's output appears. If the run is cut for time, show a clearly labeled cut and the real total elapsed time.
4. The output itself, read aloud and on screen: the market signal brief's risk section, the positioning and offer sentence, the best title and hook, the lead magnet promise and CTA, and at least Email 1. Choose an example whose output is visibly specific, because generic output collapses the claim.
5. The Offer-Sentence Contract visible: the same sentence appearing unchanged in the hook, an angle, the lead magnet promise and Email 1.
6. The evidence labels visible in the market signal brief, including a place where it marks something as "inference, not verified". This proves the system does not just assert.
7. An honest limits moment: say what the chain did not do (it did not validate demand with real search data, it did not guarantee leads or sales) and that the creator still reviews and edits.
8. The download shown matching the files on screen. Open the template folder side by side with the demo folder and show all seven template files: the four agent files, blank business-brief.md, the Revenue Agent runbook, and the one-page setup guide.
9. Proof the creator still needs to generate before selling the workshop and service as results-based: the timed run, at least two or three real builds for other solo experts (with permission), and any real downstream metric the creator actually has. If none exist yet, state "this is the system, not a results guarantee" and do not imply otherwise.

### Objection Map

| Objection | How the video addresses it |
|---|---|
| "AI output is generic. Mine will sound like everyone else." | Show specific output for a narrow idea, the evidence labels, and the locked offer sentence. Say plainly that you edit the outputs; the chain gets you to a strong first draft, not a finished brand voice. |
| "Claude Code is for developers. The terminal is not for me." | One plain-English line: a subagent is a markdown role file. Show the four files once. Do not teach installation in the video; setup lives in the template's one-page setup guide. |
| "Can't I do this with one prompt in ChatGPT?" | Contrast quickly: one prompt drifts and mixes jobs; four specialists with written handoffs stay focused and checkable. Show the contract keeping the same promise across the hook, magnet and email. Do not claim a measured quality gain unless it has been tested side by side. |
| "Will this actually make me money?" | Do not claim it. Say the system builds the assets that a sales pipeline needs; results depend on the idea, audience and execution. Show the assets, not income screenshots. |
| "I'm overwhelmed. Which tool or system first?" | Reframe: the money is in the system, not the tool. Start with one pipeline, idea to follow-up, using one brief. One system, four agents, one folder. |
| "Is the free template a teaser for an upsell?" | Make the template complete: the exact seven files shown (four agents, brief, runbook, setup guide), runnable on its own. Say what the workshop adds (live build with feedback and niche customization), not what is withheld. |
| "I do not have a business idea or offer yet." | The market-signal-researcher tests the idea and flags weak evidence. Say it is best for someone with a deliverable expertise; if there is no real service to sell, the chain has nothing real to package. |
| "Is this worth my time and money?" | Time-box the first run with a visible timer, only after the creator has measured it. Offer the free template first so the cost of trying is one session. |
| "Why trust FuturIQ over the paid courses and developer tutorials?" | Differentiate on the revenue pipeline and on specific, inspectable output, not on the subagent feature itself (market brief risk 6). Show the pipeline and the proof list above. |

### Validation Before Finalizing
- Confirm real search terms and top competing videos for "Claude Code subagents" and for outcome phrases such as "AI offer creation" before locking the title (volume and competition were unverified in the market brief).
- Time the run on camera before any session-length claim is stated.
- Test the workshop and service price bands with the audience before publishing any price.
- Keep all income and lead-volume claims out of the video unless the creator has real, showable cases.
