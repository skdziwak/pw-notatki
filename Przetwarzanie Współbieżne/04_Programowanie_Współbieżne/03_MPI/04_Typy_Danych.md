# MPI - Typy Danych

## Typy Podstawowe
- `MPI_INT`, `MPI_DOUBLE`, `MPI_CHAR`, `MPI_BYTE`.
- [[04_Programowanie_Współbieżne/03_MPI/01_Podstawy_MPI]]

## Typy Utworzone
- Konstrukcje typów danych złożonych.
-  `MPI_Type_contiguous`: przyległe zmienne w pamięci.
-  `MPI_Type_vector`: wektor bloków zmiennych.
- `MPI_Type_indexed`: bloki zmiennych o różnej długości i odległości.
-  `MPI_Type_struct`: bloki zmiennych różnych typów.
-  `MPI_Type_commit`: zapisanie definicji typu.

## Procedury Pomocnicze
-   `MPI_Get_address`.
 -  `MPI_Type_get_extent`.
-  `MPI_Type_size`.
-   `MPI_Type_create_resized`.

## Typ Pakowany
-  `MPI_Pack`,  `MPI_Unpack`
- `MPI_PACKED`
- `MPI_Pack_size`
