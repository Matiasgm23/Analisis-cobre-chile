# Análisis del Mercado del Cobre en Chile 1990-2024

## Descripción
Análisis histórico del precio del cobre usando datos reales de COCHILCO 
(Comisión Chilena del Cobre). El proyecto explora 34 años de datos para 
identificar ciclos, tendencias y el impacto de eventos globales en el 
precio del principal commodity de Chile.

## Insights encontrados
- El precio del cobre se multiplicó **4 veces** en 30 años, de 101 cUS$/lb 
  en los 90s a 380 cUS$/lb en los 2020s
- Los peores años fueron **1998** (-27.4%) y **2009** (-25.7%), ambos 
  asociados a crisis financieras globales
- El **peak histórico** fue 2021 con 422 cUS$/lb, impulsado por la 
  recuperación post-pandemia y la demanda de vehículos eléctricos
- El cobre **no tiene estacionalidad mensual** significativa — sus precios 
  responden a factores macroeconómicos globales, no a temporadas

## Fuente de datos
- **COCHILCO** (Comisión Chilena del Cobre) — cochilco.cl
- Precios del Cobre Refinado Mensual y Anual 1935-2024
- Anuario de Estadísticas del Cobre 2005-2024

## Tecnologías utilizadas
- Python (Pandas, Matplotlib, Seaborn)
- Power BI
- Jupyter Notebook

## Estructura del proyecto
proyecto2_cobre/
├── data/                          # Datasets de COCHILCO
├── graficos/                      # Gráficos generados en Python
├── 01_exploracion.ipynb           # Exploración inicial de datos
├── 02_limpieza.ipynb              # Limpieza y transformación
├── 03_eda.ipynb                   # Análisis exploratorio profundo
├── 04_storytelling.ipynb          # Narrativa y conclusiones
└── dashboard_cobre.pbix           # Dashboard Power BI

## Pasos para reproducir
1. Clonar el repositorio
2. Instalar dependencias: `pip install pandas matplotlib seaborn openpyxl`
3. Ejecutar los notebooks en orden del 01 al 04
4. Abrir `dashboard_cobre.pbix` en Power BI Desktop