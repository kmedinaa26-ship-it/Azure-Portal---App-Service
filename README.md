# Azure Portal - App Service

**Universidad Tecnológica del Valle de Toluca**
Alumna: Kenia Medina Gil · Grupo: IDGS103 · Maestro: Jorge Almeida

Laboratorio 1: creación manual, desde el portal de Azure, del ambiente de **desarrollo (dev)**
de una aplicación web con monitoreo.

## Objetivo

Crear en Azure los recursos necesarios para publicar una aplicación web Node.js y monitorearla,
siguiendo la convención de nombres definida por el maestro (ver [docs/nomenclatura.md](docs/nomenclatura.md)).

## Entorno

| Dato | Valor |
|---|---|
| Suscripción | Azure for Students |
| Región | Mexico Central |
| Ambiente | dev |
| Etiquetas | `cost_center=utvt`, `owner=equipo-integradora`, `managed_by=portal` |

## Recursos y avance

| # | Recurso | Nombre | Evidencia | Estado |
|---|---|---|---|---|
| 1 | Resource Group | `rg-utvt-integradora-dev-mxc-001` | `evidencias/01-*` | Pendiente |
| 2 | Log Analytics Workspace | `log-utvt-integradora-dev-mxc-001` | `evidencias/02-*` | Pendiente |
| 3 | Application Insights | `appi-utvt-integradora-dev-mxc-001` | `evidencias/03-*` | Pendiente |
| 4 | App Service Plan (F1) | `asp-utvt-integradora-dev-mxc-001` | `evidencias/04-*` | Pendiente |
| 5 | Web App (Node 24 LTS) | `app-utvt-integradora-web-dev-mxc-001` | `evidencias/05-*` | Pendiente |
| 6 | Web App + Application Insights | vinculación | `evidencias/06-*` | Pendiente |

## Estructura del repositorio

```
.
├── README.md          # Descripción del laboratorio y avance
├── docs/              # Documentación (nomenclatura de recursos)
└── evidencias/        # Capturas de pantalla de cada paso
```

## Historial

Cada paso del laboratorio se registra en un commit independiente, con su evidencia.
