# Diagramas_sedimentologia
Graficas de Análisis Sedimentológico y Procesamiento de Datos de Granulometría 
📂 Estructura de Datos (Compatibilidad GRADISTAT)
El flujo de trabajo está diseñado para ser compatible con la estructura de entrada de GRADISTAT. Para procesar nuevas muestras, solo debes asegurar que el archivo de entrada mantenga las columnas de:
Identificación: Proyecto, Año, Muestra.
Ubicación: Latitud y Longitud (formato grados decimales o DMS).
Distribución Granulométrica: Porcentajes de Grava, Arena y Finos (Limo/Arcilla).
Parámetros Estadísticos: El script valida los resultados de Mean, Sorting, Skewness y Kurtosis calculados bajo la escala de Krumbein ($\phi$).

📊 Visualización Automática
Con solo cargar el archivo, el notebook ejecuta:
Curvas Granulométricas: Generación de curvas de frecuencia acumulada.
Diagramas de Folk: Clasificación automática de las muestras en el triángulo textural (Arena, Limo, Arcilla).
Comparativa Temporal: Si los datos incluyen diferentes años (ej. 2012 vs 2015), el código separa las series para analizar la evolución morfológica de la costa.
