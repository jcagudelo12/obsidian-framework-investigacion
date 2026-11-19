---
tipo: fase-investigacion
fase: F7a
estado: pendiente
seccion_informe: "2.5.a + Anexo (protocolo)"
entrega: Avance 3
version_protocolo: 1
fecha_protocolo: 
---
# F7a · Protocolo de revisión de literatura

> [!info] Formato en Word o Excel: [[02_Areas/Investigacion/Framework/Adjuntos/Protocolo de revision.docx|Protocolo de revisión (.docx)]], para anexarlo al informe.

> [!warning] El protocolo se escribe **antes** de ejecutar las búsquedas
> Revísalo con el docente antes de cribar en serio: cambiar criterios a mitad de camino obliga a repetir el cribado. Todo cambio posterior se registra en la sección 10.
> Basado en Kitchenham y Charters (2007) y PRISMA 2020 (Page et al., 2021).

## 1. Pregunta de revisión (desde el PICOC de F4)

| Elemento | Contenido |
|---|---|
| Población / contexto (P) |  |
| Intervención o solución (I) |  |
| Comparación (C) |  |
| Resultados o variables (O) |  |
| Contexto de aplicación (C) |  |

**Pregunta de revisión principal:** ¿…?

**Preguntas secundarias:** (qué técnicas se han usado, cómo se han evaluado, en qué contextos, con qué resultados)
- RQ1: 
- RQ2: 

## 2. Fuentes de búsqueda

| Base de datos | Campos (título, resumen, palabras clave) | Acceso (biblioteca institucional / abierto) |
|---|---|---|
| IEEE Xplore |  |  |
| ACM Digital Library |  |  |
| Scopus |  |  |
| Semantic Scholar |  |  |
| Otras (SpringerLink, ScienceDirect, repositorios de tesis; Google Scholar solo como complemento) |  |  |

## 3. Cadenas de búsqueda

| Concepto del PICOC | Términos y sinónimos (OR) |
|---|---|
| P |  |
| I |  |
| O |  |

**Cadena genérica:** `(P1 OR P2 OR …) AND (I1 OR I2 OR …) AND (O1 OR O2 OR …)`

La sintaxis cambia según la base: registra la cadena **exacta** de cada una.

| Base | Cadena exacta | Filtros (años, tipo de documento, idioma) |
|---|---|---|
| IEEE Xplore |  |  |
| ACM DL |  |  |
| Scopus |  |  |
| Semantic Scholar |  |  |

## 4. Periodo cubierto

Años: ____ a ____. Razón (aparición de la técnica, cambio normativo, madurez del campo…): 

## 5. Criterios de inclusión

- **CI1.** El estudio aborda [problema] en [población/contexto] o uno equivalente.
- **CI2.** El estudio propone, implementa o evalúa [tipo de solución].
- **CI3.** Artículo de revista, conferencia o capítulo revisado por pares; tesis de posgrado e informes técnicos solo para antecedentes nacionales.
- **CI4.** Publicado entre ____ y ____.
- **CI5.** En inglés o español.
- **CI6.** Texto completo accesible.

## 6. Criterios de exclusión

- **CE1.** Solo resumen, póster, editorial o artículo de opinión.
- **CE2.** No reporta método ni resultados de evaluación.
- **CE3.** Duplicado o versión anterior de un estudio ya incluido.
- **CE4.** Fuera del alcance definido en CI1 y CI2 (indicar la razón concreta).
- **CE5.** Fuente no académica (blog, página comercial) usada como evidencia.

### Razones de exclusión en texto completo (para el diagrama PRISMA)

| Código | Razón | Criterio |
|---|---|---|
| R1 | Fuera del alcance | CI1 / CI2 |
| R2 | Sin método ni resultados | CE2 |
| R3 | Tipo de documento no admitido | CE1 |
| R4 | Duplicado o versión anterior | CE3 |
| R5 | Fuera del periodo o del idioma | CI4 / CI5 |
| R6 | Fuente no académica o no verificable | CE5 |

## 7. Procedimiento de selección (cribado)

| Etapa | Quién la hace | Cómo se decide | Registro |
|---|---|---|---|
| Identificación |  | Exportar los resultados de cada base con fecha y número | F7b Registro de búsquedas |
| Eliminación de duplicados |  | Por DOI o título normalizado (en el gestor) | Propiedad `duplicado` |
| Cribado por título y resumen | Dos integrantes de forma independiente | Aplicar CI/CE; los desacuerdos los resuelve un tercero | `decision_tr_r1`, `decision_tr_r2`, `decision_tr` |
| Elegibilidad por texto completo |  | Aplicar CI/CE y registrar la razón de exclusión | `decision_tc`, `razon_exclusion` |
| Inclusión |  | Estudios finales | Extracción (F7d) |

## 8. Datos que se extraen de cada estudio incluido

Autores y año · País · Tipo de publicación · Problema abordado · Población o contexto · Solución o técnica · Método de evaluación y variables medidas · Resultados principales · Limitaciones declaradas · Relación con el proyecto · DOI/URL verificado (sí/no, fecha).

Todos van como propiedades en la plantilla **Registro - articulo**.

## 9. Uso de herramientas de IA en la revisión

| Herramienta | Tarea (búsqueda, cribado, extracción, síntesis) | Cómo se verifica su salida |
|---|---|---|
|  |  |  |

> [!danger] Regla
> Ningún estudio entra al conjunto incluido **solo** porque lo propuso una herramienta de IA. Debe recuperarse en una base con la cadena registrada o, si entra por seguimiento de citas, registrarse como **"Otros métodos"**, con la fuente verificada.

## 10. Control de cambios del protocolo

| Fecha | Cambio | Razón |
|---|---|---|
|  |  |  |

## Antes de entregar

- [ ] Pregunta de revisión derivada del PICOC de la ficha EBSE (F4).
- [ ] Cadenas de búsqueda exactas y reproducibles para cada base (al menos 4 bases académicas; Google Scholar solo como complemento).
- [ ] Periodo cubierto, con su justificación.
- [ ] Criterios de inclusión y exclusión explícitos y pertinentes.
- [ ] Procedimiento de cribado definido, con regla para resolver desacuerdos.
- [ ] Protocolo escrito **antes** de la búsqueda y anexado al informe; los cambios posteriores están registrados en la sección 10.
