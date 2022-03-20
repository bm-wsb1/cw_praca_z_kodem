INSTRUKCJA NA POSTAWIE PLIKU NA MOODLU

Aby uruchomić program:

1. Pobierz pliki: app.py, index.html, login.html, requirements.txt z Moodla (zakładka Lista2).
Przekopiuj do katalogu repozytorium cw_praca_z_kodem. 
Python – zainstaluj (w wersji nie niższej niż 3.8).

2. Utwórz folder templates i umieść tam pliki index.html oraz login.html. Struktura projektu

cw_praca_z_kodem 
 |-- templates
    |-- index.html
    |-- login.html
 |-- app.py
 |-- requirements.txt
 |-- README.md

3. pobierz biblioteki
click 8.0.4
Flask 2.0.3
itsdangerous 2.1.0
Jinja 3.0.3
MarkupSafe 2.1.0
Werkzeug 2.0.3

4. zainstaluj
Curl
Pylint
Stwórz plik Makefile, który będzie zawierał komendy pip install -r requirements.txt flask run Nadanie mu atrybutu wykonywalności (za pomocą chmod) i wykonanie.



