# Synthetic example: where should a new contributor look?

This example uses fictional documents supplied in the request. It demonstrates routing, not verified facts about a real product. No web access is assumed.

## Request and supplied evidence

“I need to add CSV export to SampleTool v2. Which sources should I read? Keep it small.”

Supplied materials:
- Getting Started v2 §1: explains what a SampleTool command is.
- Export Specification v2 §4: an export must preserve field order and quote commas.
- Contributor Guide v2 §3: run the CSV fixture checks before requesting review.
- A community post about v1: claims column order may change.
- A live v2 changelog URL mentioned but not accessible in this exercise.

## Compact expert pack

Goal: implement the v2 export contract and know which checks establish it.
Field map: command input → CSV serializer → fixture checks → review.

| Question | First route | Role / why | Verification and refresh |
| --- | --- | --- | --- |
| What is a command? | Getting Started v2 §1 | Anchor; establishes vocabulary | Supplied excerpt, not independently inspected |
| Must field order be preserved? | Export Specification v2 §4 | Controlling for this v2 change | Supplied excerpt; inspect full spec before implementation |
| How do I check my change? | Contributor Guide v2 §3 | Operating instructions | Supplied excerpt; inspect current guide before running checks |
| Has v2 behavior changed recently? | Mentioned live v2 changelog | Current status | Inaccessible; current status remains unverified |

The v1 community post does not override the supplied v2 specification. It is useful historical context only; if versions or authority were unclear, retain the conflict instead of picking a winner.

Next action: inspect the full v2 export specification and fixture guide when access is available. Use the current-status route before claiming the implementation matches the latest release. No claim of exhaustive research or a successful live fetch.
