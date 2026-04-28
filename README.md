# Algoritmos de Clustering (fundamentos)

Este repositorio contiene una **píldora educativa** diseñada para estudiantes del **Bootcamp de Data Analyst**. El objetivo es proporcionar una guía teórica y práctica sobre el aprendizaje no supervisado, explorando cómo las máquinas logran identificar patrones y "tribus" ocultas en grandes volúmenes de datos sin intervención humana previa.


## 📁 Contenido del Repositorio

El proyecto se compone de los siguientes recursos fundamentales:

*   **`Algoritmos de clusstering_fundamentos.pdf`**: Un documento detallado que recorre la historia y la teoría del clustering, desde el mapa del cólera de John Snow hasta la sofisticación de los algoritmos modernos.
*   **`Comporativa_K-means y DBSCAN.png`**: Una infografía comparativa que visualiza las diferencias críticas entre el agrupamiento basado en centroides y el basado en densidad.
*   **`ejercicio_clustering_quest.ipynb`**: Un cuaderno de Jupyter interactivo que contiene implementaciones prácticas, visualizaciones y retos para aplicar los conceptos aprendidos.
*   **`README.md`**: Guía de navegación del proyecto (este archivo).


## 🚀 Conceptos Clave Explorados

A través de estos materiales, los estudiantes explorarán:

1.  **K-Means (El Enfoque Geométrico):** Entender el "baile" de los centroides y cómo los diagramas de Voronoi dividen el espacio de datos en territorios rígidos.
2.  **DBSCAN (El Enfoque de Densidad):** Cómo identificar grupos con formas orgánicas (como el *smiley face data*) y filtrar el ruido basándose en la proximidad de los datos.
3.  **Evaluación de Modelos:** Técnicas para medir el éxito en la "oscuridad" del aprendizaje no supervisado, incluyendo:
    *   **Método del Codo (Elbow Method):** Para determinar el número óptimo de clústeres (K).
    *   **Coeficiente de Silueta:** Para medir la cohesión y separación de los grupos.
4.  **Evolución Técnica:** Introducción a algoritmos avanzados como **HDBSCAN y OPTICS** para manejar densidades variables.


## 🛠️ Requisitos

Para ejecutar el cuaderno de ejercicios, se recomienda tener instaladas las siguientes librerías de Python:
* `scikit-learn`: Modelado de K-Means, DBSCAN y métricas de validación.
* `pandas` & `numpy`: Manipulación de estructuras de datos.
* `matplotlib` & `seaborn`: Visualizaciones 2D y 3D interactivas.
* `scipy`: Construcción de dendrogramas.

---


## 💡 Filosofía del Proyecto

Como se detalla en los fundamentos, el **clustering no da respuestas finales, sino pistas inteligentes para investigar**. Este repositorio busca dotar al analista de datos de la "brújula" necesaria para navegar por océanos de datos hiperdimensionales y descubrir verdades que el lenguaje ordinario aún no alcanza a nombrar.


## 🔗 Recursos Adicionales
Encuentra simuladores interactivos para ver estos algoritmos en acción:
* [Visualizando K-Means](https://www.naftaliharris.com/blog/visualizing-k-means-clustering/)
* [Visualizando DBSCAN](https://www.naftaliharris.com/blog/visualizing-dbscan-clustering/)

---
*Píldora educativa creada por Oksana Tokmakova para el Bootcamp Data Analyst, Factoría F5.*