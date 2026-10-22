# Tuxbox-OS Images

Ready-to-flash [Neutrino](https://github.com/tuxbox-neutrino/neutrino) images
for set-top boxes, built once a month from
[build-environment](https://github.com/tuxbox-neutrino/build-environment).

**→ [Download the latest release](https://github.com/tuxbox-neutrino/images/releases/latest)**

Deutsch: [README.de.md](README.de.md)

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
with a link to it, and summarises the package changes since the month before.

The "Source code" archives that GitHub adds to every release contain only
these README files. The images are built from build-environment; follow the
link in the release notes for the source state.

Neutrino for a PC (AppImage) is built separately:
[neutrino-generic-build](https://github.com/tuxbox-neutrino/neutrino-generic-build/releases).
