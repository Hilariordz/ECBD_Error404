# Datos Preprocesados - Análisis de Reservaciones

**ECBD_Error404**

Repositorio con datos preprocesados y análisis de reservaciones hoteleras.

## Contenido

### Datasets
- `reservaciones.csv` - Datos originales de reservaciones
- `reservaciones_limpias.csv` - Datos después del primer proceso de limpieza
- `reservaciones_limpias_v2.csv` - Datos con limpieza mejorada
- `reservaciones_con_clusters.csv` - Datos con clusters asignados del análisis no supervisado

### Notebooks de Análisis
- `SHU3_AnalisisSupervisado.ipynb` - Análisis supervisado de reservaciones
- `SHU4_AnálisisNoSupervisado.ipynb` - Análisis de clustering y segmentación

### Visualizaciones
- `heatmap.png` - Mapa de calor de correlaciones
- `tabla_optimizacion.png` - Resultados de optimización de clusters
- `tabla_perfil_cluster.png` - Perfil de características por cluster
- `tabla_perfil_cluster_V2.png` - Perfil de clusters versión actualizada

## Uso

1. Clonar el repositorio
2. Abrir los notebooks en Jupyter o Google Colab
3. Los datasets están listos para análisis

## Requisitos

- Python 3.x
- Jupyter Notebook
- pandas, numpy, scikit-learn, matplotlib, seaborn
