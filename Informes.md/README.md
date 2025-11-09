# 📚 Fundamentos teóricos y bibliografía del proyecto

El desarrollo de este trabajo se apoyó en una selección de fuentes científicas que abarcan tanto la comprensión biológica del gen SNCA y la enfermedad de Parkinson como los enfoques analíticos y computacionales aplicados en el procesamiento de datos y la construcción de redes génicas.

A continuación, se resumen los principales grupos temáticos en los que se fundamentó el análisis:

---

### 🧬 Contexto biológico y fisiopatología del Parkinson  
Las revisiones de **Martínez-Fernández**, **Marín**, **Konno** y **Lesnick** brindan una visión actualizada de los **mecanismos patológicos del Parkinson**, la degeneración de la sustancia negra y las alteraciones moleculares que afectan el sistema dopaminérgico.  

Estos estudios proporcionan el marco general para comprender la relevancia de los genes analizados y la elección del dataset GSE7621 como base experimental.

---

### 🧠 Rol de la α-sinucleína y del gen SNCA  
Trabajos como los de **Trinh et al.**, **Jahabardeen et al.**, **Calabresi et al.**, **Soukup et al.** y **Maraganore** abordan la función de **α-sinucleína (SNCA)** y su implicación en procesos de **proteostasis, transporte vesicular y neurotoxicidad**.  

Estas referencias respaldan la interpretación de los resultados obtenidos en torno al papel central de SNCA dentro de la red integrada y su influencia sobre las rutas de comunicación neuronal.

---

### ⚡ Energía, mitocondrias y conectividad neuronal  
Los trabajos de **Henrich et al.**, **Watanabe et al.** y **MuraliMahadevan et al.** establecen la conexión entre la **disfunción mitocondrial**, la reducción del ATP y la acumulación de α-sinucleína.  

Desde esta perspectiva, los módulos identificados en la red se interpretan como representaciones funcionales de la **homeostasis energética y metabólica** alterada en el Parkinson.

---

### 🔗 Organización de redes y hubs neuronales  
El concepto de **hubs** y de conectividad funcional se sustenta en los aportes de **van den Heuvel & Sporns**, **Sang et al.** y **Akgüller et al.**, quienes demostraron que los nodos de alta conectividad son esenciales para la integración y resiliencia de las redes cerebrales.  

Esta noción fue trasladada al análisis de redes génicas, donde los **genes hub** representan puntos críticos de regulación dentro del sistema de coexpresión.

---

### 🧩 Alteraciones sinápticas y rutas moleculares clave  
Estudios como los de **Zou**, **Soukup** y **Calabresi** profundizan en la disfunción del **ciclo vesicular sináptico**, la **neurotransmisión dopaminérgica** y la **regulación del calcio**.  

Estas investigaciones permitieron asociar los módulos sinápticos obtenidos con procesos neuronales específicos, validando la interpretación biológica de los resultados de coexpresión.

---

### 💻 Metodología bioinformática y análisis de redes  
El procesamiento y análisis computacional se apoyaron en marcos metodológicos consolidados:  
- **Zhang & Horvath (WGCNA)**: detección de módulos de coexpresión.  
- **Love et al. (DESeq2)**: análisis de expresión génica.  
- **Blondel et al.**: detección de comunidades con el algoritmo Louvain.  
- **Shannon et al. (Cytoscape)** y **Szklarczyk et al. (STRING)**: integración y visualización de redes biomoleculares.  

Estos enfoques permitieron aplicar métricas de conectividad y centralidad para identificar **genes clave (hubs)** y comunidades funcionales dentro del sistema.

---

### 🧾 Fuente de datos experimentales  
El conjunto de datos **GSE7621 (NCBI GEO)** fue utilizado como base empírica del estudio.  

Este dataset contiene perfiles de expresión génica de la **sustancia negra** de pacientes con Parkinson y controles sanos, permitiendo realizar el pipeline completo, desde la normalización y filtrado hasta la construcción de redes y detección de módulos, en un contexto biológico real.

---

📖 La lista completa de referencias bibliográficas se incluye en el archivo **`Bibliografía`**, que acompaña este repositorio.
