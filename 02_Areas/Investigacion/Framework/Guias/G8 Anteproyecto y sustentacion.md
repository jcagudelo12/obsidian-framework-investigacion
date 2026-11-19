---
tipo: guia-investigacion
fase: F8
---
# G8 · Anteproyecto completo y sustentación oral

**Plantilla:** [[Plantillas/Investigacion/F8 Anteproyecto|F8 Anteproyecto]] · **Anterior:** [[G7 Estado del arte con protocolo replicable|G7]] · **Siguiente:** [[G9 Estructura del informe final|G9]]

## Propósito

A lo largo de las fases anteriores se construyó el cuerpo investigativo: planteamiento, pregunta, hipótesis, justificación y objetivos (F2); marcos (F5); antecedentes y estado del arte con protocolo (F7). Esta fase **cierra el anteproyecto**: consolida lo trabajado, agrega una primera versión del capítulo de **Metodología** y lo sustenta.

Dos ideas la orientan:

1. **El anteproyecto es el punto de partida de la etapa siguiente.** La metodología y el alcance preliminares son el insumo del plan de gestión (alcance y WBS, estimación, cronograma, riesgos) y de la construcción y validación del producto.
2. **La sustentación es un ensayo de la sustentación final** del trabajo de grado: misma estructura, distinto estado del producto. En la final, la mayor parte del tiempo es el software funcionando; aquí se presenta lo que se va a construir y cómo.

## Qué se entrega

| Entregable | Formato | Nombre sugerido |
|---|---|---|
| Informe del anteproyecto, con anexos dentro | Word (.docx) sobre la plantilla del informe | `NombreCorto_Anteproyecto.docx` |
| Presentación de la sustentación | PowerPoint o PDF | `NombreCorto_Sustentacion.pptx` |

## Contenido del informe

### Anteproyecto consolidado (lo de mayor peso)

Versión final y coherente de: planteamiento, pregunta, hipótesis, justificación y objetivos; marcos teórico, conceptual y legal; antecedentes y estado del arte con protocolo, PRISMA, matriz comparativa y brechas.

Se incorporan todas las observaciones de la fase anterior, en especial las obligatorias: **ejecución del cribado, lista de excluidos en texto completo con su razón, aritmética del flujo PRISMA, matriz comparativa completa, referencias corregidas en el gestor y declaración de IA completa y firmada.** Si una observación no se acoge, se justifica en un comentario.

### Capítulo 3 · Metodología (versión preliminar, 3–5 páginas, narrativa)

**3.1 Metodología de desarrollo del producto.** Qué enfoque es el más apropiado (ágil como Scrum, Kanban o XP; híbrido; predictivo) y **por qué**, a partir de las características del proyecto y del equipo: tamaño y disponibilidad, estabilidad de los requisitos, incertidumbre técnica y participación del usuario. Basta con la elección razonada y una descripción general de roles e iteraciones.

**3.2 Alcance preliminar y plan general.** Qué se propone construir (componentes y funcionalidades principales), qué queda por fuera, y un cronograma general por fases o iteraciones. Es una delimitación inicial, no un plan detallado.

**3.3 Estrategia de validación de la solución.** Cómo se comprobará si el producto cumple el objetivo y responde a la hipótesis: **indicadores con línea base y meta**, sujetos o escenarios de prueba, instrumentos y comparación antes y después. Coherente con el método (design science con su componente de validación, ver [[G6 Metodos de investigacion empirica|G6]]) y con las variables del marco conceptual.

### Secciones que todavía no se desarrollan

Resumen, palabras clave, reconocimientos, resultados y conclusiones se escriben al final del proyecto. La lista de acrónimos se actualiza; las referencias van en APA 7 desde el gestor; la declaración de IA se actualiza con las tareas de esta fase. El informe es **autocontenido**: los soportes van como anexos, no como enlaces externos.

## Productos de otras asignaturas (insumos, sin nota)

Se anexan, indicando su origen, los productos que existan sobre el proyecto. No se piden productos nuevos ni se rehacen.

| Área | Productos que conviene reunir | Para qué sirven después |
|---|---|---|
| Ingeniería de requisitos | Registro de elicitación; casos de uso e historias de usuario con criterios de aceptación; especificación y modelos; priorización y matriz de trazabilidad | Gestión de requisitos |
| Arquitectura de software | Escenarios de atributos de calidad; modelo de la arquitectura (C4); decisiones registradas como ADR | Arquitectura |
| Construcción de software | Pruebas (TDD/BDD), análisis estático, pipeline CI/CD, servicio o API | Producto y calidad del código |
| Patrones y diseño | Diseño de arquitectura y prototipo con patrones | Producto y arquitectura |
| Gestión de datos | Modelo y arquitectura de datos; componente de datos para IA | Modelo de datos |

