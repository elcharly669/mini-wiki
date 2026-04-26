# Mini Wiki — Infraestructura de Pensamiento Versionado

> "Escribe con sangre: y aprenderás que la sangre es espíritu."  
> — Nietzsche, *Así habló Zaratustra*

---

## ¿Qué es esto?

**Mini Wiki** no es un blog, un curso, ni un repositorio de notas.

Es una capa intermedia entre:

```
IA ↔ humano ↔ comunidad
```

Un toolkit metodológico mínimo-viable para evaluar, formular y refinar ideas sin requerir formación filosófica extensa.

En la era LLM, el problema no será generar ideas.  
Será estructurarlas, versionarlas, validarlas y mantener trazabilidad.

---

## El Problema

El costo de entrada al pensamiento riguroso es demasiado alto.

Para evaluar correctamente una afirmación hoy se requiere conocimiento disperso en múltiples tradiciones, lenguajes técnicos, años de formación formal, y navegación entre marcos incompatibles.

Resultado: dependencia intelectual o superficialidad.

---

## La Hipótesis Central

> Es posible diseñar un conjunto mínimo de herramientas metodológicas que permitan a cualquier persona mejorar sustancialmente su capacidad de evaluar, formular y refinar ideas — sin formación filosófica extensa.

---

## Arquitectura del Proyecto

### Fase I — Compresión Metodológica

Construcción de un vault tipo Zettelkasten con entradas **accesibles, aplicables, concisas y modulares**.  
Cada entrada: leíble en < 5 minutos, con al menos una herramienta de uso inmediato.

### Fase II — Protocolo Dialéctico Operativo

Sistema de estados para ideas:

| Estado | Descripción |
|---|---|
| `Inicial` | Hipótesis sin someter a crítica |
| `Bajo objeción` | Con objeciones registradas activas |
| `Refinada` | Ajustada tras objeción |
| `Estabilizada` | Resistente a objeciones conocidas |
| `Refutada` | Falsificada con trazabilidad |
| `Aporía` | Límite irresoluble registrado explícitamente |

### Fase III — Infraestructura Pública

Wiki navegable con capas de profundidad:

- **Fast** — uso inmediato
- **Guide** — explicación operativa
- **Theory** — fundamento conceptual
- **Debate** — objeciones abiertas

---

## Principios Rectores

1. Compresión antes que exhaustividad
2. Operatividad antes que historia
3. Claridad antes que erudición
4. Neutralidad metodológica (sin afiliación a escuela)
5. Registro explícito de aporías
6. Modularidad

---

## Modelo de Jardinería

Este proyecto no está diseñado como una enciclopedia cerrada ni como un movimiento cultural.

```
Arquitecto → diseña sistema cerrado
Ingeniero  → optimiza estructura fija
Jardinero  → crea condiciones para crecimiento
```

Es ecosistema: curaduría constante, poda, injertos, registro de ideas.

---

## Qué no es este proyecto

| Plataforma | Optimiza para |
|---|---|
| LessWrong | Movimiento cultural racionalista |
| Stack Exchange | Resolución de preguntas concretas |
| GitHub | Versionado de código formal |
| **Mini Wiki** | **Evolución estructurada de ideas** |

---

## Stack

Construido sobre [Quartz v4](https://quartz.jzhao.xyz/) — publicación de digital gardens como sitio web estático.  
Notas en Markdown, compatible con Obsidian, desplegable en GitHub Pages.

```bash
npx quartz build --serve   # desarrollo local
npx quartz sync            # sincronizar y publicar
```

---

## Métricas de Éxito

El proyecto funciona si una persona puede leer una noticia, escuchar una conferencia o formular una hipótesis propia — y aplicar una estructura mínima de evaluación en **menos de 10 minutos**.

---

## Estado Actual

🌱 `Fase I en construcción` — Primeras entradas en desarrollo.

---

*Este proyecto no busca reemplazar la filosofía. Busca reducir la fricción para pensar con rigor.*
