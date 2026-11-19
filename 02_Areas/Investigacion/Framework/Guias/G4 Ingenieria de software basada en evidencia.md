---
tipo: guia-investigacion
fase: F4
---
# G4 · Ingeniería de software basada en evidencia (EBSE)

**Plantilla:** [[Plantillas/Investigacion/F4 Ficha EBSE|F4 Ficha EBSE]] · **Anterior:** [[G3 Enfoques de investigacion|G3]] · **Siguiente:** [[G5 Marco teorico conceptual y legal|G5]]

## Propósito: ¿qué sabe ya el mundo sobre mi problema?

La EBSE (*Evidence-Based Software Engineering*; Kitchenham, Dybå y Jørgensen, 2004) propone que las decisiones sobre qué construir y cómo se tomen con la **mejor evidencia disponible**, y no solo con la intuición o la experiencia del equipo. Sus cinco pasos son los que se recorren en un trabajo de grado:

1. Convertir el problema en una pregunta contestable.
2. Buscar la mejor evidencia que la responda.
3. Valorar críticamente esa evidencia (validez, aplicabilidad, confiabilidad).
4. Integrarla con la experiencia del equipo y el contexto del proyecto.
5. Evaluar el resultado y mejorar.

En esta fase se aplican los pasos 1 a 4 al propio problema, con la pregunta de investigación de F2. El objetivo es que, **antes de diseñar nada**, se sepa qué se ha investigado sobre el problema y la solución, y qué implica eso para el proyecto. La ficha resultante es la **primera unidad del estado del arte** (F7).

## Paso 1 · De la pregunta de investigación a la pregunta de evidencia

La pregunta de investigación se descompone en formato **PICOC**:

| Componente | Pregunta guía | Ejemplo |
|---|---|---|
| **P**oblación | ¿A quién afecta el problema? | Personal operativo de una pyme de servicios, con barreras de lectoescritura |
| **I**ntervención | ¿Qué tipo de solución se propone? | Asistente conversacional de consulta (texto y voz) |
| **C**omparación | ¿Frente a qué se compara? | Consulta mediada por un coordinador |
| **O**utcome (resultado) | ¿Qué se espera que cambie? | Tiempo de respuesta, consistencia de la información |
| **C**ontexto | ¿Dónde y en qué condiciones? | Empresa de aseo, comunicación interna por WhatsApp |

Con el PICOC se formula una **pregunta de evidencia**, distinta de la de investigación:

> ¿Qué evidencia existe de que **[intervención]** mejora **[resultado]** en **[población / contexto]**, frente a **[comparación]**?

La pregunta de investigación es lo que **tú** vas a averiguar; la pregunta de evidencia es lo que **otros** ya averiguaron y necesitas saber antes de empezar.

## Paso 2 · Buscar

A partir del PICOC se construye una **cadena de búsqueda**: términos en inglés y en español para población, intervención y resultado; **sinónimos unidos con OR** y **componentes unidos con AND**. Ejemplo:

```
("conversational agent" OR chatbot OR "retrieval-augmented generation")
AND ("knowledge management" OR "internal documentation")
AND (SME OR "small business")
```

Se ejecuta en Google Scholar o en el buscador de la biblioteca (todavía no se exigen bases especializadas). Se ajusta si devuelve demasiado o muy poco, y se registran la versión final y el número aproximado de resultados.

Se elige un resultado que parezca responder la pregunta de evidencia: preferiblemente un **artículo de revista o congreso, una revisión sistemática o un trabajo de grado con evaluación**, de los últimos 5 a 8 años. Se anotan título, autores, año, dónde se publicó y el **enlace o DOI** (obligatorio).

## Paso 3 · Valorar críticamente

1. **Qué tipo de estudio es:** experimento, cuasiexperimento, estudio de caso, encuesta, revisión sistemática, propuesta sin evaluación u opinión.
2. **Con quién y dónde se hizo:** población, tamaño de la muestra, sector, país.
3. **Qué midió y qué encontró:** variables, instrumentos y resultado principal (con cifras si las hay).
4. **Qué tan parecido es a mi caso:** coincidencias y diferencias con el PICOC.
5. **Qué tan confiable es y por qué:** tipo de publicación, revisión por pares, tamaño de muestra, conflicto de interés, año.

## Paso 4 · Integrar: qué le cambia al proyecto

La evidencia **confirma** la hipótesis, la **matiza** (funciona pero en otras condiciones o con otro resultado), la **contradice**, o muestra que el problema **ya está resuelto** y el aporte tiene que ser otro. Se anota qué ajuste implica para la pregunta, la hipótesis o los objetivos; ese ajuste se recoge en F3 y F5.

## Criterios de calidad

| Criterio | Peso | Nivel excelente |
|---|---|---|
| PICOC y pregunta de evidencia | 30 % | Los cinco componentes se derivan correctamente de la pregunta de investigación; la pregunta de evidencia se puede responder con literatura y se distingue de la del proyecto. |
| Búsqueda y valoración crítica | 40 % | Cadena coherente con el PICOC (términos, sinónimos, operadores); artículo pertinente y verificable; las cinco preguntas respondidas con precisión y criterio. |
| Integración con el proyecto | 30 % | Conclusión explícita sobre qué implica la evidencia para la hipótesis y los objetivos; ajuste propuesto o justificación de que no hay ajuste. |

## Para después

Con el PICOC y la cadena listos, el estado del arte (F7) consiste en correr esa cadena en bases especializadas (Scopus, IEEE Xplore, ACM DL), gestionar las referencias con Zotero o Mendeley y **repetir esta ficha para cada trabajo relevante** (plantilla [[Plantillas/Investigacion/Registro - articulo|Registro - articulo]]).

**Referencias base:** Kitchenham, B. A., Dybå, T., & Jørgensen, M. (2004). Evidence-based software engineering. *Proceedings of ICSE 2004*, 273–281. · Dybå, T., Kitchenham, B. A., & Jørgensen, M. (2005). Evidence-based software engineering for practitioners. *IEEE Software, 22*(1), 58–65.
