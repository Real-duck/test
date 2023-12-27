---
weight: 1 
date: "2019-09-18T21:57:17-07:00"
title: "CellAlyse"
image: "CellAlyse.png"
color: "#0c1023"
type: "github"
github:
    repo: "CellAlyse/CellAlyse"
    showInfo: false
terminal:
    lines:
    - type: input
      data: mkdir CellAlyse
      wait: 200
    - type: input
      data: cd CellAlyse
      wait: 200
    - type: input
      data: git clone https://github.com/CellAlyse/CellAlyse
      wait: 300
    - type: progress
      data: 100
      wait: 1000
    - data: ☕ Fertig! Viel Spaß beim Zählen!
      wait: 900
    - type: input
      data: exit
      wait: 500
---

CellAlyse revolutioniert die Bluttypisierung durch Automatisierung. Es erreicht eine beeindruckende Segmentierungsgenauigkeit von rund 95% und eine Zählgenauigkeit von 97%, was es zum einzigen Modell macht, das praktisch anwendbar ist. Dank seiner innovativen Architektur, die Überlappungen identifizieren kann, ermöglicht CellAlyse die Automatisierung komplexer Analysen bei Krankheiten wie Leukämie und Anämie.