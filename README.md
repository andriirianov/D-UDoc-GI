# U-Doc Digital — Prototyp

Digitales Instrument zur Unterstützung der Beurteilung der Urteilsfähigkeit nach U-Doc (Hermann et al. 2020), mit einem Erweiterungsmodul für den Anwendungsfall Geschlechtsinkongruenz.

> **Entwicklungsstand:** früher Prototyp zur internen Abstimmung. Nicht für den klinischen Einsatz freigegeben.

---

## Projektkontext

Dieses Repository enthält den technischen Prototyp zur Dissertation:

**Entwicklung und Validierung eines digitalisierten Instruments zur Unterstützung der Beurteilung der Urteilsfähigkeit bei Geschlechtsinkongruenz**

- **Doktorand:** Andrii Rianov (Arzt in Weiterbildung Psychiatrie & Psychotherapie, Klinikum Bremen Ost)
- **Institut:** Institut für Biomedizinische Ethik und Medizingeschichte (IBME), Universität Zürich
- **Hauptbetreuung:** Prof. Dr. med. Dr. phil. Nikola Biller-Andorno
- **Operative Betreuung:** Dr. med. Dr. sc. med. Anna Westermair
- **Promotionsart:** Allgemeines Doktorat (Dr. med.), Medizinische Fakultät UZH

Das Konzeptdokument zum Projekt liegt separat vor und ist nicht Teil dieses Repositoriums.

---

## Wissenschaftlicher Rahmen

Der Prototyp setzt das U-Doc als validiertes Kerninstrument um und ergänzt es durch eine modulare Erweiterungsstruktur. Erster Anwendungsfall des Erweiterungsmechanismus ist Geschlechtsinkongruenz.

**Beurteilungsbereiche nach U-Doc:**

1. Erkenntnisfähigkeit (Schwerpunkt: Kognition)
2. Wertungsfähigkeit (Schwerpunkt: Motivation und Emotion)
3. Willensbildung und Willensumsetzung (Schwerpunkt: Volition)

Architektur: Zwei-Schichten-Modell. Der U-Doc-Kern ist im Alleinbetrieb voll funktionsfähig; Erweiterungsmodule docken über eine definierte Schnittstelle an, ohne den Kern zu verändern.

---

## Aktueller Funktionsumfang

Diese Fassung des Prototyps ist eine **stilistische und konzeptionelle Referenz**. Sie zeigt die geplante Bedienlogik und das Layout, ist aber inhaltlich und architektonisch noch nicht der Zielzustand gemäss Entwicklungskonzept.

---

## Bedienung

Es ist keine Installation und kein Server nötig.

**Option A — direkt im Browser über GitHub Pages:**

```
https://andriirianov.github.io/D-UDoc-GI/
```

**Option B — lokal:**

1. Datei `index.html` herunterladen (Repository → grüner *Code*-Button → *Download ZIP*, dann entpacken).
2. `index.html` per Doppelklick öffnen — sie startet in jedem aktuellen Browser (Chrome, Edge, Firefox).

Empfohlene Browser: aktuelle Versionen von Chrome, Edge, Firefox. Kein Internet Explorer.

---

## Datenschutz und Speicherverhalten

Der Prototyp ist bewusst datensparsam:

- **Keine Server-Kommunikation.** Die Anwendung läuft vollständig im Browser. Es werden keine Daten übertragen.
- **Keine Persistenz.** Es wird weder `localStorage` noch `sessionStorage` verwendet; es werden keine Cookies gesetzt und keine Sitzungsdateien heruntergeladen.
- **Sitzungsdaten** existieren ausschliesslich im Arbeitsspeicher des Browsers und sind mit dem Schliessen des Tabs verloren.

Für reale klinische Sitzungen sind die geltenden datenschutz- und dokumentationsrechtlichen Vorgaben der jeweiligen Einrichtung massgeblich. Der Prototyp ist als **Dokumentationshilfe** konzipiert und nicht als Medizinprodukt zertifiziert.

---

## Technische Hinweise

- Eine einzige HTML-Datei, reines HTML, CSS und Vanilla-JavaScript.
- Keine externen Laufzeit-Abhängigkeiten, kein Build-Schritt, kein Framework, keine CDN-Einbindung.
- Diagramme als reines Inline-SVG.

---

## Hinweise zur Erprobung

Wenn Sie diesen Prototyp testen, sind insbesondere Rückmeldungen zu folgenden Punkten hilfreich:

- Verständlichkeit der Bedienführung
- Angemessenheit der Textbausteine
- Lesbarkeit der Übersicht / Druckansicht
- Konzeptionelle Anmerkungen zur geplanten Modularchitektur

Bitte beachten Sie, dass dies eine frühe Fassung ist; sichtbare Lücken im Funktionsumfang sind in der Regel bereits bekannt und Teil der nächsten Meilensteine.

---


## Kontakt

Bei Fragen oder Rückmeldungen zum Prototyp: über das IBME oder direkt an den Doktoranden (E-Mail: andrii.rianov@gmail.com).

---

*Stand: Mai 2026 · IBME, Universität Zürich*
