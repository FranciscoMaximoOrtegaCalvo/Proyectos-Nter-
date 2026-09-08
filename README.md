# Proyectos-Nter-

Repositorio con mis ejercicios prácticos de **Data & BI** — pipelines ETL, modelado de datos y dashboards — desarrollados durante mi formación en Nter.

## 📊 Power BI Service

Mis informes y dashboards también están publicados en Power BI:

👉 **[Ver mis informes en Power BI Service](https://app.powerbi.com/home?redirectedFromSignup=1&ScenarioId=Signup&redirectedWaitSimple=1&experience=power-bi)**

## 📁 Proyectos

| Proyecto | Descripción | Tecnologías |
|---|---|---|
| [Migración Fashion Shop S.A.](./Entregable_Proyecto_Tienda_Ropa_Francisco_Ortega) | ETL en Python que migra un sistema transaccional heterogéneo y sucio (SQL Server) a un Data Warehouse normalizado en PostgreSQL. Incluye limpieza y validación por reglas de negocio, cuarentena de registros erróneos, carga idempotente (UPSERT) y triggers de auditoría. | `Python` `Pandas` `SQLAlchemy` `PostgreSQL` `Docker` `Jupyter` |
| [ETL Mundial 2026](./Entregable_Proyecto_Mundial2026_Ortega_Calvo_Francisco) | Pipeline ETL en SSIS que consolida estadísticas de goleadores y asistentes del Mundial 2026 (CSV) en un Data Warehouse en PostgreSQL, con carga por lotes (COPY), cuarentena de errores y un dashboard de rendimiento en Power BI. | `SSIS` `PostgreSQL` `Docker` `Power BI` `DAX` |

Cada carpeta incluye su propia **Memoria Técnica** (`Memoria_Tecnica.docx`) con arquitectura, modelo de datos, alternativas consideradas y evidencias de pruebas, además del `docker-compose.yml` y el script DDL de cada proyecto.

## 🛠️ Stack habitual

- **ETL**: Python (Pandas, SQLAlchemy) · SSIS (Visual Studio)
- **Bases de datos**: PostgreSQL · SQL Server
- **Infraestructura**: Docker
- **Visualización**: Power BI (DAX, modelado de datos)
- **Herramientas**: DBeaver · Jupyter · Visual Studio

## 👤 Autor

**Francisco Máximo Ortega Calvo** — Data & BI
