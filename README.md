# VeyoPDF

A local, private PDF workbench. Everything happens on your computer: your documents are
never uploaded anywhere.

View, organise, comment, fill and sign, edit text and images in place, protect and redact,
scan with OCR, export to Word/Excel/PowerPoint and more.

## Download

**[Get the latest version](https://github.com/Aamirazmy92/VeyoPDF-releases/releases/latest)**
and pick the file for your computer:

| Your computer | Download |
|---|---|
| Windows 10 / 11 (64-bit) | `VeyoPDF_<version>_x64-setup.exe` (recommended) or the `.msi` |
| Mac with Apple Silicon (M1 or newer), macOS 11+ | `VeyoPDF_<version>_aarch64.dmg` |

Intel Macs and Linux are not supported yet.

## Installing on Windows

1. Download and run `VeyoPDF_<version>_x64-setup.exe`.
2. Windows may show **"Windows protected your PC"**. VeyoPDF is a new app and is not yet
   signed with a paid publisher certificate, so SmartScreen does not know it. Click
   **More info**, then **Run anyway**.
3. Follow the installer. VeyoPDF appears in the Start menu.

## Installing on Mac

1. Open the `.dmg` and drag **VeyoPDF** into **Applications**.
2. The first time, macOS says it can't verify the app (it is not notarized by Apple).
   **Right-click** (or Control-click) VeyoPDF in Applications, choose **Open**, then
   **Open** again. You only need to do this once.
   - If there is no Open button: open **System Settings → Privacy & Security**, scroll
     down and click **Open Anyway** next to VeyoPDF.
   - Or, in Terminal: `xattr -dr com.apple.quarantine /Applications/VeyoPDF.app`

On a Mac, signing a PDF with a digital ID (certificate) is not available yet; it works
on Windows.

## Updates

VeyoPDF checks for a new version shortly after it starts, at most once a day. When there
is one, a card appears in the corner: choose **Update**, then **Restart to install**. You
can also click the refresh button in the title bar to check right away. Updates are signed
and verified before they are installed, and should not show the warnings above (only the first install does).

## Licence

VeyoPDF is released under the AGPL-3.0-or-later and uses [MuPDF](https://mupdf.com).
