# Sistema de Auditoría de Calidad Industrial - ILEPSA 

Este repositorio contiene el prototipo final de Inteligencia Artificial desarrollado para la Maestría en IA Aplicada, enfocado en el control de calidad de botellas.

## Resultados de Entrenamiento (Modelo v7)
El modelo final alcanzó una precisión óptima para la detección de objetos en tiempo real.

![Métricas de Entrenamiento](resultados/image_56b601.png)

- **mAP50:** 0.94
- **Precisión:** 93%
- **Latencia:** 24 ms

## Validación con Dataset de Control (55 Imágenes)
Se evaluó el sistema con un lote crítico de imágenes de la planta para medir la sensibilidad del prototipo.

![Resultado de Validación](resultados/image_564cc8.png)

- **Tasa de Calidad Detectada:** 58.82%
- **Fallas Identificadas:** 25 botellas sin etiqueta y 3 con nivel de llenado incorrecto.

## Tecnologías y Metodología
- **Arquitectura:** YOLOv8 Nano (Ultralytics).
- **Procesamiento:** Lógica Híbrida con OpenCV (Umbral de transparencia 145).
- **Gestión de Datos:** Etiquetado y aumentación en Roboflow.
