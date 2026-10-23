# Tuxbox-OS Images

Fertige [Neutrino](https://github.com/tuxbox-neutrino/neutrino)-Images zum
Flashen auf Set-Top-Boxen, einmal im Monat aus
[build-environment](https://github.com/tuxbox-neutrino/build-environment) gebaut.

**→ [Neuestes Release herunterladen](https://github.com/tuxbox-neutrino/images/releases/latest)**

English: [README.md](README.md)

## Boxen

| Dateiname enthält | Box |
|---|---|
| `hd51` | Mut@nt HD51 |
| `hd60` | AX HD60 |
| `h7` | Zgemma H7 |

## Welche Datei brauche ich?

| Datei | Was sie ist |
|---|---|
| `…_multi.zip` | Das Image: Kernel und Root-Dateisystem. Das ist der normale Download. |
| `…_recovery_emmc.zip` | Recovery-Paket. Nur nötig, wenn die Box ihr Multiboot-Menü nicht mehr erreicht oder sich die Partitionierung ändert. **Kann den gesamten Flash löschen.** |
| `SHA256SUMS` | Prüfsummen. Im Download-Ordner `sha256sum -c SHA256SUMS` ausführen. |

Jedes Release nennt den genauen Stand von build-environment, aus dem es
gebaut wurde, verlinkt ihn und fasst die Paketänderungen gegenüber dem
Vormonat zusammen.

Die „Source code“-Archive, die GitHub an jedes Release hängt, enthalten nur
diese README-Dateien. Gebaut werden die Images aus build-environment; den
Quellstand findest du über den Link in den Release-Notes.

Neutrino für den PC (AppImage) wird getrennt gebaut:
[neutrino-generic-build](https://github.com/tuxbox-neutrino/neutrino-generic-build/releases).
