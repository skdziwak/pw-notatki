# Pthreads - Atrybuty Wątków

## Atrybuty
- Konfiguracja wątków przed uruchomieniem.
- `pthread_attr_t`
- [[04_Programowanie_Współbieżne/02_Pthreads]]

## Funkcje
- `pthread_attr_init` - inicjalizacja atrybutów.
- `pthread_attr_destroy` - niszczenie atrybutów.
-  `pthread_attr_setdetachstate` – Ustawienie stanu odłączenia.
-   `pthread_attr_getdetachstate` – Pobranie stanu odłączenia.
 - PTHREAD_CREATE_JOINABLE
 - PTHREAD_CREATE_DETACHED
 -  `pthread_attr_getstacksize` - pobranie rozmiaru stosu.
 -   `pthread_attr_getstackaddr` - pobranie adresu stosu.
 - `pthread_attr_getstack` - pobranie rozmiaru i adresu stosu
