# OpenMP - Redukcja

## Definicja
- Operacja łączenia wartości zmiennej z różnych wątków w jedną wartość.
- [[04_Programowanie_Współbieżne/01_OpenMP/01_Dyrektywy]]
- Klauzula reduction(op, lista_zmiennych).

## Operatory
- +, *, -, &, ^, |.

## Działania
- Wyrażenia (x = x op wyrażenie), x++, x op= wyrażenie.

## Inicjalizacja
- Zmienna odpowiednio inicjowana na początku pętli.

## Wynik
- Wynik po zrównolegleniu taki sam jak w wersji sekwencyjnej.
