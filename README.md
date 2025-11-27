# ScriptConverter

Egyszerű parancssori eszköz script fájlok konvertálásához és csomagolásához.

## Gyors kezdés

1. Töltsd le a `scriptconverter.exe` binárist a Release-ből.
2. Ellenőrizd a fájl integritását a mellékelt SHA‑256 hash segítségével.

**SHA‑256:** 158F1EBFE63FDABB2E92F2BA1AC79E28D81A2EEB57C7B5FFA7243E263EA96FAB  
**Fájl:** scriptconverter.exe

# PowerShell
Get-FileHash .\scriptconverter.exe -Algorithm SHA256

# Windows certutil
certutil -hashfile scriptconverter.exe SHA256

# Linux / macOS
sha256sum scriptconverter.exe
