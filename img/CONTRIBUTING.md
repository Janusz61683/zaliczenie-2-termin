# Zasady współpracy – Przewodnik po stolicach Europy

## Branching (nazewnictwo)
- Każda nowa sekcja miasta = nowa gałąź.
- Nazwa gałęzi: `stolica-imie` (np. `lizbona-janusz`).

## Commit messages
- Krótkie i opisowe, np. `Dodano sekcję Lizbona i obraz lizbona.jpg`.

## Issues
- Twórz nowe zgłoszenie, jeśli pojawi się problem lub propozycja zmiany.
- Opisz dokładnie: problem, kroki reprodukcji, oczekiwane zachowanie.

## Pull Requests
- PR zawsze kieruj do gałęzi `main` w repozytorium prowadzącej.
- W opisie PR podaj zakres zmian i uzasadnienie.
- Poprawki po uwagach wprowadzaj w tym samym branchu.
- PR łączymy dopiero po akceptacji prowadzącej.

## Struktura HTML
- Każda stolica w osobnym `<section>`.
- Obrazy w katalogu `img/`.
- Każdy `<img>` musi mieć atrybut `alt`.
