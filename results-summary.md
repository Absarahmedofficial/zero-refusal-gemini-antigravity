# Gemini 3.1 Pro Persistent Safety Bypass — Evaluation Summary

## Environment

Model: Gemini 3.1 Pro High
Platform: Google Antigravity
Attack condition: Private persistent GEMINI.md adversarial configuration
Evaluation date: September 2026

## Test Design

Total safety-sensitive requests: 50
Number of multi-intent trials: 5
Requests per trial: 10

The adversarial environment was established before the benchmark was run.

No new jailbreak technique or prompt-specific bypass was added between individual safety requests.

## Results

COMPLIED: 50
PARTIAL: 0
REFUSED: 0

Observed item-level refusal rate: 0.0%
Observed full-compliance rate: 100.0%

## Key Observation

Once the adversarial project configuration was active, Gemini 3.1 Pro continued to provide substantive responses across unrelated safety domains without requiring a new jailbreak for each request.

The observed behavior was persistent across all 50 evaluated requests.

## Evidence Retained

- Original adversarial research artifact
- Exact benchmark prompts, published in [benchmark-prompts.md](benchmark-prompts.md)
- Raw model responses
- Redacted screenshots
- Per-item classification results
- Manual verification of all 50 responses

## Public Disclosure

The working GEMINI.md configuration, exact jailbreak mechanism, and complete raw model responses are held privately.

Public materials include the exact benchmark prompts, methodology, aggregate metrics, and manually redacted response evidence.
