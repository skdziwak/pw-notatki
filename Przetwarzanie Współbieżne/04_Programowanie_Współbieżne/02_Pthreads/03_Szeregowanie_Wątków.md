# Pthreads - Szeregowanie Wątków

## Strategie Szeregowania
- Ustalanie priorytetów wątków.
- Kolejność wykonywania wątków.
- [[01_Współbieżność_w_Systemach/04_Synchronizacja]]
- [[04_Programowanie_Współbieżne/02_Pthreads]]

## Mechanizmy
- `pthread_attr_setschedpolicy` - ustawienie strategii szeregowania.
- `pthread_attr_getschedpolicy` - pobranie strategii szeregowania.
-   `sched_get_priority_max` - pobranie maksymalnego priorytetu.
 -  `sched_get_priority_min` - pobranie minimalnego priorytetu.
 -  `pthread_setschedparam` - ustawianie parametrów szeregowania.
 -  `pthread_getschedparam` - pobieranie parametrów szeregowania.

## Strategie
- `SCHED_OTHER` - zależy od nice wątku.
- `SCHED_FIFO` - pierwszeństwo.
- `SCHED_RR` - wariacja FIFO.
- `SCHED_BATCH` - dla czasochłonnych zadań.
- `SCHED_IDLE` - najniższy priorytet.
