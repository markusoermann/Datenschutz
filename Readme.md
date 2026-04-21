# Datenschutzrecht: Materialien für die Lehrveranstaltung

Herzlich willkommen im Repository für das Modul **Datenschutzrecht** im Studiengang Digitale Gesellschaft (Bachelor of Science) an der Technischen Hochschule Würzburg-Schweinfurt (THWS). Alle Infos zum Studiengang finden sich unter: https://fiw.thws.de/studium/bachelor-digitale-gesellschaft-bdgd/. 

Dieses Projekt nutzt einen modernen **Single-Source-Publishing-Ansatz** auf Basis von **Quarto**. Aus den hier vorliegenden Markdown-Quelldateien (`.qmd`) werden sowohl interaktive Lernmodule für Moodle als auch statische PDF-Skripte generiert.

## 🎓 Struktur der Lerneinheiten

Das Repository umfasst vier Kapitel, die den Semesterverlauf abbilden:

| Kapitel | Thema | Quelldatei |
|---------|-------|------------|
| 1 | Einführung und Grundfragen | [kap-01-datenschutz-einfuehrung.qmd](kap-01-datenschutz-einfuehrung.qmd) |
| 2 | Rechtsgrundlagen der Datenverarbeitung | [kap-02-datenschutz-rechtsgrundlagen.qmd](kap-02-datenschutz-rechtsgrundlagen.qmd) |
| 3 | Informationspflichten und Betroffenenrechte | [kap-03-datenschutz-betroffenenrechte.qmd](kap-03-datenschutz-betroffenenrechte.qmd) |
| 4 | Technik, Organisation und Durchsetzung | [kap-04-datenschutz-technik-organisation-durchsetzung.qmd](kap-04-datenschutz-technik-organisation-durchsetzung.qmd) |

## 🛠 Interaktive Elemente (Widgets)

Ein besonderes Merkmal dieses Kurses sind die **interaktiven HTML-Widgets**, die direkt in die Skripte eingebettet sind. Sie dienen dazu, komplexe datenschutzrechtliche Abwägungen und technische Abläufe spielerisch zu erkunden.

Die Widgets befinden sich im Verzeichnis `/widgets`, gegliedert nach Kapiteln:

| Widget | Kapitel |
|--------|---------|
| Anwendbarkeits-Prüfer | Kapitel 1 |
| Datenschutz-Grundsätze | Kapitel 1 |
| Personenbezug | Kapitel 1 |
| Daten-Klassifizierung | Kapitel 2 |
| Informationspflichten | Kapitel 3 |
| DSB-Pflicht | Kapitel 4 |
| TOMs & SDM | Kapitel 4 |

## 🚀 Technischer Stack

- **Framework:** [Quarto](https://quarto.org/)
- **Templates:** https://github.com/c-kraus - Mit großem Dank an Prof. Dr. Christian Kraus!
- **Skills für Gemini/Claude:** https://github.com/c-kraus/claude-code-skills - Mit großem Dank an Prof. Dr. Christian Kraus!
- **Output-Formate:** `moodle-html` (via THWS-Erweiterung), `pdf`
- **Widgets:** Vanilla HTML5, CSS3 und JavaScript (Inter UI Font-Stack)

## ✍️ Autor

**Prof. Dr. Markus Oermann**  
Professor für Digitale Ethik und Medienrecht  
Fakultät Informatik und Wirtschaftsinformatik  
Technische Hochschule Würzburg-Schweinfurt (THWS)  
[markus.oermann@thws.de](mailto:markus.oermann@thws.de)