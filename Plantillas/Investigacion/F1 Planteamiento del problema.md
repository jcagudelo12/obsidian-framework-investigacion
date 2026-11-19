---
tipo: fase-investigacion
fase: F1
estado: pendiente
seccion_informe: "1.1–1.2 (insumo)"
entrega: Técnicas de planteamiento del problema
---
# F1 · Planteamiento del problema

> [!info] Objetivo de esta fase
> Pasar de una **idea** (intuición) a un **problema demostrado**: qué pasa, qué lo causa y qué consecuencias tiene, con evidencia. Se aplican tres técnicas que forman **un solo análisis** (no tres trabajos pegados).

## 1. Idea inicial

Enunciado tal como se presentó en el banco de ideas (3–4 líneas):

> 

## 2. Técnica 1 · Diagrama de Ishikawa (obligatoria)

Organiza las causas por categorías para no quedarse con la primera explicación. Cambia o elimina las categorías que no apliquen.

```mermaid
flowchart LR
    subgraph Personas
      P1[Causa]
    end
    subgraph Proceso
      PR1[Causa]
    end
    subgraph Tecnologia["Tecnología"]
      T1[Causa]
    end
    subgraph Datos["Datos / información"]
      D1[Causa]
    end
    subgraph Entorno["Entorno / normativa"]
      E1[Causa]
    end
    P1 --> EF
    PR1 --> EF
    T1 --> EF
    D1 --> EF
    E1 --> EF
    EF[["EFECTO / PROBLEMA"]]
```

| Causa | Categoría | Evidencia (cifra, fuente, observación, testimonio) | ¿Hecho o hipótesis del grupo? |
|---|---|---|---|
|  |  |  |  |

## 3. Técnica 2 · Árbol de problemas (obligatoria)

Las **raíces** son las causas, el **tronco** es el problema central y las **ramas** son los efectos. Es la base del árbol de objetivos y de la justificación.

```mermaid
flowchart BT
    C1[Causa 1] --> P
    C2[Causa 2] --> P
    C3[Causa 3] --> P
    CR1[Causa raíz de C1] --> C1
    P[["PROBLEMA CENTRAL"]] --> E1[Efecto directo 1]
    P --> E2[Efecto directo 2]
    E1 --> EI[Efecto indirecto]
```

| Elemento | Descripción | Evidencia | ¿Hecho o hipótesis? |
|---|---|---|---|
| Problema central |  |  |  |
| Causa 1 |  |  |  |
| Causa 2 |  |  |  |
| Efecto 1 |  |  |  |
| Efecto 2 |  |  |  |

## 4. Técnica 3 · Técnica de libre elección

Debe **complementar** a las anteriores, no repetirlas. Opciones: 5 porqués (profundizar una rama) · mapa de empatía o de actores · DOFA del contexto · Pareto (si hay datos) · **Es / No es** (delimitar) · Problem Statement Canvas · árbol de objetivos.

**Técnica elegida y por qué:** 

**Fuente que la describe:** 

**Aplicación al proyecto:**

## 5. Problema reformulado

| Antes (idea inicial) | Después (tras las tres técnicas) |
|---|---|
|  |  |

**Delimitación**
- **Quiénes:** 
- **Dónde:** 
- **Alcance (qué incluye):** 
- **Qué queda por fuera:** 

**Pregunta de investigación preliminar:** ¿…?

## 6. Conclusiones del grupo

- Qué aprendimos de la idea: 
- Qué cambió: 
- Dudas abiertas: 

## Evidencia recolectada

Guarda fotos del tablero, borradores y fuentes: sirven de evidencia para el informe.

- 

## Antes de entregar

- [ ] Cada técnica tiene explicación (qué es, para qué sirve, cómo se construye, **cuándo conviene y sus limitaciones**).
- [ ] Cada técnica está aplicada de forma específica al proyecto, no genérica.
- [ ] Las causas y los efectos tienen evidencia, y lo que es hipótesis está marcado como tal.
- [ ] Las tres técnicas forman un solo análisis y no se contradicen.
- [ ] El problema reformulado mejora claramente el inicial y está delimitado (quiénes, dónde, alcance).
- [ ] La pregunta preliminar se deriva del análisis y es viable.
- [ ] Diapositivas: un diagrama por diapositiva, legible y con poco texto. Ensayado con cronómetro.
