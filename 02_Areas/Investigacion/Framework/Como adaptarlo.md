---
tipo: framework-investigacion
tags:
  - investigacion
---
# Cómo adaptarlo

El framework nació de un programa de posgrado en ingeniería de software con trabajo en grupo y entregas por avances. Esto es lo que conviene ajustar a tu contexto.

## Rúbricas y pesos

Los **criterios de calidad** de cada guía, con su peso y su nivel "excelente", son una **referencia**. Si tu programa tiene su propia rúbrica:
- reemplaza la tabla de criterios de la guía con la tuya;
- revisa el checklist **"Antes de entregar"** de la plantilla correspondiente para que pida lo mismo.

Las reglas de integridad sí son universales: una cita inexistente o que no se pueda verificar invalida la entrega.

## Trabajo individual

Las plantillas asumen un **equipo** (propiedad `grupo`, "integrantes", una técnica por estudiante en F1 y F3). Si trabajas solo:
- **F1 y F3:** aplica tú las técnicas y los enfoques; la parte de "responsable" no aplica.
- **F7a (protocolo):** el cribado por **dos revisores independientes** es la recomendación de Kitchenham y Charters. Solo, puedes pedirle a tu asesor o a un colega que revise una muestra (por ejemplo, el 20 %) y reportar el acuerdo. Declara la desviación en el protocolo.
- **Registros:** deja vacías `decision_tr_r2` y `desacuerdo_resuelto_por`.

## Entregas y secciones del informe

- **Los nombres de las entregas** (Avance 1, Avance 2…) y la numeración del informe (1.1–1.6, 2.1–2.5, 3.1–3.3) siguen una estructura común de informe de trabajo de grado ([[02_Areas/Investigacion/Framework/Guias/G9 Estructura del informe final|G9]]). Si tu institución usa otra plantilla, cambia la propiedad `seccion_informe` de cada fase y la tabla *Entregas* de `00 Proyecto`.
- **Los nombres de archivo** sugeridos (`NombreCorto_Avance1.docx`) son solo una convención.

## Marco legal

La lista de normas de [[02_Areas/Investigacion/Framework/Guias/G5 Marco teorico conceptual y legal|G5]] y de la plantilla F5 es de **Colombia**. En otro país, reemplázala por las normas equivalentes de:
- protección de datos personales;
- delitos informáticos;
- firma electrónica;
- protección del consumidor;
- lineamientos de IA.

## Otras disciplinas

Las fases F1, F2, F4 y F7 sirven para casi cualquier investigación aplicada. Lo específico de software está en:
- **F6:** *design science* con validación experimental.
- **G7:** las bases de datos (IEEE Xplore, ACM DL), que en otra disciplina se cambian por las de tu área (PubMed, ERIC, EconLit…).
- **F8:** la metodología de desarrollo del producto.

## Si cambias la estructura de carpetas

Los enlaces del framework usan rutas completas (`02_Areas/Investigacion/...`, `Plantillas/Investigacion/...`). Si mueves las carpetas **desde Obsidian**, los enlaces se actualizan solos (Ajustes → Archivos y enlaces → *Actualizar enlaces internos automáticamente*). Si las mueves desde fuera de Obsidian, los enlaces se rompen.
