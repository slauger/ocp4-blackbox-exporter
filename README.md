# ocp4-blackbox-exporter

Example for adding a blackbox exporter to the internal OpenShift cluster monitoring.

## Alerts

- BlackboxProbeFailed
- BlackboxSlowProbe
- BlackboxProbeHttpFailure
- BlackboxSslCertificateWillExpireSoon
- BlackboxSslCertificateExpired

Provided by https://awesome-prometheus-alerts.grep.to/rules.html

## Usage

### Dry run

```
helmfile template
```

## Deploy to cluster

```
helmfile sync
```
