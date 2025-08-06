# Klasyfikacja Sportów z Wykorzystaniem Uczenia Maszynowego

## Cel Projektu
Celem projektu jest zbudowanie i ocena modelu uczenia maszynowego do klasyfikacji obrazów przedstawiających różne dyscypliny sportowe. Projekt ma na celu stworzenie modelu, który potrafi rozpoznać, czy dany obraz przedstawia siatkówkę, piłkę nożną, rugby, pływanie czy golfa.

## Źródło Danych
Dane wykorzystane w projekcie to zbiór obrazów różnych dyscyplin sportowych.

* **Pobieranie danych**: Zbiór danych został pobrany ze źródła online (Google Drive) przy użyciu biblioteki `gdown` i rozpakowany do folderu `data`.

Zbiór danych zawiera łącznie 934 przykłady różnych sportów.
Rozkład klas w zbiorze danych wygląda następująco:
* **Siatkówka (volleyball)**: 165 przykładów
* **Piłka nożna (football)**: 221 przykładów
* **Rugby**: 191 przykładów
* **Pływanie (swimming)**: 179 przykładów
* **Golf**: 178 przykładów

## Dotychczasowe Kroki Realizacji Projektu
### 1. Przygotowanie danych
* **Pobieranie i rozpakowywanie danych**: Pobrano spakowany plik ze zdjęciami, a następnie rozpakowano go do katalogu `data`.
* **Analiza danych**: Przeprowadzono weryfikację wielkości bazy danych oraz rozkładu zdjęć dla poszczególnych dyscyplin sportowych.
* **Wizualizacja danych**: Wyświetlono przykładowe zdjęcia, aby zweryfikować poprawność wczytania danych.

### 2. Implementacja i Ocena Modeli
* **Framework**: Do budowy modelu wykorzystano biblioteki `tensorflow` i `keras`.
* **Architektura modelu**: Zbudowano konwolucyjną sieć neuronową (CNN).
* **Metryki oceny**: Oceniono wydajność modelu na danych testowych. Metrykami takimi jak dokładność, precyzja, czułość oraz macierz pomyłek.
