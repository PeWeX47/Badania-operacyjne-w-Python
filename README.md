# Badania-operacyjne-w-Python

Repozytorium zawiera przykłady zastosowania algorytmów optymalizacyjnych w języku Python, z wykorzystaniem bibliotek Numpy, SciPy i PuLP.

## Algorytm węgierski
Ten notebook prezentuje zastosowanie algorytmu węgierskiego do rozwiązania problemu przypisania. <br>
*MPK zamierza przekształcić cztery warsztaty naprawcze taboru w specjalizowane punkty obsługi czterech typów samochodów osobowych: forda, volkswagena, toyoty i fiata. Dana jest macierz, której elementy oznaczają przeciętny czas remontu (w dniach) samochodu j-tego typu w i-tym warsztacie. <br><br>
![image](https://github.com/PeWeX47/Badania-operacyjne-w-Python/assets/93322616/8ea7ca15-10c6-4b12-99d4-36391d731971)
<br><br>
Nalezy przydzielić remonty wymienionych typów samochodów poszczególnym punktom obsługi optymalnie z punktu widzenia minimalizacji łącznego czasu wykonywania remontów.*

## Algorytm transportowy
Ten notebook przedstawia zastosowanie algorytmu transportowego do opracowania planu transportu produktów z fabryk do magazynów z minimalizacją kosztów. <br>
*Firma produkcyjna ma trzy fabryki (F1, F2, F3), które produkują różne produkty. Produkty te muszą być dostarczone do trzech magazynów (M1, M2, M3), z których zostaną przetransportowane do klientów. <br>
Poniżej znajduje się lista fabryk, magazynów oraz koszty transportu między nimi:*

*Koszty transportu:*

|    | M1 | M2 | M3 |
|----|----|----|----|
| F1 | 10 | 20 | 15 |   
| F2 | 18 | 12 | 20 |   
| F3 | 25 | 24 | 10 |   

*Dostępność jednostkowa produktów w fabrykach: F1 (60), F2 (40), F3 (90)
Zapotrzebowanie w magazynach: M1 (50), M2 (60), M3 (80)*

*Celem jest opracowanie planu transportu, który spełnia powyższe ograniczenia dostępności i popytu oraz minimalizuje łączny koszt transportu.*

## Wymagania
Przed rozpoczęciem pracy z tymi notebookami i kodem, upewnij się, że spełniasz następujące wymagania:

- **Python**: Wszystkie przykłady zostały napisane w języku Python. Upewnij się, że masz zainstalowanego interpretera Pythona w wersji 3.x.

- **Biblioteki**: Wiele zastosowanych funkcji i algorytmów korzysta z zewnętrznych bibliotek. Upewnij się, że zainstalowałeś je za pomocą narzędzia pip. Możesz to zrobić poprzez uruchomienie poniższych komend:
`
pip install numpy scipy pulp
`
- **Jupyter Notebook**: Aby uruchamiać i modyfikować notatniki Jupyter, zalecane jest zainstalowanie środowiska Jupyter Notebook. Możesz je zainstalować używając komendy:
`pip install jupyter
`

