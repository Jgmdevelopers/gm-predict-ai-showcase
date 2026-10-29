# GM Predict AI

**Investigación y desarrollo de una plataforma modular de análisis de series temporales con Python.**

**Estado:** prototipo de investigación. El trabajo actual se centra en la adquisición, paginación y validación de datos históricos. Los módulos predictivos se encuentran en la hoja de ruta; no se presentan resultados de modelos entrenados ni métricas de predicción.

## ¿Qué problema busca resolver?

Organizar un flujo reproducible que permita obtener datos históricos, verificar su integridad y preparar el terreno para experimentar con modelos predictivos de forma controlada.

## Enfoque técnico

- **Python** para construir módulos independientes.
- **Datos temporales OHLCV** como ejemplo de entrada para investigaciones de series temporales.
- **Validación de datos**: controles de rangos, intervalos, orden temporal y consistencia de registros.
- **Pruebas automatizadas con pytest**, incluyendo casos límite y simulación de proveedores externos con mocks.
- **TDD y refactorización incremental** para reducir errores y facilitar el mantenimiento.

## Arquitectura conceptual

```text
Fuente de datos
     |
     v
Ingesta y validación  <-- etapa en desarrollo
     |
     v
Construcción de características -- planificada
     |
     v
Entrenamiento y evaluación ------ planificados
     |
     v
Predicción y seguimiento ------- planificados
```

Este diagrama describe una **hoja de ruta conceptual**, no funcionalidades completadas.

## Qué demuestra este proyecto

El trabajo con GM Predict AI pone el foco en la calidad de datos, el diseño modular, el manejo de condiciones de error y una forma de desarrollar guiada por pruebas. No se utiliza para operar con fondos reales ni constituye un servicio de recomendaciones financieras.

## ¿Por qué el código es privado?

El desarrollo y su historial permanecen en un repositorio privado mientras continúa la investigación y se evalúa su posible uso comercial. Este espacio público funciona como **presentación técnica**, sin contener el código propietario, estrategias ni datos internos.

## Autor

**Gabriel Molina** — Técnico Superior en Programación, desarrollador backend.

- [GitHub](https://github.com/Jgmdevelopers)
- [LinkedIn](https://www.linkedin.com/in/gabriel-molina-ush/)

---

*Información general sobre un proyecto en evolución. Las funcionalidades y los resultados indicados se actualizarán cuando puedan verificarse.*
