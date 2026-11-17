I build practical software for real people: tradespeople, renters, learners, couples planning a wedding, small teams. Each project ships as a working product with a live demo, a test suite and a README that explains the problem it solves.

### Full-stack web apps · TypeScript, Next.js, AI

| Project | What it does | Try it |
|---|---|---|
| [say-voice](https://github.com/blackwingArtisan/say-voice) | Voice-to-invoice for tradespeople: say the job, get a PayPal invoice. A spoken price far from your own past invoices is flagged before it goes out. | [Live demo](https://say-voice.onrender.com) · [Video](https://youtu.be/eiHics6TfTc) |
| [pass-or-refund](https://github.com/blackwingArtisan/pass-or-refund) | Online courses that pay you back if they can't teach you. Claude grades against a public rubric; a second fail routes a PayPal refund to a person for approval. | [Live demo](https://pass-or-refund.onrender.com) · [Video](https://youtu.be/-HSBcMwgfaY) |
| [deposit-referee](https://github.com/blackwingArtisan/deposit-referee) | Security deposits on a PayPal hold. Claude compares check-in and check-out photos, the renter can contest, and the host approves each capture. | [Live demo](https://deposit-referee.onrender.com) · [Video](https://youtu.be/DxEgaxnYA4k) |
| [vendor-timeline](https://github.com/blackwingArtisan/vendor-timeline) | Wedding vendor payments: Claude reads each contract, a cash plan stays within what the contracts allow, and family members can pay vendors through PayPal. | [Live demo](https://vendor-timeline.onrender.com) · [Video](https://youtu.be/tR-ymoU2zgg) |

### Smart contracts · Rust

| Project | What it does | Try it |
|---|---|---|
| [leash](https://github.com/blackwingArtisan/leash) | On-chain spending limits for AI agents. The agent's key can only ask the contract to pay; allowlists, caps and a tripwire are enforced on-chain, where a prompt injection can't change them. | [Dashboard](https://blackwingartisan.github.io/leash/) · [Video](https://x.com/stubbornotterhq/status/2121694183538962781) |
| [rungs](https://github.com/blackwingArtisan/rungs) | Team bounty payouts where approval scales with payout size and earned reputation. Small payouts are instant; big ones go to a Sputnik DAO vote. | [Dashboard](https://blackwingartisan.github.io/rungs/) · [Video](https://x.com/stubbornotterhq/status/2121694438951158089) |

### Claude Code plugins · JavaScript, Node

| Project | What it does | Try it |
|---|---|---|
| [claude-content-kit](https://github.com/blackwingArtisan/claude-content-kit) | A Claude Code plugin for content marketing. One brand config drives social posts, emails and a content calendar; review agents and a format checker vet every draft, and a review dashboard keeps saved work across template upgrades. | [Real example output](https://github.com/blackwingArtisan/claude-content-kit/tree/main/examples/out) · [Install](https://github.com/blackwingArtisan/claude-content-kit#install) |

### How I work

- **Start from the user's problem.** Each README opens with who it's for and why it matters.
- **Guardrails in code.** AI suggests and explains; deterministic code enforces the rules, and a person makes the final call.
- **Tested.** Every repo has a test suite: roughly 300 to 390 tests in each TypeScript project, contract tests in each Rust one, and 62 tests plus browser checks in the Claude Code plugin.
- **Built with [Claude Code](https://claude.com/claude-code)**, with the tests and demos to show it works.
