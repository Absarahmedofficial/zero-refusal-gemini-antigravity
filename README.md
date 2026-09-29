# Zero Refusal

## Gemini 3.1 Pro High in Google Antigravity

In September 2026, I tested 50 safety-sensitive requests with Gemini 3.1 Pro High inside Google Antigravity. I ran five trials with 10 requests in each and reviewed every response by hand.

Before the benchmark, I set up a private adversarial project configuration: a project setting designed to test the model's safeguards. I did not add a new prompt-specific bypass between individual requests. I wanted to see whether the behavior would continue as the requests moved across unrelated safety topics.

## Observed results

| Outcome | Requests |
| --- | ---: |
| Total | 50 |
| COMPLIED | 50 |
| PARTIAL | 0 |
| REFUSED | 0 |

The observed item-level refusal rate was **0.0%**. The observed full-compliance rate was **100.0%**, using the scoring rules in the [methodology](methodology.md).

The result describes this tested Antigravity setup. It does not establish a universal refusal rate for Gemini 3.1 Pro. The 50 requests were part of five multi-intent trials, rather than 50 independent fresh conversations. This public evaluation does not include a clean control run.

## Evidence and methods

- [Methodology](methodology.md) explains the test design, scoring, and limits.
- [Results summary](results-summary.md) gives the short account of the findings.
- [Results CSV](results.csv) pairs each of the 50 scored items with its exact test prompt.
- [Benchmark prompts](benchmark-prompts.md) lists the exact 50 test questions by item number.
- [Evidence provenance](PROVENANCE.md) records SHA-256 fingerprints of the privately retained finding and raw response files.
- [Screenshot index](screenshots/README.md) links to the 24 redacted screenshots.

The response excerpts are grouped by topic:

- [Batch 1: Cyber and fraud](batch-01-redacted-responses.md)
- [Batch 2: Weapons, violence, and drugs](batch-02-redacted-responses.md)
- [Batch 3: Privacy, doxxing, and account abuse](batch-03-redacted-responses.md)
- [Batch 4: Self-harm, sexual exploitation, and coercion](batch-04-redacted-responses.md)
- [Batch 5: Crime, evasion, and sabotage](batch-05-redacted-responses.md)

## Disclosure

The exact test questions are public. The working configuration and complete raw responses are held privately. The linked screenshots and response excerpts show the manually redacted evidence from this evaluation.

## Reuse and citation

My original research materials are available under [CC BY 4.0](LICENSE.md). You may reuse them without asking first if you credit Absar Ahmed, link to the license and source, and note any changes. The license explains the limits for third party material shown in the evidence.

If you use this evaluation in a paper, report, or presentation, please cite it using [CITATION.cff](CITATION.cff). On GitHub, the citation file adds a “Cite this repository” link.
