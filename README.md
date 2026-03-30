<div align="center">

  <img src="./images/00-haos-view-dark.png" alt="HAOS Material You Dock Preview" width="100%">

  <h1>HAOS Material You Dock</h1>

  <p>Modernes Home Assistant UI im Material You Stil mit Bottom Dock, Swipe Tabs und modularen Feature Cards.</p>

  <p>
    <img src="https://img.shields.io/badge/Home_Assistant-Dashboard-41BDF5?style=for-the-badge&logo=homeassistant&logoColor=white">
    <img src="https://img.shields.io/badge/style-Material_You-8b9cf6?style=for-the-badge">
    <img src="https://img.shields.io/badge/license-MIT-black?style=for-the-badge">
    <img src="https://img.shields.io/badge/platform-Android_%26_iOS-4caf50?style=for-the-badge&logo=android&logoColor=white">
  </p>

  <p>
    <a href="https://github.com/Mxipe07/HAOS-Material-You-Dock-Erweiterungen/stargazers">
      <img src="https://img.shields.io/github/stars/Mxipe07/HAOS-Material-You-Dock-Erweiterungen?style=social" alt="GitHub Stars">
    </a>
    <a href="https://github.com/Mxipe07/HAOS-Material-You-Dock-Erweiterungen/issues">
      <img src="https://img.shields.io/github/issues/Mxipe07/HAOS-Material-You-Dock-Erweiterungen" alt="Open Issues">
    </a>
    <a href="https://github.com/Mxipe07/HAOS-Material-You-Dock-Erweiterungen/commits">
      <img src="https://img.shields.io/github/last-commit/Mxipe07/HAOS-Material-You-Dock-Erweiterungen" alt="Last Commit">
    </a>
  </p>

</div>

---

## Überblick

**HAOS Material You Dock** ist ein modernes, mobiles Dashboard-UI für Home Assistant.  
Das Projekt enthält wiederverwendbare YAML-Komponenten für:

- Bottom Dock Navigation
- Swipe Tabs / Filterleisten
- Feature Cards

Optimiert für **Dark Mode / Light Mode**.

---

## Vorschau

### Dashboard

| Dark Mode | Light Mode |
|---|---|
| ![Dark](./images/00-haos-view-dark.png) | ![Light](./images/00-haos-view-light.png) |

---

## Komponenten

### Bottom Dock Navigation

| Dark | Light |
|---|---|
| ![Dark](./images/01-bottom-dock-dark.png) | ![Light](./images/01-bottom-dock-light.png) |

Fixierte Navigation am unteren Bildschirmrand mit Animationen und Theme-Anpassung.

**Datei:** `01-bottom-dock.yaml`

**Anpassbar:**
- `navigation_path`
- Icons
- Labels
- Avatar / Profilbild

---

### Swipe Tabs

| Dark | Light |
|---|---|
| ![Dark](./images/02-swipe-tabs-dark.png) | ![Light](./images/02-swipe-tabs-light.png) |

Horizontale Tab-Leiste mit dynamischen Pills und Swipe-Navigation.

**Datei:** `02-swipe-tabs.yaml`

**Anpassbar:**
- Helper-Entity
- Tabs & Icons
- Zustände / Filter

---

### Feature Cards

| Dark | Light |
|---|---|
| ![Dark](./images/03-feature-cards-dark.png) | ![Light](./images/03-feature-cards-light.png) |

Material-inspirierte Schnellzugriffskarten.

**Datei:** `03-feature-cards.yaml`

**Anpassbar:**
- `navigation_path`
- Icons
- Farben
- Texte

---

## Features

| Feature | Status |
|---|---|
| Material You Design | ✅ |
| Dark / Light Mode | ✅ |
| Animationen | ✅ |
| Mobile optimiert | ✅ |
| Wiederverwendbare Komponenten | ✅ |

---

## Voraussetzungen

- Home Assistant
- `button-card`
- `card-mod`
- `swipe-card`

👉 Empfohlen: eigenes Material You Theme

---

## Installation

```bash
git clone https://github.com/Mxipe07/HAOS-Material-You-Dock-Erweiterungen.git
