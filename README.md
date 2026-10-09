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

| # | Recurso | Nombre | Configuración clave | Estado |
|---|---|---|---|---|
| 1 | Resource Group | `rg-utvt-integradora-dev-mxc-001` | Mexico Central, 3 etiquetas | Completado |
| 2 | Log Analytics Workspace | `log-utvt-integradora-dev-mxc-001` | Mexico Central | Completado |
| 3 | Application Insights | `appi-utvt-integradora-dev-mxc-001` | Basado en el workspace del paso 2 | Completado |
| 4 | App Service Plan | `asp-utvt-integradora-dev-mxc-001` | Plan Free F1 | Completado |
| 5 | Web App | `app-utvt-integradora-web-dev-mxc-001` | Código, Node 24 LTS, plan del paso 4 | Completado |
| 6 | Vinculación Web App + Application Insights | `appi-utvt-integradora-dev-mxc-001` | Monitoring > Application Insights | Pendiente |

## Estructura del repositorio

```
.
├── README.md          # Descripción del laboratorio y avance
└── docs/
    └── nomenclatura.md  # Convención de nombres por ambiente
```

## Historial

Cada paso del laboratorio se registra en un commit independiente que actualiza el estado
del recurso en la tabla anterior. Las capturas de pantalla se entregan en el reporte de evidencias (Word).
