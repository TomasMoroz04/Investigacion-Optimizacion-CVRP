<h1 align="center">🚚 Análisis y Diseño de Algoritmos</h1>
<h3 align="center">Capacitated Vehicle Routing Problem (CVRP)</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Investigación-Académica-6C5CE7?style=for-the-badge" alt="Investigación académica">
  <img src="https://img.shields.io/badge/Optimización-CVRP-0A7EA4?style=for-the-badge" alt="CVRP">
  <img src="https://img.shields.io/badge/IA-Deep%20Learning-412991?style=for-the-badge" alt="Deep Learning">
  <img src="https://img.shields.io/badge/Computación-Cuántica-00897B?style=for-the-badge" alt="Computación cuántica">
  <img src="https://img.shields.io/badge/Documento-LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white" alt="LaTeX">
</p>

Artículo de investigación académica desarrollado para la cátedra de **Análisis y Diseño de Algoritmos** (3.° año de Ingeniería en Informática, UGD).

Este repositorio contiene un estudio sobre la evolución de los métodos de resolución del **Problema de Enrutamiento de Vehículos Capacitados (CVRP)**, un problema clásico de optimización combinatoria de clase NP-hard. El trabajo analiza la transición desde heurísticas y metaheurísticas tradicionales hacia enfoques de frontera, con énfasis en **Optimización Combinatoria Neuronal (NCO)**, **Grandes Modelos de Lenguaje (LLM)** y **computación cuántica híbrida**.

---

## 📑 Índice

- [Contexto y autores](#-contexto-del-proyecto-y-autores)
- [Tecnologías y enfoques](#-tecnologías-y-enfoques-investigados)
- [Hallazgos del análisis](#-hallazgos-clave)
- [Archivos del repositorio](#-estructura-del-repositorio)

---

## 👥 Contexto del proyecto y autores

Esta investigación fue realizada de forma colaborativa durante el ciclo lectivo 2026.

**Autores de la investigación:**

- S. Halberstadt
- M. Kalesplaner
- **Tomás Moroz** — curador de este repositorio
- R. Ruiz

---

## 🔬 Tecnologías y enfoques investigados

El estudio compara familias de algoritmos considerando el tiempo de ejecución (latencia), la calidad de la solución (brecha o *gap*) y la escalabilidad.

### 🧮 Enfoques clásicos

Análisis de las limitaciones de algoritmos exactos como **Branch-and-Bound** y **Branch-and-Cut**, junto con metaheurísticas tradicionales como **Tabu Search**, **Ant Colony Optimization** y **Genetic Algorithms**, frente al crecimiento combinatorio del problema.

### 🧠 Deep Learning y NCO

Estudio de redes neuronales de grafos (**GNN**) y aprendizaje por refuerzo (**PPO**) con técnicas de enmascaramiento de acciones (*Action Masking*) para generar soluciones con baja latencia y responder a escenarios variables, como cambios de tráfico o demanda.

### 💬 LLM como guías heurísticas

Análisis de la integración de modelos de lenguaje para aportar información semántica y razonamiento estructurado (*Chain-of-Thought*), orientando fases iniciales de algoritmos de aprendizaje por refuerzo y filtrando rutas temporalmente inviables.

### ⚛️ Computación cuántica híbrida

Estudio de solucionadores como **Hybrid Quantum Tabu Search (HQTS)** sobre procesadores **D-Wave Advantage** mediante *Quantum Annealing*, combinados con CPU clásicas para explorar espacios de soluciones.

---

## 📊 Hallazgos clave

El documento presenta las siguientes conclusiones dentro del alcance de la investigación:

1. **Reducción de latencia:** los enfoques neuronales e híbridos pueden trasladar parte del costo computacional a una etapa de entrenamiento *offline*, permitiendo tiempos de inferencia bajos frente a ciertos métodos clásicos.
2. **Adaptabilidad dinámica:** los métodos basados en IA pueden facilitar el recálculo de rutas ante cambios logísticos e imprevistos en tiempo real.
3. **Competitividad en precisión:** el documento reporta brechas (*gaps*) de entre el **1 % y el 4,7 %** respecto de la solución óptima teórica para los métodos y las instancias analizados.

> **Alcance:** los resultados y comparaciones deben interpretarse según las instancias, métricas y fuentes citadas en el artículo; no implican que un método sea superior en todos los escenarios de CVRP.

---

## 📂 Estructura del repositorio

- **`Investigacion_CVRP.pdf`** — artículo completo en formato académico IEEE/Springer LNCS, con introducción, estado del arte, análisis técnico, tabla comparativa y referencias bibliográficas.
- **`Investigacion_CVRP_Latex.tex`** — código fuente en LaTeX utilizado para generar el documento.

---

<p align="center"><b>Algoritmos · Optimización combinatoria · IA · Computación cuántica</b></p>
