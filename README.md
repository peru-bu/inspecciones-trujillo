# Inspecciones Trujillo - Frontend

Frontend movil para inspecciones de equipos.

## Backend

El backend sigue viviendo en Google Apps Script.

URL del web app/API:

```text
https://script.google.com/macros/s/AKfycbwaATbROKgQiLNeC_7-FC8RnkPIv6ssRFHaq8lgfx1GS7tNKrDD6aR5xRFkwuZAKVJA9w/exec
```

## Funcionamiento

- Si el HTML se sirve desde Apps Script, usa `google.script.run`.
- Si se sirve desde GitHub Pages, usa el fallback JSONP hacia Apps Script.
- El flujo de auditoria y guardado se mantiene en Apps Script.
