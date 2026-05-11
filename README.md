# Numeryczne rozwiązywanie równań różniczkowych zwyczajnych w Pythonie

Repozytorium przedstawia numeryczne rozwiązywanie równań różniczkowych zwyczajnych (ODE) z wykorzystaniem języka Python oraz bibliotek naukowych.

W projekcie zaimplementowano metodę Eulera i porównano rozwiązania numeryczne z rozwiązaniem symbolicznym wyznaczonym przy użyciu biblioteki SymPy. Przeprowadzono również analizę wpływu kroku czasowego na dokładność rozwiązania.

Dodatkowo przeanalizowano wybrane układy dynamiczne, takie jak model Lotki–Volterry opisujący zależność pomiędzy populacją drapieżników i ofiar oraz układ Lorenza ilustrujący zjawiska chaotyczne.

## Cel projektu

Celem projektu było zastosowanie metod numerycznych do rozwiązywania równań różniczkowych zwyczajnych oraz analiza zachowania wybranych modeli matematycznych.

## Zakres analizy

Projekt obejmuje:

- implementację metody Eulera,
- porównanie rozwiązania numerycznego i symbolicznego,
- analizę dokładności metody dla różnych kroków czasowych,
- model Lotki–Volterry,
- układ Lorenza,
- wizualizację wyników w środowisku Jupyter Notebook.

## Wykorzystane technologie

- Python
- NumPy
- SciPy
- SymPy
- Matplotlib
- Jupyter Notebook

## Czego nauczyłam się podczas projektu

Podczas realizacji projektu nauczyłam się:

- implementacji metod numerycznych do rozwiązywania równań różniczkowych,
- porównywania rozwiązań numerycznych i symbolicznych,
- analizy wpływu kroku czasowego na dokładność rozwiązania,
- modelowania wybranych układów dynamicznych,
- wizualizacji wyników obliczeń z wykorzystaniem biblioteki Matplotlib,
- wykorzystania bibliotek naukowych do analizy numerycznej w Pythonie.

## Wizualizacje wyników

### Porównanie rozwiązania numerycznego i dokładnego

Porównanie rozwiązania uzyskanego metodą Eulera z rozwiązaniem dokładnym równania różniczkowego.

![Porównanie rozwiązania](images/wykres_porownanie.png)

### Analiza dokładności metody Eulera

Wpływ kroku czasowego na maksymalny błąd rozwiązania numerycznego.

![Analiza dokładności](images/wykres_dokladnosc.png)

### Układ Lorenza

Wizualizacja atraktora Lorenza przedstawiającego zachowanie układu chaotycznego.

![Atraktor Lorenza](images/wykres_atraktor.png)

## Uruchomienie projektu

1. Sklonuj repozytorium:

```bash
git clone https://github.com/olganalytics/ordinary-differential-equations-python.git
```

2. Przejdź do folderu projektu:

```bash
cd ordinary-differential-equations-python
```

3. Zainstaluj wymagane biblioteki:

```bash
pip install numpy scipy sympy matplotlib jupyter
```

4. Uruchom Jupyter Notebook:

```bash
jupyter notebook
```

5. Otwórz plik:

```text
numerical_ode_analysis.ipynb
```

6. Uruchom wszystkie komórki notebooka.
