# 📊 Inventuroptimierung im Einzelhandel
### Datenbasierte Analyse zur Verbesserung der Bestandsgenauigkeit

---

## 🎯 Zielsetzung
Entwicklung eines datenbasierten Konzepts zur Verbesserung der Bestandsgenauigkeit im Einzelhandel — basierend auf Praxiserfahrung im filialbasierten Einzelhandel (Lidl, TEDi).

---

## 📁 Projektstruktur

|
`Inventur Optimization.xlsx`
,
 Excel-Analyse mit 8 Sheets 
|
`Inventur Optimization.pbix`
,
 Interaktives Power BI Dashboard 
|
`Dashboard_PowerBI.png`
,
 Screenshot: Power BI Dashboard 
|
`Dashboard_Filtered.png`
,
 Screenshot: Gefiltertes Dashboard 
|
`Dashboards.jpg`
,
 Screenshot: Excel Dashboard 
|
`ABC Pareto Diagram.jpg`
,
 Screenshot: ABC-Analyse 
|

---

## 📊 Datengrundlage
- **900 simulierte Inventurdatensätze**
- 5 Filialen | 15 Milchprodukte | 12 Monate
- Realistische Schwundmuster basierend auf Praxiserfahrung
- Modellierte Effekte: Diebstahl, Kassenfehler, Verderb, MHD-Prozessfehler, saisonale Schwankungen

---

## 🔧 Methoden & Analysen

### Excel (8 Sheets):
Stammdaten 
|
 Master Data: Filialen, Artikel, Monate, Parameter 
|
|
 Rohdaten 
|
 900 Zeilen Inventurdaten mit 26+ Spalten 
|
|
 ABC-Analyse 
|
 Pareto-Analyse: 20% der Artikel → 78% des Schwunds 
|
|
 Schwundanalyse 
|
 6 Pivot Tables: Filiale, Monat, Kategorie, Typ, Ereignis, MHD 
|
|
 Ursachenanalyse 
|
 Root-Cause-Klassifikation der Bestandsabweichungen 
|
|
 Prognose 
|
 Moving Average Forecast für zukünftige Schwund-Vorhersage 
|
|
 Dashboard 
|
 KPI-Übersicht mit Charts 
|
|
 Ergebnisse 
|
 Zusammenfassung und Handlungsempfehlungen 
|

### Power BI:
- 4 KPI Cards (Gesamtschwund, Bestandsgenauigkeit, Schwundquote, Schwund-Fälle)
- Interaktive Charts (Filiale, Monat, Kategorie, Abweichungstyp)
- Cross-Filtering: Klick auf jedes Element filtert alle anderen Visuals

---

## 📈 Kernergebnisse

|
 Ergebnis 
|
 Detail 
|
|

|
|
**
Filiale Zentrum
**
|
 Höchster Schwund-Wert (25.7%) — Diebstahlrisiko im Stadtgebiet 
|
|
**
Dezember & April
**
|
 Höchste saisonale Peaks (Weihnachten & Ostern) 
|
|
**
Joghurt & Milch
**
|
 Meister Schwund — kurze Haltbarkeit (7-14 Tage) 
|
|
**
74% Schwund
**
|
 Mehrheit der Datensätze zeigt negative Bestandsabweichung 
|
|
**
17% Überbestand
**
|
 Kassenfehler-bedingte positive Abweichungen 
|
|
**
15% MHD-Fehler
**
|
 Prozessfehler bei MHD-Reduzierung (Zählfehler, FIFO, Eingabefehler) 
|
|
**
Freitag + Samstag
**
|
 55% des wöchentlichen Schwunds 
|

---

## 💡 Handlungsempfehlungen

1. **A-Artikel wöchentlich zählen** → 78% des Schwunds kontrolliert
2. **MHD-Prozess automatisieren** → Scanner statt manuelles Zählen
3. **Diebstahlprävention in Filiale Zentrum** → Höchster Schwund-Standort
4. **Kassenschulungen** → Reduzierung von Kassenfehler-bedingten Abweichungen
5. **MHD-Checks morgens** → Vor Kundenansturm (Fr/Sa)
6. **FIFO konsequent umsetzen** → Weniger versteckte abgelaufene Ware
7. **Bestellmengen anpassen** → Bei hoher Reduzierungsquote
8. **Forecast für A-Artikel priorisieren** → Bessere Prognose

---

## 🖼️ Screenshots

### Power BI Dashboard
<img width="2116" height="1185" alt="Dashboard_PowerBI" src="https://github.com/user-attachments/assets/fb49765d-4c8b-4603-87b1-5dc6a0f91a8f" />


### Power BI — Gefiltert (Filiale Zentrum)
<img width="2110" height="1181" alt="Dashboard_Filtered" src="https://github.com/user-attachments/assets/10986243-b532-4cfd-b09b-b3ac3b8982da" />


### Excel Dashboard
<img width="1131" height="1072" alt="Dashboards" src="https://github.com/user-attachments/assets/88eb2d91-68ec-40e9-960d-0b14786808b4" />


### ABC-Analyse
<img width="1317" height="798" alt="ABC Pareto Diagram" src="https://github.com/user-attachments/assets/c6f09b5a-2334-45dd-b4f0-a5a6377ae1d9" />


---

## 🛠️ Tools
- Microsoft Excel (Pivot Tables, VLOOKUP, SUMIFS, Bedingte Formatierung, Diagramme)
- Microsoft Power BI (KPI Cards, Bar/Column/Donut Charts, Cross-Filtering, DAX Measures)

---

## 👤 Autor
**Akshat Garg**
- Masterstudent Technische Logistik | Universität Duisburg-Essen
- [LinkedIn](https://www.linkedin.com/in/akshatgargde)
- akshatgarg2706@gmail.com

---

## 📝 Kontext
Dieses Projekt wurde eigenständig entwickelt, basierend auf Praxiserfahrung als Werkstudent im filialbasierten Einzelhandel (Lidl, TEDi). Die Daten sind simuliert, aber die Muster und Ursachen spiegeln reale Beobachtungen wider.
