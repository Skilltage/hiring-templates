# Criteria voor cv-screening afstemmen

Templates en kolomtoelichtingen zijn beschikbaar in vier talen. CSV-kolomsleutels blijven Engels, zodat bestanden consistent vergeleken en geïmporteerd kunnen worden. Raadpleeg worksheet-guide.md voor de betekenis van de kolommen.

## screening-calibration.csv

| Kolomsleutel | Betekenis |
| --- | --- |
| `criteria_version` | Criteriaversie |
| `owner` | Verantwoordelijke |
| `review_date` | Beoordelingsdatum |
| `criterion` | Criterium |
| `priority` | Prioriteit |
| `expected_evidence` | Verwachte onderbouwing |
| `synthetic_sample_id` | ID fictief voorbeeld |
| `reviewer_a_interpretation` | Interpretatie beoordelaar A |
| `reviewer_b_interpretation` | Interpretatie beoordelaar B |
| `disagreement` | Verschil |
| `agreed_revision` | Afgesproken wijziging |
| `next_action` | Volgende handeling |
| `unresolved_question` | Open vraag |
| `reopening_condition` | Voorwaarde voor herziening |

## vendor-comparison.csv

| Kolomsleutel | Betekenis |
| --- | --- |
| `vendor` | Leverancier |
| `product_version` | Productversie |
| `notes_complete` | Aantekeningen afgerond |
| `evidence_visibility_0_to_2` | Zichtbare informatie en bronnen (0–2) |
| `uncertainty_0_to_2` | Onzekerheid (0–2) |
| `human_control_0_to_2` | Menselijke regie (0–2) |
| `failure_handling_0_to_2` | Foutafhandeling (0–2) |
| `data_answers_0_to_2` | Antwoorden over gegevens (0–2) |
| `claim_credibility_0_to_2` | Geloofwaardigheid claims (0–2) |
| `not_observed_items` | Niet-waargenomen onderdelen |
| `non_negotiable_zero` | Ononderhandelbare eis met nul punten |
| `decision_and_follow_up` | Beslissing en vervolg |

Leg productversie, configuratie, waargenomen gedrag en bewaarde onderbouwing vast vóór de puntentoekenning. Gebruik 0 afwezig of ongewenst, 1 gedeeltelijk, 2 aangetoond. Noteer niet waargenomen bij onbeantwoorde vragen en herhaal de test; geef niet zonder observatie nul punten. Leg ononderhandelbare eisen vooraf vast. Leveranciersscores mogen nooit kandidaatscores worden.

[README](README.md)
