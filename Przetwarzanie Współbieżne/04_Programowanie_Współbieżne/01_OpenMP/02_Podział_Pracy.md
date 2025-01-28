# OpenMP - Dyrektywy Podziału Pracy

## Definicja
- Dyrektywy do podziału pracy między wątki.
- [[04_Programowanie_Współbieżne/01_OpenMP/01_Dyrektywy]]

## Charakterystyka
- Wymagają, by wszystkie wątki wykonywały te same dyrektywy.
- Nie ma bariery przy wejściu.
- Wykonanie z synchronizacją.

## Najważniejsze Dyrektywy
- `single`: wykonanie przez jeden wątek.
    - `private`, `firstprivate`, `copyprivate`, `nowait`
- `sections`: podział na sekcje.
    - `private`, `firstprivate`, `lastprivate`, `reduction`, `nowait`
- `for`: równoległe wykonanie pętli.
    - `private`, `firstprivate`, `lastprivate` oraz `schedule` i `reduction`.
    - `nowait`
