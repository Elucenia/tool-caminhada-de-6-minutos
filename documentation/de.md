<!-- ELUCENIA technical documentation · caminhada-de-6-minutos · de · no clinical/professional/rights approval -->

# 6-Minuten-Gehtest: vorhergesagte Strecke

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/caminhada-de-6-minutos)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Geschlecht

`sexo`

- `F` — Weiblich
- `M` — Männlich

### Alter

`idade`

Jahre · Bereich: 18–100

### Körpergröße

`altura`

cm · Bereich: 120–220

### Gewicht

`peso`

kg · Bereich: 30–250

### Zurückgelegte Strecke

`dist`

m · optional · Bereich: 0–1000

## Fassung der Methode

Enright/Sherrill 1998:Regression Geschlecht, Alter, Größe/Gewicht,40–80 Jahre; Untergrenze−153/−139m

## Dokumentierte Formel

Männer: (7,57 × Größe cm) − (5,02 × Alter) − (1,76 × Gewicht kg) − 309 m. Untergrenze = Sollwert − 153 m.

Frauen: (2,11 × Größe cm) − (2,29 × Gewicht kg) − (5,78 × Alter) + 667 m. Untergrenze = Sollwert − 139 m.

## Grenzen und Population

Die Enright/Sherrill-Gleichungen wurden bei gesunden Erwachsenen von 40–80 Jahren für den ersten Test nach standardisiertem Protokoll entwickelt. Sie erklären ungefähr 40% der Distanzvariabilität. Vorhersage und Prozentwert sind keine Diagnose; Alter außerhalb des Bereichs oder ein anderes Protokoll erfordern eine andere geeignete Referenz.

## Referenzen

- [Enright PL, Sherrill DL. Reference equations for the six-minute walk in healthy adults. Am J Respir Crit Care Med, 1998.](https://doi.org/10.1164/ajrccm.158.5.9710086)

- [ATS Committee on Proficiency Standards for Clinical Pulmonary Function Laboratories. ATS statement: guidelines for the six-minute walk test. Am J Respir Crit Care Med, 2002.](https://doi.org/10.1164/ajrccm.166.1.at1102)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
