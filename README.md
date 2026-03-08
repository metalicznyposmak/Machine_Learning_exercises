# Machine Learning Exercise

Repozytorium zawiera materiały i notebooki Jupyter przygotowane w ramach nauki podstaw machine learningu. Projekt ma charakter edukacyjny i skupia się na przetwarzaniu danych oraz wprowadzeniu do metod uczenia nadzorowanego, ze szczególnym naciskiem na regresję liniową.

## Cel projektu

Celem repozytorium jest uporządkowanie ćwiczeń z bootcampu ML w jednym miejscu i pokazanie podstawowego workflow pracy z danymi:

- przygotowanie i czyszczenie danych
- obsługa brakujących wartości
- ekstrakcja i kodowanie cech
- podział danych na zbiory treningowe i testow
- pierwsze modele regresji liniowej.

## Struktura repozytorium

```text
MLBootcamp1/
├── intro.ipynb
└── supervised/
    ├── 01_basics/
    │   ├── 01_preprocessing.ipynb
    │   ├── 02_missing_values.ipynb
    │   ├── 03_feature_extraction.ipynb
    │   └── 04_train_test_split.ipynb
    └── 02_regression/
        ├── 01_linear_regresion_normal_equation.ipynb
        ├── 02_gradient_descent.ipynb
        └── 03_linear_regression.ipynb
```

## Zakres materiału

### 1. Podstawy pracy z danymi
W części `supervised/01_basics` znajdują się notebooki dotyczące podstaw przygotowania danych do modelowania:

- preprocessing danych
- praca z brakującymi wartościami
- feature extraction
- train/test split

### 2. Regresja
W części `supervised/02_regression` znajdują się materiały wprowadzające do regresji liniowej:

- równanie normalne
- gradient descent
- klasyczna implementacja linear regression

## Technologie i biblioteki

Projekt jest oparty o notebooki Jupyter i środowisko Python. W ćwiczeniach wykorzystywane są między innymi:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Czego można się nauczyć

Repozytorium dobrze nadaje się jako baza do powtórki lub nauki następujących zagadnień:

- konwersja i analiza typów danych,
- kodowanie zmiennych kategorycznych,
- użycie `LabelEncoder` i `OneHotEncoder`,
- praca z `SimpleImputer`,
- przygotowanie danych do trenowania modeli,
- podstawy regresji liniowej.

## Jak uruchomić

### Wymagania

- Python 3.x
- Jupyter Notebook lub JupyterLab

### Instalacja zależności

```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook
```
Następnie otwórz wybrany notebook i uruchamiaj komórki krok po kroku.


### Proponowany opis repozytorium

Materiały z bootcampu ML w Pythonie: preprocessing danych, missing values, feature extraction oraz podstawy regresji liniowej w notebookach Jupyter.
