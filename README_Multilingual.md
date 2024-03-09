
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

## Making Your GitHub Repository Interesting and Informative

- **README.md**: Your README file is the first thing people see in your repository. Make it informative and engaging by explaining what your project does, how to install it, and how to use it.
- **Contributing Guidelines**: Encourage contributions by including a CONTRIBUTING.md file with instructions for potential contributors.
- **License**: Clearly state the license under which your project is released, making it easier for others to know how they can use your work.

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

## Ihr GitHub-Repository interessant und informativ gestalten

- **README.md**: Ihre README-Datei ist das Erste, was Personen in Ihrem Repository sehen. Machen Sie es informativ und ansprechend, indem Sie erklären, was Ihr Projekt macht, wie man es installiert und wie man es benutzt.
- **Beitragende Richtlinien**: Ermutigen Sie Beiträge, indem Sie eine CONTRIBUTING.md-Datei mit Anweisungen für potenzielle Mitwirkende einschließen.
- **Lizenz**: Erklären Sie deutlich die Lizenz, unter der Ihr Projekt veröffentlicht wird, damit andere leicht verstehen können, wie sie Ihre Arbeit nutzen dürfen.
