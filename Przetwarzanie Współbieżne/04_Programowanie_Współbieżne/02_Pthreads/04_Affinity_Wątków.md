# Pthreads - Affinity Wątków

## Przypisywanie Wątków
- Przypisywanie wątków do konkretnych rdzeni procesora.
- Poprawa wydajności przez redukcję kosztu przełączania kontekstu.
- [[01_Współbieżność_w_Systemach/05_Wywłaszczanie_i_Przełączanie_Kontekstu]]
- [[04_Programowanie_Współbieżne/02_Pthreads]]

## Funkcje
- `pthread_setaffinity_np` - ustawienie powinowactwa.
- `pthread_getaffinity_np` - pobranie powinowactwa.

## Typ danych
- `cpu_set_t`

## Operacje
-  `CPU_ZERO`, `CPU_SET`, `CPU_SETSIZE`, `CPU_ISSET`.
