# AI Skills — Fundación Invictus Chile

Repositorio de prompts estructurados (skills) para sistematizar el trabajo de gestión de proyectos, postulaciones a fondos y análisis institucional de Fundación Invictus Chile.

## ¿Qué es un skill?

Un skill es un prompt profesional con estructura fija que define:
- El **rol** que debe asumir el modelo de IA
- El **contexto organizacional** relevante
- La **tarea específica** a realizar
- El **formato de salida** esperado

## Cómo usar estos skills

1. Abre el skill relevante (archivo `.md`)
2. Copia su contenido completo como primer mensaje a Claude
3. En el mensaje siguiente, proporciona los datos o documentos del caso concreto

O bien, adjunta el skill como documento de contexto al inicio de una conversación.

## Skills disponibles

| # | Skill | Cuándo usar |
|---|-------|-------------|
| 01 | [Resumen Ejecutivo de Postulaciones](./01_resumen_postulaciones.md) | Al recibir o enviar una postulación a fondo |
| 02 | [Pipeline de Fondos](./02_pipeline_fondos.md) | Para actualizar o revisar el estado de todos los fondos |
| 03 | [Banco de Proyectos](./03_banco_proyectos.md) | Para registrar, actualizar o consultar proyectos |
| 04 | [Análisis de Elegibilidad y Fit](./04_analisis_elegibilidad.md) | Antes de decidir postular a un nuevo fondo |

## Estructura del repositorio

```
/skills
  01_resumen_postulaciones.md
  02_pipeline_fondos.md
  03_banco_proyectos.md
  04_analisis_elegibilidad.md

/proyectos          ← fichas del banco de proyectos
  EM-2025-001_taller-madera.md
  CM-2025-001_casa-maule.md
  ...

/postulaciones      ← resúmenes ejecutivos de postulaciones
  2025_CNED_vigésima.md
  2025_SENCE_becas-laborales.md
  ...

/pipeline
  pipeline_2025.md  ← tabla actualizada del pipeline de fondos
```

## Convenciones de nomenclatura

**Proyectos (banco):** `[PROG]-[AÑO]-[NRO]`
- `EM` = Espacio Mandela
- `CM` = Casa Maule
- `OT` = OTEC
- `LM` = La Última Milla
- `IN` = Investigación

**Postulaciones:** `[AÑO]_[FONDO]_[nombre-corto]`

## Mantenimiento

- Responsable: Director Ejecutivo
- Frecuencia de revisión: mensual (pipeline) / por evento (banco de proyectos)
- Los skills deben actualizarse cuando cambie la oferta programática de la fundación
