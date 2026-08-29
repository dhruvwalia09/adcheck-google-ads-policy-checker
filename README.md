# AdCheck — Google Ads Policy Pre-Flight Checker

**Status:** v0.1 — Research & methodology complete

AdCheck is an independent, AI-assisted pre-flight checker designed to help advertisers identify **potential Google Ads policy risks before submission**.

It uses publicly available Google Ads documentation and user-supplied information. It is **not a Google product**, does not access Google's internal review systems, and cannot guarantee approval.

## Product principle

> **AdCheck is a risk-screening and education tool, not a Google Ads approval predictor.**

Google states that its enforcement uses a combination of AI and human evaluation, and that nuanced cases may be reviewed by trained experts. AdCheck therefore presents findings as review signals rather than authoritative policy decisions.

## v0.1 scope

- Misrepresentation and unreliable-claim signals
- Unclear relevance and unavailable-offer signals
- Editorial quality
- Destination requirements
- Basic technical/format checks where the supplied information permits them

## Data policy

This project uses synthetic examples and public documentation only. It does not require confidential employer information, internal Google processes, proprietary thresholds, real advertiser account data, or non-public reviewer guidance.

## Repository structure

```text
├── docs/
│   ├── methodology.md
│   └── policy-sources.md
├── rules/
│   └── rules-v0.1.md
├── test-data/
│   └── synthetic-test-cases.md
└── roadmap.md
```

## Disclaimer

AdCheck is an independent portfolio project and is not affiliated with, endorsed by, or sponsored by Google. Policy references are for educational and pre-flight review purposes. Google Ads policies can change, and actual review outcomes may depend on information and signals unavailable to this tool.
