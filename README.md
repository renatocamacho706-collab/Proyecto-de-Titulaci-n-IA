# Sistema de Auditoría de Calidad Industrial con IA - ILEPSA 

Este repositorio contiene el desarrollo integral de un sistema híbrido de Inteligencia Artificial para la optimización del control de calidad en la producción de botellas.

## Evolución y Métricas del Modelo
El proyecto atravesó 7 fases de ensayo para alcanzar la optimización actual, logrando un equilibrio entre precisión y reducción de errores.

| Progreso de Precisión (7 Ensayos) | Comparativa Inicial vs Final |
|---|---|
| ![Evolución](resultados/Precisión%20vs%20reducción%20de%20errores%20ensayo%207) | ![Comparativa](resultados/comparación%20inicial%20con%20la%20final%20del%20modelo%20me...) |

> **Métricas Clave:** mAP50 de **0.94** | Latencia de **24ms** | Precisión Final de **93%**.

---

## Validación de Auditoría (Dataset de Control)
Evaluación del prototipo mediante análisis de defectos (etiquetado y llenado) y rendimiento estadístico.

| Auditoría Integral de Defectos | Rendimiento Final (F1/Recall) |
|---|---|
| ![Auditoría Integral](resultados/auditoria%20integral) | ![Rendimiento](resultados/rendimiento%20final.png) |

---

## Análisis Operativo y Económico
Visualización del flujo de producción en tiempo real y el impacto financiero del prototipo frente a la línea base manual.

| Flujo de Detecciones en Tiempo Real | Recuperación Económica |
|---|---|
| ![Flujo](resultados/flujo%20de%20detecciones.jpg) | ![Economía](resultados/comparacion%20economica%20referencial%20de%20la%20linea...) |

---

## Tecnologías y Metodología
- **Arquitectura de IA:** YOLOv8 Nano optimizado para baja latencia.
- **Visión Artificial:** Lógica híbrida con OpenCV (Filtro Gaussiano y análisis de ROI).
- **Procesamiento:** Script integral de auditoría (`auditoria_ilepsa_final.py`).
- **Dataset:** Gestión y aumentación de datos en Roboflow.

---
