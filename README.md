# Kalkulator klasy społecznej i siły nabywczej

Samodzielna, lokalna strona HTML (bez backendu) do oszacowania:

- **klasy dochodowej** gospodarstwa (metoda PIE / EHDI),
- **percentyla** dochodów w Polsce,
- **siły nabywczej** w dolarach międzynarodowych (PPP),
- opcjonalnie **klasy majątkowej** (nieruchomości + oszczędności − kredyty).

## Bezpieczeństwo

To jeden plik `index.html`. Wszystkie obliczenia dzieją się w przeglądarce. Strona:

- nie ma serwera ani API,
- nie ładuje skryptów zewnętrznych / CDN,
- nie używa cookies, `localStorage` ani analityki,
- nigdzie nie wysyła wpisanych danych.

Możesz to sprawdzić w DevTools → Network (poza samym załadowaniem HTML nie powinno być żadnych requestów) albo przeglądając kod źródłowy.

## Relacja do raportu Deutsche Bank / rp.pl

**Nie.** To nie jest ranking miast ani implementacja raportu DB „Mapping the World's Prices” 2026.

Z tego raportu kalkulator bierze **tylko jedną liczbę porównawczą**: przeciętną pensję netto w Warszawie (~$2221/mies.). Reszta to:

| Element | Źródło |
|---|---|
| Klasa dochodowa (EHDI) | Polski Instytut Ekonomiczny |
| Mediana dochodu | GUS 2025 |
| PPP | Bank Światowy |
| Rozkład majątku | NBP/GUS BZGD 2016 (indeksacja własna do 2025) |
| Porównanie z Warszawą | Deutsche Bank 2026 (jedna liczba) |

## Uruchomienie lokalne

Otwórz `index.html` w przeglądarce (podwójne kliknięcie albo `open index.html`).

## Live

https://kris-welc.github.io/kalkulator-klasy-spolecznej/
