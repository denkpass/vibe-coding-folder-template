# [PROJEKTNAME HIER EINFÜGEN]

> Ein kurzer Satz, der beschreibt, was dieses Projekt tut.

## Dies ist ein Template-Repository.

> **Benutze es NICHT direkt!**

**🚀 So startest du dein eigenes Projekt damit**:

1.  Klicke auf den grünen Button **"Use this template"** oben rechts.
2.  Wähle **"Create a new repository"**.
3.  Gib deinem neuen Projekt einen Namen und erstelle es.
4.  **Klone dein neues Repository** (nicht dieses hier!) auf deinen lokalen Rechner.

Dies ist ein Template für ein Verzeichnis fürs Vibe-Coden, das dann gepullt wird als Ausgangsbasis für deine eigenen Projekte.

---

## 🚀 Setup & Installation

Dieses Projekt verwendet Python und wird mit `pip` und einem virtuellen Environment verwaltet.

1.  **Erstelle ein virtuelles Environment:**
    ```bash
    python3 -m venv .venv
    ```

2.  **Aktiviere das Environment:**
    * macOS / Linux:
        ```bash
        source .venv/bin/activate
        ```
    * Windows:
        ```bash
        .\.venv\Scripts\activate
        ```

3.  **Installiere die Abhängigkeiten:**
    Dieses Projekt nutzt die `pyproject.toml`. Installiere das Projekt im "editable" Modus (`-e .`) zusammen mit allen Entwicklungs-Abhängigkeiten (`[dev]`):
    ```bash
    pip install -e ".[dev]"
    ```

---

## 🛠️ Entwicklungs-Workflow & Qualitätssicherung

Wir verwenden ein Set an Werkzeugen, um die Code-Qualität hoch zu halten.

### Tests (pytest)
Alle Tests liegen im `/tests` Verzeichnis und werden mit `pytest` ausgeführt. Wir verfolgen einen strikten TDD-Ansatz.

* **Alle Tests ausführen:**
    ```bash
    pytest
    ```
* **Tests mit Testabdeckung (Coverage) ausführen:**
    ```bash
    pytest --cov=src
    ```

### Linting & Formatierung (Ruff)
Wir verwenden `ruff` für extrem schnelles Linting und Formatierung.

* **Code-Stil prüfen:**
    ```bash
    ruff check .
    ```
* **Code automatisch formatieren:**
    ```bash
    ruff format .
    ```

### Typ-Prüfung (mypy)
Wir verwenden `mypy` zur statischen Typprüfung.

* **Typen im `src`-Ordner prüfen:**
    ```bash
    mypy src
    ```

---

## 🤖 AI Pair Programming

Dieses Projekt ist für die Zusammenarbeit mit einem KI-Pair-Programmer (wie Gemini) im TDD-Modus optimiert. Die genauen Verhaltensregeln, Antwortformate und Ziele sind in der `agents.md`-Datei in diesem Verzeichnis definiert.

## 💡 Danksagung (Acknowledgements)

Der TDD-Workflow und die Nutzung einer `agents.md` zur Steuerung des KI-Pair-Programmers sind stark inspiriert von den Konzepten und der `CLAUDE.md` von [Harper Reed](https://github.com/harperreed).

* **Harper Reed's Dotfiles:** [github.com/harperreed/dotfiles](https://github.com/harperreed/dotfiles)