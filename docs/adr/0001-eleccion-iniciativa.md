# ADR 0001 — Elección de iniciativa

- **Estado:** Aceptado
- **Fecha:** 20/10/2026
- **Autores:** Sebastián Chacon

## 1. Contexto

El equipo debía seleccionar una iniciativa entre las alternativas presentadas en la actividad, considerando su utilidad, viabilidad y posibilidades de aplicar los conocimientos de arquitectura de software.

## 2. Decisión

Se seleccionó AulaViva, una plataforma educativa SaaS multi-tenant con tutor de Inteligencia Artificial basado en RAG.

La plataforma permitirá gestionar estudiantes, docentes, cursos y evaluaciones, incorporando un tutor IA que utilice contenidos educativos para contextualizar sus respuestas.

## 3. Justificación

- Permite abordar una necesidad del entorno educativo.
- Incorpora Inteligencia Artificial aplicada al aprendizaje.
- Presenta desafíos relevantes de seguridad y aislamiento de datos.
- Permite desarrollar un MVP de manera incremental.
- Facilita aplicar conocimientos de arquitectura, API, servicios cloud y pruebas.

## 4. Consecuencias

### Positivas

- El equipo dispone de un objetivo común.
- Las funcionalidades pueden organizarse en módulos.
- Se pueden planificar entregas incrementales.
- Se pueden evaluar progresivamente la seguridad y la calidad del tutor IA.

### Desafíos

- Garantizar el aislamiento de los datos entre instituciones.
- Evaluar la calidad y pertinencia de las respuestas de la IA.
- Controlar los costos y la complejidad técnica.
- Realizar pruebas y mantener la documentación actualizada.

## 5. Alternativas descartadas

[Indicar las otras iniciativas evaluadas durante la actividad y explicar brevemente por qué no fueron seleccionadas.]

## 6. Resultado esperado

Desarrollar un MVP educativo con gestión académica básica, separación de información por institución y un tutor IA basado en RAG.
