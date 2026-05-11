# Afstemning af kriterier til CV-screening

Skabeloner og kolonneforklaringer findes på fire sprog. CSV-kolonnenavne forbliver på engelsk, så filerne kan sammenlignes og importeres ensartet. Brug worksheet-guide.md til at se kolonnernes betydning.

## screening-calibration.csv

| Kolonnenavn | Betydning |
| --- | --- |
| `criteria_version` | Kriterieversion |
| `owner` | Ansvarlig |
| `review_date` | Dato for gennemgang |
| `criterion` | Kriterium |
| `priority` | Prioritet |
| `expected_evidence` | Forventet dokumentation |
| `synthetic_sample_id` | ID for fiktivt eksempel |
| `reviewer_a_interpretation` | Vurdering fra person A |
| `reviewer_b_interpretation` | Vurdering fra person B |
| `disagreement` | Uenighed |
| `agreed_revision` | Aftalt ændring |
| `next_action` | Næste handling |
| `unresolved_question` | Åbent spørgsmål |
| `reopening_condition` | Betingelse for ændring |

## vendor-comparison.csv

| Kolonnenavn | Betydning |
| --- | --- |
| `vendor` | Leverandør |
| `product_version` | Produktversion |
| `notes_complete` | Noter færdige |
| `evidence_visibility_0_to_2` | Synlige oplysninger og kilder (0–2) |
| `uncertainty_0_to_2` | Usikkerhed (0–2) |
| `human_control_0_to_2` | Menneskelig kontrol (0–2) |
| `failure_handling_0_to_2` | Fejlhåndtering (0–2) |
| `data_answers_0_to_2` | Svar om databehandling (0–2) |
| `claim_credibility_0_to_2` | Troværdige produktudsagn (0–2) |
| `not_observed_items` | Ikke observeret |
| `non_negotiable_zero` | Ufravigeligt krav med nul point |
| `decision_and_follow_up` | Beslutning og opfølgning |

Registrér produktversion, opsætning, observationer og gemt dokumentation før pointgivning. Brug 0 manglende eller uhensigtsmæssig funktion, 1 delvis, 2 demonstreret. Skriv ikke observeret ved ubesvarede spørgsmål, og gentag testen; giv ikke nul uden observation. Fastlæg ufravigelige krav inden demonstrationen. Leverandørpoint må aldrig bruges som kandidatpoint.

[README](README.md)
