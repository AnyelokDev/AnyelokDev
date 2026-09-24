## Miguel Angel Peralta Cano

**Ingeniería de Software** — Universidad de La Salle
**Técnico en Servicios de Seguridad Informática** — Fundación Politécnico Minuto de Dios (TECMD) *(etapa práctica)*

Trabajo entre el desarrollo de software y la seguridad informática.

Casi todo lo que hay aquí nació en el programa técnico del TECMD: laboratorios y auditorías
con un alcance definido por la institución. Lo que pongo yo en ellos es el rigor con que los
documento — procedimiento, evidencia y hallazgos, incluidos los fallos que no estaban en el
guion y lo que se aprendió de ellos. El SOC purple team de abajo es la excepción: se construyó
fuera del aula, en un *build day*, y es de donde más he aprendido.

> **Busco práctica o pasantía en ciberseguridad** (pentesting, blue team, análisis forense) — Bogotá o remoto.

---

### Proyecto destacado · SOC Purple Team en vivo

**[soc-purple-team-wazuh](https://github.com/AnyelokDev/soc-purple-team-wazuh)** — dashboard web
que lee alertas **reales** de Wazuh y pinta una cuadrícula MITRE ATT&CK que se actualiza en vivo
por SSE. Se lanzan ataques, unas técnicas se detectan y otras no; el hueco de **T1136 (Create
Account)** se cierra escribiendo una regla custom durante la demo y la cobertura pasa de 71 % a
100 %. Eso es **detección como código**.

[![Panel SOC purple team con cuadrícula MITRE ATT&CK en vivo](https://raw.githubusercontent.com/AnyelokDev/soc-purple-team-wazuh/main/evidencia/08_panel_71_flujo_completo.png)](https://github.com/AnyelokDev/soc-purple-team-wazuh)

Backend en Python de solo librería estándar, reglas y decoders custom de Wazuh mapeados a ATT&CK,
informe técnico con 22 evidencias y guion de demo reproducible.

---

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white)

![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=flat&logo=kalilinux&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat&logo=debian&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat&logo=gnometerminal&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat&logo=wireshark&logoColor=white)
![Snort](https://img.shields.io/badge/Snort_3-E5332A?style=flat&logo=snort&logoColor=white)
![Nagios](https://img.shields.io/badge/Nagios-CA2027?style=flat&logo=nagios&logoColor=white)

---

### Seguridad informática

| Proyecto | Qué resuelve |
|---|---|
| **[soc-purple-team-wazuh](https://github.com/AnyelokDev/soc-purple-team-wazuh)** | Dashboard en vivo sobre alertas reales de Wazuh con cuadrícula MITRE ATT&CK por SSE. El hueco T1136 se cierra con una regla custom durante la demo y la cobertura pasa de 71 % a 100 %. |
| **[snort-ids-ips-kali-linux](https://github.com/AnyelokDev/snort-ids-ips-kali-linux)** | Snort 3 como IDS/IPS sobre Kali: migración de `snort.conf` a `snort.lua`, modo inline con NFQUEUE y bloqueo de tráfico saliente. Incluye cuatro fallos no documentados y su análisis. |
| **[nmap-security-audit](https://github.com/AnyelokDev/nmap-security-audit)** | Auditoría perimetral con Nmap: script Bash de automatización y reportes HTML de puertos TCP/UDP. |
| **[linux-forensics-incident-response](https://github.com/AnyelokDev/linux-forensics-incident-response)** | Análisis forense de logs en Linux y playbook de respuesta a incidentes en 5 fases para malware USB y DDoS. |
| **[postgresql-hardening-metrics](https://github.com/AnyelokDev/postgresql-hardening-metrics)** | Hardening de PostgreSQL y 5 KPIs de seguridad con su formulación matemática. |
| **[nagios-snmp-monitoring](https://github.com/AnyelokDev/nagios-snmp-monitoring)** | Monitoreo de red LAN con Nagios y SNMP: disponibilidad de hosts y métricas vía MIBs y OIDs. |

<sup>Salvo el primero, que es propio, son trabajos del programa técnico (TECMD).</sup>

### Desarrollo

| Proyecto | Qué resuelve |
|---|---|
| **[nublus-fleet-manager](https://github.com/AnyelokDev/nublus-fleet-manager)** | Gestión de flotas con control de vencimiento de documentos y alertas por estado. JavaScript + `localStorage`. |
| **[dimayor-league-manager](https://github.com/AnyelokDev/dimayor-league-manager)** | Gestor de liga de fútbol en Java Swing con arquitectura MVC y exportación de la tabla a HTML. |
| **[java-utility-billing-system](https://github.com/AnyelokDev/java-utility-billing-system)** | Liquidación de servicios públicos aplicando herencia y polimorfismo por estrato socioeconómico. |
| **[polyglot-matrix-toolkit](https://github.com/AnyelokDev/polyglot-matrix-toolkit)** | El mismo taller de vectores y matrices resuelto en Python (Tkinter), C# (WinForms) y Java (Swing). |
| **[dispatch-warehouse-db](https://github.com/AnyelokDev/dispatch-warehouse-db)** | Base de datos relacional de despachos: esquema, consultas avanzadas y gestión de privilegios. |
| **[urbanstyle-landing-page](https://github.com/AnyelokDev/urbanstyle-landing-page)** | Landing page responsive con Tailwind CSS, tema oscuro y hoja de estilos de impresión. |

<sup>Trabajos académicos del TECMD y de la Universidad de La Salle.</sup>

---

### Ahora mismo

- Cursando la etapa práctica del Técnico en Servicios de Seguridad Informática.
- Ampliando el panel del SOC purple team con más técnicas de ATT&CK.
- Practicando en máquinas de **Hack The Box** para afianzar pentesting.
- Profundizando en análisis forense y operaciones de blue team.

---

### Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miguel-angel-peralta-cano-167776313)
![Bogotá](https://img.shields.io/badge/Bogotá,_Colombia-333333?style=flat&logo=googlemaps&logoColor=white)
