# Uzgodnienie kryteriów analizy CV

Szablony i objaśnienia kolumn są dostępne w czterech językach. Klucze kolumn CSV pozostają po angielsku, aby pliki można było spójnie porównywać i importować. Znaczenie kolumn opisuje worksheet-guide.md.

## screening-calibration.csv

| Klucz kolumny | Znaczenie |
| --- | --- |
| `criteria_version` | Wersja kryteriów |
| `owner` | Osoba odpowiedzialna |
| `review_date` | Data przeglądu |
| `criterion` | Kryterium |
| `priority` | Priorytet |
| `expected_evidence` | Oczekiwane potwierdzenie |
| `synthetic_sample_id` | ID fikcyjnego przykładu |
| `reviewer_a_interpretation` | Interpretacja osoby A |
| `reviewer_b_interpretation` | Interpretacja osoby B |
| `disagreement` | Rozbieżność |
| `agreed_revision` | Uzgodniona zmiana |
| `next_action` | Następne działanie |
| `unresolved_question` | Otwarte pytanie |
| `reopening_condition` | Warunek ponownego przeglądu |

## vendor-comparison.csv

| Klucz kolumny | Znaczenie |
| --- | --- |
| `vendor` | Dostawca |
| `product_version` | Wersja produktu |
| `notes_complete` | Notatki zakończone |
| `evidence_visibility_0_to_2` | Widoczność informacji i źródeł (0–2) |
| `uncertainty_0_to_2` | Niepewność (0–2) |
| `human_control_0_to_2` | Kontrola człowieka (0–2) |
| `failure_handling_0_to_2` | Obsługa błędów (0–2) |
| `data_answers_0_to_2` | Odpowiedzi o danych (0–2) |
| `claim_credibility_0_to_2` | Wiarygodność deklaracji (0–2) |
| `not_observed_items` | Elementy bez obserwacji |
| `non_negotiable_zero` | Zero w wymaganiu nieprzekraczalnym |
| `decision_and_follow_up` | Decyzja i dalsze działania |

Przed punktacją zapisz wersję produktu, konfigurację, obserwacje i zachowane materiały. Stosuj 0 brak lub niepożądane działanie, 1 częściowe, 2 wykazane. Pytania bez obserwacji oznacz jako nie zaobserwowano i powtórz test; nie przyznawaj zera. Przed demonstracją ustal wymagania nieprzekraczalne. Punktów dostawcy nigdy nie używaj do oceny kandydatów.

[README](README.md)
