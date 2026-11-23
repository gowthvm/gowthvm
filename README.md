# Gowtham G.K.

Building **FluorineOS** and **Flint**.

---

<table>
<tr>
<td width="110" valign="middle">
  <a href="https://fluorineos.pages.dev/" target="_blank" rel="noopener noreferrer">
    <img src="./assets/fluorine.svg" width="90" alt="FluorineOS emblem">
  </a>
</td>
<td valign="middle">

## FluorineOS

**A clean, customizable Wayland workstation built on Debian 13 and Hyprland.**

</td>
</tr>
</table>

FluorineOS is an opinionated Linux distribution engineered around plain-text configuration, deterministic packaging, and focused keyboard-driven workflows:

> **Cohesive out of the box. Readable in plain text.**

Built on Debian 13 (Trixie), it pairs a custom-configured Hyprland desktop with a signed APT repository, an offline Calamares installer, and lightweight system utilities.

### Highlights

- Debian 13 (`x86_64`) foundation with Hyprland configured in Lua
- Unified dark Wayland desktop (`waybar`, `fuzzel`, `kitty`, `swaync`, `hyprlock`)
- Offline graphical installation via Calamares with LUKS2 encryption support
- Custom GPG-signed APT repository (`fluorine-desktop`, `fluorine-artwork`, `fluorine-keyring`)
- Built-in CLI utilities (`flr-ctl`, `flr-doctor`, `flr-update`, `flr-keys`, `flr-shot`)
- Reproducible live ISO pipeline built with `live-build` and validated in QEMU

### Built with

**Debian 13 · Hyprland · Lua · POSIX Shell · Next.js · GitHub Actions**

**Website:** [fluorineos.pages.dev](https://fluorineos.pages.dev)

**Organization:** [github.com/FluorineOS](https://github.com/FluorineOS)

**Repository:** [github.com/FluorineOS/fluorine](https://github.com/FluorineOS/fluorine)

---

<table>
<tr>
<td width="110" valign="middle">
  <a href="https://flintweb.vercel.app/" target="_blank" rel="noopener noreferrer">
    <img src="./assets/flint.png" width="90" alt="Flint logo">
  </a>
</td>
<td valign="middle">

## Flint

**A Windows-native bootable USB and disk-image writer built with Python.**

</td>
</tr>
</table>

Flint is a disk imaging tool designed around one simple idea:

> **Writing an image isn't enough. Verify it.**

After writing an ISO or raw disk image, Flint re-reads the target drive and verifies the written data against the source using **SHA-256**, detecting corrupted or mismatched sectors rather than blindly trusting the write operation.

### Highlights

- ISO and raw disk-image writing
- Full-drive SHA-256 verification and byte-level mismatch detection
- Drive backup, cloning, bad-block scanning, and wiping
- Linux persistence and Windows To Go support
- Graphical interface and headless, scriptable CLI workflows
- Portable Windows executable with flash history and reports

### Built with

**Python · PyQt6 · Windows APIs · WMI · psutil**

**Website:** [flintweb.vercel.app](https://flintweb.vercel.app)

**Repository:** [github.com/flintusb/Flint](https://github.com/flintusb/Flint)

**License:** MIT

---

<p align="center">
  <sub>Build clean systems. Verify everything.</sub>
</p>
