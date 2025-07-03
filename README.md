# EET Analyse App

Diese App erlaubt es, eine ISIN einzugeben und eine grafische sowie statistische Analyse zu den folgenden Nachhaltigkeitskennzahlen durchzuführen:

- Vorvertragliche nachhaltige Mindestinvestitionen (in %)
- Tatsächliche nachhaltige Mindestinvestitionen (in %)
- CO2 Ausstoß (in MT)

Die App basiert auf einer fest hinterlegten Excel-Datei (`EET_Beispieldaten.xlsx`), die sich im gleichen Verzeichnis wie die `app.py` befinden muss.

## Nutzung

1. Lade das Projekt in Streamlit Cloud oder führe es lokal mit `streamlit run app.py` aus.
2. Gib eine der enthaltenen ISINs ein (siehe Excel-Datei).
3. Die App zeigt dir Histogramm, Boxplot und Kennzahlen für alle drei Variablen zur ISIN.

## Voraussetzungen

Die Abhängigkeiten sind in `requirements.txt` aufgelistet.