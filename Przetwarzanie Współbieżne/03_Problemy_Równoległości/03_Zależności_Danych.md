# Zależności Danych

## Definicja
- Zależności związane z przepływem danych pomiędzy instrukcjami.
- [[03_Problemy_Równoległości/01_Zależności]]

## Rodzaje
- **RAW (Read After Write):** Odczyt po zapisie.
- **WAR (Write After Read):** Zapis po odczycie.
- **WAW (Write After Write):** Zapis po zapisie.

## Znaczenie
- Ograniczają równoległe wykonywanie instrukcji.
- Mogą być eliminowane przez przemianowanie zmiennych.
