# EEDPF-LA: Systematic Review on Student Dropout Prediction in Latin America

Bienvenido al repositorio oficial de material complementario (Open Science) del artículo científico: 
**"Modelos predictivos de aprendizaje automático y variables determinantes en la deserción estudiantil en educación superior en América Latina: Una revisión sistemática de literatura (2020–2026)"**.

Este repositorio ha sido creado para garantizar la total transparencia, trazabilidad y reproducibilidad de nuestra Revisión Sistemática de Literatura (SLR), conducida bajo los lineamientos del estándar **PRISMA 2020**.

---

## Resumen del Estudio
A pesar de la probada efectividad de los clasificadores de *Machine Learning* a nivel internacional, su extrapolación al contexto de América Latina presenta vacíos empíricos. Este estudio analiza sistemáticamente 156 investigaciones primarias para evaluar las arquitecturas predictivas, el tratamiento de clases desbalanceadas (ej. SMOTE vs. GANs) y la integración de técnicas de Inteligencia Artificial Explicable (XAI). 

Como contribución teórica central, el artículo propone el **EEDPF-LA** (*Explainable Educational Dropout Prediction Framework for Latin America*), una arquitectura de cinco capas orientada a superar el enfoque predictivo de "caja negra" y fomentar la intervención pedagógica prescriptiva e hiper-personalizada.

### Preguntas de Investigación (PI) abordadas:
* **PI1:** ¿Cuáles son las variables predictoras (académicas, socioeconómicas, institucionales o demográficas) de mayor prevalencia e impacto algorítmico identificadas en los modelos de predicción de deserción en América Latina?
* **PI2:** ¿Qué arquitecturas de aprendizaje automático reportan la mayor frecuencia de implementación y efectividad comparativa en la literatura regional reciente?
* **PI3:** ¿Qué métricas de desempeño y técnicas de preprocesamiento (ante clases desbalanceadas) constituyen el estándar de evaluación del rigor metodológico en estos estudios empíricos?

---

## Estructura del Repositorio

En este repositorio encontrarás los insumos metodológicos detallados:

* **`Cadenas_Busqueda.txt`**: Contiene la parametrización exacta de las ecuaciones de búsqueda booleanas aplicadas en Scopus, Web of Science (WoS), IEEE Xplore y ACM Digital Library.
* **`ExtraccionDataPrisma.csv`**: Matriz de extracción de datos consolidada. Contiene la codificación manual de las 12 dimensiones analíticas extraídas de los 156 estudios primarios de la muestra final.
* **`diagrama_prisma.pdf`**: Diagrama de flujo completo según la declaración PRISMA 2020, detallando la inclusión y exclusión de los registros en cada fase.
* **`Archivos_VOSviewer.zip`**: *Datasets* relacionales exportados para la generación de las redes bibliométricas de coocurrencia (evolución temática) y coautoría analizadas en el Capítulo 4.

---

## Sobre el Framework (EEDPF-LA)
El framework propuesto consolida el estado del arte regional en 5 capas secuenciales:
1. Ingesta y Gobernanza de Datos (DAMA-DMBOK y Privacidad *by-design*).
2. Preprocesamiento y Balanceo Sintético mediante Redes Generativas Adversarias (CTGAN / WGAN-GP).
3. Motor Predictivo Híbrido (Ensambles basados en árboles + Redes Neuronales Recurrentes LSTM).
4. Inteligencia Artificial Explicable (Modelos agnósticos locales y globales como SHAP y LIME).
5. Intervención y Diseño Centrado en el Usuario (UX) para reducir la carga cognitiva del gestor académico.

---

## Contacto
Para dudas sobre la metodología, el análisis de datos o posibles colaboraciones de investigación, no dude en abrir un *Issue* en este repositorio o contactar a los autores del artículo.

