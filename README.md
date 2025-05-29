# Lastgangprognose
Diese Case Study wurde im Rahmen des Moduls *Business Intelligence & Analytics* im Master Wirtschaftsinformatik an der Hochschule Luzern durchgeführt. Ziel war es, unterschiedliche Prognoseverfahren für den Stromverbrauch eines fiktiven Energieversorgers zu entwickeln und zu vergleichen.

## Modelle
In der Analyse wurden drei Prognosemodelle eingesetzt:

- **SARIMA** – klassische Zeitreihenmodellierung mit Saisonalität
- **SARIMAX** – Erweiterung mit exogenen Variablen (Temperatur)
- **XGBoost** – nicht-lineares Regressionsmodell mit 15-Minuten-Auflösung

## Datenquellen
Die verwendeten Daten basieren auf öffentlich zugänglichen, realitätsnahen Quellen:

- **Stromverbrauchsdaten:** Kanton Basel-Stadt – Open Data Plattform [data.bs.ch](https://data.bs.ch/explore/dataset/100020/table/)
- **Wetterdaten (Lufttemperatur):** MeteoSchweiz – [opendata.swiss](https://opendata.swiss/de/dataset/lufttemperatur-1m)

Die Daten wurden aggregiert und bereinigt, um sie für die Prognosemodelle nutzbar zu machen. Der betrachtete Versorger ist hypothetisch, die Verbrauchswerte und zeitliche Auflösung orientieren sich jedoch an realen Bedingungen.

## Inhalte

- `notebook/` – Hauptanalyse als Jupyter Notebook 
- `data/` – verwendete Datensätze 
- `images/` – verwendete Bilder