## Presentación (10–12 diapositivas, poco texto, figuras legibles)

| # | Bloque | Qué debe mostrar | Tiempo |
|---|---|---|---|
| 1 | Título, integrantes y asesor | Una diapositiva | 0,5 min |
| 2 | Problema | Contexto con datos, situación negativa, causas y efectos; pregunta e hipótesis | 2,5 min |
| 3 | Justificación y objetivos | Por qué importa y para quién; objetivo general y específicos | 1,5 min |
| 4 | Estado del arte | PRISMA en una diapositiva; matriz con el proyecto como última fila; brechas | 3,5 min |
| 5 | Metodología y alcance | Enfoque y por qué; qué se construirá y qué no; cronograma | 2,5 min |
| 6 | Validación | Indicadores, línea base, metas y cómo se medirán | 2 min |
| 7 | Insumos de otras asignaturas | Lo más representativo de requisitos, arquitectura y construcción | 2,5 min |

**Dinámica:** 15 minutos de presentación y 5 de preguntas. Todos exponen y cualquiera puede ser interrogado sobre cualquier parte. Se expone **sin leer** (sin guiones ni notas), con cámara encendida si es virtual. **Lo que más pesa son las respuestas a las preguntas.** Lo que no se alcance a presentar no se evalúa.

En la sustentación final del trabajo de grado (unos 30 minutos ante jurados) los bloques 2 a 6 se reducen a unos cinco minutos y el bloque 7 se convierte en la demostración del producto, sus requisitos y su arquitectura.

## Criterios de calidad

| Criterio | Peso | Nivel excelente |
|---|---|---|
| **Informe** | **80 %** | |
| Planteamiento, objetivos y marcos en versión final | 20 % | Problema, pregunta, hipótesis, justificación y objetivos coherentes; marcos articulados con el proyecto; observaciones incorporadas. |
| Antecedentes y estado del arte en versión final | 25 % | Correcciones obligatorias incorporadas; protocolo y PRISMA auditables; matriz completa; brechas conectadas con la pregunta y los objetivos. |
| Estrategia de validación | 12 % | Indicadores con línea base y meta; instrumentos; coherencia con la hipótesis y el método. |
| Metodología de desarrollo | 8 % | Enfoque elegido con razones frente al contexto del proyecto y del equipo; roles e iteraciones. |
| Alcance preliminar y plan | 5 % | Delimitación de lo que se construye y lo que no; cronograma coherente con los objetivos. |
| Formato, referencias e integridad | 10 % | Documento con acabado final (sin marcadores de plantilla ni comentarios abiertos); figuras y tablas numeradas y explicadas; APA 7 desde el gestor; anexos dentro; declaración de IA completa. |
| **Sustentación** | **20 %** | |
| Coherencia y completitud | 5 % | Cubre los bloques y muestra un solo proyecto: el problema explica los objetivos, el estado del arte justifica la propuesta y la validación responde a la hipótesis. |
| Dominio y respuestas | 12 % | Cada integrante explica y defiende cualquier parte; respuestas pertinentes y honestas sobre lo que aún no se sabe. |
| Comunicación y tiempo | 3 % | Exposición sin leer, participación equilibrada, diapositivas legibles, 15 minutos. |

## Recomendaciones

- Dediquen la mayor parte del tiempo a dejar en versión final lo ya trabajado: es lo que más pesa y lo que recibe la etapa siguiente.
- En la metodología de desarrollo, una elección razonada vale más que una descripción extensa: digan qué característica del proyecto y del equipo hace apropiado el enfoque.
- Mantengan el alcance realista para el tamaño del equipo y el tiempo disponible.
- **La hipótesis manda sobre la validación:** si promete una reducción de tiempo, debe haber línea base medida o un plan concreto para medirla en la primera iteración.
- No produzcan nada nuevo para los insumos de otras asignaturas: reúnan lo que tienen. Su valor está en tener todo en un solo lugar.
- Ensayen con cronómetro: quince minutos para siete bloques exige ir a lo esencial.
- Hagan una pasada de edición final: marcadores de plantilla, comentarios abiertos, numeración de secciones, listas de tablas y figuras.
