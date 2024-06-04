# Saper

Saper to klasyczna gra logiczna, w której celem gracza jest odkrycie wszystkich pól na planszy, które nie zawierają bomb. 
Gracz może również oznaczać potencjalne bomby flagami, aby ułatwić sobie rozgrywkę.

## Funkcjonalności

- Odkrywanie pól na planszy.
- Oznaczanie i usuwanie flag na polach, które mogą zawierać bomby.
- Wygrana, gdy wszystkie pola bez bomb zostaną odkryte.
- Przegrana, gdy gracz odkryje pole z bombą.

## Jak uruchomić

Aby uruchomić projekt, wykonaj poniższe kroki:

1. Sklonuj repozytorium na swój lokalny komputer:
    ```bash
    git clone https://github.com/twoje-repozytorium/saper.git
    ```
2. Przejdź do katalogu projektu:
    ```bash
    cd saper
    ```
3. Upewnij się, że masz zainstalowane środowisko .NET SDK. Możesz je pobrać z [oficjalnej strony .NET](https://dotnet.microsoft.com/download).

4. Skompiluj i uruchom projekt:
    ```bash
    dotnet run
    ```

## Jak grać

1. Po uruchomieniu gry zobaczysz pustą planszę o zdefiniowanych wymiarach.
2. Aby odkryć pole, wprowadź współrzędne w formacie `x y` (np. `2 3`) i naciśnij Enter.
3. Aby oznaczyć lub usunąć flagę z pola, wprowadź współrzędne poprzedzone literą `f` w formacie `f x y` (np. `f 2 3`) i naciśnij Enter.
4. Gra kończy się wygraną, gdy wszystkie pola bez bomb zostaną odkryte, lub przegraną, gdy odkryjesz pole z bombą.
