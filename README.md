# Dokumentacja Currency App - Projekt BAI

## Wstęp
Aplikacja pozwala przy pomocy naszego konta Google na obserwacje dowolnej ilości walut z wybranej przez użytkownika ilości dni.

***

## Temat
Aplikacja do kontroli obcych walut

***

## Cele projektu:
Menedżer obcych walut, użytkownik w prosty sposób będzie mógł gromadzić interesujące go waluty, dodawać je do ulubionych oraz stale śledzić ich kurs. Dodatkową opcją będzie kontrola kursu waluty na przestrzeni czasu.

## Funkcjonalności:

**1. Autentykacja użytkownika za pomocą konta Google.**
Po wejściu do serwisu użytkownik zostaje poproszony o zalogowanie się:
![Strona Główna](screens/SCREEN1.png)

**2. Wyszukiwanie walut.**
Po zalogowaniu użytkownik otrzymuje możliwość wyboru dowolnej waluty z określonej przez siebie ilości dni
![Strona Główna](screens/SCREEN2.png)

**3. Kontrola obecnego kursu waluty**
Po wybraniu pojawi się informacja o aktualnym kursie waluty:
![Strona Główna](screens/SCREEN3.png)

**4. Kontrola kursu waluty na przestrzeni czasu (zobrazowana poprzez wykres)**
Po wybraniu pokazuje się wykres z określonego przedziału, po najechaniu widzimy stan z dowolnego dnia z wybranego wcześniej przedziału:
![Strona Główna](screens/SCREEN4.png)

**5. Możliwość tworzenia oraz edycji list ulubionych walut**
Waluty zapisywane są do bazy firebase przez co użytkownik nie musi za każdym razem wyszukiwać swoich ulubionych walut.
![Strona Główna](screens/SCREEN5.png)

## Wersja mobilna:
![Strona Główna](screens/SCREEN6.png)

### [Linnk do aplikacji](http://bai.v50.pl/)
### [Linnk do proojektu github](https://github.com/szymonzalega/currency-app)
### [Linnk do hsitorii prowadzenia projektu](https://github.com/szymonzalega/currency-app/projects/2)

## Wykorzystane API
[Firebase](https://firebase.google.com/docs/reference?hl=pl)
[NBP](https://api.nbp.pl/)

## Wykorzystane technologie
* vue.js
* html
* css

## Dodatkowe komponenty
* vuechartjs
