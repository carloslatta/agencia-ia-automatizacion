# Plan de Estudio — Agencia de IA y Automatización (12 semanas)

## Objetivo doble, con prioridad explícita

1. **Facturar.** Antes de la semana 6 quiero clientes reales pagando. Este es el objetivo #1.
2. **Cambiar de carrera a programación.** Se sirve en segundo plano, con el código que ya voy a escribir por los clientes.

El error que este plan corrige: el plan original tenía la monetización en el **Mes 3**, con el primer cliente en el día ~71-84. Eso son 2.5 meses sin facturar, contra un objetivo #1 que es facturar.

---

## Principio rector

Soy técnico en diseño gráfico. Casi todo el que vende automatizaciones con IA sabe programar y **no sabe diseñar**. Mi positioning no es "soy dev junior": es **"soy el que entrega automatizaciones que además producen piezas visuales terminadas"**.

Cada entregable de este plan pasa por esta pregunta: *¿puedo añadir una capa visual que lo haga el doble de vendible?*

Si la respuesta es sí y no lo estoy haciendo, es una prioridad equivocada.

---

## Estructura diaria

No importa a qué hora despiertes. Respeta el **orden** y la **duración**.
Micro-bloques de 45 min de trabajo por 15 min de descanso.

| Bloque | Horario | Contenido |
|---|---|---|
| 1 | 01:00 – 01:45 | Teoría: concepto nuevo |
| — | 01:45 – 02:00 | Descanso. Sin pantallas. |
| 2 | 02:00 – 02:45 | Práctica en pantalla: construir |
| — | 02:45 – 03:00 | Descanso |
| 3 | 03:00 – 03:45 | Depurar errores + tomar notas |
| — | 03:45 – 06:00 | Tiempo libre. Sin culpa |
| 4 | 08:00 – 08:45 | Proyecto real / bot del cliente |
| — | 08:45 – 09:00 | Descanso |
| 5 | 09:00 – 09:45 | Documentar + **1 acción de venta** |
| — | 09:45 – 10:00 | Cierre y registro |

**Cambio respecto al plan original:** el Bloque 5 era "documentación e interacción con Big Pickle" — pasivo. Ahora incluye **una acción de venta concreta** (mandar un mensaje, publicar un servicio, escribir una propuesta). Vender es una habilidad que se entrena con práctica, no leyendo sobre ello.

---

## Certificaciones (integradas en el plan)

Certificaciones gratuitas con badge verificable, elegidas porque **aportan señal real** y cuestan poco tiempo. Detalle en `docs/certificaciones.md`.

| Cuándo | Certificación | Tiempo |
|---|---|---|
| Sem 1 | n8n Academy `QS101 Quickstart` | 3-5 h |
| Sem 2 | n8n Academy `n8n101 Essentials` | 3-4 h |
| Sem 5 | Hugging Face MCP Course | ~8 h |
| Sem 7 | Hugging Face AI Agents Course | ~10 h |
| Sem 8 | n8n Academy `n8n102` + `n8n103` | 6-8 h |

Total: ~30 h repartidas en 12 semanas. Coste marginal 2.5 h/semana.

**Descartado:** el Certified Full-Stack Developer de freeCodeCamp. Son ~1.800 horas de React/Mongo que no tocan n8n, ni APIs, ni webhooks, ni LLMs. Es la ruta equivocada para este objetivo.

---

## Mes 1 — Fundamentos, Git, y el primer cliente

### Semana 1 — Cerrar lo que está hecho (en curso, ~70%)

**Ya completado:**
- [x] Fundamentos por práctica, sin curso
- [x] Webhook, Router, Filter, JSON, triggers vs actions
- [x] Entregable: Webhook → Filter → Router → Sheets + Telegram + Gmail

**Pendiente:**
- [ ] `1.4` Validación de formato de email, manejo de duplicados, ejecuciones fallidas
- [ ] `1.5` **Git**: primer commit, repo público, verificar que ningún secreto quedó expuesto
- [ ] `1.6` n8n Academy `QS101` → certificado
- [ ] `1.7` Documentar el flujo en `entregables/semana-01-webhook-enrutador/`

**Bloqueante de esta semana:** definir mi nicho. Sin nicho no puedo escribir una sola propuesta comercial. Se resuelve en el Bloque 4 de hoy o mañana.

**Checkpoint S1** — rúbrica, necesita ≥ 7.

### Semana 2 — PRIMER CLIENTE (aquí, no en el mes 3)

Esta es la semana más importante del plan.

- [ ] `2.1` Terminar pendientes de Semana 1
- [ ] `2.2` **Definir nicho** — algo que ya compra, que le duela, y que me deje acceso a sus datos. Candidatos: restaurantes, inmobiliarias, talleres, e-commerce, agencias de marketing
- [ ] `2.3` Calcular precio: cuánto cobro por un flujo, cuánto me cuesta la API, cuánto me cuesta el tiempo. Hoja en `docs/ofertas-comerciales.md`
- [ ] `2.4` n8n Academy `n8n101 Essentials` → certificado
- [ ] `2.5` **Entregable vendible #1**: automatizar un proceso real de un negocio real. Aunque cobre poco, **nunca gratis**
- [ ] `2.6` Pedir testimonio escrito del cliente 1

**Checkpoint S2** — no evalúo código, evalúo la propuesta comercial: claridad, precio, qué promete.

### Semana 3 — APIs reales + el diferenciador visual

