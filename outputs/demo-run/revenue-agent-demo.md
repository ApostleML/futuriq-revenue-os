# Revenue Agent Demo (demo-run): Leadership coaching for first-time engineering managers

Coordinator: the main Claude Code session. The runbook was run on a one-line idea instead of the root `business-brief.md`: "a leadership coaching program for first-time engineering managers." The coordinator wrote a short brief for it (`business-brief.md` in this folder), with every assumption marked [ASSUMPTION]. Each agent read only this folder.

| Phase | Agent | Output |
|---|---|---|
| 0 | coordinator | `business-brief.md` (demo brief) |
| 1 | market-signal-researcher (read-only, so the coordinator saved its brief) | `01-market-signal.md` |
| 2 | offer-architect | `02-offer-architecture.md` |
| 3 | content-angle-strategist | `03-content-strategy.md` |
| 4 | conversion-system-builder | `04-conversion-system.md` |

## The One-Sentence Offer (locked in phase 2)

I help first-time engineering managers hold their first underperformance conversation with a former peer within a week, without avoiding it or souring the relationship, by building a rehearsed, reviewed conversation runbook.

### Offer-Sentence Contract check

Each location was checked with an exact, character-for-character string match, limited to that section of the file, against the line under "### One-Sentence Offer" in `02-offer-architecture.md`.

| Where | File | Result |
|---|---|---|
| Hook (word-for-word script, 0:00–0:22) | `03-content-strategy.md` | Exact match |
| Angle rationale | `03-content-strategy.md` | Exact match |
| Lead magnet Promise | `04-conversion-system.md` | Exact match |
| Email 1 body | `04-conversion-system.md` | Exact match |

The chain held.

## 1. Market Signal

- **Evidence [PUBLIC]:**
  - Small academic studies treat the engineer-to-manager transition as a known hard part: Purdue (16 managers), BYU (220 managers), and an ASEE paper.
  - A crowded field of books and guides already exists, and "first 90 days" is the dominant, crowded framing.
  - No search volume, view or price data was found.
- **Audience:** technically advanced, new to people management, and skeptical of MBA or HR language. They want scripts and templates, not theory.
- **Opportunity score: 22 / 35**

| Category | Score |
|---|---|
| Urgency | 4 |
| Willingness to pay | 3 |
| Searchability | 3 |
| Clickability | 3 |
| Credibility | 1 |
| Business fit | 4 |
| Under-15-minute viability | 4 |

- **Biggest risk:** credibility. The coach is unnamed and has no stated proof. The plan is viable only if the coach supplies real background, or if the video leans on a process viewers can test themselves.

## 2. Offer Architecture

- **Narrowed to one scenario:** a new manager's first underperformance conversation with a former peer who now reports to them.
- **Buyer:** the individual manager. The employer path is deferred to a separate funnel.
- **Mechanism:** a six-step "debug the conversation" runbook:
  1. Reproduce the problem with observable facts.
  2. Define the expected bar.
  3. Script the first 30 seconds.
  4. Test the likely pushbacks.
  5. Rehearse out loud.
  6. Ship it with a follow-up date.

  It builds on the public Situation-Behavior-Impact feedback model. That attribution still needs checking. No AI angle is forced in.
- **Outcome promised:** a process outcome only. The conversation is held within 7 days of review, with written expectations and a follow-up date. There is no promise that the report improves or stays.

## 3. Content Strategy

- **Best title:** Your Old Teammate Now Reports to You. Do This First.
- **Thumbnail:** NOW THEY REPORT TO YOU / THE RUNBOOK / DON'T WING IT / SAY THIS FIRST / FORMER PEER?
- **Hook:** about 22 seconds. It opens on the viewer's situation, then the offer sentence word for word, then a bridge into the live build.
- **Retention map, about 11:45:**

| Time | Segment |
|---|---|
| 0:00 | Hook |
| 0:22 | Honest credibility moment [PLACEHOLDER] |
| 1:15 | Scope and limits |
| 2:00 | Hypothetical scenario |
| 2:30–9:15 | Steps 1–4 filled in live |
| 9:15 | Labeled role-play demonstration |
| 10:30 | The honest gap: rehearsal is the part a template can't do |
| 11:15 | CTA |

- **The "real build":** the runbook filled in on screen, labeled "Hypothetical scenario, not a client" throughout.

## 4. Conversion System

- **Lead magnet:** the Former-Peer Conversation Runbook (working name). It has three parts:
  - The blank six-section runbook, with the same fields as on screen.
  - The filled hypothetical example.
  - A 10-point readiness checklist, drafted for the coach to edit.

  A scope line on the opt-in page says the download is the half you can build alone.
- **In-video CTA (11:15):** about 30 seconds, one link, no price. It mentions once that the email has a link to rehearse with the coach.
- **Emails (days 0, 2, 4, 6, 9):**
  1. Delivery, the offer sentence, and "which pushback do you dread?", with a booking link in the P.S.
  2. Finish your opening.
  3. The part a template can't do.
  4. Fit, limits and reimbursement.
  5. No-pressure close.
- **Sales path:**
  - Video
  - Free runbook
  - Emails
  - Review and Rehearse session. Price hypothesis: $150–400.
  - A roughly 6-week 1:1 program later. Price hypothesis: $1,500–4,000.
  - Employer package as a separate path.

## Monetization Path

Video → free runbook template → 5 emails → paid Review and Rehearse session → 1:1 program. The free half (steps 1–4) is taught in full. The paid half is rehearsal and review of the viewer's own case, which a template can't do.

## Coordinator Flags (fix before filming or sending)

1. **Credibility is the blocker.** The 0:22 segment, the email sender and the opt-in page all need the coach's real name and background. If the coach has no experience yet, they must say "none yet". Nothing was invented.
2. **The "within a week" promise isn't delivered by the free download.** The sentence promises a rehearsed, reviewed runbook. The template covers only the part you build alone. The scope line in `04` handles this; keep it on the opt-in page and in Email 1.
3. **The checklist isn't shown in the video.** It's in the download as a quiet bonus, and the CTA doesn't promise it. Either show it briefly at 11:15 or accept it as an unannounced extra.
4. **The booking link must work on day 0.** The video promises "a link in the email". If booking isn't ready, delay the video or cut that line from the CTA.
5. **Check the SBI attribution** (Center for Creative Leadership) before naming it on screen.
6. **Placeholders to fill:**
   - coach name and background
   - scenario text
   - template name
   - checklist wording
   - prices
   - refund policy
   - booking link
   - scope and confidentiality statement
   - email consent wording and mailing address
7. **Demand is unvalidated.** Test the titles and scenario hooks against real search terms and competitor videos, and run a price test of 5–10 conversations before publishing any price.
8. **Fit note:** the market researcher pointed out that this is a career-risk play, not an "AI workflow to revenue" one. The system still produced a coherent revenue path. The agents' FuturIQ-specific instructions (AI, Claude Code) were set aside for this idea, as the coordinator instructed.
