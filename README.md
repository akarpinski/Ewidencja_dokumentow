Mój własny projekt bazy danych z zajęć w trakcie studiów IT na Uniwersytecie Gdańskim.

Cały opis projetu w załączonej dokumentacji (pdf).

## Ewidencja dokumentów

### Aplikacja klient-serwer do ewidencji dokumentów przychodzących do firmy.

Sekretariat przyjmuje dokumenty i wprowadza je do ewidencji, następnie przekazuje dokumenty do konkretnych działów lub użytkowników. Typy dokumentów: faktury, faktury korygujące, pozostałe dokumenty księgowe, korespondencja urzędowa, korespondencja, pozostałe dokumenty.

1. Środowisko
* Linux Fedora 15 uruchomiony w sieci lokalnej
* Apache + PHP, baza danych MySql
c. Dostęp publiczny do aplikacji – konfiguracja sieci przez administratora.
d. Środowisko użytkownika – przeglądarka internetowa
e. Uruchamianie aplikacji – adres ip lub lokalna domena, konfiguracja lokalnej domeny – plik hostów w komputerach lub konfiguracja lokalnego DNS

2. Ogólny zarys aplikacji
a. Obieg dokumentów przychodzących i wychodzących, rejestracja, ewidencja, raporty
b. W drugim etapie rejestracja zamówień, ewidencja w połączeniu z fakturami (zamówienie -> faktura)

3. Baza danych:
a. Tabele:
i. Użytkownik
ii. Dział
iii. Dokument
iv. Klient

```
Do budowy aplikacji użyto następujących technologii:
• Język skryptowy PHP 5.3.13
• Baza danych MySql 5.5.23-1
• HTML5
• CSS3
• JavaScript
• JQuery
• Ckeditor – edytor WYSIWYG – wizualny edytor HTML, który pozwala na łatwe wprowadzanie tekstu za pomocą interfejsu przypominającego programy typu OpenOffice czy Microsoft Word.
• Bootstrap – biblioteka graficznych interfejsów użytkownika
• JQuery UI – biblioteka JavaScript z dodatkami, w aplikacji użyto kalendarza do wpisywania daty w formularzach.

Środowisko serwerowe:
• Aplikacja w wersji internetowej - hosting Home.pl
• Aplikacja w wersji intranetowej:
o Serwer Linux Fedora 15
o Serwer www Apache 22.22-1 + MySQL + PHP
```
