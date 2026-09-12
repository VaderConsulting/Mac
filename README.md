# Mac

VB6 GetEthAdr utility (project `GetMacAdr`) that uses NetBIOS NCB `ASTAT` (`NCBASTAT`) to read the local adapter MAC address and shows the six hex octets in a message box from a single Address button. Same NetBIOS ASTAT pattern as the getmacadr tree.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `GetMacAdr` (`GetMacAdr.vbp`) | VB6 | WinForms exe | Local Ethernet MAC via NetBIOS ASTAT |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `GetMacAdr.vbp`

## Requirements

- Visual Basic 6.0 IDE
- NetBIOS / NetAPI (`netapi32` NCB path used by the form)

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Mac`.
Company names in project files: x. Companion pattern to `getmacadr`.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
