# Układ Słoneczny — strona przykładowa na zajęcia z informatyki

Strona-wzór dla uczniów klas VII–VIII, którzy przygotowują własny projekt strony WWW
w HTML-u i CSS-ie (pisany w Notatniku, bez JavaScriptu).

**Strona na żywo:** https://mikub97.github.io/uklad-sloneczny/

## Po co to repozytorium

Uczniowie mogą tu podejrzeć kod gotowego projektu, który spełnia wszystkie wymagania:
część startowa, cztery części tematyczne, podstrona z powrotem na stronę główną, menu,
nagłówki, akapity, lista, pięć grafik (w tym trzy własne), odnośniki do źródeł, link do
filmu, sekcja „Źródła”, tabela z obliczeniami i wykres z arkusza kalkulacyjnego.

Podstrona [jak-to-zrobione.html](jak-to-zrobione.html) wypisuje każde wymaganie i wskazuje,
gdzie dokładnie zostało spełnione.

## Pliki

| Plik | Co zawiera |
|---|---|
| `index.html` | strona główna: część startowa, części tematyczne 1–2, źródła |
| `planety.html` | podstrona: części 3–5, tabela na trzy sposoby, wykres, wniosek |
| `jak-to-zrobione.html` | ściąga dla uczniów: lista wymagań i typowe błędy |
| `style.css` | wygląd całej strony, komentowany po polsku |
| `imgs/` | 3 grafiki własne + 2 zdjęcia NASA (domena publiczna) |
| `arkusz/uklad-sloneczny.xlsx` | arkusz z danymi, formułami i wykresem |
| `arkusz/tabela-google.html` | ta sama tabela wyeksportowana z Arkuszy Google (dla `iframe`) |

## Zasady, których trzyma się ten kod

- tylko HTML i CSS — **zero JavaScriptu**,
- tylko te znaczniki i właściwości, które uczniowie poznają na zajęciach
  (bez flexboksa, grida, zmiennych CSS i frameworków),
- komentarze po polsku w kodzie, oznaczające poszczególne wymagania,
- każde zdjęcie z internetu ma podanego autora i licencję w sekcji „Źródła”.

## Źródła danych

- średnice i odległości: NASA Science — Solar System,
- liczba księżyców: NASA/JPL, *Planetary Satellite Discovery Circumstances* (dostęp 16.11.2026),
- zdjęcia: NASA/SDO oraz NASA/JPL/USGS — domena publiczna.
