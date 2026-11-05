# Rastix BLE UI

Browser-Steuerung für Rastix (ESPHome) per Web Bluetooth.

## Öffentlich

**Eltern-UI:** https://eckih.github.io/rastix-ble-ui/  
**Kids-UI:** https://eckih.github.io/rastix-ble-ui/kids.html

Handy und ESP in Bluetooth-Reichweite; Seite per HTTPS öffnen, **BLE verbinden**, Gerät `rastix-…` wählen.

## Lokal

```powershell
cd rastix-ble-ui
python -m http.server 8080
```

Dann: http://localhost:8080/

## Hinweis

Firmware-Configs und Secrets liegen **nicht** hier, sondern im privaten Repo `esphome-configs`.
