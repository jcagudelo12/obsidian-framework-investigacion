---
tipo: fase-investigacion
fase: F4
estado: entregado
seccion_informe: "Insumo de 2.5 (estado del arte)"
entrega: Taller EBSE
---
# F4 · Ficha EBSE (ejemplo ficticio)

> [!example] El artículo de esta ficha es **inventado**. En tu proyecto, el artículo debe existir y tener DOI o enlace verificable.

## Paso 1 · PICOC

| Componente | Mi proyecto |
|---|---|
| **P** Población | Estudiantes que usan salas de estudio de una biblioteca universitaria |
| **I** Intervención | Sistema de reservas con disponibilidad en tiempo real y liberación automática de reservas no usadas |
| **C** Comparación | Reserva por formulario con confirmación manual |
| **O** Resultado | Tiempo para conseguir sala · tasa de reservas no usadas |
| **C** Contexto | Biblioteca universitaria en hora pico |

**Pregunta de evidencia:** ¿Qué evidencia existe de que los sistemas de reserva con disponibilidad en tiempo real y liberación automática reducen el tiempo de búsqueda y las reservas no usadas en espacios de estudio universitarios, frente a la reserva manual?

## Paso 2 · Búsqueda

**Cadena (inglés):**
```
("study room" OR "library space" OR "group study room")
AND ("booking system" OR "reservation system")
AND ("no-show" OR "utilization" OR "waiting time")
```

| Dónde se ejecutó | Fecha | Resultados aprox. | Ajustes |
|---|---|---|---|
| Google Scholar | 2026-03-05 | ~1.200 | Se añadió `"no-show"` como bloque obligatorio |
| Google Scholar | 2026-03-05 | ~140 | Filtro 2018–2026 |

### Artículo seleccionado

Ficha completa en [[02_Areas/Investigacion/Framework/Ejemplo-Reservas/Registros/S001 Autora 2023|S001]] *(ficticio)*.

## Paso 3 · Valoración crítica

1. **Tipo:** cuasiexperimento pre-post en una sola biblioteca.
2. **Con quién y dónde:** 20 salas, un semestre, ~3.000 reservas.
3. **Qué encontró:** la liberación automática a los 15 minutos bajó las reservas no usadas del 31 % al 12 %; no midió el tiempo de búsqueda.
4. **Parecido con mi caso:** muy parecido en contexto e intervención; difiere en que allí la confirmación ya era automática.
5. **Confiabilidad:** media. Revista con revisión por pares, pero un solo sitio y sin grupo de control.

## Paso 4 · Integración

- [ ] Confirma la hipótesis
- [x] **La matiza**
- [ ] La contradice
- [ ] El problema ya está resuelto

La liberación automática reduce las reservas no usadas, pero **nadie midió el tiempo para conseguir sala**. Por eso se añadió Rnu a la hipótesis y Tsala se mantiene como la variable principal: ahí está el aporte.
