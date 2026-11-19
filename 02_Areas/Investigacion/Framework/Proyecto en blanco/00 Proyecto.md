---
tipo: proyecto-investigacion
estado: en curso
titulo_provisional: 
grupo: 
asesor: 
programa: 
inicio: 
tags:
  - investigacion
---
# Nombre corto del proyecto

> [!info] Cómo usar esta nota
> Esta es la nota central del proyecto. Las notas de cada fase (F1…F9) ya están en esta carpeta: llénalas en orden, leyendo antes su guía. Las fichas de artículos van en la subcarpeta `Registros/`, creadas con la plantilla **Registro - articulo**.
> Mapa del método: [[02_Areas/Investigacion/Framework/Framework de investigacion|Framework de investigación]] · Primeros pasos: [[02_Areas/Investigacion/Framework/00 Empieza aqui|Empieza aquí]]

## Cadena de coherencia (versión vigente)

Copia aquí la versión **actual** de cada pieza. Si cambias una, revisa las demás: tienen que derivarse unas de otras.

| Pieza | Texto vigente | Se deriva de |
|---|---|---|
| Problema central |  | Árbol de problemas (F1) |
| Pregunta de investigación |  | Problema |
| Hipótesis (variable + dirección) |  | Pregunta |
| Variable(s) medida(s) y definición operacional |  | Hipótesis (F3, F5) |
| Objetivo general |  | Problema negado + medio |
| OE1 Diagnóstico / línea base |  | Causas intervenidas |
| OE2 Diseño |  | Causas intervenidas |
| OE3 Construcción |  | Causas intervenidas |
| OE4 Evaluación contra la línea base |  | Hipótesis |
| Método (principal + validación) |  | F6 |
| Brechas que atiende |  | Estado del arte (F7) |

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

## Entregas

| Entrega | Fecha límite | Archivo entregado | Nota / calificación |
|---|---|---|---|
| Técnicas de planteamiento (F1) |  |  |  |
| Avance 1 (F2) |  |  |  |
| Ficha EBSE (F4) |  |  |  |
| Enfoques (F3) |  |  |  |
| Avance 2 (F5) |  |  |  |
| Avance 3 (F7) |  |  |  |
| Anteproyecto y sustentación (F8) |  |  |  |

## Retroalimentación pendiente

Anota cada observación de la rúbrica como tarea y márcala cuando la resuelvas. Si decides no acogerla, escribe por qué (en el informe se justifica con un comentario).

- [ ] 

## Registro de decisiones y cambios

| Fecha | Qué cambió (pregunta, hipótesis, objetivo, alcance…) | Por qué |
|---|---|---|
|  |  |  |
