# Forecast ledger

These are the dated forecasts from my newsletter, [jerrylieveld.substack.com](https://jerrylieveld.substack.com), and how each one turns out.

Each forecast goes in on the day its piece is published. The outcome, the dates or chance, the review and what would prove me wrong are quoted from the piece. The name of each forecast and any line marked "Note" are mine.

At the end of every quarter (March, June, September and December) I mark each open forecast as still open, hit or missed, with the evidence, and misses stay in. Some can only be settled on their own review date, such as an October count, so they stay open until then.

Every change is kept in the [history of this page](https://github.com/jml-2023/forecast-ledger/commits/main), so you can check when a forecast went in and that it hasn't been changed since.

A P50 is the date, or the count, by which I think the outcome is as likely as not, and a P80 the one by which I think it's four-in-five likely. Where a piece gives a chance instead of two dates, the row quotes that forecast, then shows its chance and the date it applies to. If I'm well calibrated, about half the forecasts with a P50 and a P80 will have come true by their P50 dates, and about four in five by their P80 dates. The same goes for chances: about seven in ten of the forecasts I give 70% should come true.

## Summary

7 forecasts: 7 open, 0 hit, 0 missed.

| ID | Forecast | From | Dates or chance | Status |
|---|---|---|---|---|
| [F-001](#f-001) | The duty spreads | [The design organisation in 2028](https://jerrylieveld.substack.com/p/the-design-organisation-in-2028), 15 November 2026 | P50 the October 2027 count; P80 the October 2028 count | open |
| [F-002](#f-002) | The job gets a name | [The design organisation in 2028](https://jerrylieveld.substack.com/p/the-design-organisation-in-2028), 15 November 2026 | P50 the October 2027 count; P80 the October 2028 count | open |
| [F-003](#f-003) | Design systems add agent-surface patterns | [The interface you never render](https://jerrylieveld.substack.com/p/the-interface-you-never-render), 15 November 2026 | P50 31 December 2027; P80 31 December 2028 | open |
| [F-004](#f-004) | Agent protocols ship per-tool reversibility and blast-radius routing | [Why "Are you sure?" modals fail agents: the reversibility matrix for speculative UI](https://jerrylieveld.substack.com/p/why-are-you-sure-modals-fail-agents), 19 November 2026 | P50 31 December 2027; P80 31 December 2028 | open |
| [F-005](#f-005) | Major API platforms cap reasoning tokens separately from visible output | [Why turning reasoning effort down rescued my flagship audit](https://jerrylieveld.substack.com/p/raising-reasoning-effort-broke-the-winner), 24 November 2026 | P50 30 June 2027; P80 31 December 2027 | open |
| [F-006](#f-006) | Agent harnesses ship cross-family review routing | [In, near, and out of the loop](https://jerrylieveld.substack.com/p/in-near-and-out-of-the-loop), 27 November 2026 | P50 30 June 2027; P80 30 June 2028 | open |
| [F-007](#f-007) | Coding harnesses gate context compaction on prompt-cache TTL | [Passed 19 of 19 tests — and made my agent 56% slower](https://jerrylieveld.substack.com/p/passed-19-of-19-tests-made-agent-56-percent-slower), 27 November 2026 | P50 31 December 2027; P80 30 June 2028 | open |

## Quarterly scorecards

The first scorecard is for the quarter ending 31 December 2026.

## The forecasts

### F-001

**The duty spreads.** From [The design organisation in 2028](https://jerrylieveld.substack.com/p/the-design-organisation-in-2028), published 15 November 2026. Status: open.

- Outcome: The share of design postings asking for either duty at least doubles: from 19.6% on 30 October 2026 to 39.3%, and from 17.8% to 35.7% without whichever company posts the most of them.
- P50: the October 2027 count
- P80: the October 2028 count
- Review: 30 October 2027, then every October
- Wrong if: The October 2028 count misses either threshold.
- Note: "Either duty" is judging what AI makes, or setting the rules it works to. The postings are those on the 80 public job boards the piece counts.

### F-002

**The job gets a name.** From [The design organisation in 2028](https://jerrylieveld.substack.com/p/the-design-organisation-in-2028), published 15 November 2026. Status: open.

- Outcome: At least 5 design postings on these boards have a title naming the work: evaluation or evals, quality, QA, guardrails, model or AI behaviour, or a design system for AI. None did on 30 October 2026.
- P50: the October 2027 count
- P80: the October 2028 count
- Review: With the first forecast
- Wrong if: The October 2028 count finds fewer than 5.
- Note: "These boards" are the 80 public job boards the piece counts. Reviewed with The duty spreads, from the same piece.

### F-003

**Design systems add agent-surface patterns.** From [The interface you never render](https://jerrylieveld.substack.com/p/the-interface-you-never-render), published 15 November 2026. Status: open.

- Outcome: At least two of six major public design systems — IBM Carbon, GOV.UK, USWDS, Apple HIG, Shopify Polaris, or Stripe's public design/docs system — publish an explicit pattern or specification for agent-consumed / headless product surfaces alongside human screens.
- P50: 31 December 2027
- P80: 31 December 2028
- Review: 31 December 2027
- Wrong if: Fewer than two of those six have published one by 31 December 2028.
- Note: Checked against the public documentation of those six named design and developer systems.

### F-004

**Agent protocols ship per-tool reversibility and blast-radius routing.** From [Why "Are you sure?" modals fail agents: the reversibility matrix for speculative UI](https://jerrylieveld.substack.com/p/why-are-you-sure-modals-fail-agents), published 19 November 2026. Status: open.

- Outcome: At least two of six major agentic developer or protocol ecosystems — Model Context Protocol (MCP), Anthropic Claude Code, OpenAI Codex, Cursor, GitHub Copilot, or Windsurf — ship a declarative per-tool reversibility and blast-radius field (beyond a single boolean readOnlyHint or destructiveHint) that UI clients use to route reversible workspace mutations into preview diffs without modal prompts while keeping hard confirmation on external calls.
- P50: 31 December 2027
- P80: 31 December 2028
- Review: 31 December 2027
- Wrong if: Fewer than two ship such schema-driven routing by 31 December 2028.
- Note: Checked against official public protocol specifications and client documentation of MCP, Claude Code, Codex, Cursor, GitHub Copilot, and Windsurf.

### F-005

**Major API platforms cap reasoning tokens separately from visible output.** From [Why turning reasoning effort down rescued my flagship audit](https://jerrylieveld.substack.com/p/raising-reasoning-effort-broke-the-winner), published 24 November 2026. Status: open.

- Outcome: At least two of four major API platforms — OpenRouter, Anthropic, OpenAI, or Google Vertex/AI Studio — expose a documented request parameter that caps reasoning tokens, where reasoning tokens do not count against the visible-output cap (so a reasoning burst cannot shorten the visible answer).
- P50: 30 June 2027
- P80: 31 December 2027
- Review: 30 June 2027
- Wrong if: Fewer than two of those four expose such a parameter by 31 December 2027.
- Note: Checked against official public API request documentation of OpenRouter, Anthropic, OpenAI, and Google Vertex/AI Studio.

### F-006

**Agent harnesses ship cross-family review routing.** From [In, near, and out of the loop](https://jerrylieveld.substack.com/p/in-near-and-out-of-the-loop), published 27 November 2026. Status: open.

- Outcome: At least two of five major coding/agent harnesses — Anthropic Claude Code, OpenAI Codex, Cursor, GitHub Copilot, or Google's developer agent tooling — ship built-in configuration for cross-family review routing.
- P50: 30 June 2027
- P80: 30 June 2028
- Review: 30 June 2027
- Wrong if: Fewer than two of those five ship it by 30 June 2028.
- Note: Requires configuration-level cross-family reviewer routing rather than prose prompt advice.

### F-007

**Coding harnesses gate context compaction on prompt-cache TTL.** From [Passed 19 of 19 tests — and made my agent 56% slower](https://jerrylieveld.substack.com/p/passed-19-of-19-tests-made-agent-56-percent-slower), published 27 November 2026. Status: open.

- Outcome: At least two of four major coding-agent harnesses — Anthropic Claude Code, OpenAI Codex, Cursor, or OpenCode — gate automatic context compaction or tool-output pruning on upstream prompt-cache TTL state (delaying history rewrites while a prefix cache is warm, unless approaching the context-window ceiling).
- P50: 31 December 2027
- P80: 30 June 2028
- Review: 31 December 2027
- Wrong if: Fewer than two implement cache-TTL-aware compaction by 30 June 2028.
- Note: Checked against official public documentation and source releases of Claude Code, Codex, Cursor, and OpenCode.

---

Views are my own, not my employer's.
