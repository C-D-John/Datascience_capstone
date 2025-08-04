# IBM Data Science Capstone Project – SpaceX Launch Prediction

Dieses Repository enthält mein Capstone-Projekt im Rahmen des IBM Data Science Professional Certificate. 
Ziel war es, mithilfe öffentlich zugänglicher Daten ein Modell zu entwickeln, das den Erfolg von SpaceX-Starts vorhersagt.

## Projektziel

Vorhersage, ob die erste Stufe der Falcon 9 erfolgreich landen wird – ein entscheidender Faktor für Wiederverwendbarkeit 
und Kosteneffizienz in der Raumfahrt.

## Datenquellen

- **SpaceX API** – Abfrage aktueller Startdaten (JSON)
- **Wikipedia** – Webscraping historischer Launch-Daten mit BeautifulSoup

## Verwendete Technologien

- Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- SQL (SQLite für explorative Abfragen)  
- Folium für interaktive Karten  
- Plotly Dash für Dashboard-Entwicklung  
- Jupyter Notebooks

## Projektinhalte

- **Data Wrangling**: Strukturierung, Bereinigung und Zusammenführung der Daten
- **EDA & Visualisierung**: Scatterplots, Erfolgstrends, Payload-Analysen
- **SQL-Analyse**: Launch-Sites, Erfolgsraten, Booster-Vergleiche
- **Geodatenanalyse**: Kartierung der Launch-Sites mit Folium
- **Dashboard**: Interaktive Visualisierung mit Plotly Dash
- **ML-Modellierung**:
  - Klassifikation mit Logistic Regression, KNN, SVM und Decision Trees
  - Hyperparameter-Tuning mit GridSearchCV
  - Evaluation mit Accuracy-Score und Confusion-Matrix

## Ergebnis

Das beste Modell, ein Decision Tree Classifier, erreicht eine **Genauigkeit von 89 %**. 
Die Ergebnisse zeigen, dass spätere Launches tendenziell erfolgreicher sind – 
daher wäre ein gewichtetes Modell für zukünftige Vorhersagen denkbar.

## Struktur

- `capstone_project_notebook.ipynb`: Hauptprojekt mit EDA, Modellierung und Visualisierung
- Weitere Notebooks zu Webscraping, API-Nutzung, SQL, Folium, Dashboard
- Präsentation: [Abschlusspräsentation (PDF)](./ds-capstone-template-coursera-1.pdf)

## Lernfortschritt

Im Rahmen dieses Projekts habe ich den gesamten Data-Science-Workflow umgesetzt:
Von der Datenerfassung über die Analyse bis zur Vorhersage und Visualisierung – mit echtem Bezug zu einem praktischen Problem.

---

**Projekt von**: Carolin John  
**Abgeschlossen**: März 2025  
🔗 [GitHub-Repository](https://github.com/C-D-John/Datascience_capstone)
