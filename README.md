# Web-Scraping
Stockholm Insights was hired by “Retail AB,” an electronics distributor, to monitor competitor pricing. The goal was to identify real-time price changes and analyze the availability of key products. The data is cleaned and visualized in a dashboard that enables the pricing team to detect competitive opportunities


# 📊 Retail Pricing Intelligence Demo – Stockholm Insights

## Cliente ficticio
Retail AB – distribuidor de electrónica en Suecia.

## Objetivo
Monitorear precios y disponibilidad de productos en 2 competidores clave.  
El proyecto recolecta información, limpia los datos y los visualiza en un dashboard interactivo.

## Flujo del proyecto
1. **Scraping**: extracción de productos desde 2 sitios web (ejemplo).  
2. **Limpieza**: normalización de precios, categorías y nombres.  
3. **Análisis**: dataset limpio en CSV listo para explorar.  
4. **Dashboard**: visualización de precios, categorías y evolución temporal.

## Entregables
- Código de scraping en `scraping/`.  
- Scripts de limpieza en `analysis/`.  
- Dataset de ejemplo en `data/`.  
- Mini-dashboard en Streamlit (`dashboard/app.py`).  
- Capturas del dashboard en `reports/`.  

## Ejecución
```bash
# Instalar dependencias
pip install -r requirements.txt

# Ejecutar scraper
python scraping/scraper_site1.py
python scraping/scraper_site2.py

# Limpiar datos
python analysis/clean_data.py
