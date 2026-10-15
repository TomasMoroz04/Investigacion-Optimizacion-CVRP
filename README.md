# 🚚 Análisis y Diseño de Algoritmos: Capacitated Vehicle Routing Problem (CVRP)

Artículo de investigación académica desarrollado para la cátedra de **Análisis y Diseño de Algoritmos** (3.° año de Ingeniería en Informática, UGD).

Este repositorio aloja un estudio exhaustivo sobre la evolución de los métodos de resolución para el **Problema de Enrutamiento de Vehículos Capacitados (CVRP)**, un clásico problema de optimización combinatoria de clase NP-Hard. El paper analiza la transición desde las heurísticas y metaheurísticas tradicionales hacia las tecnologías de frontera, enfocándose en la **Optimización Combinatoria Neuronal (NCO)**, el uso de **Grandes Modelos de Lenguaje (LLMs)** y los enfoques híbridos de **Computación Cuántica**.

---

## 👥 Contexto del Proyecto y Autores

Esta investigación fue realizada de forma colaborativa durante el ciclo lectivo 2026. 

**Autores de la investigación:**
* S. Halberstadt
* M. Kalesplaner
* **Tomás Moroz** *(Curador de este repositorio)*
* R. Ruiz

---

## 🔬 Tecnologías y Enfoques Investigados

El estudio realiza un análisis comparativo de algoritmos para evaluar el balance entre tiempo de ejecución (latencia), precisión de la solución (gap) y escalabilidad:

*   **Enfoques Clásicos:** Limitaciones de los algoritmos exactos (Branch-and-Bound, Branch-and-Cut) y metaheurísticas tradicionales (Tabu Search, Ant Colony Optimization, Genetic Algorithms) frente a la explosión combinatoria.
*   **Deep Learning & NCO:** Aplicación de Redes Neuronales de Grafos (GNN) y Aprendizaje por Refuerzo (PPO) con técnicas de enmascaramiento de acciones (*Action Masking*) para generar soluciones en milisegundos y manejar la incertidumbre (tráfico, demanda dinámica).
*   **LLMs como Guías Heurísticas:** Integración de modelos de lenguaje para aplicar lógica semántica y razonamiento estructurado (*Chain-of-Thought*) que guían las primeras fases de algoritmos Q-Learning, filtrando rutas temporalmente inviables.
*   **Computación Cuántica Híbrida:** Solucionadores como el *Hybrid Quantum Tabu Search (HQTS)* ejecutados en procesadores *D-Wave Advantage* (Quantum Annealing) combinados con CPUs clásicas para explorar espacios de soluciones masivos en microsegundos.

---

## 📊 Hallazgos Clave

El análisis comparativo desarrollado en el documento demuestra que:
1.  **Reducción drástica de latencia:** Los métodos neuronales e híbridos cuánticos trasladan el costo computacional a la fase de entrenamiento *offline*, permitiendo resolver instancias complejas en milisegundos o microsegundos, a diferencia de las horas requeridas por métodos clásicos.
2.  **Adaptabilidad Dinámica:** Las tecnologías basadas en IA superan la rigidez de los enfoques estáticos, permitiendo recalcular rutas en tiempo real ante imprevistos logísticos (Logística 4.0).
3.  **Competitividad en Precisión:** A pesar de la velocidad extrema, los modelos cuánticos y neuronales logran mantener brechas de error (*gaps*) marginales (1% - 4.7%) respecto a la solución óptima teórica.

---

## 📂 Estructura del Repositorio

* `Investigacion_CVRP.pdf` — Documento completo del artículo de investigación (formato académico IEEE/Springer LNCS), incluyendo introducción, estado del arte, análisis técnico detallado, tabla comparativa y referencias bibliográficas.
* `Investigacion_CVRP_Latex.tex` — Documento con el código en LaTeX.
