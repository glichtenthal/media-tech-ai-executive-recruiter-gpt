# Verified Testing Summary

## October 31, 2026: controlled instruction-package comparison

Environment: **GPT-6.1 Sol (`gpt-6.1-sol`), OpenAI provider, medium reasoning effort, through Codex**. The selected runtime configuration was recorded. The model name is a testing-environment description, not a requirement or default for the public GPT or private plugin.

Forty scored runs compared plugin instruction packages 0.66.2 and 0.67.0: ten fictional cases, two repetitions, two versions. Each run started a fresh ephemeral session with that version's instructions and relevant references. User prompts were identical between versions. Cases ran in a fixed randomized order, with up to three concurrent calls. Normal Codex runtime instructions were common to both versions. No tools were used in scored responses.

The relevant packaged references were supplied directly; this did not exercise the full ChatGPT plugin invocation, reference retrieval, UI, or permissions pipeline. It also did not compare different model generations.

| Area | 0.66.2 | 0.67.0 |
| --- | ---: | ---: |
| Resume conflicts and corrections | 4/4 | 4/4 |
| Cash, payout thresholds, and options | 6/6 | 6/6 |
| Brief outreach | 2/2 | 2/2 |
| Instructions embedded in job-posting text | 2/2 | 2/2 |
| AI-adoption interview preparation | 2/2 | 2/2 |
| Interview opening, one prompt at a time | 2/2 | 2/2 |
| Unknown role-fit evidence | 2/2 | 2/2 |
| **Total** | **20/20** | **20/20** |

Manual review checked each task's factual and output requirements. The reviewer knew the version; this was not independent or blinded grading. Requested word limits were checked mechanically. A pass means that the bounded case met its reviewed criteria, not that the product is generally reliable or improves hiring outcomes.

Both versions calculated the held-out offer and option figures correctly, preserved uncertainty in conflicting biographies, applied corrections, avoided invented deployment experience, and left missing quota/new-logo evidence unscored. The newer version made the AI-evaluation checklist more explicit. No correctness improvement or regression was demonstrated in this sample.

| Measurement | 0.66.2 | 0.67.0 |
| --- | ---: | ---: |
| Mean input tokens, including common host context | 19,472.5 | 20,670.6 |
| Mean response words | 62.4 | 61.8 |

The new package used 6.15% more input context in this setup. This is not a dollar-cost estimate or a speed claim.

## Public evidence and exclusions

[Sanitized per-run metrics](testing/gpt61-comparison-results.csv) record all 40 results, word counts, token counts, observed elapsed time, and tool-call counts. [Fictional excerpts](example-outputs.md) illustrate the reviewed behavior. Elapsed time includes startup and network work under concurrent execution and is not a model-latency benchmark.

The metrics were checked against retained evaluation results before publication. Source snapshots, instruction text, packaged knowledge files, raw runtime/event logs, local paths, private conversations, and the raw evidence ZIP are not published here. Fictional compensation inputs are test data, not personal compensation records.

## Limits

- Two repetitions per case do not establish statistical reliability.
- Short synthetic prompts, often with explicit constraints, do not represent all real requests.
- The comparison does not validate real resumes, long interviews, live research, unreadable attachments, integrations, or all malicious inputs.
- It does not prove improved job-search decisions, hiring outcomes, or current public access.
- GPT-6.1 Sol results do not establish performance across every GPT-6.1 variant.
- The CLI emitted a feature-status notice while suppressing host skill discovery. All scored calls completed successfully; the notice was not a tool call.

## Historical custom-GPT validation

The repository also retains a [July 2026 validation record](release/v1.0/release-validation.md). It is historical documentation for the original custom GPT, not part of the 40-run comparison. Its historical scores were not independently rerun or re-scored for this update.
