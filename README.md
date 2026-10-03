# Agencia de IA y Automatización

Plan de estudio de 12 semanas para vender servicios de automatización con IA, con la certificación y el código como consecuencia — no como el objetivo.

**En construcción.** El historial de commits es el registro real de avance.

---

## Qué es esto

Soy técnico en diseño gráfico y quiero vivir de vender automatizaciones con IA. Este repo es:

1. El plan de estudio de 12 semanas con entregables concretos.
2. El registro diario de trabajo.
3. El portafolio: los flujos y scripts que construyo, documentados.

## Objetivo, en este orden

1. **Facturar.** Clientes reales pagando antes de la semana 6.
2. **Cambiar de carrera a programación.** En segundo plano, con el código que ya escribo por los clientes.

Mi ventaja: la mayoría de gente que vende automatizaciones con IA sabe programar y **no sabe diseñar**. Yo entrego automatizaciones que además producen piezas visuales terminadas.

## Estado actual

**Semana 1 — en curso, ~70%**

- [x] Fundamentos por práctica (Make), sin curso
- [x] Webhook, Router, Filter, JSON, triggers vs actions
- [x] Entregable: Webhook → Filter → Router → Sheets + Telegram + Gmail
- [ ] Validación de email, duplicados, ejecuciones fallidas
- [x] Git: repo público en `carloslatta/agencia-ia-automatizacion`, primer commit, sin secretos
- [ ] n8n Academy `QS101` → certificado
- [ ] **Definir nicho** ← bloqueante

Ver `TODO.md` para el detalle completo.

## Estructura

```
PLAN.md                     Hoja de ruta de 12 semanas. Explica el porqué
TODO.md                     Tareas. Fuente de verdad del estado
AGENTS.md                   Reglas del asistente: cómo me evalúa y qué espera de mí
bitacora/                   Registro diario (uno por fecha)
entregables/semana-NN-*/    Artefactos de cada semana, con su documentación
docs/
  rubrica-evaluacion.md     Criterios del checkpoint semanal
  certificaciones.md        Solo certificaciones que aportan señal
  ofertas-comerciales.md    Precios y propuestas
assets/                     Capturas para el portafolio
apuntes/                    Notas de curso
```

## Reglas de este repo

- **Este repo es público.** Nunca se commitean secretos. `.gitignore` cubre `.env`, claves, exportaciones de n8n/Make y datos reales de clientes. Si ves una clave expuesta, dilo de inmediato.
- Cada entregable semanal vive en su carpeta con su documentación.
- Cada día de estudio deja registro en `bitacora/`.
- Las certificaciones van en el plan solo si pasan el filtro de `docs/certificaciones.md`.

## Cómo trabajamos

Yo entrego un artefacto al final de la semana. Big Pickle lo evalúa con la rúbrica de `docs/rubrica-evaluacion.md` — Eficiencia, Manejo de errores, Estructura lógica.

- **≥ 7** pasa la semana. **≥ 8** es el objetivo del mes.
- Las observaciones llegan como preguntas socráticas, no como la respuesta.
- Las notas nunca se inflan.

## Lo descartado, y por qué

- **Certified Full-Stack Developer de freeCodeCamp.** ~1.800 horas de React y MongoDB. Cero relación con n8n, APIs, webhooks o LLMs. Es la ruta equivocada para este objetivo.
- **Empezar por Upwork.** Es el canal más lento para una cuenta sin reseñas. El outreach directo a Pymes va primero.
