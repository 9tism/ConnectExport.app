# Drittanbieter-Hinweise / Third-Party Notices

ConnectExport selbst ist proprietär (siehe [LICENSE](LICENSE)). Die App bündelt
jedoch Software Dritter, die unter eigenen Lizenzen steht. Diese Lizenzen gelten
für die jeweiligen Komponenten vorrangig; die Rechte- und Urheberrechtsvermerke
der Autoren bleiben unberührt.

ConnectExport itself is proprietary (see [LICENSE](LICENSE)), but the app bundles
third-party software under its own licenses. Those licenses take precedence for
the respective components.

## Gebündelte Laufzeit-Komponenten / Bundled runtime components

| Komponente | Lizenz |
| --- | --- |
| Python (CPython) | PSF-2.0 |
| annotated-types, anyio, cffi (MIT-0), charset-normalizer, curl_cffi, fastapi, garminconnect, h11, idna, jaraco.classes, jaraco.context, jaraco.functools, keyring, markdown-it-py, mdurl, more-itertools, pydantic, pydantic-core, pyobjc-core, pyobjc-framework-Cocoa, rich, typing-inspection, urllib3 | MIT |
| click, httpcore, httpx, pycparser, starlette, uvicorn | BSD-3-Clause |
| Pygments | BSD-2-Clause |
| rumps | BSD |
| requests, ua-generator | Apache-2.0 |
| packaging | Apache-2.0 OR BSD-2-Clause |
| typing-extensions | PSF-2.0 |
| certifi (CA-Bundle) | MPL-2.0 |
| altgraph, macholib | MIT |

## Build-Werkzeuge / Build tooling

- **PyInstaller** – GPL-2.0-or-later mit Bootloader-Ausnahme. Die Ausnahme
  erlaubt ausdrücklich, damit erzeugte proprietäre Anwendungen zu verteilen,
  ohne deren Quellcode offenzulegen. Nur der Bootloader wird mitgeliefert.
- **setuptools**, **pytest**, **pip** – MIT (nicht Teil der ausgelieferten App).

## Marken / Trademarks

„Garmin“ und „Garmin Connect“ sind eingetragene Marken der Garmin Ltd. oder
ihrer Tochtergesellschaften; das FIT-Dateiformat gehört ebenfalls Garmin Ltd.
ConnectExport und dessen Autor stehen in keiner Verbindung zu Garmin.

## Vollständige Lizenztexte / Full license texts

Die vollständigen Lizenztexte liegen den jeweiligen Paketen bei und sind über
ihre Projektseiten auf <https://pypi.org> abrufbar. Auf Anfrage stellt der Autor
sie bereit – Anfragen über <https://github.com/9tism/ConnectExport.app/issues>.

Stand / Last reviewed: 2026-08-10
