# Source Intelligence Navigator

**Know where to look. Know what the source actually proves.**

An AI skill for turning a field or research question into a small, reusable map of trustworthy sources. It builds a question-to-source router instead of handing you a giant reading list.

```text
Question → Best source → Relevant section → Supported answer
               ↓                               ↓
         Fallback / gap ← Saved route + refresh trigger
```

## What it helps with

- Learn the shape of a field without collecting endless links.
- Separate overview, controlling, operating and current-status sources.
- Map recurring questions to the first useful source and fallback.
- Track inspected, supplied, unread and inaccessible evidence separately.
- Preserve successful searches and know when old answers need rechecking.
- Explain conflicts by version, applicability and authority.

## Install and try

Download this repository and copy the **`source-intelligence-navigator` folder** into `~/.codex/skills/`. Use a new session if your host has already loaded its skill list.

```text
Use $source-intelligence-navigator to help me learn database backups.
I need to understand the core concepts and find the right references
for my database version. Keep the source stack small.
```

```text
Use $source-intelligence-navigator to turn these supplied documents
into a question-to-source router. Label anything you cannot verify.
```

Start with [the synthetic worked example](examples/worked-example.md). The [expert-pack template](source-intelligence-navigator/assets/EXPERT_PACK.template.md) is included; it is not a mandatory long report.

No script, account or paid API is required. Live checking requires a host with browsing/source access. Other hosts can read the skill instructions and resources, but automatic integration and cross-host discovery have not been tested.

## Better evidence, fewer false claims

An unread link is not a verified source. A search snippet is not the full document. A credible source may be wrong for your version or jurisdiction. The skill records those distinctions and stops when the questions have adequate coverage or visible gaps.

Optional: use the router inside [Project Book](https://github.com/rarora2414/project-book) or alongside [Job Application Sprint](https://github.com/rarora2414/job-application-sprint). Each skill works independently; links do not install automatic sync.

## Privacy and limits

Do not publish your private reference packs or source contents with this reusable skill. Save only when requested. Local files may still be processed by your AI provider. This skill does not confer professional qualifications or guarantee source completeness, correctness or time savings.

This is a **0.1.0 public edition**. See [validation and limits](VALIDATION.md). Useful corrections and examples are welcome; redact private information before opening an issue.

## License

[MIT](LICENSE) · Copyright © 2026 Aurora Product Systems.
