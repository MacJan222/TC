# TC
Techniki programowania projekt4.
 Created new branch "testing"
 
 
INFORMACJE DLA UŻYTKOWNIKA:
Program symuluje dźwig, który z 3 róznych miejsc podnosi ładunki o różnym kształcie.
Dzwig zawiera system, który pozwala mu podnieść jedynie trójkąty.
Przyciski "1","2" i "3" służą do zmiany figury na danym polu.
Dźwigiem można sterować za pomocą okrągłych guzików z opisanymi kierunkami oraz guzikiem stop.
Przyciski "grab" i "relesase" służą do chwytania i puszczania figury.
Należy wcisnąć przycisk "start", aby rozpocząć pracę.
///// nieukończone//////
Użytkownik może ułożyć wieżę z maksymalnie 3 trójkątów.

INFORMACJE DLA PROGRAMISTY:
Obszar rysowania dzieli się na 2 części: dźwig i figury, rysowane przez 2 funkcje o tej samej nazwie.
3 obszary startowe zawierają "worki" z figurami- za jedną kryje się następna.
zmienne i, j odpowiadają za położenie ramienia dźwiga, a dx i dy za przesunięcie podnoszonego trójkąta.

Opisy funkcji:
jaki_zaczepiony- funkcja bada, czy ramię znalazło się w strefie zaczepienia i czy próbujemy zaczepić trójkąt. Jeśli tak, umożliwia poruszanie figurą.

czy_mozna_odczepic- funkcja sprawdza, czy jesteśmy w strefie upuszczania ładunku i umożliwia przyczepienie kolejnej figury.

figury- funkcja rysuje 3 wybrane figury w miejscach startowych oraz figurę przyczepioną do dźwiga. 

paint- maluje na nowo obszar rysowania.

repaintWindow- rysuje na nowo pożądane elementy, umożliwiając animację.

tWinMain- główna funkcja.

czy_trojkat- funkcja sprawdza na bazie położenia i zmiennych P1, P2, P3 czy figura, którą zamierzamy podnieść jest trójkątem 

INFORMACJE DLA LISY:
musisz zrobić tak, żeby dało się zrobić wieżę z 3 trójkątów. Myślę, że wystarczy zmieniać warunek gdzie jest platforma i jak nisko i jak daleko w lewo można przesuwać.
figury czasem są o 1 albo 2 piksele za daleko w którąś stronę, a figury na krawędziach wychodzą poza obszar rysowania. Można to poprawić, ale nie trzeba.
