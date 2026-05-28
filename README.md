# bigData-Class
Espacio subir cont para las clases ML

## Estado actual del trabajo
- Limpiado y reducido el dataset de GBIF para Colombia.
- Notebook `Notebook/01_read_filter_data.ipynb` genera `biodiversidad_limpa.parquet` con columnas limpias: `species`, `decimalLatitude`, `decimalLongitude`.
- Notebook `Notebook/02_agrupar_por_lat_lon.ipynb` realiza clustering KMeans y evalúa `k` con `silhouette` y `wss`.
- Se agregó análisis extendido de clusters con conteo de puntos, riqueza de especies y top especies por cluster.
- Resultados de clusters salvados en `Notebook/biodiversidad_clusters.parquet`.

> Continuar en la tarde desde `Notebook/02_agrupar_por_lat_lon.ipynb` para ajustar `k`, explorar mapas y refinar hotspots.
