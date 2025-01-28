# MPI - Komunikacja Dwupunktowa

## Charakterystyka
- Przesyłanie komunikatów między dwoma konkretnymi procesami.
- [[04_Programowanie_Współbieżne/03_MPI/01_Podstawy_MPI]]

## Blokujące Przesyłanie
- `MPI_Send`: wysyłanie.
- `MPI_Recv`: odbieranie.
- `MPI_Status`: status odebranego komunikatu.

## Nieblokujące Przesyłanie
- `MPI_Isend`: wysyłanie.
- `MPI_Irecv`: odbieranie.
- `MPI_Request`: status operacji nieblokujących.
- `MPI_Wait`, `MPI_Test` - funkcje do testowania.
- `MPI_Probe`, `MPI_Iprobe`.

## Komunikaty
- Użycie tagu do rozróżnienia komunikatów.
