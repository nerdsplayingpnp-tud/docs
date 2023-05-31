Diese Webseite wurde mit [MkDocs](https://www.mkdocs.org/) erstellt. Das Theme ist [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## Lokale Entwicklungsumgebung
Wenn du die Webseite lokal ausführen möchtest, musst du folgende Schritte ausführen:

* Installiere Python 3.10 oder höher. Stelle außerdem sicher, dass `pip`, `git` und `python3-venv` installiert sind.
* Klone das Projekt: 
   ```sh
   git clone https://github.com/nerdsplayingpnp-tud/docs.git
   ```
* Erstelle ein virtuelles Python-Environment: `python -m venv venv`
* Aktiviere das virtuelle Environment:
=== "Windows"
    ```bat
    venv\Scripts\activate.bat
    ```
=== "Linux"
    ```sh
    source venv/bin/activate
    ```
=== "MacOS"
    ```sh
    source venv/bin/activate
    ```

* Installiere die notwendigen Pakete: `pip install -r requirements.txt`
* Starte die Webseite: `mkdocs serve` 

## Code contributen

Wenn du einen Fehler findest oder eine Verbesserung vorschlagen möchtest, kannst du das gerne tun. Dafür musst du folgende Schritte ausführen:

* Erstelle einen Fork des Projekts
* Füge deine Verbesserungen oder Veränderungen als commits hinzu
* Erstelle einen Pull Request