# Raspberry.IpBlocker

Generateur de regles iptables pour bloquer des plages d'IP geolocalisees, avec agregation de fichiers de zones.

## Structure

| Fichier / Dossier | Role |
|-|-|
| `block-french-ips.py` | Script de generation des regles iptables |
| `fr-aggregated.zone` | Fichier de zones IP agregees (France) |

## Stack

- Python
- iptables
- Fichiers de zones IP
