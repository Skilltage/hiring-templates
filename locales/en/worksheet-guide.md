# Screening calibration

Templates and column explanations are available in four languages. CSV column keys remain English so files can be compared and imported consistently. Use worksheet-guide.md for the column meanings.

## screening-calibration.csv

| Column key | Meaning |
| --- | --- |
| `criteria_version` | Criteria version |
| `owner` | Owner |
| `review_date` | Review date |
| `criterion` | Criterion |
| `priority` | Priority |
| `expected_evidence` | Expected evidence |
| `synthetic_sample_id` | Synthetic sample ID |
| `reviewer_a_interpretation` | Reviewer A interpretation |
| `reviewer_b_interpretation` | Reviewer B interpretation |
| `disagreement` | Disagreement |
| `agreed_revision` | Agreed revision |
| `next_action` | Next action |
| `unresolved_question` | Unresolved question |
| `reopening_condition` | Reopening condition |

## vendor-comparison.csv

| Column key | Meaning |
| --- | --- |
| `vendor` | Vendor |
| `product_version` | Product version |
| `notes_complete` | Notes complete |
| `evidence_visibility_0_to_2` | Evidence visibility (0–2) |
| `uncertainty_0_to_2` | Uncertainty (0–2) |
| `human_control_0_to_2` | Human control (0–2) |
| `failure_handling_0_to_2` | Failure handling (0–2) |
| `data_answers_0_to_2` | Data-handling answers (0–2) |
| `claim_credibility_0_to_2` | Claim credibility (0–2) |
| `not_observed_items` | Items not observed |
| `non_negotiable_zero` | Non-negotiable gate scored zero |
| `decision_and_follow_up` | Decision and follow-up |

Record product version, configuration, observed behaviour and retained evidence before scoring. Use 0 absent or adverse, 1 partial, 2 demonstrated. Mark unobserved questions as not observed and rerun; do not score them zero. Set non-negotiable gates before the demonstration. Vendor scores must never become candidate scores.

## code-sample-review.csv

| Column key | Meaning |
| --- | --- |
| `rubric_version` | Rubric version |
| `reviewer` | Reviewer |
| `review_date` | Review date |
| `candidate_ref` | Candidate reference (not a name) |
| `sample_description` | Sample description |
| `criterion` | Criterion |
| `notes` | Notes |
| `evidence_location` | Where in the sample the note comes from |
| `score_1_to_5` | Score (1–5) |
| `follow_up_question` | Follow-up question for the interview |

One row per criterion per reviewer. Write notes and evidence location before the score. Score independently, then compare; discuss differences of two or more. Scores prepare the interview and are not a hiring decision on their own.

[README](README.md)
