# 🔍 Análisis funcional de los módulos de coexpresion

Con los módulos de coexpresión ya identificados, se llevó a cabo un análisis de enriquecimiento funcional para determinar qué procesos biológicos, rutas metabólicas o mecanismos moleculares estaban sobrerrepresentados dentro de cada conjunto de genes.
El objetivo de este análisis fue interpretar biológicamente los módulos, vinculando las correlaciones observadas con funciones celulares relevantes en la enfermedad de Parkinson.

El enriquecimiento funcional consiste en comparar la lista de genes de un módulo con bases de datos de conocimiento biológico (como GEO) identificando aquellos términos que aparecen con mayor frecuencia de lo esperado por azar.
De este modo, es posible inferir qué funciones o rutas biológicas comparten los genes que se coexpresan, ofreciendo una interpretación funcional de los módulos detectados.


## STRING

El análisis se realizó utilizando la plataforma STRING que permiten ingresar listas de genes y obtener los procesos enriquecidos con sus respectivos valores de significancia estadística (p-ajustada o FDR).
Cada módulo (M1, M2, M3, etc.) fue analizado por separado, empleando como organismo de referencia Homo sapiens y estableciendo un umbral de significancia de p-ajustada < 0.05.
Para cada módulo se generaron salidas en formato tabular (.tsv) y visualizaciones gráficas (gráficos de barras o burbujas), donde se destacaron las principales categorías funcionales enriquecidas.

### Integración con la red centrada en SNCA
Una vez caracterizados los módulos de coexpresión y sus respectivas funciones biológicas, se procedió a integrar los resultados con una red centrada en el gen SNCA (α-sinucleína), ampliamente reconocido como uno de los principales actores moleculares implicados en la enfermedad de Parkinson.
El propósito de esta etapa fue evaluar la relación entre los módulos detectados y las interacciones moleculares que involucran a SNCA, con el fin de identificar posibles genes conectores o rutas compartidas que pudieran explicar mecanismos patológicos de la enfermedad.

## Cytoscape

Tras la obtención de los módulos de coexpresión y la red centrada en SNCA, se utilizó la plataforma Cytoscape para realizar la visualización e integración final de toda la red génica.

Dentro de Cytoscape se pueden calcular indicadores de centralidad, principalmente el grado (degree) y la intermediación (betweenness), con el fin de evaluar la importancia topológica de cada gen dentro de la red.

La representación final en Cytoscape permitió observar de manera integrada la arquitectura de la red, mostrando cómo los módulos coexpresados se interrelacionan y en qué posición se encuentra SNCA dentro del sistema.
Gracias a esta visualización fue posible distinguir módulos densamente conectados, identificar genes puente entre comunidades y reconocer a SNCA como un nodo de alta conectividad, coherente con su papel central en la fisiopatología del Parkinson.
