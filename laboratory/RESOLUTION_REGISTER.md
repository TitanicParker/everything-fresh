# Resolution register

**Purpose:** maintain an append-only trail of candidate sentence resolutions, independent comparisons, revisions and abstentions. The original corpora are not annotated in place.

## Record schema

| Field | Meaning |
|---|---|
| Record ID | Unique, permanent analysis ID |
| Sentence ID | A-001…A-100 or B-001…B-100; use EXT-… for examples outside the corpora |
| Exact sentence | Verbatim source, or an immutable source link |
| Assay version | Version of the resolution instructions |
| Frozen Stage One | Governing demand, unfolding, decisive dependency, minimal Operative Centre, sufficiency |
| Stage Two | Transformation × Topology × Persistence; cell number and canonical name |
| Alternatives | Strongest one-axis rival and cross-pattern rival if relevant |
| Diagnostics | Counterfactuals and what they actually distinguish |
| Confidence/status | Candidate, contested, revised, abstained; uniqueness explicitly addressed |
| Provenance | Assessor, date, prompt, blind/nonblind conditions, original output link |
| Revision | Prior record ID, changed interpretation and rationale |

## Stewardship and permanent records

[Fresher stewardship and one-at-a-time write procedure](FRESHER_STEWARDSHIP.md). Each first-pass result must have a full immutable record at `laboratory/resolutions/{Sentence-ID}.md` **before** it is indexed here. The register, not chat history, is the queue and progress authority. Entries must link to the full record and report status, cell/rivals, version, assessor and date. Future changes are separately indexed revisions.

## Register

_No corpus sentence has been entered here yet. Existing exhibition examples in [the sentence laboratory](../10-sentence-laboratory.md) remain illustrative and are not silently promoted to independently verified corpus resolutions._

## Independent comparison

Record exact-cell agreement separately from dimensional agreement (Transformation, Topology, Persistence). Disagreement is evidence about reproducibility, not a reason to edit the frozen response.

See [workflow](../WORKFLOW.md).

## First-pass entries — 20 October 2026

The empty-register statement above is retained as the pre-stewardship historical checkpoint. The entries below are the appended live index.

| Record ID | Sentence / full record | Date / assessor | Assay version | Outcome | Rivals / confidence / uniqueness |
|---|---|---|---|---|---|
| FRESHER-A-001-2026-10-20-01 | [A-001 — complete resolution and diligence](resolutions/A-001.md) | 2026-10-20; Fresher / OpenAI Codex | Achieved-identity protocol, commit `69cbdfc6574278b7ebbeb9ee1acd4a2d011e83e5` | Candidate: **22 — Sequential link; Relating × Distributed × Standing**. Frozen Centre: morning sunlight reaches mountain villages substantially earlier than warmth reaches their own valleys; the achievement is that complete ordered configuration. | Nearest: **23 — Reciprocal shift; Relating × Distributed × Bearing**. Cross-pattern: 04 (05 also tested). Medium-high confidence in preference; exhaustive uniqueness not established. Diligence A-001-D1/D2 retained. Nonblind first persisted assay; no prior persisted revision. |

**Persistence provenance:** the full A-001 record was created first in [commit `4c4280c`](https://github.com/TitanicParker/everything-fresh/commit/4c4280c92417f6e3ec3ecc49dc60b232d0896f1b) and read back with exact content equality before this index update; verified record blob `035f53afede6b05e3ebee57134780eade50e2233`.

**First-pass progress:** 1/200 indexed. **Next target:** A-002. No other sentence was processed in this run. Later revisions must be separate records and appended index entries.
