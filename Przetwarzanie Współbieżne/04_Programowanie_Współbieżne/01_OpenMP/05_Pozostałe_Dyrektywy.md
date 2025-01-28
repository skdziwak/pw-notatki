# OpenMP - Pozostałe Dyrektywy

## master
- Wykonanie kodu przez wątek master.
- #pragma omp master znak_nowej_linii {....}

## critical
- Wykonywanie kodu w sekcji krytycznej.
- #pragma omp critical nazwa znak_nowej_linii {....}

## barrier
- Bariera synchronizacyjna.
- #pragma omp barrier znak_nowej_linii

## atomic
- Wykonanie atomowe operacji.
- #pragma omp atomic znak_nowej_linii

## ordered
- Wykonanie kodu w kolejności.
- Nie wymusza kolejności na wątkach.
