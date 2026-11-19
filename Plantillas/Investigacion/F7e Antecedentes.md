---
tipo: fase-investigacion
fase: F7e
estado: pendiente
seccion_informe: "2.4"
entrega: Avance 3
---
# F7e · Antecedentes

> [!info] Qué son
> Trabajos previos (proyectos de grado, informes técnicos, productos o iniciativas institucionales y artículos) que abordaron el mismo problema o uno cercano. Mínimo **3 nacionales o regionales** y **3 internacionales**, en forma narrativa. Entre 2 y 3 páginas.
> Pueden salir de una búsqueda complementaria fuera del flujo PRISMA: regístrala en F7b y declara si usaste IA (F7f).

Marca cada registro con `antecedente: nacional` o `antecedente: internacional`:

```base
filters:
  and:
    - tipo == "registro-revision"
    - file.inFolder(this.file.folder)
    - or:
        - antecedente == "nacional"
        - antecedente == "internacional"
views:
  - type: table
    name: Antecedentes
    groupBy:
      property: antecedente
      direction: ASC
    order:
      - file.name
      - autores
      - anio
      - titulo
      - pais
      - verificado
```

## 2.4.1 Antecedentes nacionales o regionales

### 1. Título (institución, año)

- **Propósito:** 
- **Método o solución:** 
- **Resultados:** 
- **Qué aporta o qué le falta frente a nuestro proyecto:** 

### 2. 

### 3. 

### Síntesis de los antecedentes nacionales

## 2.4.2 Antecedentes internacionales

### 1. Título (autores, año)

- **Propósito:** 
- **Método o solución:** 
- **Resultados:** 
- **Qué aporta o qué le falta frente a nuestro proyecto:** 

### 2. 

### 3. 

### Síntesis de los antecedentes internacionales

## Antes de entregar

- [ ] Al menos 3 nacionales o regionales y 3 internacionales.
- [ ] Cada uno con propósito, método, resultados y aporte o vacío frente al proyecto.
- [ ] Redacción narrativa (no una lista).
- [ ] Todos verificados en la fuente original, con DOI o URL.
