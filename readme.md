# Konfiguration fuer den Service "DNS" im Baikonur-Netzwerk
Service-Beschreibung:

## Rolle "service_dns"
Richtet die Software für folgende Services ein:
* [SOFTWAREBEZEICHNUNG]

## Verzeichnisse:
* **tasks:** Playbook-Tasks, welche in der Rolle durchgeführt werden
* **defaults:** Standard-Variablen für die Rolle (werden von anderen Variabledefinitionen übersteuert)
* **vars:** Weitere Variablen für die Rolle
* **templates:** Jinja2-Templates, welche von der Rolle benötigt werden könnten
* **files:** Files, welche von der Rolle benötigt werden könnten
* **handlers:** Ansible-Handler-Definitionen
* **meta:** Meta-Daten für die Rolle

## Anmerkungen:
* Das kopieren des Zone-Files wird aufgrund des Syncs der Konfiguration immer getriggert... Ich sollte hierfür noch eine Lösung finden.