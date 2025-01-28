# Java - Synchronizacja

## Synchronized
-  Metody oraz bloki synchronizowane
- Wzajemne wykluczanie.
- [[02_Problemy_Współbieżności/02_Wzajemne_Wykluczanie]]
- [[02_Problemy_Współbieżności/04_Muteksy]]

## Monitor
- Każdy obiekt posiada monitor.
- Monitor blokuje metody oraz bloki `synchronized`.
- Kolejka oczekujących wątków.
- Ograniczenie na wywoływanie - tylko jeden wątek w monitorze.

## Przykład
-  Klasa z metodami `synchronized`.
-  Synchronizowane bloki z argumentem (`synchronized(this) {...}`).

## Lock
-   Interfejs Lock z metodą trylock.
-   Alternatywa do `synchronized`.

## Monitory - Dodatkowe
 - Konstruktory nie mogą być synchronizowane.
