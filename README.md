# Beispielprojekt für Monitoring mit Prometheus und Grafana

## Software

git

Für die Java Beispiel Java JDK in Version 17.
Docker und docker-compose empfohlen.

Prometheus Download:
Grafana Download:


## Einrichtung

Linux:
`chmod -R a+w data`

## Beispiele
In den Ordnern `spring` und `prometheus` befinden sich Beispielprojekte mit unterschiedlichen Zwischenständen zur leichten Nachvollziehbarkeit.

### Beispiel-Aufrufe

```
$ watch -n 5 curl -sSL http://localhost:8080/account/register
$ watch -n 3 curl -sSL http://localhost:8080/login
$ watch -n 2 curl -sSL http://localhost:8080/shop
$ watch -n 2 curl -sSL http://localhost:8080/search
```
