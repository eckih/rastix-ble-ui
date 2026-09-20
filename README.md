# Rastix BLE UI

Browser-Steuerung für Rastix (ESPHome) per Web Bluetooth.

## Öffentlich

**https://eckih.github.io/rastix-ble-ui/**

Handy und ESP im Bluetooth-Reichweite; Seite per HTTPS öffnen, **BLE verbinden**, Gerät `rastix-…` wählen.

## Lokal

```powershell
cd rastix-ble-ui
python -m http.server 8080
```

Dann: http://localhost:8080/

## Hinweis

Firmware-Configs und Secrets liegen **nicht** hier, sondern im privaten Repo `esphome-configs`.
