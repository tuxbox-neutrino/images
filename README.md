# Tuxbox-OS Images

Ready-to-flash [Neutrino](https://github.com/tuxbox-neutrino/neutrino) images
for set-top boxes, built once a month from
[build-environment](https://github.com/tuxbox-neutrino/build-environment).

**→ [Download the latest release](https://github.com/tuxbox-neutrino/tuxbox-os-images/releases/latest)**

Deutsch: [siehe unten](#deutsch)

## Boxes

| File name contains | Box |
|---|---|
| `hd51` | Mut@nt HD51 |
| `hd60` | AX HD60 |
| `h7` | Zgemma H7 |

## Which file do I need?

| File | What it is |
|---|---|
| `…_multi.zip` | The image: kernel and root file system. This is the normal download. |
| `…_recovery_emmc.zip` | Recovery package. Only needed when the box no longer reaches its multiboot menu or the partition layout changes. **It can erase everything in flash.** |
| `….tuxbox.tar.bz2` | The root file system as a plain archive, for developers and special tools. |
| `SHA256SUMS` | Checksums. Run `sha256sum -c SHA256SUMS` in the download folder. |

Each release names the exact state of build-environment it was built from,
with a link to it, and lists the packages that changed since the month before.

The "Source code" archives that GitHub adds to every release contain only
this README. The images are built from build-environment; follow the link
in the release notes for the source state.

Neutrino for a PC (AppImage) is built separately:
[neutrino-generic-build](https://github.com/tuxbox-neutrino/neutrino-generic-build/releases).

## Deutsch

Fertige Neutrino-Images zum Flashen, einmal im Monat aus
[build-environment](https://github.com/tuxbox-neutrino/build-environment) gebaut.

**→ [Neuestes Release herunterladen](https://github.com/tuxbox-neutrino/tuxbox-os-images/releases/latest)**

- `…_multi.zip` – das Image (Kernel und Root-Dateisystem), der normale Download.
- `…_recovery_emmc.zip` – Recovery-Paket. Nur nötig, wenn die Box ihr
  Multiboot-Menü nicht mehr erreicht oder sich die Partitionierung ändert.
  **Kann den gesamten Flash löschen.**
- `….tuxbox.tar.bz2` – Root-Dateisystem als Archiv, für Entwickler und
  spezielle Werkzeuge.
- `SHA256SUMS` – Prüfsummen: `sha256sum -c SHA256SUMS` im Download-Ordner.

Jedes Release verlinkt den Stand von build-environment, aus dem es gebaut
wurde. Die „Source code“-Archive, die GitHub an jedes Release hängt,
enthalten nur diese README.
