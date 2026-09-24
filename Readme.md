# Datenschutzrecht: Materialien für die Lehrveranstaltung

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22932605.svg)](https://doi.org/10.5281/zenodo.22932605)

Herzlich willkommen im Repository für das Modul **Datenschutzrecht** im Studiengang Digitale Gesellschaft (Bachelor of Science) an der Technischen Hochschule Würzburg-Schweinfurt (THWS). Alle Infos zum Studiengang finden sich unter: https://fiw.thws.de/studium/bachelor-digitale-gesellschaft-bdgd/. 

Dieses Projekt nutzt einen modernen **Single-Source-Publishing-Ansatz** auf Basis von **Quarto**. Aus den hier vorliegenden Markdown-Quelldateien (`.qmd`) werden sowohl interaktive Lernmodule für Moodle als auch statische PDF-Skripte generiert.

## 🎓 Struktur der Lerneinheiten

Das Repository umfasst vier Kapitel, die den Semesterverlauf abbilden:

| Kapitel | Thema | Quelldatei |
|---------|-------|------------|
| 1 | Einführung und Grundfragen | [01_datenschutz_einfuehrung.qmd](01_datenschutz_einfuehrung.qmd) |
| 2 | Rechtsgrundlagen der Datenverarbeitung | [02_datenschutz_rechtsgrundlagen.qmd](02_datenschutz_rechtsgrundlagen.qmd) |
| 3 | Informationspflichten und Betroffenenrechte | [03_datenschutz_betroffenenrechte.qmd](03_datenschutz_betroffenenrechte.qmd) |
| 4 | Technik, Organisation und Durchsetzung | [04_datenschutz_technik_organisation_durchsetzung.qmd](04_datenschutz_technik_organisation_durchsetzung.qmd) |

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

## 📌 Zitation & DOI

Jedes Release dieses Repositories wird auf Zenodo archiviert und erhält eine zitierfähige DOI. Der Badge oben verweist auf die *Concept-DOI*, die immer auf die neueste Version auflöst.

- **Concept-DOI (alle Versionen):** [10.5281/zenodo.22932605](https://doi.org/10.5281/zenodo.22932605)
- **Diese Version (SoSe 26, v1.0.0):** [10.5281/zenodo.22932606](https://doi.org/10.5281/zenodo.22932606)

> Oermann, M. (2026). *Datenschutzrecht: Kursmaterialien* (Version 1.0.0) [Lehrmaterial]. Zenodo. https://doi.org/10.5281/zenodo.22932605

```bibtex
@misc{oermann_datenschutz_2026,
  author       = {Oermann, Markus},
  title        = {Datenschutzrecht: Kursmaterialien},
  year         = {2026},
  version      = {1.0.0},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.22932605},
  url          = {https://doi.org/10.5281/zenodo.22932605}
}
```

## ✍️ Autor

**Prof. Dr. Markus Oermann**  
Professor für Digitale Ethik und Medienrecht  
Fakultät Informatik und Wirtschaftsinformatik  
Technische Hochschule Würzburg-Schweinfurt (THWS)  
[markus.oermann@thws.de](mailto:markus.oermann@thws.de)