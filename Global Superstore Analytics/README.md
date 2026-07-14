# Global Superstore Analytics

<br>

## Źródło danych: 
- https://www.kaggle.com/datasets/fatihilhan/global-superstore-dataset
- https://www.kaggle.com/datasets/andradaolteanu/country-mapping-iso-continent-region

<br>

## Wykorzystane ikony:
https://fonts.google.com/icons

<br>

## Cel projektu:
Celem projektu była analiza zbioru danych dotyczącego zamówień w globalnym sklepie po pod kątem rentowności, logistyki dostaw, oferowanego asorytmentu oraz zachowań klientów.

<br>

## Struktura projektu:
### Strona główna -prezentująca najważniejsze informacje sprzedażowe oraz umożliwiająca nawigację:
- karty wskażników: wartość przychodu oraz dochodu, łączna liczba zamówień, unikalnych produktów oraz unikalnych klientów,
- wizualizacja liczby zamówień z podziałem na kraje przedstawiona na interaktywneh mapie,
- przyciski przenoszące do kolejnych stron raportu.
<img width="1440" height="806" alt="home" src="https://github.com/user-attachments/assets/b1938c62-fc95-4512-9e07-5a8af9ff9c99" />
<br>
<br>
<br>

### Analiza sprzedaży - zawierającą informacje o rentowności firmy:
- karty wskaźników: wartość przychodu oraz dochodu, marża zysku, łączna liczba zamówień, liczba sprzedanych przedmiotów,
- interaktywne filtry: rok, region, kategoria przedmiotu
- wizualizacja trendu dochodu w kolejnych miesiącach,
- wizualizacja 5 najbardziej dochodowych pod kategorii oferowanego asortymentu,
- wizualizacja 10 najbardziej dochodowych krajów.
<br>
<img width="1442" height="810" alt="sales" src="https://github.com/user-attachments/assets/866e7353-fd2b-4267-a35f-2a99c8f1a735" />
<br>
<br>
<br>

### Logistyka i łańcuch dostaw - zawierającą informacje o składanych zamówieniach oraz dostawach:
- karty wskaźników: łączna liczba zamówień, wartość dochodu, liczba krajów, średni czas dostawy oraz średnia ilość przedmitów w zamówieniu
- interaktywne filtry: rok, region, kategoria przedmiotu oraz priorytet zamówienia
- wizualizacja 10 krajów z największymi kosztami dostaw zestawiona z wartościa dochodu z zamówień,
- wizualizacja prezentująca ilość zamówień z podziałem na tryb dostawy,
- wizualizacja trendu średniego czasu dostawy zamówienia w kolejnych miesiącach,
- wizualizacja liczby zamówień z podziałem na segmenty klientów (klienci indywidualni, korporacje, biura domowe).
<br>
<img width="1432" height="808" alt="products (1)" src="https://github.com/user-attachments/assets/d6390574-1239-4fb9-8ed6-7bf455f947ed" />
<br>
<br>
<br>

### Efektywność Produktów - zawierającą informacje o najbardziej dochodowych i najczęsciej kupowanych produktach:
- karty wskaźników: liczba unikalnych produktów, wartośc dochodu, łączna liczba zamówień, liczba sprzedanych przedmiotów, średnia cena produktu
- interaktywne filtry: rok, region, segment klienta,
- wizualizacjaprzedstawiająca strukturę hierarchiczną asortymentu (z podziałem na kategorie i podkategorie)
- wizualizacja prezentująca 5 najbardziej dochodowych produktów,
- wizualizacja prezentująca 5 najczęsciej kupowanych produktów.
<br>
<img width="1436" height="810" alt="logistis" src="https://github.com/user-attachments/assets/96e1f4df-08df-4534-a34c-1b0f0017af8d" />
<br>
<br>
<br>

### Analiza klientów - zawierającą informacje o współpracach z klientami przynoszącymi największe zyski i straty:
- karty wskaźników: liczba unikalnych klientów, wartość dochodu, średnia liczba zamówień przypadająca na klienta, średnia wartość zamówienia oraz średnia ilość przedmitów w zamówieniu
- interaktywne filtry: rok, segment klienta, imię i nazwisko klienta
- wizualizacja prezentująca udział dochodu z podziałem na segment klienta oraz regionu,
- wizualizacja prezentująca 10 najbardziej dochodowych współprac z klientami,
- wizualizacja prezentująca 10 najmniej dochodowych współprac z klientami.
<br>
<img width="1440" height="806" alt="client" src="https://github.com/user-attachments/assets/2afa681a-d622-41e6-ba2c-5fbb9d3b180e" />
<br>
<br>
<br>

### Boczne menu nawigacji:
- typu "hamburger" zrealizowane z wykorzystaniem zakładek.
<br>
<img width="1438" height="808" alt="menu" src="https://github.com/user-attachments/assets/efb2de5c-3e84-4111-91b7-1e0e268e53a0" />
<br>
<br>
<br>

### Wnioski:
- Dynamiczny wzrost dochodu (2011 vs 2014) - Przedsiębiorstwo wykazuje dwukrotny wzrost dochodu na przestrzeni analizowanych lat przy prawie niezmiennej wartości marży zysku, co wskazuje na dynamiczny rozwój i skuteczną ekspansję firmy.
- Kluczowe rynki - Główne dochody przedsiębiorstwa stanowią zamówienia realizowane w Stanach Zjednoczonych, Chinach, Indiach, Wielkiej Brytanii i Francji.
- Problemy logistyczne - Mimo, że Stany Zjednoczone generują prawie dwukrotny zysk względem drugiego kraju w zestawieniu (Chiny), to pod względem dochodu koszty logistyczne są wyjątkowo wysokie W USA dochód jest porównywalny z kosztami logistycznymi, podczas gdy w Chinach koszty logistyczne są prawie dwukrotnie niższe niż dochód. Sugeruje to pilną potrzebe optymalizacji logistycznej lub zmiany sposobów wysyłki w Ameryce Północnej.
- Oferowany asortyment - Pośród oferowanych kategorii produktów (Zaopatrzenie biurowe, Technologia, Meble) meble generują zaledwie 1/6 uzyskiwanych przychodów, co wynika z marży zysku na poziomie 7% (przy około 14% w pozostałych kategoriach) oraz kosztów dostawy wynoszących około 150% uzyskanego dochodu. Dane te sugerują potrzebę zmiany cen tych produktów oraz sposobów dostawy, a w przypadku braku poprawy całkowitą rezygnację z ich sprzedaży.
- Analiza klientów - Dane wskazują na dwukrotny wzrost częstotliwości składania zamówień przez dotychczasowych klientów na przestrzeni lat 2011–2014. Jednocześnie jednak firma nie pozyskuje nowych konsumentów, co w dłuższej perspektywie może znacząco hamować dalszy rozwój przedsiębiorstwa i uzależnia organizację od obecnych odbiorców.
