# Nomenclatura de recursos

Convención definida en el archivo *Componentes a crear* del laboratorio.
Patrón: `<tipo>-utvt-integradora-<ambiente>-mxc-001`

| Recurso | Desarrollo (dev) | Pruebas (qa) | Producción (prod) |
|---|---|---|---|
| Resource Group | rg-utvt-integradora-dev-mxc-001 | rg-utvt-integradora-qa-mxc-001 | rg-utvt-integradora-prod-mxc-001 |
| App Service Plan | asp-utvt-integradora-dev-mxc-001 | asp-utvt-integradora-qa-mxc-001 | asp-utvt-integradora-prod-mxc-001 |
| Web App | app-utvt-integradora-web-dev-mxc-001 | app-utvt-integradora-web-qa-mxc-001 | app-utvt-integradora-web-prod-mxc-001 |
| Key Vault (si se utiliza) | kv-utvt-int-dev-mxc-001 | kv-utvt-int-qa-mxc-001 | kv-utvt-int-prod-mxc-001 |
| Application Insights | appi-utvt-integradora-dev-mxc-001 | appi-utvt-integradora-qa-mxc-001 | appi-utvt-integradora-prod-mxc-001 |
| Log Analytics Workspace | log-utvt-integradora-dev-mxc-001 | log-utvt-integradora-qa-mxc-001 | log-utvt-integradora-prod-mxc-001 |
| PostgreSQL Flexible Server | pgsql-utvt-integradora-dev-mxc-001 | pgsql-utvt-integradora-qa-mxc-001 | pgsql-utvt-integradora-prod-mxc-001 |

En este laboratorio se crea únicamente el ambiente **dev**, sin Key Vault ni PostgreSQL.
