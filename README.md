Link do 1 zajęć:

* https://colab.research.google.com/drive/1zOnRZfEWfA7JXe7K_H7Wfc57dNd91Eop?usp=sharing
* https://colab.research.google.com/drive/14ka-dj8HdD1hCq8unMMg5r020zS_I1GT?usp=sharing

Formularz na kod:
* https://forms.gle/x2ZVJ6CcK9aUUnHi8


# PODSTAWY-UCZENIA-MASZYNOWEGO-W-PYTHONIE-

Opis programu zajęć: 

* Wprowadzenie do Pythona środowiska google colab i podstawowe informacje o wizualizacji danych.
* Populacje i próby. Charakterystyki prób i odpowiadające im statystyki: średnia, wariancja, odchylenie standardowe, kwantyle.
* Wprowadzenie do uczenia maszynowego, uczenie nadzorowane.
* Prosta prognoza: Regresja liniowa i logistyczna, klasyfikacja i klastrowanie.
* Analiza i oczyszczanie danych i dzielenie na zbiór uczący i testowy. Pojęcie zbalansowania zbioru.
* Jednokierunkowe sieci neuronowe, perceptron.
* Konwolucyjne sieci neuronowe.
* Ucznie nienadzorowane.



import pandas as pd

df = pd.read_csv('https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv')

### Zadanie 2

1. Wczytaj ramkę titanic.csv 
2. Sprawdź ile jest wierszy w tej ramce. 
3. Policz średnią wieku osób na Tytanicu. 
4. Narysuj histogram dla wieku osób będącnych na titanicu. 
5. Jaka jest mediana dla wieku osób będących na titanicu? 
6. Odfiltruj te osoby, które były w 3 klasie pasażerów, ile jest takich osób? 
7. Ile osób przetrwało tą tragedię, ile spośród nich było kobietami? 
8. Ile było kobiet a ile facetów na pokładzie tytanica? Narysuj histogram. 
9. Ile osób było pełnoletnich, narysuj dla ich wieku histogram? 
10. Użyj metody .describe(), ile lat ma najstarsza i najmłodsza osoba na titanicu?
