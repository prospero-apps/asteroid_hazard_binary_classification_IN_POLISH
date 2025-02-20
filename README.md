# asteroid_hazard_binary_classification_IN_POLISH
Klasyfikacja binarna - Przewidywanie zagrożenia uderzenia asteroidy w Ziemię na podstawie parametrów asteroidy

Celem niniejszej analizy jest zbudowanie i porównanie kilku modeli uczenia maszynowego, których zadaniem jest klasyfikacja binarna asteroid na podstawie dostarczonych danych jako obiektów, które zagrażają lub nie zagrażają zderzeniem z Ziemią.

## Spis treści:

### 1. Zbieranie danych
Analiza będzie oparta na zbiorze danych 'NASA: Asteroids Classification' dostępnym na kaggle.com. Dane objęte są licencją CC0: Public Domain. Dane pochodzą z CNEOS (Center for Near Earth Object Studies, http://neo.jpl.nasa.gov/), który jest ośrodkiem NASA zajmującym się obliczaniem orbit asteroid i komet oraz prawdopodobieństwa zderzenia tych obiektów z Ziemią. API utrzymywane jest przez zespół SpaceRocks w składzie: David Greenfield, Arezu Sarvestani, Jason English i Peter Baunach.

![image](https://github.com/user-attachments/assets/e7892128-fcec-4fae-a5c3-435e76200521)

### 2. Eksploracyjna analiza danych (Exploratory Data Analysis, EDA) i inżynieria cech (Feature Engineering)
Na tym etapie dokonamy jedynie wstępnej analizy danych. W dalszej kolejności przyjrzymy się danym dokładniej i dokonamy ich wizualizacji. Wtedy, o ile będzie to wskazane, ponownie przeprowadzimy niektóre z powyższych czynności, takie jak usunięcie zbędnych wierszy i kolumn czy transformacje danych.

![image](https://github.com/user-attachments/assets/d67a6785-cc80-4535-902b-4173e83136d2)

### 3. Trenowanie modeli
Wytrenujemy kilka modeli, a następnie porównamy je za pomocą łatwych do zrozumienia metryk. Będą to zarówno modele tradycyjnego uczenia maszynowego (machine learning), jak i uczenia głębokiego (deep learning).

![image](https://github.com/user-attachments/assets/2025454f-c50c-4a7b-9d17-40afba3c8ca1)

