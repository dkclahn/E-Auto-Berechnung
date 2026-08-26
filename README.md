# E-Auto-Berechnung


[![Python](https://img.shields.io/badge/python-3.9%2B-blue)]()
[![License](https://img.shields.io/badge/license-MIT-green)]()
[![Notebook](https://img.shields.io/badge/jupyter-notebook-orange)]()

Kurze Beschreibung
------------------
Berechnung von E Auto Kosten im Vergleich zum aktuellen Auto

Inhaltsverzeichnis
------------------
- [Technologien](#technologien)
- [Quickstart](#quickstart)
- [Daten](#daten)


Technologien
------------
- Python 3.9+
- pandas, odfpy
- Jupyter Notebook

Quickstart
----------
1. Repository clonen:
```bash
git clone https://github.com/dkclahn/E-Auto-Berechnung.git
cd E-Auto-Berechnung
```

2. Virtuelle Umgebung anlegen und aktivieren:
```bash
python -m venv .venv
# macOS / Linux:
source .venv/bin/activate
# Windows (PowerShell):
.venv\Scripts\Activate.ps1
```

3. Abhängigkeiten installieren:
```bash
pip install -r requirements.txt
```
(Hinweis: Falls `requirements.txt` noch fehlt, erstelle es z. B. mit `pip freeze > requirements.txt` nachdem du lokal installiert hast.)

4. Notebook starten:
```bash
jupyter notebook
```
Öffne dann `notebooks/E-Auto vergleich.ipynb` (oder das entsprechende Notebook).

Daten
-----
- Beschreibe hier, welche Dateien benötigt werden (z. B. `data/e autos.ods`) und die erwarteten Spalten, z. B.:
  - name: Automodell
  - Kaufpreis: Preis als Zahl in Euro
  - Verbrauch: Durchschnittlicher Verbrauch des E-Autos als Zahl in kWh/100 km
  - Reichweite: Zahl in km
  - SOH: Prozentzahl der Batterie Leistung in Bezug auf originale Leistung
  - Erstzulassung: Jahr der Erstzulassung
  - km Stand: aktueller km Stand als Zahl
- Falls die Daten sensibel sind: den Beispieldatensatz im Ordner benutzen
