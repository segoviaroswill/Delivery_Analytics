# Análisis de factores que influyen en el tiempo de entrega

## Descripción
Este proyecto analiza los tiempos de entrega de pedidos con el objetivo de identificar los factores que generan retrasos y proponer mejoras operativas basadas en datos.


## Objetivo
Evaluar cómo influyen variables como el tráfico, el clima, el tipo de vehículo y la ciudad en la eficiencia del servicio de entrega.

## Preguntas de negocio
- ¿Qué factores impactan más el tiempo de entrega?
- ¿Cómo varía el tiempo según el tráfico y el clima?
- ¿Existen diferencias significativas por ciudad o tipo de vehículo?
- ¿En qué franjas horarias se presentan más retrasos?

## Conjunto de datos
- Más de **40.000 registros** de pedidos de entrega.
- Variables temporales, geográficas y operativas.
- División en **train** y **test** para análisis y validación.

## Proceso de análisis
1. Limpieza de datos (nulos, formatos, outliers).  
2. Ingeniería de variables (fechas, tiempos, categorías).  
3. Análisis exploratorio (EDA).  
4. Definición y cálculo de KPIs.  
5. Visualización de resultados.  
6. Conclusiones y recomendaciones.

## KPIs analizados

### KPIs operativos
- Tiempo promedio de preparación  
- Tiempo promedio de entrega  
- Tiempo total promedio por pedido  
- Calificación promedio  

### KPIs por condiciones externas
- Tiempo por clima  
- Tiempo por tráfico  
- Tiempo por ciudad  
- Tiempo por tipo de vehículo  

### KPIs de actividad y demanda
- Actividad por día de la semana  
- Pedidos por hora punta  

## Herramientas utilizadas
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Jupyter Notebook  

## Resultados principales
- El **tráfico alto** incrementa significativamente el tiempo promedio de entrega.  
- Las **motos** presentan mejores tiempos en horas pico.  
- La **distancia recorrida** tiene menor impacto que factores operativos y contextuales.

  
