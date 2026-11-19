---
tipo: fase-investigacion
fase: F7d
estado: pendiente
seccion_informe: "2.5.c + Anexo (extracción)"
entrega: Avance 3
---
# F7d · Extracción, síntesis crítica y brechas

> [!info] De la lista de estudios al argumento
> El estado del arte **no es una lista de trabajos relacionados**. Organiza los estudios por temas o enfoques, discute en qué coinciden, en qué difieren y qué limitaciones comparten, y termina en las **brechas** que justifican el proyecto.
> Para un proyecto de design science se buscan tres cosas: qué artefactos se han propuesto, cómo se evaluaron y qué resultados obtuvieron.

## Tabla de extracción (anexo)

Se llena sola con las propiedades de los registros incluidos.

```base
filters:
  and:
    - tipo == "registro-revision"
    - file.inFolder(this.file.folder)
    - decision_tc == "Incluir"
views:
  - type: table
    name: Extracción
    order:
      - file.name
      - autores
      - anio
      - pais
      - tipo_publicacion
      - problema
      - poblacion
      - solucion
      - metodo_evaluacion
      - variables
      - resultados
      - limitaciones
      - relacion_proyecto
      - doi
  - type: table
    name: Por tema
    groupBy:
      property: tema
      direction: ASC
    order:
      - file.name
      - anio
      - pais
      - solucion
      - metodo_evaluacion
      - resultados
  - type: table
    name: Distribución por año y país
    groupBy:
      property: anio
      direction: ASC
    order:
      - file.name
      - pais
      - tipo_publicacion
```

## 2.5.c Síntesis crítica

### Estudios agrupados por tema o enfoque

Asigna a cada registro incluido la propiedad `tema` y usa la vista **Por tema**.

#### Tema 1: 
- Estudios: 
- Qué proponen: 
- Cómo evalúan: 
- Qué encuentran: 

#### Tema 2: 

### Distribución temporal y geográfica

### Coincidencias, diferencias y limitaciones compartidas

## Matriz comparativa

Elige como columnas **lo que distingue a tu propuesta** (población, contexto, técnica, forma de evaluación, variable, disponibilidad). Tu proyecto va en la **última fila**.

| Solución / estudio (ID) | Población o contexto | Técnica o arquitectura | Forma de evaluación | Variable medida y resultado | Disponibilidad / madurez | Criterio propio | Diferencia principal con la propuesta |
|---|---|---|---|---|---|---|---|
|  |  |  |  |  |  |  |  |
| **NUESTRA PROPUESTA** |  |  |  |  |  |  | — |

## Brechas identificadas

> [!tip] Redáctalas en positivo y comprobables
> ✅ "No se encontraron estudios que evalúen **X** en **Y** con la variable **Z**."
> ❌ "Hay poca literatura sobre el tema."

| # | Brecha | Evidencia en la matriz | Objetivo(s) que la atiende(n) |
|---|---|---|---|
| B1 |  |  |  |
| B2 |  |  |  |

## Limitaciones de la revisión

Cobertura de bases, idioma, periodo, textos no recuperados, cribado no independiente, sesgos posibles:

- 

## Antes de entregar

- [ ] Estudios organizados por temas, no uno por uno.
- [ ] Discusión de coincidencias, diferencias y limitaciones.
- [ ] Matriz comparativa completa, con criterios pertinentes y el proyecto como última fila.
- [ ] Brechas explícitas y comprobables, conectadas con la pregunta y los objetivos.
- [ ] Limitaciones de la revisión declaradas.
- [ ] Tabla de extracción en el anexo.
- [ ] Entre 5 y 8 páginas en total (sin anexos).
