# DeliveryMate

Aplikacja PWA do ewidencji kursów delivery, przychodów, kosztów paliwa i opłacalności.

## Uruchomienie lokalne

Otwórz `index.html` w przeglądarce. Do testowania instalacji/offline uruchom serwer w katalogu aplikacji:

```bash
python3 -m http.server 8000
```

Następnie wejdź na `http://localhost:8000`.

## Publikacja

Możesz opublikować folder na GitHub Pages lub innym hostingu HTTPS. Po publikacji otwórz adres w Safari na iPhonie i wybierz Udostępnij → Dodaj do ekranu głównego.

## Funkcje

- Start każdego dnia od 0 km, bez pytania o początkowy stan licznika.
- Dystans zamówienia obliczany z różnicy kolejnych odczytów licznika.
- Ocena każdego kursu: SŁABO / MOŻE BYĆ / SUPER.
- Przychód, paliwo, netto i netto/km.
- Cel dzienny brutto lub netto oraz dwa konfigurowalne progi opłacalności.
- Własne profile pojazdów (skuter, samochód, rower), edycja i usuwanie.
- Statystyki dzienne, miesięczne i per platforma.
- Zamykanie dnia, historia zamkniętych dni i eksport/import JSON.
- Dane przechowywane lokalnie w przeglądarce (localStorage).

## Ważne

To wersja lokalna/PWA bez konta i synchronizacji w chmurze. Kopie zapasowe należy eksportować i przechowywać samodzielnie.
