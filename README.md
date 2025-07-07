# 📊 Análisis del Rendimiento de AWC con Power BI

---

## 🏢 Contexto

Adventure Works Cycles es una empresa multinacional que fabrica y distribuye bicicletas y accesorios en Norteamérica, Europa y Asia. Ante la ausencia de indicadores clave para la toma de decisiones, se desarrolló un **dashboard en Power BI** para monitorear y mejorar su rendimiento comercial.

---

## 🎯 Objetivo

Crear un **informe integral e interactivo** que:
- Analice ventas, utilidades y costos.
- Visualice datos por categorías y territorios.
- Permita comparativos interanuales.
- Sirva como herramienta de soporte para decisiones estratégicas.

---

## 🛠️ Proceso del Proyecto

### 1. 🔗 Conexión y Limpieza de Datos
- Base de datos: `AdventureWorksDW2019` (restaurada en SQL Server).
- Tablas utilizadas: `FactInternetSales`, `DimProduct`, `DimCustomer`, `DimGeography`, entre otras.
- Limpieza: Eliminación de nulos, relaciones entre tablas optimizadas, importación adicional desde Excel.

### 2. 🧠 Modelado y Mockup
- Modelo en estrella para eficiencia y claridad.
- Uso de DAX para medidas calculadas.
- Diseño visual basado en el patrón de lectura en Z.
- Paleta de colores profesional (morado, rosa claro, blanco).

### 3. 📐 Medidas y Cálculos DAX
Incluye KPIs como:
- **Ingresos / Ingresos acumulados**
- **Costos (Producción, Envío, Totales)**
- **Utilidad Bruta y Neta (y sus acumulados)**
- **Clientes únicos, artículos vendidos**
- **Comparativos interanuales (LY)**
- **Ratios e indicadores financieros** como ROI, márgenes y variaciones porcentuales

### 4. 🧩 Parámetros y Grupos de Cálculo
- Se implementaron campos parametrizados para cambiar dinámicamente entre métricas clave como Ingresos, Utilidad Neta, COGS, etc.
- Mejora del rendimiento y experiencia del usuario sin duplicar visualizaciones.

### 5. 📊 Desarrollo del Dashboard

🔗 **[Haz clic aquí para ver el dashboard interactivo en Power BI](https://app.powerbi.com/view?r=eyJrIjoiNGVmM2UzZWItNmZiZi00YzA5LWI0OTMtMjA5YzVmODVkYjI1IiwidCI6ImQ4MzdlZDExLWY2OTYtNGM4OS04OGZkLTdjY2Q5NmY4NjAxNSJ9&pageName=554374e4d42bec4a87d4)**

Pantallas diseñadas:
- **Portada:** Logotipo, navegación jerárquica y botones principales.
- **Informe General:** KPIs, gráficos por categoría, mapa geográfico.
- **Detalle Financiero:** Análisis por mes y categoría, tendencias y márgenes.
- **Reporte USA:** KPIs regionales, tabla por estado, gráficos de pastel.

---

## 📈 Principales Hallazgos

- **Estacionalidad de ingresos:** Picos en ciertas campañas promocionales.
- **Rentabilidad:** Utilidad bruta estable, pero presión en utilidad neta por mayores costos logísticos.
- **Clientes y ventas:** Estables, pero sin crecimiento exponencial.
- **Comparativos temporales:** Disminuciones en algunos trimestres que requieren revisión operativa y de mercado.

---

## 🧭 Recomendaciones y Futuro

1. **Segmentación de clientes:** Identificar recurrentes vs nuevos.
2. **Optimización logística:** Analizar rutas y proveedores de envío.
3. **Simulación de descuentos:** Evaluar impacto en márgenes y ROI.
4. **Customer Lifetime Value (CLV):** Para estrategias de retención.
5. **Pronóstico de ventas:** Incorporar IA o Power BI Forecast.

---

## 💡 Reflexión Personal

Este proyecto me permitió consolidar habilidades en:
- Modelado de datos eficiente
- Análisis estratégico de KPIs
- Diseño de dashboards funcionales y visualmente atractivos
- Comunicación efectiva de insights

Transformar datos en decisiones fue el mayor aprendizaje. Si lo volviera a hacer, priorizaría una exploración más profunda desde el inicio y automatización de filtros avanzados.

---

## 📎 Recursos

- Power BI Desktop
- SQL Server
- AdventureWorksDW2019
- Excel para carga adicional de datos

---

## 📌 Notas Finales

Este dashboard no solo refleja el estado actual de la empresa, sino que se convierte en una plataforma para una toma de decisiones **ágil, fundamentada y escalable**.

---
## 👩‍💻 Autor

**Martha Flor Salinas Guadarrama**  
📧 [marthaflorsg@gmail.com](mailto:marthaflorsg@gmail.com)  
🔗 [LinkedIn – Martha Flor Salinas G.](https://www.linkedin.com/in/mflor-salinas-g)

> Proyecto desarrollado como parte del Módulo 3 del programa **Data Analytics 2.0** de Henry Bootcamp.
