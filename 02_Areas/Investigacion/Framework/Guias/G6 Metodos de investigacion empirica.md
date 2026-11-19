---
tipo: guia-investigacion
fase: F6
---
# G6 · Métodos de investigación empírica en ingeniería de software

**Plantilla:** [[Plantillas/Investigacion/F6 Metodo de investigacion|F6 Método de investigación]] · **Anterior:** [[G5 Marco teorico conceptual y legal|G5]] · **Siguiente:** [[G7 Estado del arte con protocolo replicable|G7]]

## Para qué sirve

Con problema, pregunta, hipótesis, objetivos y marcos listos, falta decir **con qué método se va a responder la pregunta**. Esa decisión determina dos cosas: qué debe buscar el estado del arte y cómo se diseña la evaluación. Se elige entre cuatro métodos: revisión sistemática de literatura, design science, estudio de caso y experimento.

> [!important] Enfoque ≠ método
> El **enfoque** (cuantitativo, cualitativo o mixto) dice qué tipo de datos se recogen; el **método** dice cómo se organiza la investigación para responder la pregunta. Un mismo método admite varios enfoques: un estudio de caso puede ser mixto, un experimento es cuantitativo y design science suele combinar ambos.

## 1. Revisión sistemática de literatura (RSL)

- **Qué es.** Un método para identificar, evaluar e interpretar toda la evidencia disponible sobre una pregunta, con un protocolo explícito y replicable (Kitchenham y Charters, 2007). Es la forma rigurosa de la EBSE.
- **Cuándo es el método principal.** Cuando la pregunta se responde con lo ya publicado ("¿qué técnicas se han usado para X y con qué resultados?"). Es el método de un trabajo cuya contribución es la síntesis misma.
- **Cuándo es un componente.** En todos los demás métodos: es la forma de construir el estado del arte y justificar las brechas.
- **Qué produce.** Protocolo, flujo PRISMA 2020, tabla de extracción, síntesis por temas y brechas.
- **Calidad.** Replicabilidad del protocolo, cobertura de fuentes, acuerdo entre revisores en el cribado y verificación de cada estudio incluido.

## 2. Design science (ciencia del diseño)

- **Qué es.** Un método para proyectos que diseñan un **artefacto** (software, arquitectura, método, modelo) para intervenir un problema en un contexto, y que evalúan si produce el efecto esperado (Wieringa, 2014; Hevner et al., 2004). Su ciclo tiene cuatro momentos: investigación del problema, diseño del tratamiento, validación del tratamiento e implementación del tratamiento.
- **Cuándo aplica.** Cuando la pregunta tiene la forma *"¿en qué medida un artefacto que haga A modifica la variable B en el contexto C?"*. Si la contribución es un artefacto y la evidencia de que funciona, el método es design science, sin importar la tecnología.

| Momento del ciclo (Wieringa) | Dónde está en el trabajo de grado |
|---|---|
| Investigación del problema: actores, causas, efectos, teoría | F1, F2, F5 y estado del arte (F7) |
| Diseño del tratamiento: requisitos, alternativas, decisión de diseño | Alcance preliminar (F8); ingeniería de requisitos y gestión del proyecto |
| Validación del tratamiento: ¿produce el efecto? ¿bajo qué condiciones? | Diseño de la validación (F8); ejecución en la etapa de desarrollo (F9) |
| Implementación del tratamiento: uso real en la organización | Fuera del alcance académico; trabajo futuro |

> [!important] La validación no es un método en sí: se hace con uno de los otros (experimento, estudio de caso, simulación, encuesta). Un proyecto de design science declara **dos cosas**: que es design science y qué método usa para validar.

- **Qué produce.** El artefacto, su justificación de diseño (de las teorías a las decisiones) y la evidencia de validación.
- **Calidad.** Relevancia del problema, rigor del diseño (trazabilidad de cada decisión), rigor de la validación y claridad de las condiciones bajo las cuales el efecto se sostiene.

## 3. Estudio de caso

- **Qué es.** Investigación empírica de un fenómeno contemporáneo en su contexto real, cuando los límites entre fenómeno y contexto no son claros, con múltiples fuentes de evidencia (Yin, 2018; Runeson y Höst, 2009).
- **Cuándo aplica.** Preguntas de "cómo" o "por qué" en las que el investigador no controla las variables. También como método de validación en design science cuando el artefacto se despliega en una organización y se observa su uso.
- **Qué produce.** Descripción del caso y su contexto, unidades de análisis, cadena de evidencia (entrevistas, observación, documentos, registros), hallazgos y lecciones transferibles (no generalizables estadísticamente).
- **Calidad.** Triangulación de fuentes, cadena de evidencia trazable, validación con los participantes, protocolo del caso, discusión de validez de constructo, interna, externa y fiabilidad.

## 4. Experimento