- [ ] `3.1` Make Academy Intermediate (APIs y HTTP). Foundation Level 2 se salta: ya sabes routers y filtros
- [ ] `3.2` Verbos HTTP, headers, tokens, API keys, webhooks entrantes
- [ ] `3.3` **Entregable vendible #2 con capa visual**: generar piezas (imágenes, posts, PDFs, thumbnails) automáticamente con IA
- [ ] `3.4` Outreach directo: 10 propuestas personalizadas a Pymes del nicho. LinkedIn, Instagram, visita, email. **No esperes a Upwork**

**Checkpoint S3** — el entregable tiene que tener el componente visual funcionando.

### Semana 4 — Cierre Mes 1

- [ ] `4.1` Entregable integrador: bot de captura de prospectos con salida visual
- [ ] `4.2` Documentar arquitectura en `entregables/semana-04-*/`
- [ ] `4.3` Clientes: **2 pagados**
- [ ] `4.4` Evaluación Mes 1 — requiere ≥ 7

---

## Mes 2 — IA, agentes, n8n

### Semana 5 — APIs de IA y prompt engineering

- [ ] `5.1` DeepLearning.AI — el curso actual equivalente (el "Prompt Engineering for Developers" de 2023 está superado; elegir el vigente)
- [ ] `5.2` Modelos, temperatura, tokens, system prompts, structured output
- [ ] `5.3` Hugging Face MCP Course → certificado
- [ ] `5.4` **Entregable estrella**: generador automático de contenido visual mensual para un negocio (imágenes + copy + hashtags, listo para publicar)
- [ ] `5.5` Outreach: 10 propuestas más

**Checkpoint S5** — el entregable se vende solo sin que tengas que explicar mucho.

### Semana 6 — Agentes y clasificación

- [ ] `6.1` Agentes: cuándo usarlos y cuándo no. La diferencia entre cadena y agente
- [ ] `6.2` Extracción de datos estructurados (JSON output), análisis de sentimiento
- [ ] `6.3` Entregable: sistema que clasifica comentarios y responde
- [ ] `6.4` Clientes: **3 pagados**
- [ ] `6.5` Publicar 2 servicios en Upwork/Fiverr como canal *secundario*, no principal

**Checkpoint S6**

### Semana 7 — n8n avanzado (esto es lo que vendo)

- [ ] `7.1` n8n self-hosted en un VPS barato. El self-hosting es lo que me da margen del 100%: costo marginal ~0
- [ ] `7.2` Nodos comunitarios, manejo de errores, reintentos, idempotencia
- [ ] `7.3` Replicar los 3 flujos de Make en n8n
- [ ] `7.4` Hugging Face AI Agents Course → certificado
- [ ] `7.5` Documentar diferencias Make vs n8n y cuándo recomiendo cada uno al cliente

**Checkpoint S7**

### Semana 8 — Cierre Mes 2

- [ ] `8.1` Entregable: agente de ventas por Telegram/WhatsApp con IA
- [ ] `8.2` Documentar arquitectura
- [ ] `8.3` n8n Academy `n8n102` + `n8n103` → certificados
- [ ] `8.4` Evaluación Mes 2 — requiere ≥ 7

---

## Mes 3 — Escalar lo que funciona

### Semana 9 — Empaquetar servicios

- [ ] `9.1` 2 fichas técnicas de servicio: Atención con IA / Automatización operativa visual
- [ ] `9.2` Lista de precios y qué incluye cada una
- [ ] `9.3` Qué NO ofrezco (delimitar el alcance evita clientes malos)

### Semana 10 — Prueba social

- [ ] `10.1` Portafolio visual: capturas de los entregables de Sem 3, 5, 6, 8
- [ ] `10.2` Un caso de estudio completo de principio a fin
- [ ] `10.3` Subir el repo a GitHub limpio y con README que se entienda solo

### Semanas 11-12 — Clientes

- [ ] `11.1` 30 propuestas personalizadas. Canal principal: directo a Pymes del nicho
- [ ] `11.2` Cerrar 3 proyectos piloto
- [ ] `11.3` Retrospectiva de 3 meses. Qué funcionó, qué no, qué automatizar de mi propio proceso

**Checkpoint Final** — ≥ 8. Activo real: cartera de clientes, repo público con historial, 4-6 certificados.

---

## Riesgos

| Riesgo | Impacto | Mitigación |
|---|---|---|
| No conseguir clientes | Alto | Outreach empieza semana 3, no 11. Directo a Pymes antes que Upwork |
| Fatiga / procrastinación | Alto | Bloques 45/15, bitácora diaria, checkpoint semanal |
| API se cobra y el margen desaparece | Medio | Modelar el costo por operación en la hoja de precios antes de cotizar |
| Insistir en full stack de freeCodeCamp | Alto | Descartado explícitamente. Es un pozo de 1.800 horas sin retorno para este objetivo |
| Nicho mal definido | Alto | Es la tarea bloqueante de Semana 1. Nada comercial avanza sin esto |
| Filtrar un secreto en el repo público | Alto | `.gitignore` estricto. Revisar antes de cada commit |

## Preguntas abiertas

- [ ] **¿Cuál es mi nicho?** (bloqueante — necesito respuesta en 24h)
- [ ] ¿Tengo cuenta de Make activa?
- [ ] ¿En qué VPS quiero el self-host de n8n y cuánto cuesta el dominio?
- [ ] ¿Cuánto estoy dispuesto a cobrar por el primer flujo? Necesito un número, aunque sea provisional
