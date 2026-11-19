---
tipo: guia-investigacion
fase: F5
---
# G5 · Marco teórico, conceptual y legal

**Plantilla:** [[Plantillas/Investigacion/F5 Marcos|F5 Marcos]] · **Anterior:** [[G4 Ingenieria de software basada en evidencia|G4]] · **Siguiente:** [[G6 Metodos de investigacion empirica|G6]]

## Propósito

El informe se construye de forma incremental sobre el mismo documento. En esta fase se **corrige lo anterior** con base en la retroalimentación y se construyen los marcos del proyecto:

- el **teórico**, que explica el problema y la solución desde la teoría;
- el **conceptual o referencial**, que precisa los conceptos del dominio y de la solución;
- el **legal**, que identifica la normativa aplicable y analiza cómo condiciona el diseño.

Los antecedentes y el estado del arte se desarrollan en la fase siguiente (F7). La ficha EBSE es el punto de partida de ese trabajo.

## 1. Introducción corregida

Se incorporan todas las observaciones de la retroalimentación de F2 y los ajustes identificados en F3 (B3) y F4 (paso 4): enunciado del problema, delimitación, pregunta, hipótesis con **variable operacionalizada**, objetivo general y específicos. Si una observación no se acoge, se dice y se justifica brevemente en el texto o en un comentario del documento.

## 2.1 Marco teórico

Fundamentos teóricos, modelos y enfoques que permiten comprender el problema y sustentar la solución. Responde, en forma narrativa, a dos preguntas:

- **¿Desde qué teoría se entiende el problema?** (por ejemplo: accesibilidad y comunicación, gestión del conocimiento en organizaciones, economía de plataformas y costos de búsqueda, planificación con restricciones).
- **¿Desde qué teoría se entiende la solución?** (por ejemplo: arquitectura de software, sistemas de recomendación, recuperación de información y generación aumentada, reconocimiento de patrones, satisfacción de restricciones).

**Cada bloque teórico cierra explicando qué aporta al proyecto:** qué decisión de diseño, qué variable o qué criterio de evaluación se deriva de él.

> [!warning] El marco teórico no es una recopilación de definiciones ni el resumen de un libro de texto. Extensión orientativa: 4 a 8 páginas, con fuentes académicas (libros, artículos, normas técnicas) citadas en el texto.

## 2.2 Marco conceptual o referencial

Explica los conceptos clave del dominio del problema y de la solución, **integrados en párrafos** que muestran cómo se relacionan entre sí y con el proyecto. Deben quedar definidos, como mínimo, los términos que aparecen en el enunciado del problema, en la pregunta, en la hipótesis (incluida **la variable que se va a medir y su definición operacional**) y en los objetivos.

> [!warning] No es un glosario
> No se acepta una lista de términos con definiciones independientes ni viñetas tipo diccionario. Si un concepto tiene varias acepciones en la literatura, se dice cuál se adopta y por qué. Extensión orientativa: 2 a 4 páginas.

## 2.3 Marco legal, normativo o regulatorio

Identificación y análisis de la normativa que aplica al problema y a la solución: leyes, decretos y resoluciones; regulaciones del sector; y, cuando apliquen, estándares técnicos (presentados como **estándares**, no como normas jurídicas). Para cada norma relevante se explica **qué exige** y **cómo condiciona el diseño o la operación**: qué datos se pueden tratar y cómo, qué consentimientos se necesitan, qué obligaciones tiene la organización y qué restricciones técnicas se derivan.

Lista de referencia para proyectos en Colombia (en otro país, reemplazar por las normas equivalentes). Revisar como mínimo la pertinencia de:

- Ley 1581 de 2012 y Decreto 1377 de 2013 (protección de datos personales; datos sensibles como biometría, salud o discapacidad).
- Ley 1273 de 2009 (delitos informáticos).
- Ley 527 de 1999 (mensajes de datos y firma electrónica).
- Ley 1480 de 2011 (Estatuto del Consumidor), cuando hay usuarios finales.
- CONPES 4144 de 2025 y lineamientos sobre inteligencia artificial, cuando la solución usa modelos de IA.
- Normativa sectorial propia del proyecto (laboral, educativa, de accesibilidad, financiera o comercial).

No se trata de listar normas sino de **analizar su impacto**: una norma que no condiciona nada en el proyecto no necesita estar.

## Referencias

Lista completa en **APA 7** de todas las fuentes citadas en el texto, y solo de ellas. Se espera citación correcta; se tolera algún detalle de formato que el gestor bibliográfico resolverá, pero no citas faltantes, fuentes sin citar ni fuentes no académicas (blogs, páginas comerciales) usadas como soporte teórico.

## Numeración del informe

Todo el planteamiento va dentro de *1. Introducción*; los marcos teórico, conceptual y legal como 2.1, 2.2 y 2.3 dentro de *2. Marco teórico*, dejando espacio para antecedentes (2.4) y estado del arte (2.5). Extensión orientativa de lo nuevo: 8 a 14 páginas.

## Criterios de calidad

| Criterio | Peso | Nivel excelente |
|---|---|---|
| Correcciones de la fase anterior | 20 % | Todas las observaciones y los ajustes de enfoques y EBSE incorporados o justificados; planteamiento, pregunta, hipótesis y objetivos coherentes. |
| Marco teórico | 25 % | Teorías pertinentes para el problema y la solución, narrativas, con fuentes académicas y el aporte de cada bloque explícito. |
| Marco conceptual | 20 % | Conceptos del problema, de la hipótesis (variable operacionalizada) y de la solución, definidos con fuentes, integrados en párrafos, con la acepción declarada. |
| Marco legal | 20 % | Normativa pertinente con el análisis de cómo cada norma condiciona el diseño u operación; estándares diferenciados de normas jurídicas. |
| Coherencia, formato y fuentes | 15 % | Los marcos sostienen el planteamiento y los objetivos; plantilla respetada; citas APA y lista de referencias correspondiente. |

## Recomendaciones

- Empiecen por releer toda la retroalimentación anterior y marquen cada observación a medida que la resuelvan, para que ninguna se pierda.
- Para el marco teórico, partan de la **variable de la hipótesis** y de las **causas que el proyecto interviene**: la teoría que necesitan es la que explica esas causas y la que fundamenta la forma de intervenirlas. Lo demás es relleno.
- Escriban el marco conceptual **al final**, cuando sepan qué términos usaron en el teórico y en el planteamiento; así no definen conceptos que luego no aparecen.
- En el marco legal, pregúntense por cada norma: *"¿qué tendría que cambiar en mi diseño si esta norma no existiera?"*. Si la respuesta es "nada", la norma no va.
- Usen las fuentes de la ficha EBSE y de la fase de enfoques como primeras entradas del marco teórico: ya las tienen valoradas.