- **Qué es.** El investigador manipula una variable independiente (el tratamiento) y mide su efecto sobre una o más dependientes, controlando las demás (Wohlin et al., 2024). Responde a "¿en qué medida A cambia B?" con la mayor fuerza causal.
- **Variantes:**
  - **Controlado:** asignación aleatoria a grupos de tratamiento y control. Poco frecuente en trabajos de grado por la muestra.
  - **Cuasiexperimento:** hay comparación, pero sin asignación aleatoria.
  - **Pre-post de un solo grupo:** se mide antes y después sobre los mismos sujetos, sin control. Es el más común; exige declarar las amenazas (historia, maduración, aprendizaje de la tarea, novedad, instrumentación) y cómo se mitigan.
  - **Pareado:** cada sujeto se compara consigo mismo en dos condiciones; reduce la variabilidad y permite muestras pequeñas.
  - **Por simulación:** el tratamiento se aplica sobre un modelo o datos sintéticos; la validez depende de la calibración del modelo (De França y Travassos, 2015).
- **Qué produce.** Hipótesis operativas, variables con definición operacional, diseño (sujetos, tratamientos, objetos, instrumentos), procedimiento, análisis estadístico y amenazas a la validez.
- **Calidad.** Validez de conclusión, interna, de constructo y externa; fiabilidad de los instrumentos y evaluadores; potencia estadística o justificación del tamaño de muestra.

## 5. Cómo se combinan en un trabajo de grado de ingeniería de software

La forma típica: se construye un artefacto para intervenir un problema y se quiere saber si produce el efecto prometido. Eso es **design science**, con una **RSL** como componente de investigación del problema y un **experimento** (en alguna variante) o un **estudio de caso** como componente de validación. La decisión tiene tres partes:

1. **Método principal:** design science, porque la contribución es un artefacto y su validación.
2. **Componente de revisión:** la RSL con protocolo (F7).
3. **Componente de validación:** el diseño concreto (pre-post, pareado, simulación, caso), las variables del marco conceptual, la línea base, los instrumentos, el análisis y las amenazas a la validez.

## 6. Cómo decidir: cuatro preguntas en orden

La primera respuesta afirmativa fija el método principal; las siguientes fijan los componentes.

1. ¿La pregunta se responde con lo ya publicado, sin construir ni medir nada nuevo? **Sí →** revisión sistemática. **No →** siga.
2. ¿La contribución es un artefacto que se construye para intervenir un problema, y la pregunta es si produce un efecto? **Sí →** design science (la RSL es su componente); pase a la 3. **No →** pase a la 4.
3. ¿Se puede manipular la variable independiente y medir el efecto contra una línea base o una condición alternativa? **Sí →** validación experimental (controlado, cuasi, pre-post, pareado o simulación). **No, porque se despliega en una organización real y interesa cómo se usa →** validación por estudio de caso.
4. ¿Se quiere entender cómo o por qué ocurre un fenómeno en su contexto real, sin controlar variables? **Sí →** estudio de caso. **No, se quiere probar una relación causal sin construir un artefacto →** experimento.

> [!tip] Criterio de cierre
> Si la hipótesis dice "el artefacto reduce o aumenta X en al menos Y %" → design science con validación experimental. Si dice "el artefacto mejora la práctica en la organización Z" → design science con validación por estudio de caso. Si no hay artefacto, es uno de los otros dos.

## 7. Ejercicio: ubica tu proyecto

Responde la tabla de la plantilla F6: artefacto, efecto y variable, método principal, componente de validación, línea base, sujetos o escenarios, principal amenaza a la validez y **qué debe buscar el estado del arte**.

> [!tip] Pista
> El estado del arte de un proyecto de design science busca tres cosas: **qué artefactos** se han propuesto para el mismo problema, **cómo los evaluaron** (método, variables, instrumentos) y **qué resultados** obtuvieron. Esas tres cosas son las columnas de la matriz comparativa y la base de las brechas.

## Referencias

De França, B. B. N., & Travassos, G. H. (2015). Simulation based studies in software engineering: A matter of validity. *CLEI Electronic Journal, 18*(1). · Hevner, A. R., March, S. T., Park, J., & Ram, S. (2004). Design science in information systems research. *MIS Quarterly, 28*(1), 75–105. · Kitchenham, B., & Charters, S. (2007). *Guidelines for performing systematic literature reviews in software engineering* (EBSE Technical Report 2007-01). · Page, M. J., et al. (2021). The PRISMA 2020 statement. *BMJ, 372*, n71. · Peffers, K., Tuunanen, T., Rothenberger, M. A., & Chatterjee, S. (2007). A design science research methodology for information systems research. *Journal of Management Information Systems, 24*(3), 45–77. · Runeson, P., & Höst, M. (2009). Guidelines for conducting and reporting case study research in software engineering. *Empirical Software Engineering, 14*(2), 131–164. · Shadish, W. R., Cook, T. D., & Campbell, D. T. (2002). *Experimental and quasi-experimental designs for generalized causal inference*. Houghton Mifflin. · Wieringa, R. J. (2014). *Design science methodology for information systems and software engineering*. Springer. · Wohlin, C., et al. (2024). *Experimentation in software engineering* (2.ª ed.). Springer. · Yin, R. K. (2018). *Case study research and applications* (6.ª ed.). Sage.
