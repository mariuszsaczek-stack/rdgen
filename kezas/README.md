# KEZAS DESK - konfiguracja budowy

Workflow: `.github/workflows/kezas-desk-windows.yml` (Actions > "KEZAS DESK Windows" > Run workflow).
- `version` - tag RustDesk (np. 1.5.0), `source_branch` - galaz w forku `rustdesk` z commitami KEZAS DESK (np. kezas-desk-1.5.0).
- Kod zrodlowy: fork `rustdesk`, galaz `kezas-desk-<wersja>` = tag + commit "KEZAS DESK: confirm before closing every remote session".
- `custom.json` - wbudowane ustawienia domyslne (custom_.txt). BEZ HASLA.
- Grafiki: icon.ico (ikona programu, wiele rozmiarow), icon.png (256), tray-icon.ico (32), 32/64/128/256 PNG,
  icon_symbol_256.png i icon48.png (ikona w oknie), logo*.png (logo w oknie, max 300x60; light/dark).
- Wynik: artefakt `kezas-desk-windows` (exe, msi, SHA256SUMS.txt).
