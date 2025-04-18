---
title: Preise
---

Unter dem Reiter **„Palletspace-Preise“** im Bereich **„Standort bearbeiten“** kannst du individuelle Preise für deinen Lagerstandort hinterlegen. Diese Preisangaben sind die Grundlage für automatische Buchungen auf der Plattform. {% .lead %}

---

## Preisstruktur definieren

Die Preislogik auf Palletspace basiert auf **Mengenbereichen**, also Staffelpreisen abhängig von der gebuchten Lagermenge. Du kannst entweder einen allgemeinen Preis für alle Mengen hinterlegen oder gestaffelte Preise für bestimmte Mengenabschnitte definieren.

---

### Allgemeiner Preis (Standard)

Wenn du nur einen einzigen Preis für alle Bestellungen festlegen möchtest:

- **Menge beginnt bei:** 1
- **Menge endet bei:** leer lassen  
  → Gilt automatisch für alle Bestellungen, unabhängig vom Volumen

---

### Staffelpreise (Mengenbereiche)

Für differenzierte Preise nach Lagervolumen legst du mehrere Mengenbereiche an:

Beispiel:

- **Mengenbereich 1:**
    - Menge beginnt bei: 1
    - Menge endet bei: 1.000
    - Definiere Preise für diesen Bereich

- **Mengenbereich 2:**
    - Menge beginnt bei: 1.001
    - Menge endet bei: leer
    - Definiere separate Preise für größere Buchungen

> Hinweis: Sobald ein zweiter Bereich angelegt wird, gelten die Bereiche exklusiv. Bereiche dürfen sich **nicht überschneiden**.

---

## Preisfelder pro Bereich

Für jeden Mengenbereich sind folgende Preise anzugeben:

### Einlagerung

- **Einlagerung***  
  Nettopreis pro Ladungsträger für die Wareneingangsbuchung

### Auslagerung

- **Auslagerung***  
  Nettopreis pro Ladungsträger für die Warenausgangsbuchung

### Tägliche Lagergebühr pro Ladungsträger

- **CCG1***  
  Nettopreis pro Tag für Paletten mit einer Höhe unter 110 cm

- **CCG2***  
  Nettopreis pro Tag für Paletten mit einer Höhe ab 110 cm

- **Blocklagerung***  
  Nettopreis pro Tag und Quadratmeter bei Blocklagerung

> Alle Preise sind Nettoangaben. Die Abrechnung gegenüber dem Kunden erfolgt automatisch anhand dieser Werte.

---

## Nächste Schritte

- [Kapazitäten festlegen](/docs/capacities-and-pricing)
- [Lager veröffentlichen](/docs/publish-warehouse)
- [Buchungen verwalten](/docs/bookings)
