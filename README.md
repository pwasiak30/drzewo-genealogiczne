# Moje Drzewo Genealogiczne

Aplikacja webowa (jeden plik HTML + biblioteki D3.js i jsPDF, działające w pełni offline) do tworzenia, rozwijania i wizualizowania drzewa genealogicznego.

## Funkcje
- Dodawanie osób z datami/miejscami urodzenia i śmierci oraz dodatkowymi faktami
- Łączenie osób relacjami (rodzic, dziecko, małżonek/partner, rodzeństwo) — z listy już dodanych osób lub jako nowa osoba
- Żywo aktualizujący się, graficzny widok drzewa (D3.js), wielopokoleniowy
- Zapis danych lokalnie w przeglądarce + eksport/import JSON (kopia zapasowa, przenoszenie między urządzeniami)
- Eksport do formatu GEDCOM (.ged) — standard wymiany danych genealogicznych, do przenoszenia drzewa do innych programów (np. Gramps, FamilySearch, MyHeritage)
- Eksport widocznego drzewa (rozgałęzień połączonych z wybraną osobą) do pliku PDF — przycisk „Eksportuj drzewo do PDF" w panelu Osoby
- Panel szybkiego wyszukiwania w darmowych, publicznych wyszukiwarkach archiwów (FamilySearch, Geneteka/Geneszukacz PTG)
- Wskaźnik ostatniej kopii zapasowej w panelu Osoby (przypomina o eksporcie, jeśli minęło ponad 14 dni)
- Tryb ciemny/jasny z zapamiętywaniem wyboru

## Użycie
Otwórz `index.html` w przeglądarce, albo skorzystaj z wersji online przez GitHub Pages.

Dane przechowywane są lokalnie w przeglądarce (localStorage) — pamiętaj o regularnym eksporcie do pliku JSON (kopia zapasowa 1:1) lub GEDCOM (do innych programów genealogicznych).
