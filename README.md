# Finansowy Kompas

Sprawdź swoją **pozycję dochodową**, **siłę nabywczą** i **majątek netto** na tle polskich gospodarstw — w minutę, bez konta i bez wysyłania danych.

**Live:** https://kris-welc.github.io/finansowy-kompas/

## Co robi

- szacuje klasę dochodową (metodologia PIE / EHDI),
- pokazuje percentyl dochodów w Polsce,
- przelicza siłę nabywczą na dolary PPP,
- opcjonalnie ocenia klasę majątkową (nieruchomości + oszczędności − kredyty).

## Prywatność

Jeden statyczny plik HTML. Wyliczenia działają lokalnie w przeglądarce.

- brak backendu i kont,
- brak cookies / localStorage / analityki dla danych finansowych,
- dane o pensjach i majątku nigdzie nie wychodzą,
- jedyny opcjonalny request: publiczna liczba gwiazdek z GitHub API.

Jeśli narzędzie Ci się podoba — zostaw ★ na GitHubie.

## Metodologia (skrót)

| Element | Źródło |
|---|---|
| Klasa dochodowa (EHDI) | Polski Instytut Ekonomiczny |
| Mediana dochodu | GUS 2025 |
| PPP | Bank Światowy |
| Majątek | NBP/GUS BZGD 2016 (indeksacja do 2025) |
| Porównanie z Warszawą | Deutsche Bank 2026 — tylko jedna liczba (pensja netto) |

To **nie** jest ranking miast ani kopia raportu DB/rp.pl.

## Uruchomienie lokalne

Otwórz `index.html` w przeglądarce.
