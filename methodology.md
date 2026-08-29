# AdCheck Methodology v0.1

## 1. Objective

Translate selected public Google Ads policy requirements into practical pre-flight checks that an advertiser can run before submission.

## 2. Evidence hierarchy

Each rule is classified as one of:

- **Public requirement:** directly grounded in Google's public documentation.
- **Derived check:** an operational test created from a public requirement.
- **Quality enhancement:** an independent best-practice check that is useful but should not be presented as a Google policy requirement.

## 3. Result model

Each check returns one of:

- **PASS** — no issue identified from the supplied information.
- **REVIEW** — a potential risk or insufficient information requires human review.
- **FAIL** — the supplied information indicates a clear mismatch with the modeled requirement.
- **NOT ASSESSABLE** — the tool lacks enough information to make a meaningful determination.

## 4. Risk model

- **Low:** quality improvement or low-impact concern.
- **Medium:** meaningful risk that should be reviewed before submission.
- **High:** substantial potential policy concern or a clear mismatch with a public requirement.
- **Critical:** reserved for severe signals that may indicate serious deceptive or harmful behavior. The tool should not make an automated final enforcement decision.

## 5. Confidence

Every AI-assisted finding should carry confidence:

- Low
- Medium
- High

Confidence describes how strongly the supplied evidence supports the finding. It does not describe Google's likelihood of approving the ad.

## 6. Human-in-the-loop rule

AI may identify patterns, explain risks, and propose revisions. It must not represent an ambiguous finding as a confirmed Google policy violation. The user remains responsible for reviewing the original Google policy and deciding whether to edit or seek clarification.

## 7. Scoring

v0.1 intentionally avoids claiming that a numeric score predicts Google approval. If a health score is shown, it represents **AdCheck's internal risk-screening result only**.

Suggested presentation:

`AdCheck Review Status: REVIEW`

`Potential findings: 3`

`Highest risk: HIGH`

A numerical score may be added later after validation of the rule set and test cases.
