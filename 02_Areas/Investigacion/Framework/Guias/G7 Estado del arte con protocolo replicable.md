---
tipo: guia-investigacion
fase: F7
---
# G7 · Antecedentes y estado del arte con protocolo replicable

**Plantillas:** [[Plantillas/Investigacion/F7a Protocolo de revision|F7a Protocolo]] · [[Plantillas/Investigacion/F7b Registro de busquedas|F7b Registro de búsquedas]] · [[Plantillas/Investigacion/Registro - articulo|Registro - articulo]] · [[Plantillas/Investigacion/F7c Cribado y PRISMA|F7c Cribado y PRISMA]] · [[Plantillas/Investigacion/F7d Sintesis y brechas|F7d Síntesis y brechas]] · [[Plantillas/Investigacion/F7e Antecedentes|F7e Antecedentes]] · [[Plantillas/Investigacion/F7f Declaracion uso de IA|F7f Declaración de IA]]
**Formatos para anexar:** [[02_Areas/Investigacion/Framework/Adjuntos/Protocolo de revision.docx|Protocolo (.docx)]] · [[02_Areas/Investigacion/Framework/Adjuntos/Bitacora revision de literatura.xlsx|Bitácora (.xlsx)]] · [[02_Areas/Investigacion/Framework/Adjuntos/Diagrama PRISMA 2020.docx|Diagrama PRISMA (.docx)]] · [[02_Areas/Investigacion/Framework/Adjuntos/Lista de verificacion PRISMA 2020.docx|Lista PRISMA (.docx)]] · [[02_Areas/Investigacion/Framework/Adjuntos/Declaracion de uso de IA.docx|Declaración de IA (.docx)]]
**Anterior:** [[G6 Metodos de investigacion empirica|G6]] · **Siguiente:** [[G8 Anteproyecto y sustentacion|G8]]

## Propósito

Responder la pregunta que dejó abierta la ficha EBSE: **¿qué sabe ya el mundo sobre mi problema y sobre las soluciones que se le han dado, y qué falta por hacer?** La respuesta no es una lista de trabajos relacionados: es un estado del arte **riguroso y replicable**, construido con un protocolo de revisión (pregunta, cadenas, fuentes, criterios) y reportado con el flujo **PRISMA 2020**, de modo que otro investigador pueda repetir la búsqueda y llegar al mismo conjunto de estudios. De esa revisión salen las **brechas** que justifican el proyecto y los referentes con los que se compara la propuesta.

Se puede apoyar en herramientas de IA para búsqueda, cribado y síntesis (Elicit, Consensus, Research Rabbit, Connected Papers, Semantic Scholar), usadas de forma **responsable y verificada**: toda fuente que proponga la IA se verifica contra la base original antes de citarse, y el uso se declara según RAISE y PRISMA-trAIce.

> [!danger] Integridad
> Una cita inexistente o no verificada se trata como falta de integridad académica.

## Qué se produce

### Correcciones de la fase anterior
Se incorporan todas las observaciones (introducción, marcos y formato). Si una no se acoge, se justifica en un comentario.

### 2.4 Antecedentes → [[Plantillas/Investigacion/F7e Antecedentes|F7e]]
Trabajos previos (proyectos de grado, informes técnicos, productos o iniciativas institucionales y artículos) que abordaron el mismo problema o uno cercano, en el contexto nacional o regional y en el internacional. Cada uno en forma narrativa: **propósito, método o solución, resultados y qué aporta o qué le falta frente al proyecto**. Mínimo 3 nacionales o regionales y 3 internacionales. Entre 2 y 3 páginas.

### 2.5 Estado del arte, en tres partes

**a) Protocolo de revisión → [[Plantillas/Investigacion/F7a Protocolo de revision|F7a]].** Pregunta de revisión derivada del PICOC; cadenas por base (IEEE Xplore, ACM Digital Library, Scopus y Semantic Scholar como mínimo; Google Scholar solo como complemento); periodo cubierto y su justificación; criterios de inclusión y exclusión (tipo de documento, idioma, periodo, pertinencia al problema y a la solución, calidad); procedimiento de cribado (quién cribó, en qué etapas, cómo se resolvieron desacuerdos). **Se escribe antes de ejecutar la búsqueda** y va como anexo; en el cuerpo se resume.

**b) Ejecución y flujo PRISMA 2020 → [[Plantillas/Investigacion/F7b Registro de busquedas|F7b]] y [[Plantillas/Investigacion/F7c Cribado y PRISMA|F7c]].** Registro de cada búsqueda (fecha, base, cadena exacta, número de resultados); diagrama PRISMA 2020 con los números de cada etapa (identificación, cribado, elegibilidad, inclusión) y las razones de exclusión en texto completo; tabla de los estudios incluidos con sus datos de extracción (autores, año, país, problema, solución, método de evaluación, resultados, relación con el proyecto). El registro de búsquedas y la tabla de extracción van como anexo.

**c) Síntesis crítica y brechas → [[Plantillas/Investigacion/F7d Sintesis y brechas|F7d]].** Estudios organizados **por temas o enfoques** (no uno por uno), con discusión de coincidencias, diferencias y limitaciones compartidas; **matriz comparativa** de las soluciones existentes frente a la propuesta, con los criterios que importan para el problema; e identificación explícita de las **brechas** que atiende el proyecto, redactadas como vacíos de conocimiento o de solución y conectadas con la pregunta y los objetivos. Entre 5 y 8 páginas sin anexos.

