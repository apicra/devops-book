# Apicra 
To scyzoryk dla każdego administratora i programisty, który potrzebuje w trudnych warunkach i w codziennej rutynie szybko wykonać określone zadania, nie chcąc przy tym otwierać puszki pandory, jakimi bywają problemy środowiskowe, któe trudno przewidzieć, zwłaszcza gdy to serwer produkcyjny.

Korzyści leżą też po stronie samego rozwoju orpgroamowania, które wspiera społczeność.

To co czeka Apicra za jakiś czas, to nowe wyzwania przy podejmowania coraz głębszych problemów wynikających nie tylko po stronie serwera ale też uruchamianego oprogramowania.

## Obecne rozwiązania
Obecne stosowane rozwiązania mają za zadanie zbadanie zgodności i dostarczenie określonej wersji oprogramowania,
na użytkowniku spoczywa usunięcie trybów niezgodności i błędów występująych w srodowisku.
Tutaj pojawia się Apicra, która analizuje te błędy i stara się znaleźć rozwiązanie, poprzez analizę i identyfikację źródła tych problemów a następnie stworzeniu rozwiązania i instalacji.

## Learning by doing

Oprogramowanie Apicra devops tool
Realizuje idee uczenia poprzez dzialanie, ktore jest silnie wspierane przez spolecznosc
W naszej spolecznosci naturalne jest i pozadane zroznicowanie w zawansowaniu znajomosci technologii
Niedoswiadczeni zadaja pyt
Eksperci odpowiadaja, 

Nauczyc mozna sie wielu rzeczy w rozmy sposob, przy roznym zaangazowaniu. 

Naszym celem jest skrocenie drogi poprzez analize sytuacji i podaniu ty na aktualny problem. 
Analiza jest konieczna aby nie tracic czasu na poboczne problemy ktore nie maja. Przelozenia na rozwiazanie. 

Maksymalne zogniskowanie na rozwiazanie. 
Dzialanie majace na celu zrozumienie problemu. 



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