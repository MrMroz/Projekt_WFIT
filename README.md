# Projekt_WFIT
Realizacja Gry w życie w języku Python w ramach projektu zaliczającego przedmiot WFIT.
---
## Autorzy:
- M. Mazur
- P. Mróz

## Wymagania
Aplikacja nie wymaga żadnych zewnętrznych bibliotek do działania, jedynie do zbudowania projektu konieczny jest **cx_Freeze**.

## Korzystanie z programu
Oprócz uruchomienia pliku wykonywalnego dostępnego w [Releases](https://github.com/MrMroz/Projekt_WFIT/releases/tag/v1.0.0), można uruchomić program poprzez wykonanie pliku **run.py**.

Po włączeniu widoczna będzie plansza na której można malować klikając i przeciągając lewym kursorem myszy.

- Przycisk *reset* służy do resetu planszy - ustawienia wszystkich komórek jako martwych.

- Przycisk *next state* służy do manualnego wyzwalania kolejnego stanu.

- Przycisk *start/stop* służy do włączania/wyłączania automatycznego zegara wyzwalającego kolejne stany.

- Slider pozwala ustawić częstotliwość odświeżania planszy.

- Menu w górnym lewym rogu okna pozwala wczytać lub zapisać stan planszy.

## Pokazowe struktury
Aplikacja ma możliwość wczytywania i zapisywania stanu do pliku **.json** za pomocą menu rozwijanego w górnym lewym rogu okna.
W folderze `przykladowe_struktury` znajduje się kilka wybranych przez nas struktur.

## Budowanie aplikacji
Aby zbudować projekt samemu, należy wywołać komendę.
```
python setup.py build
```
