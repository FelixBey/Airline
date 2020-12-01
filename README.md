<div align="center">
  <img width="650" src="https://github.com/FelixBey/Airline/blob/master/data/github_banner.jpg"><br><br>
</div>


# Vorhersage und Interpretation der Kundenzufriedenheit einer Fluggesellschaft mittels Machine Learning

Dies ist das ergänzende Repository zur Seminararbeit "Vorhersage und Interpretation der Kundenzufriedenheit einer Fluggesellschaft mittels Machine Learning" am Lehrstuhl von Prof. Dr. Frédéric Thiesse, Julius-Maximilians-Universität Würzburg.

Zur Reproduktion der Ergebnisse wird die Verwendung von Google Drive zum Entpacken und Speichern der Daten sowie Google Colaboratory für die Ausführung des Codes empfohlen. Der Datensatz wurde einer [Kaggle-Challenge](https://www.kaggle.com/sjleshrac/airlines-customer-satisfaction) entnommen.

## Quick Start

- Lege in der Google Drive ein Google Colaboratory-Notebook an (Neu --> Mehr --> Google Colaboratory)

- Verbinde Notebook mit Google Drive:
```python
from google.colab import drive
drive.mount('/content/drive')
```

- Wechsle Verzeichnis zu Google Drive:
```python
cd 'drive/My Drive'
```

- Kopiere GitHub-Repository in Google Drive:
```python
! git clone https://github.com/FelixBey/Airline.git
```

Nach dem Ausführen dieser Schritte sollten die Notebooks mit Daten und trainierten Modellen im Zielordner 'Airline' abliegen. Die Ergebnisse der Arbeit können nun repliziert werden:

- Führe zuerst das
[EDA and Preprocessing-Notebook](https://github.com/FelixBey/Airline/blob/master/EDA%20and%20Preprocessing.ipynb)
aus
- Anschließend können die Notebooks mit verschiedenen *Machine Learning*-Ansätzen ausgeführt werden

