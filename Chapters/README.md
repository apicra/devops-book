# Wstęp
Ta książka powstała jako jeden z elementów projektu apicra.
Projekt ma na celu rozpowszechnianie i współtworzenie automatyzacji w tworzeniu aplikacji, czyli DEVOPS.
DevOps która polega na współpracy **administratorów** odpowiedzialnych za utrzymanie sprzętu i oprogramowania
 oraz **programistów** czyli specjalistów od rozwoju oprogramowania.
https://pl.wikipedia.org/wiki/DevOps

Inne Publikacje w tematyce DevOps (za darmo)
https://github.com/TechBookHunter/Free-DevOps-Books


# O czym jest ksiazka
W książce zawarte są dobre praktyki:
+ Narzędzia
+ Przykładowe rozwiązania
+ Drogi rozwoju
+ Dane badawcze pokazujące wpływ użycia narzędzi DEVOPS na efektywność tworzenia i serwisowania oprogramowania

# Narzedzia
Na dzien dzsiiejszy 2018 roku s dostepne setki narzedzi dla deweleoperow.
Kazde z nich ma specyfike, pozwalaja na wyplyniecie na szerokie wody i w swiat chmur.
Jednak kazde z nich ogranicza tez w okreslony sposob, gdyz sluzy okreslonemu celowi.

Opgramowania ktore sa dedykowane, maja w swej sepcyfice ograniczone dzialanie i potrzebne sa mosty w celu dzialania w okreslonym 
przez ludzi i czas kierunku.
To co mamy dzis wynika z przeszlosci, a to co bedzie jutro wynika z woczoraj
Jednak narzedzia czesto nie sa kompatybilne w stecz i stad potrzebna jest edukacja, by te narzedzia zrozumiec i utrzymywac
tak by nie powstawaly problemy wynikajace z niedostosowania.

# Apicra standardy
Pierwszym standardem jaki niesie ze soba apicra sa komendy
install
update
downgrade
remove
info
status
logs

prawie kazda aplikacja moze bezposrednio obslugiwac te komendy
jednak nie wszystkie dzialaj aw tak bezposeredni sposob i jest wiele drog chocby pobrania aplikacji i jej zainstalowania
a potem odinstalowania
stad przy uzyciu standardow, latwiej pisac kolejne poziomy abstrakcji, np automatyzacje przy podejmowaniu decyzji o wynku dzialania

## Rozszerezenia
    -code
    -help
    -ticket
    
Paramter code wyswietla zrodlo komendy co sluzy transparentnosci, np
    
    dot composer install -code    
    
Parametr help pokazuje pomoc kontekstowa, ktora normalnie wyswietla program, pomocne przy automatyzacji
    
    dot composer install -help    

Parametr ticket pozwala uzytkownikkowi lub systemowi podczas automatyzacji wyslania informacji o bledzie lub logow
    
    dot composer install -ticket "tresc zadania"

## Transparntnosc 
To bardzo istotne w celu budowania zaufania, tak by kazdy przed podjeciem decyzji o wykonaniu jakiejs komendy mial mozliwosc sprawdzenia co tak na prawde zostanie wykonane
Wazne jest to w kontekscie ewentualnych bledow, jakie moglyby powstac, albo poznania zasady dzialania,
lub wyslania poprawy
mozna transparentnie

# Pomysł 
Skąd wziął się Pomysł na powstanie tej książki?

Jak wielu programistów napotykam na wiel barier i szukam rozwiązań,
Ta książka jest zbiorem moich doświadczeń, które zbieram w jedną całość, aby 
w przytsępny sposób podzielić się wiedzą, która może być przydatna dla tych którzy:
+ chcą szybko zarządzać dużym projektem
+ chcą zacząć nowe środowisko programowania
+ chcą się przebranożowić a nie wiedzą jak zacząć

Czyli wszędzie tam, gdzie można szybciej zrealizować to, co wielu programistom zajmuje wiele 
 nieprzespanych nocy, dodatkowych nadgodzin, stresu w czasie oddawania oprogramowania dla klienta oraz już po oddaniu, 
 gdy konieczne są zmiany, które przysparzają sporo problemu z uwagi na środowisko oraz dane. 

## Charakter książki

Jestem praktykiem, dlatego w kolejnych rozdziałach będzie sporo przykładów użycia narzędzi w codziennej pracy.
 

## Książka jako drogowskaz
Chciałbym pokazać każdym przykładem uyycia, specyfikę narzędzia i sposób w jaki warto praktycznie rozwiązać wiele problemów na raz

### Książka kucharska
To trochę jak z książką kucharską z przepisami, gdzie te same wypieki są wykonane w inny sposób, 
pokazując jak wiele rozwiązan, prowadzi do tego samego celu.


# Moja motywacja do pisania
W związku z rozwojem własnych kompetencji i eksplorowaniem dostępnych źródłe zauważyłem zbyt małą dostępność prostych narzędzi do użycia, które można by było łatwo dostosować, bez względu na system, nie przechodząc od razu do rozwiązan SaaS
Oprogramowanie dostępne w konsoli lokalnie w oparciu o otwarte źródło z możliwością łatwej adaptacji do własnych warunków już jest wyjątkowe, a przy wsparciu społeczności staje się potężnym narzedziem w rękach wielu rzemieślników: programistów i administratorów.

# Apicra i inne narzędzia
Narzędzia opisane w książce można łatwo zainstalować przy użyciu apicra, nawet tę książkę, można lokalnie renderować przy użyciu Apicra DevOps Tool.
To narzędzie okaże się bardzo pomocne przy uruchamianiu przykładów praktycznych zaprezentowanych w tej książce.


# Konspekt
(konspekt)[konspekt.md]

# Zadania do wykonania

- [ ] Znaleźć informacje na temat krytycznych ocen publikacji, aby dowiedzieć się jakie   

# Spis treści

+
