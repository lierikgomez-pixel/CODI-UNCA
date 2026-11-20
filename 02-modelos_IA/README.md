# 02 · Modelos de IA

Paquete de entregables de los dos modelos integrados en CODI-UNCA. Este repo no incluye código ejecutable; los scripts están en el repositorio de código fuente.

| Entregable | Archivo |
| --- | --- |
| Paquete de entrenamiento (4 páginas) | `paquete_entrenamiento.pdf` |
| Evidencias de evaluación (3 páginas) | `evidencias_evaluacion.pdf` |
| Información del dataset de visión | `01-modelo_vision/informacion_dataset.md` |
| Entrenamiento de visión y métricas | `01-modelo_vision/entrenamiento/` |
| Evaluación de visión y app | `01-modelo_vision/evaluacion/` |
| Modelo base del asistente | `02-llm/modelo_base.md` |
| Dataset del asistente (12 FAQs) | `02-llm/dataset/` |
| Ajuste RAG local + few-shot | `02-llm/ajuste/` |
| Arquitectura | `03-arquitectura/arquitectura.md` |

## Resultados reales

- Visión: accuracy **0.9868**, F1 macro **0.9897**, 596/604 aciertos, recall `sin_limon` **1.00**.
- App: **12/12** casos.
- Asistente: base **1/10**, adaptado **10/10**, consistencia **10/10** en 3 repeticiones.

El asistente **no** se ajustó con LoRA/QLoRA; se usó RAG local + few-shot por trazabilidad y funcionamiento sin servicios externos.
