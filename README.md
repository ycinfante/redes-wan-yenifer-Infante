# WAN Architect AI

## Proyecto: Herramienta de Redes WAN — Corte 2

**Estudiante:** Yenifer Galeano  
**Programa:** Ingeniería de Telecomunicaciones  
**Institución:** Fundación Universitaria UCompensar  

## Descripción

WAN Architect AI es una herramienta desarrollada en HTML para apoyar el diseño y gestión de una red WAN corporativa.

La herramienta permite realizar el direccionamiento de red, visualizar la topología WAN de diferentes sedes y generar configuraciones básicas para equipos Cisco y Huawei.

## Funcionalidades

- Cálculo de subnetting IPv4.
- Planificación de direccionamiento mediante VLSM.
- Visualización de tres sedes y su infraestructura.
- Consulta de la distribución de red por pisos.
- Visualización de VLAN, gateway y direccionamiento.
- Representación gráfica de la topología WAN corporativa.
- Generación automática de configuraciones Cisco.
- Generación automática de configuraciones Huawei.
- Validaciones básicas orientadas a ciberdefensa.
- Manejo de información de ejemplo sin almacenar contraseñas ni credenciales reales.

## Uso de la herramienta

1. Descargar el archivo HTML del repositorio.
2. Abrir el archivo en Google Chrome.
3. Ingresar al módulo de Subnetting para consultar el direccionamiento.
4. Ingresar a Topología para visualizar la arquitectura WAN y las sedes.
5. Seleccionar una sede para consultar su infraestructura.
6. Ingresar a Configuraciones para generar comandos Cisco o Huawei.

## Evidencias Corte 2

| Evidencia | Descripción |
|---|---|
| 01-subnetting.png | Funcionamiento del cálculo de subnetting |
| 02-topologia.png | Topología WAN con dispositivos y enlaces |
| 03-config-cisco.png | Configuración generada para Cisco |
| 04-config-huawei.png | Configuración generada para Huawei |
| 05-github-commits.png | Historial de mínimo 5 commits |

## Estructura del repositorio

- Herramienta WAN en HTML
- README.md
- docs/informe-corte2.pdf
- docs/politicas-ia.md
- docs/capturas/

## Seguridad

El proyecto utiliza únicamente información de laboratorio. No se almacenan contraseñas, tokens ni credenciales reales dentro del código. Los archivos `.env` deben mantenerse fuera del repositorio mediante `.gitignore`.
