# OpenMP - Traktowanie Zmiennych

## Klauzule
- Sposób definiowania widoczności zmiennych w obszarach równoległych.
- [[04_Programowanie_Współbieżne/01_OpenMP/01_Dyrektywy]]

## Klauzule
- `shared`: zmienna wspólna.
- `private`: zmienna lokalna dla wątku.
- `firstprivate`: lokalna zmienna z kopią wartości inicjalnej.
- `lastprivate`: lokalna zmienna z wartością końcową z ostatniej sekwencyjnej iteracji.

## Dyrektywa Threadprivate
- Zmienne z takim zasięgiem jak deklarowana nazwa.
- #pragma omp threadprivate lista_zmiennych znak_nowej_linii
