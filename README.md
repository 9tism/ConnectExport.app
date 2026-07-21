# ConnectExport

**Lokale macOS-App zum Export aller eigenen Garmin-Connect-Daten** –
Aktivitäten als **FIT**, Gesundheitsdaten als **JSON**. Die Bedienung erfolgt
ausschließlich über eine lokale Weboberfläche, gestartet aus der
macOS-Menüleiste. Die Daten bleiben auf deinem Rechner.

## Download & Installation

Die fertige App gibt es unter **[Releases](../../releases/latest)**:

1. `ConnectExport-<version>-macos-arm64.zip` herunterladen und entpacken.
2. `ConnectExport.app` z. B. in den Ordner **Programme** ziehen und starten.

> Für Apple Silicon (arm64). Die App ist nur **ad-hoc signiert**, nicht
> notarisiert – beim ersten Start ggf. per **Rechtsklick → „Öffnen"** freigeben
> oder im Terminal `xattr -d com.apple.quarantine ConnectExport.app`.

## Lizenz & Hinweise

MIT © 2026 Tim Stegmann. Die vollständige Lizenz liegt dem Release als
`LICENSE`-Datei bei.

Garmin bietet keine offizielle öffentliche Export-API; die App nutzt die
inoffizielle Web-Schnittstelle. Sie ist ausschließlich für den Export der
**eigenen** Kontodaten gedacht. Nutzung auf eigenes Risiko (Garmin-AGB).

„Garmin" und „Garmin Connect" sind eingetragene Markenzeichen von Garmin Ltd.
oder deren Tochtergesellschaften. ConnectExport und dessen Autor stehen in
keiner Verbindung zu Garmin.
