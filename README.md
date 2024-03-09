
# Pi-hole Configuration and Maintenance Guide 

This guide provides an overview of useful commands for managing and monitoring your Pi-hole system. It includes commands for functional tests, DNS tests, updating Pi-hole, and general configuration data.

## General Commands

### Check Pi-hole Status

```sh
pihole status
```

### Display Pi-hole Versions

```sh
pihole -v
```

### Update Pi-hole

```sh
pihole -up
```

### Test DNS Resolution

```sh
dig @127.0.0.1 example.com
```

### View Pi-hole Query Log

Access the Pi-hole log file for detailed queries (requires `sudo`):

```sh
sudo less /var/log/pihole/pihole.log
```

### Display Network Configuration

```sh
ip -br a
ip route
```

### Measure System Temperature

```sh
vcgencmd measure_temp
```

## Further Support

For additional support and detailed questions, you can visit the community and documentation on [Pi-hole GitHub](https://github.com/pi-hole/pi-hole) or the [Pi-hole Forum](https://discourse.pi-hole.net/).


---

# Pi-hole Konfiguration und Wartungshandbuch

Diese Anleitung bietet einen Überblick über nützliche Befehle zur Verwaltung und Überwachung Ihres Pi-hole-Systems. Sie umfasst Befehle für Funktionstests, DNS-Tests, die Aktualisierung von Pi-hole und allgemeine Konfigurationsdaten.

## Allgemeine Befehle

### Pi-hole Status überprüfen

```sh
pihole status
```

### Pi-hole Versionen anzeigen

```sh
pihole -v
```

### Pi-hole aktualisieren

```sh
pihole -up
```

### DNS-Auflösung testen

```sh
dig @127.0.0.1 example.com
```

### Pi-hole Query Log anzeigen

Zugriff auf die Pi-hole Logdatei für detaillierte Anfragen (erfordert `sudo`):

```sh
sudo less /var/log/pihole/pihole.log
```

### Netzwerkkonfiguration anzeigen

```sh
ip -br a
ip route
```

### Systemtemperatur messen

```sh
vcgencmd measure_temp
```

## Weitere Unterstützung

Für weitere Unterstützung und detaillierte Fragen können Sie die Community und Dokumentation auf [Pi-hole GitHub](https://github.com/pi-hole/pi-hole) oder das [Pi-hole Forum](https://discourse.pi-hole.net/) besuchen.