### Declaración de uso de IA → [[Plantillas/Investigacion/F7f Declaracion uso de IA|F7f]]
Herramientas usadas, para qué tarea, con qué consultas, qué se verificó y cómo, y qué **no** se hizo con IA. Es obligatoria aunque no se haya usado IA.

### Referencias
Lista completa en APA 7 **generada desde el gestor** (Zotero o Mendeley), con autores corporativos bien registrados. Toda fuente citada aparece en la lista y toda referencia está citada. Cada estudio incluido tiene DOI o URL verificable.

## La bitácora de revisión (cómo se lleva en Obsidian)

La bitácora reemplaza una hoja de cálculo con cinco hojas: registro de búsquedas, cribado, extracción, matriz comparativa y PRISMA. En este framework:

| Hoja de la bitácora | En Obsidian |
|---|---|
| Registro de búsquedas | Tabla en F7b (una fila por búsqueda ejecutada) |
| Cribado | Una nota por registro en `Registros/` (plantilla Registro - articulo) |
| Extracción | Propiedades de extracción de cada registro incluido → vista en F7d |
| Matriz comparativa | Tabla en F7d, con el proyecto como última fila |
| PRISMA 2020 | Vistas de F7c: el número de resultados de cada vista es el valor del diagrama |

**Valores permitidos**
- **Fuente:** `Base de datos` (resultado de una cadena registrada) u `Otros métodos` (seguimiento de citas, sugerencia de IA verificada, búsqueda manual).
- **Decisión en título y resumen y en texto completo:** `Incluir` / `Excluir`. En texto completo también `No recuperado`.
- **Razón de exclusión en texto completo:** R1 Fuera del alcance (CI1/CI2) · R2 Sin método ni resultados (CE2) · R3 Tipo de documento no admitido (CE1) · R4 Duplicado o versión anterior (CE3) · R5 Fuera del periodo o idioma (CI4/CI5) · R6 Fuente no académica o no verificable (CE5).

> [!danger] Regla de integridad
> Ningún registro pasa a `Incluir` en texto completo sin estar **verificado en la fuente original**, con fecha. Un estudio sugerido por IA que no se encuentre en la fuente original se marca `Excluir` con razón **R6** y se cuenta en la declaración de uso de IA.

**Controles de coherencia (deben dar 0)**
- Total del registro de búsquedas − registros con fuente "Base de datos".
- Cribados = identificados (bases + otros métodos) − duplicados.
- Evaluados en texto completo = buscados − no recuperados.
- Evaluados − excluidos con razón − incluidos.
- Excluidos sin razón registrada; incluidos sin verificación.

## Criterios de calidad

| Criterio | Peso | Nivel excelente |
|---|---|---|
| Correcciones de la fase anterior | 15 % | Observaciones incorporadas o justificadas en la introducción, los marcos y el formato. |
| Protocolo de revisión | 20 % | Pregunta derivada del PICOC; cadenas reproducibles por base; periodo justificado; criterios explícitos y pertinentes; cribado definido; protocolo escrito antes y anexado. |
| Ejecución, PRISMA y verificación | 15 % | Registro de búsquedas completo; diagrama con números coherentes y razones de exclusión; tabla de extracción; todas las fuentes verificables (DOI/URL) y existentes. |
| Antecedentes | 10 % | Referentes nacionales o regionales e internacionales con propósito, método, resultados y aporte o vacío; no es una lista. |
| Síntesis, matriz y brechas | 25 % | Estudios por temas con coincidencias, diferencias y limitaciones; matriz con criterios pertinentes frente a la propuesta; brechas explícitas conectadas con la pregunta y los objetivos. |
| Declaración de IA e integridad | 10 % | Declaración completa; ninguna cita inexistente o no verificable; uso de IA coherente con lo declarado. |
| Formato y referencias | 5 % | Plantilla respetada; estilos unificados; APA 7 desde el gestor; figuras y tablas numeradas, referenciadas y explicadas. |

## Recomendaciones

- **Partan del PICOC y de las fuentes de la ficha EBSE:** la pregunta de revisión es la del PICOC y las primeras cadenas ya están probadas. No empiecen de cero.
- **Escriban el protocolo y revísenlo con el asesor antes de cribar en serio:** cambiar criterios a mitad de camino obliga a repetir el cribado.
- **Usen la IA para ampliar y acelerar, no para sustituir:** Elicit y Consensus para encontrar candidatos y extraer datos; Research Rabbit y Connected Papers para seguir citas. Pero el conjunto incluido sale de las bases con la cadena registrada, y **cada referencia se abre y se lee antes de citarse**.
- **La matriz comparativa es el puente entre el estado del arte y el proyecto:** como columnas, lo que distingue la propuesta (población, contexto, técnica, forma de evaluación, variable); el proyecto en la última fila.
- **Las brechas se redactan en positivo y comprobables:** "no se encontraron estudios que evalúen X en Y con la variable Z", no "hay poca literatura".
- **Corrijan primero las referencias anteriores en el gestor:** es la misma lista que va a crecer.
- Extensión orientativa de lo nuevo: 8 a 12 páginas sin anexos ni referencias. Los anexos (protocolo, registro, extracción, declaración de IA) van dentro del mismo documento.

**Base metodológica:** Kitchenham y Charters (2007); Page et al. (2021), PRISMA 2020, *BMJ, 372*, n71; RAISE (2024); PRISMA-trAIce (2025).
