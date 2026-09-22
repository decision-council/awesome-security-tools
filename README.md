# Awesome Security Tools — OSC

Lista curada de **herramientas de seguridad de código abierto** (y versiones licenciadas legítimas) avaladas o recomendadas por **Open Security Collective** para auditorías éticas.

> Las metodologías y fases de trabajo están en [standards](https://github.com/opensecuritycollective/standards). Este repo solo lista herramientas.

## Principios de selección

* Preferencia por software OSS o licencias comerciales legítimas.
* Prohibido el uso de software “crackeado” en operaciones oficiales de OSC.
* Toda herramienta se usa **solo** dentro de alcance autorizado.

## Análisis web

* [OWASP ZAP](https://www.zaproxy.org/) — proxy de pruebas de seguridad web
* [Burp Suite](https://portswigger.net/burp) — plataforma de testing web (Community/Pro)
* [ffuf](https://github.com/ffuf/ffuf) — fuzzer web rápido
* [sqlmap](https://sqlmap.org/) — detección/explotación de SQLi (uso autorizado)
* [KeyDrift](https://keydrift.dev) — Scans deployed HTML and JavaScript for exposed secrets while recognizing public browser credentials that should not be treated as leaks.

## Escaneo de red e infra

* [Nmap](https://nmap.org/) — descubrimiento y auditoría de red
* [Masscan](https://github.com/robertdavidgraham/masscan) — escaneo masivo de puertos
* [RustScan](https://github.com/RustScan/RustScan) — escaneo de puertos rápido
* [Nuclei](https://github.com/projectdiscovery/nuclei) — escaneo basado en templates

## OSINT

* [Amass](https://github.com/owasp-amass/amass) — enumeración de superficie de ataque
* [theHarvester](https://github.com/laramies/theHarvester) — recolección OSINT
* [Shodan](https://www.shodan.io/) / [Censys](https://censys.io/) — buscadores de dispositivos/exposición (APIs legítimas)
* [Maltego](https://www.maltego.com/) — grafos de inteligencia (según licencia)

## Severidad y reporte

* [cvss-calculator](https://github.com/opensecuritycollective/cvss-calculator) — CVSS v3.1 (OSC)
* [vulnera-calc](https://github.com/opensecuritycollective/vulnera-calc) — modelo de 7 ejes (OSC)

## Cómo proponer una herramienta

1. Abre un issue o PR con: nombre, URL, licencia, categoría y justificación ética/técnica.
2. Confirma que no requiere software ilegal ni bypasa controles sin autorización.
3. Sigue el [Código de conducta](https://github.com/opensecuritycollective/.github/blob/main/CODE_OF_CONDUCT.md).

## Licencia

Contenido de esta lista: [Apache License 2.0](./LICENSE). Las herramientas enlazadas conservan sus propias licencias.
