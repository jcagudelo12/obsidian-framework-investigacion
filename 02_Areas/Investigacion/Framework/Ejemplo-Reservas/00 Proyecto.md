---
tipo: proyecto-investigacion
estado: ejemplo
titulo_provisional: Asistente de reservas de salas de estudio con disponibilidad en tiempo real y liberación automática
grupo: Equipo de ejemplo
asesor: 
programa: Posgrado en ingeniería de software (ficticio)
inicio: 2026-02-02
tags:
  - investigacion
  - ejemplo
---
# Ejemplo · Reservas de salas de estudio

> [!example] Proyecto ficticio
> Todo en esta carpeta es **inventado** para mostrar cómo se llena el framework: la universidad, las cifras, los autores y los artículos. **No cites nada de aquí.**
> Están desarrolladas **F1, F2, F4 y F7c** con 6 registros de muestra, para que veas las tablas automáticas con datos. Las demás fases de un proyecto real se llenan igual, con sus plantillas.

## Cadena de coherencia (versión vigente)

| Pieza | Texto vigente | Se deriva de |
|---|---|---|
| Problema central | En la biblioteca central de la Universidad Modelo (ficticia, ~12.000 estudiantes), los estudiantes tardan en promedio 18 minutos en conseguir una sala de estudio en hora pico, mientras el 27 % de las reservas confirmadas no se usa. | Árbol de problemas (F1) |
| Pregunta de investigación | ¿En qué medida un asistente de reservas con disponibilidad en tiempo real y liberación automática de reservas no usadas reduce el tiempo para conseguir sala y la proporción de reservas no usadas, frente al proceso actual por formulario y confirmación manual? | Problema |
| Hipótesis (variable + dirección) | El asistente reduce en al menos 30 % el tiempo para conseguir sala (Tsala) y reduce la tasa de reservas no usadas (Rnu) frente a la línea base. | Pregunta |
| Variable(s) medida(s) y definición operacional | **Tsala:** minutos desde que el estudiante empieza a buscar sala hasta que la ocupa (registro del sistema y observación). **Rnu:** reservas confirmadas sin registro de ingreso en los primeros 15 minutos ÷ reservas confirmadas. | Hipótesis (F3, F5) |
| Objetivo general | Reducir el tiempo para conseguir sala de estudio y las reservas no usadas en la biblioteca central mediante un asistente de reservas con disponibilidad en tiempo real y liberación automática. | Problema negado + medio |
| OE1 Diagnóstico / línea base | Medir Tsala y Rnu del proceso actual durante dos semanas de hora pico. | Causas intervenidas |
| OE2 Diseño | Diseñar las reglas de disponibilidad, confirmación de llegada y liberación automática. | Causas intervenidas |
| OE3 Construcción | Construir el asistente web integrado al registro de ingreso de las salas. | Causas intervenidas |
| OE4 Evaluación contra la línea base | Comparar Tsala y Rnu con la línea base en un piloto de dos semanas. | Hipótesis |
| Método (principal + validación) | Design science con validación cuasiexperimental pre-post en la misma biblioteca. | F6 |
| Brechas que atiende | (Se completan en F7d.) | Estado del arte (F7) |

## Avance por fase

```base
filters:
  and:
    - tipo == "fase-investigacion"
    - file.inFolder(this.file.folder)
views:
  - type: table
    name: Fases
    order:
      - file.name
      - fase
      - estado
      - seccion_informe
      - entrega
    sort:
      - property: fase
        direction: ASC
```

## Retroalimentación pendiente

- [x] Separar el problema de la solución: el primer enunciado decía "no existe un sistema de reservas en línea". *(Resuelto en F2.)*
- [x] Dar fuente a la cifra de reservas no usadas. *(Se tomó del registro de ingreso de un mes; ver F1.)*
- [ ] Definir cómo se medirá Tsala cuando el estudiante desiste sin conseguir sala.

## Registro de decisiones y cambios

| Fecha | Qué cambió | Por qué |
|---|---|---|
| 2026-02-20 | El problema pasó de "falta de un sistema de reservas" a "tiempo para conseguir sala y reservas no usadas" | Retroalimentación de F1: el enunciado contenía la solución |
| 2026-03-12 | Se añadió la variable Rnu a la hipótesis | La ficha EBSE (F4) mostró que la liberación automática es lo que más reduce el desperdicio |
