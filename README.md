# Gowtham G.K.

Building **Flint**.

---

<table>
<tr>
<td width="110" valign="middle">
  <img src="./assets/flint.png" width="90" alt="Flint logo">
</td>
<td valign="middle">

## Flint

**A Windows-native bootable USB and disk-image writer built with Python.**

</td>
</tr>
</table>

Flint is a disk imaging tool designed around one simple idea:

> **Writing an image isn't enough. Verify it.**

After writing an ISO or raw disk image, Flint can re-read the target drive and verify the written data against the source using **SHA-256**, helping detect corrupted or mismatched data rather than blindly trusting the write operation.

### Features

* ISO and raw disk-image writing
* Full-drive SHA-256 verification
* Byte-level mismatch detection
* Drive backup and cloning
* Bad-block scanning
* Drive wiping
* Linux persistence
* Windows To Go
* Graphical interface
* Command-line interface
* Headless and scriptable workflows
* Portable Windows executable
* Flash history and reports

### Built with

**Python · PyQt6 · Windows APIs · WMI · psutil**

---

## Why Flint?

Most disk imaging software treats a successful write operation as the end of the process.

Flint treats it as the beginning of verification.

The target drive can be read back after flashing and compared against the original image, allowing Flint to report whether the written data actually matches what was intended.

---

## Project

**Repository:** [github.com/gowthvm/Flint](https://github.com/gowthvm/Flint)

**Website:** [flintweb.vercel.app](https://flintweb.vercel.app)

**License:** MIT

---

<p align="center">
  <sub>Write. Verify. Trust.</sub>
</p>
