# Infraestructura Web con Alta Disponibilidad

Proyecto intermodular desarrollado en 2º SMR basado en una infraestructura web con balanceo de carga, alta disponibilidad y tolerancia a fallos utilizando tecnologías Linux.

## Contenido del repositorio

* `Manual_Tecnico_Grupo2.pdf` → Documentación técnica completa del proyecto.
* `Presentacion_Grupo2.pdf` → Presentación utilizada durante la exposición y defensa del proyecto.
* `Manual_Usuario_Grupo2.mp4` → Video demostración breve mostrando el funcionamiento del sistema.

## Tecnologías utilizadas

* Debian Linux
* Docker
* Nginx
* HAProxy
* Keepalived
* OpenSSH
* rsync
* cron
* iptables
* VirtualBox

## Descripción general

La infraestructura implementa un sistema de alta disponibilidad mediante una IP virtual (VIP) gestionada por Keepalived y un balanceador de carga HAProxy encargado de distribuir las peticiones entre distintos servidores web.

El proyecto incluye:

* Balanceo de carga
* Failover automático
* Firewall mediante iptables
* Sincronización automática de contenido
* Virtualización de servicios
* Página web de validación con HTML, CSS y JavaScript

## Documentación

Para detalles técnicos completos consultar:

* `Manual_Tecnico_Grupo2.pdf`

Para la presentación del proyecto:

* `Presentacion_Grupo2.pdf`

Para una demostración práctica del funcionamiento:

* `Manual_Usuario_Grupo2.mp4`
* Video tutorial / Manual de usuario:
  https://drive.google.com/file/d/1f3w1AAJ3RRgaxouPEDPiatDOb1z6WJT8/view?usp=sharing

  
