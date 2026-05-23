# Mining Safety Analytics 

### Análisis de Accidentabilidad en la Industria Minera de U.S.A. (2000–2024)
---
## 👤 Autor
---
## 📌 Descripción del proyecto
Este proyecto analiza alrededor de **300,000 registros reales** de accidentes, lesiones  y fatalidades en la industria minera de EE.UU., utilizando datos oficiales del **Mine Safety and Health Administration (MSHA)**.
Se debe aplicar un analisis de datos en para responder preguntas criticas en la seguridad minera ¿qué tipo de accidentes ocurren con mas frecuencia ?, ¿en qué operaciones ocurren más fatalidades?,¿Cual es la tendencia del FIR.AIR desde 2000 hasta el 2025?

---

## 🎯 Preguntas de negocio
---
## 🗂️ Estructura del repositorio
---
## 📦 Fuente de datos
| Dataset | Fuente | Registros | Actualización |
|---|---|---|---|
| Accident & Injuries | [MSHA Open Data](https://www.msha.gov/msha-datasets) | +300,000 | Semanal |
| Mines Information | [MSHA Mines Dataset](https://catalog.data.gov/dataset/msha-mines-dataset) | +96,000 minas | Semanal |
|AIR & FIR|[Number of employee hours reported](https://wwwn.cdc.gov/NIOSH-Mining/MMWC/Employee/Hours)|+25 registro|anual|

>Los datos son de **acceso público y gratuito**.
---
## 🔄 Flujo de trabajo
---
## 📊 Hallazgos principales
---
## 📐 KPIs calculados

| KPI | Definición | Fórmula |
|---|---|---|
| **AIR** | All injures Rate(Tasa de lesiones totales) | (Accidentes registrables × 200,000) / Horas trabajadas |
| **FIR** | fatality Injury Rate (Tasa de Fatalidades) | (  Fatalidades registradas  × 200,000) / Horas trabajadas |
| **Días perdidos promedio** | Severidad promedio por evento | Total días perdidos / Total accidentes con días perdidos |
> El factor 200,000 corresponde a las horas trabajadas por 100 trabajadores en un año de 50 semanas.

> Días perdidos promedio solo se utilizan los eventos que ocurren lesion, es decir, se excluyen las fatalidades y sin eventos de lesion y dias perdidos, ya que afecta al calculo del promedio. 
---
## 🖼️ Vista previa del dashboard

### Página 1 — Accidentabilidad.

### Página 2 — Fatalidad.

### Página 3 — Causa.

### Página 4 — Comparacion.

### Página 5 — Modelo de Datos.
---
## 📄 Licencia
Los datos utilizados son de dominio público, publicados por el U.S. Department of Labor bajo la iniciativa Open Government Data.
