# Semafor

## Definicja
- Zmienna globalna do synchronizacji.
- Umożliwia synchronizację wątków.
- [[02_Problemy_Współbieżności/02_Wzajemne_Wykluczanie]]
- Atomowe operacje P (wait) i V (signal).

## P (wait)
- Zmniejszenie wartości semafora.
- Wątek usypia gdy semafor jest 0.

## V (signal)
- Zwiększenie wartości semafora.
- Obudzenie wątku, jeśli ten usnął.

## Zastosowania
- Wzajemne wykluczanie.
- Synchronizacja wątków.

## Binarny Semafor
- Semafor z wartościami 0 i 1.
- Zbliżony do muteksa.
