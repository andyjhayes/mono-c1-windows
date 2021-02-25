# Monogram + Capture One for Windows (Unofficial)

This is a collection of Monogram and Palette Gear module presets for Capture One on Windows.

### Prerequisites ###

- Windows 10 PC
- [Monogram Creator](https://monogramcc.com/download/)
- [Monogram Creative Console (recommended) or Palette Gear](https://monogramcc.com/)
- [Capture One](https://captureone.com/) (Version 9.3 or later required)

### Known Issues ###

- No assignments available or possible for slider modules (inherent incompatibility)
- No assignments available or possible for Orbiter disc (inherent incompatibility)
- Some assignments may not work with non-QWERTY keyboards. This can be worked around by re-mapping the broken shortcuts in Monogram Creator and Capture One (Edit > Keyboard Shortcuts)

---

## Setup Instructions ##

### Add keymap to Capture One ###

1. Download and unzip latest release; copy the unzipped folder to a safe location like your Documents folder.
2. Locate <code>Keymaps > Monogram EN-US.xml</code> inside downloaded package.
3. In Windows File Explorer, go to <code>\%localappdata%\CaptureOne\CustomCommands\\</code>. (Tip: Paste this directory into the File Explorer path bar or the taskbar search)
4. Move <code>Monogram EN-US.xml</code> to inside the CustomCommands folder.

### Optional: add icon ###

I don't have copyright to distribute a Capture One icon. To add one, simply add an image titled <code>icon.png</code> inside the <code>captureone</code> folder. This icon will show up in Creator and also on the Monogram core screen.

Recommended: 240px square .png

### Add integration bundle to Monogram Creator ###

1. In Monogram Creator, go to File > Preferences > Integrations.
2. Hit the + button (lower right); this should open a file browser.
3. Browse for your <code>mono-c1-windows</code> folder, then double-click it to look inside for the <code>captureone</code> folder.
4. Select the <code>captureone</code> without opening it, then hit "Select Folder" (bottom right).

---

## Disclaimers ##

This is purely a homebrewed set of Monogram presets for Capture One. A few things to keep in mind:

- It isn't developed or endorsed by either company. 
- It's provided with no warranty and it may not work on your system.
- Future Capture One or Monogram updates might break this.
- It's licensed under <a href="https://www.gnu.org/licenses/gpl-3.0.en.html">GPLv3</a>. Pull requests and issues are welcome :)
