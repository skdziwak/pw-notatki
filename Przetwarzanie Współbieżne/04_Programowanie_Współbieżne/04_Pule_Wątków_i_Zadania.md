# Pule Wątków i Zadania

## Pula Wątków
- Zarządzanie pulą wątków, a nie pojedynczymi.
-  [[01_Wątki]]

## Zadania
- Obiekt do wykonania na wątku z puli.

## Języki
-  Java - ExecutorService, Executors.
 - C++ - std::thread, Boost.Asio
 - JavaScript - module worker_threads.
 -  Go - "goroutines".
 - Rust - rayon, tokio.
 - Ruby - Concurrent::ThreadPool.
 -  [[01_Wątki]]

## OpenMP
- Dyrektywa task - do tworzenia zadań.
 - #pragma omp task lista_klauzul
- Właściwości zadań OpenMP:
    -  kod do wykonania, powiązane zmienne, zmienne kontrolne.
-  `untied` - możliwość wykonania zadania przez dowolny wątek.
-  Punkty szeregowania - domyślnie zdefiniowane.
-  `if` - warunkowe tworzenie instancji zadania.
