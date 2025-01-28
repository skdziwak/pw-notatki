# OpenMP - Funkcje Biblioteczne

## Plik Nagłówkowy
- omp.h
-  [[04_Programowanie_Współbieżne/01_OpenMP]]

## Funkcje ze Środowiskiem
- `omp_set_num_threads` – ustawienie liczby wątków.
- `omp_get_num_threads` – pobranie liczby wątków.
- `omp_get_num_procs` – pobranie liczby procesorów.
- `omp_get_thread_num` – pobranie numeru wątku.
-   `omp_in_parallel` - Sprawdzenie wykonania równoległego.
 - `omp_get_max_threads` - Pobranie maksymalnej liczby wątków.
 - `omp_set_dynamic`, `omp_get_dynamic` -  Ustalanie dynamiicznej liczby wątków.
 - `omp_set_nested`, `omp_get_nested` - Umożliwianie zagnieżdżenia.

## Funkcje obsługi zamków
- `omp_init_lock`, `omp_destroy_lock`, `omp_set_lock`, `omp_test_lock`, `omp_unset_lock`.

## Funkcje pomiaru czasu
- `omp_get_wtime`, `omp_get_wtick`.
