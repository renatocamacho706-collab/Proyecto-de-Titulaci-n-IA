# Sistema de Auditoría de Calidad Industrial con IA - ILEPSA

Este repositorio contiene el desarrollo de un sistema de visión artificial híbrido diseñado para optimizar el control de calidad en la producción de envases.

## Evolución y Métricas del Modelo
El proyecto se perfeccionó a través de 7 ensayos técnicos, logrando una optimización progresiva de la precisión.

| Progreso de Precisión (7 Ensayos) | Comparativa Inicial vs Final |
|---|---|
| ![Evolución](https://github.com/renatocamacho706-collab/Proyecto-de-Titulaci-n-IA/blob/main/resultados/Precisi%C3%B3n%20vs%20reducci%C3%B3n%20de%20errores%20ensayo%207?raw=true) | ![Comparativa](resultados/comparación%20inicial%20con%20la%20final%20del%20modelo%20metrica_entrenamiento_v7.png) |

> **Cifras de Desempeño (Modelo v7):**
> * **mAP50:** 0.94 (Precisión Media del 94%)
> * **Precisión de Clasificación:** 93%
> * **Latencia:** 24.3 ms (Procesamiento en tiempo real)

---

## Validación de Auditoría (Dataset de Control)
Evaluación del prototipo sobre un lote de 55 imágenes críticas de la planta.

| Auditoría Integral de Defectos | Rendimiento Final (F1/Recall) |
|---|---|
| ![Auditoría Integral](resultados/auditoria%20integral%20de%20defectos.jpg) | ![Rendimiento](resultados/rendimiento%20final.png) |

> **Resultados de la Validación:**
> * **Tasa de Calidad Detectada:** 58.82%
> * **Detección de Fallos:** 25 botellas sin etiqueta y 3 con nivel de llenado bajo identificadas con éxito.

---

## Análisis Operativo y Económico
Impacto financiero y flujo de trabajo comparado con la línea base de inspección manual.

| Flujo de Detecciones | Recuperación Económica |
|---|---|
| ![Flujo](resultados/flujo%20de%20detecciones.jpg) | ![Economía](resultados/comparacion%20economica%20referencial%20de%20la%20linea%20base%20y%20el%20prototipo.png) |

---

## Metodología Técnica
* **Modelo:** YOLOv8 Nano optimizado.
* **Lógica Híbrida:** IA para detección + Visión Clásica para niveles de transparencia (Umbral 145).
* **Dataset:** 600+ imágenes procesadas y aumentadas en Roboflow.
