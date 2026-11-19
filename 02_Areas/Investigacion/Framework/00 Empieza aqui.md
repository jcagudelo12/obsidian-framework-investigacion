---
tipo: framework-investigacion
tags:
  - investigacion
---
# Empieza aquí

Este framework te guía para llevar un **trabajo de grado o proyecto de investigación aplicada en ingeniería de software** desde la idea hasta el informe final, paso a paso y con plantillas listas en Obsidian.

Integra cuatro prácticas reconocidas:
- **Análisis del problema:** Ishikawa y árbol de problemas.
- **Ingeniería de software basada en evidencia (EBSE):** con la estructura PICOC.
- **Revisión sistemática de literatura:** reportada con PRISMA 2020.
- **Design science:** como método principal, con validación empírica.

> [!tip] Si solo tienes 5 minutos
> 1. Lee el flujo en [[02_Areas/Investigacion/Framework/Framework de investigacion|Framework de investigación]].
> 2. Abre el [[02_Areas/Investigacion/Framework/Ejemplo-Reservas/00 Proyecto|proyecto de ejemplo]] para ver cómo se ve un proyecto en marcha.
> 3. Copia la carpeta `Proyecto en blanco` (paso 3 de abajo) y empieza tu F1.

## 1. Requisitos de Obsidian

| Qué | Dónde se configura | Por qué |
|---|---|---|
| Obsidian **1.9 o superior** | Ajustes → General | Las tablas automáticas usan **Bases**, que llegó en la 1.9 |
| Complementos principales **Bases**, **Plantillas** y **Propiedades** activados | Ajustes → Complementos principales | Tablas automáticas, insertar plantillas y propiedades de las notas |
| Carpeta de plantillas = `Plantillas` | Ajustes → Plantillas → Ubicación de la carpeta de plantillas | Para que *Insertar plantilla* encuentre las de `Plantillas/Investigacion` |
| **Detectar todas las extensiones de archivo** activado | Ajustes → Archivos y enlaces | Para ver los `.docx` y `.xlsx` de `Adjuntos` en el explorador |

> [!note] Si abriste la bóveda compartida (o el repositorio)
> Ya trae esta configuración hecha. Si Obsidian pregunta si confías en el autor de la bóveda, la bóveda no trae complementos de terceros, solo los que vienen incluidos.

## 2. Qué hay en cada carpeta

| Ruta | Contenido |
|---|---|
| `02_Areas/Investigacion/Framework/Framework de investigacion` | **Mapa del método:** fases, guías, plantillas y reglas |
| `Framework/Guias/` | **G1–G9:** una guía por fase, con qué se pide, criterios de calidad y recomendaciones |
| `Framework/Proyecto en blanco/` | Un proyecto con todas las notas ya creadas, **para copiar** |
| `Framework/Ejemplo-Reservas/` | Un proyecto **ficticio** ya avanzado, para ver cómo se llena cada fase |
| `Framework/Adjuntos/` | Formatos en Word y Excel (protocolo, bitácora, PRISMA, declaración de IA) |
| `Framework/Vistas/` | Panel con todos tus proyectos y el estado de cada fase |
| `Plantillas/Investigacion/` | Las plantillas sueltas, por si quieres crear notas una a una |
| `01_Proyectos/` | Aquí van **tus** proyectos |

## 3. Arrancar un proyecto (10 minutos)

1. **Copia la carpeta** `02_Areas/Investigacion/Framework/Proyecto en blanco` dentro de `01_Proyectos/`. Obsidian no duplica carpetas, así que hazlo desde el explorador de archivos de tu sistema (copiar y pegar) y vuelve a Obsidian.
2. **Renómbrala** con un nombre corto: `01_Proyectos/Inv-NombreCorto`.
3. Abre `00 Proyecto` y llena las propiedades de arriba (`titulo_provisional`, `grupo`, `asesor`, `programa`, `inicio`).
4. Abre la guía [[02_Areas/Investigacion/Framework/Guias/G1 Tecnicas de planteamiento del problema|G1]] y luego la nota `F1 Planteamiento del problema` de tu carpeta. Empieza por la idea inicial.
5. Cada vez que termines una fase, cambia su propiedad `estado`. La tabla **Avance por fase** de `00 Proyecto` se actualiza sola.

> [!warning] No cambies los nombres de las notas ni las saques de la carpeta
> Las tablas automáticas buscan las notas **dentro de la carpeta del proyecto** por su propiedad `tipo`. Si mueves una nota fuera, desaparece de las tablas.

## 4. Cómo se trabaja cada fase

1. **Lee la guía** (G1…G9) antes de empezar: dice qué se pide y cómo se evalúa.
2. **Llena la nota de la fase** en tu carpeta. Cada una trae instrucciones en recuadros y espacios para completar.
3. **Repasa el checklist "Antes de entregar"** al final de la nota.
4. **Actualiza la Cadena de coherencia** en `00 Proyecto` si cambió el problema, la pregunta, la hipótesis o los objetivos.

## 5. Para seguir leyendo

- [[02_Areas/Investigacion/Framework/Glosario|Glosario]]: EBSE, PICOC, PRISMA, CI/CE, R1–R6, línea base…
- [[02_Areas/Investigacion/Framework/Cronograma orientativo|Cronograma orientativo]]: cuánto toma cada fase.
- [[02_Areas/Investigacion/Framework/Como adaptarlo|Cómo adaptarlo]]: a tu programa, a trabajo individual o a otra disciplina.
- [[02_Areas/Investigacion/Framework/Creditos y licencia|Créditos y licencia]].
