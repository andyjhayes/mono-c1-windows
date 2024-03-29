# Monogram + Capture One for Windows (Unofficial)

This is a collection of Monogram and Palette Gear module presets for Capture One on Windows.

### Prerequisites ###

- Windows 10 PC
- [Monogram Creator](https://monogramcc.com/download/)
- [Monogram Creative Console (recommended) or Palette Gear](https://monogramcc.com/)
- [Capture One](https://captureone.com/) (Version 9.3 or later required, 21 or later recommended)

---

## Setup Instructions ##

### Add keymap to Capture One ###

1. Download and unzip latest release (select Download Code at top right); copy the unzipped folder to a safe location like your Documents folder.
2. Locate <code>Keymaps > Monogram EN-US.xml</code> inside downloaded package.
3. In Windows File Explorer, go to <code>\%localappdata%\CaptureOne\CustomCommands\\</code>. (Tip: Paste this directory into the File Explorer path bar or the taskbar search)
4. Move <code>Monogram EN-US.xml</code> to inside the CustomCommands folder.
5. Restart Capture One, then go to Edit > Keyboard Shortcuts and choose "Monogram EN-US" keymap.

### Add integration bundle to Monogram Creator ###

1. In Monogram Creator, go to File > Preferences > Integrations.
2. Hit the + button (lower right); this should open a file browser.
3. Browse for your <code>mono-c1-windows</code> folder, then double-click it to look inside for the <code>captureone</code> folder.
4. Choose the <code>captureone</code> folder, then hit "Open" (bottom right).

---

## Disclaimers ##

This is purely a homebrewed set of Monogram presets for Capture One. A few things to keep in mind:

- It isn't developed or endorsed by either company. 
- It's provided with no warranty and it may not work on your system.
- Future Capture One or Monogram updates might break it.
- It's licensed under <a href="https://opensource.org/licenses/MIT">MIT</a>. Pull requests and issues are welcome :)

### Known Limitations ###

- No assignments available or possible for slider modules (inherent incompatibility)
- No assignments available or possible for Orbiter inner disc (inherent incompatibility)
- Some assignments may not work with non-QWERTY keyboards. This can be worked around by re-mapping the broken shortcuts in Monogram Creator and Capture One (Edit > Keyboard Shortcuts)
