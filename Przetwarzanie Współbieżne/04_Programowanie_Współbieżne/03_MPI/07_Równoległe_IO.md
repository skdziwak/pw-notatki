# MPI - Równoległe IO

## Interfejs
- Operacje wejścia/wyjścia na plikach z MPI.
- [[04_Programowanie_Współbieżne/03_MPI/01_Podstawy_MPI]]

## Pojęcia
- Typ elementarny (etype).
- Typ plikowy (filetype).
- Widok pliku (view).

## Wskaźniki
- offset.
- Wskaźnik pliku.

## Operacje
- `MPI_File_open`, `MPI_File_close`
- `MPI_File_set_view`
- `MPI_File_read_at`, `MPI_File_write_at`
- `MPI_File_read`, `MPI_File_write`
- `MPI_File_seek`
- Operacje blokujące i nieblokujące
