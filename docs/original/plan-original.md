# Implementation Plan: Agencia de IA y Automatización - Plan de Estudio 3 Meses

## Overview
Este plan convierte el documento de estudio en tareas ejecutables y verificables para los 3 meses (12 semanas). Cada semana tiene entregables concretos que se validan con Big Pickle.

## Architecture Decisions
- **Tracking**: Usar `tasks/todo.md` como lista maestra de tareas semanales
- **Verificación semanal**: Big Pickle evalúa cada viernes (criterios: Eficiencia, Manejo de errores, Estructura)
- **Entregables**: Cada semana produce un artefacto tangible (flujo Make, script, propuesta, etc.)
- **Herramientas base**: Make/Integromat (Mes 1), n8n + APIs IA (Mes 2), Upwork/Fiverr + portfolio (Mes 3)

## Task List

### Fase 1: Fundamentos y Automatización Visual (Make/Integromat) - Semanas 1-4

#### Semana 1: Módulos y Triggers
- [ ] Task 1.1: Completar Make Academy Foundation Level 1
- [ ] Task 1.2: Entender JSON básico, Webhooks, Triggers vs Actions
- [ ] Task 1.3: **Entregable**: Crear automatización que capture email → guarde en Google Sheets/Airtable

#### Semana 2: Enrutamiento y Filtrado
- [ ] Task 2.1: Completar Make Academy Foundation Level 2
- [ ] Task 2.2: Dominar Routers, Filtros, Iteradores, Agregadores
- [ ] Task 2.3: **Entregable**: Flujo que filtre emails importantes → envíe a Telegram/Discord

#### Semana 3: APIs y Solicitudes HTTP
- [ ] Task 3.1: Completar Make Academy Intermediate
- [ ] Task 3.2: Dominar HTTP verbs (GET, POST), Headers, Auth tokens, API Keys
- [ ] Task 3.3: **Entregable**: Conectar API pública (clima/finanzas) → hoja de cálculo

#### Semana 4: Proyecto Integrador Mes 1
- [ ] Task 4.1: **Entregable final**: Bot captura prospectos automático para tienda/servicio
- [ ] Task 4.2: Documentar arquitectura del bot
- [ ] Task 4.3: Evaluación Big Pickle (semana 4)

### Checkpoint: Mes 1 Completo
- [ ] 3 automatizaciones funcionales en Make
- [ ] Entregable integrador funcionando end-to-end
- [ ] Puntuación Big Pickle ≥ 7/10

---

### Fase 2: Integrador de IA y Prompt Engineering - Semanas 5-8

#### Semana 5: Fundamentos APIs de IA (OpenAI/Anthropic)
- [ ] Task 5.1: Curso DeepLearning.AI "ChatGPT Prompt Engineering for Developers"
- [ ] Task 5.2: Entender modelos (GPT-4o, Claude), Temperature, Tokens, System Prompts
- [ ] Task 5.3: **Entregable**: Script/nodo Make que procese texto largo → resumen ejecutivo

#### Semana 6: Agentes y Clasificación de Datos
- [ ] Task 6.1: Extracción entidades estructuradas (JSON output), Análisis sentimiento
- [ ] Task 6.2: **Entregable**: Sistema atención que clasifique comentarios → "Positivo"/"Queja"/"Venta"

#### Semana 7: Automatización Avanzada con n8n
- [ ] Task 7.1: Instalar n8n (local/cloud), explorar nodos comunitarios
- [ ] Task 7.2: Replicar flujos Make en n8n (3 flujos previos)
- [ ] Task 7.3: Documentar diferencias Make vs n8n

#### Semana 8: Proyecto Integrador Mes 2
- [ ] Task 8.1: **Entregable final**: "Agente de Ventas" WhatsApp/Telegram con IA (responde FAQs)
- [ ] Task 8.2: Documentar arquitectura del agente
- [ ] Task 8.3: Evaluación Big Pickle (semana 8)

### Checkpoint: Mes 2 Completo
- [ ] 2 proyectos con IA funcionando (resumen + clasificador + agente ventas)
- [ ] n8n replicando flujos Make
- [ ] Puntuación Big Pickle ≥ 7/10

---

### Fase 3: Oferta Comercial y Evaluación - Semanas 9-12

#### Semana 9: Empaquetado de Servicios
- [ ] Task 9.1: Definir oferta High-Ticket, auditoría procesos para Pymes
- [ ] Task 9.2: **Entregable**: 2 propuestas comerciales (ficha técnica):
  - Servicio Atención con IA
  - Servicio Automatización Operativa

#### Semana 10: Lanzamiento en Plataformas Freelance
- [ ] Task 10.1: Optimizar perfiles Upwork/Fiverr
- [ ] Task 10.2: Crear portafolio visual (casos de estudio Mes 1-2)
- [ ] Task 10.3: **Entregable**: 3 Gigs/Services publicados en Upwork/Fiverr

#### Semana 11-12: Consecución de 3 Primeros Clientes
- [ ] Task 11.1: Enviar 20 propuestas personalizadas a Pymes/internacionales
- [ ] Task 11.2: Cerrar 3 proyectos piloto
- [ ] Task 11.3: Evaluación final Big Pickle + retrospectiva 3 meses

### Checkpoint: Mes 3 Completo / Plan Finalizado
- [ ] 2 propuestas comerciales listas
- [ ] 3 servicios publicados en plataformas
- [ ] 3 clientes piloto cerrados
- [ ] Puntuación Big Pickle ≥ 8/10

---

## Risks and Mitigations

| Risk | Impact | Mitigation |
|------|--------|------------|
| Fatiga de decisión / procrastinación | Alto | Bloques rígidos 45/15, Big Pickle accountability diario |
| Complejidad técnica APIs/IA | Medio | Progresión gradual Make → n8n → IA, replicar antes de innovar |
| No conseguir clientes | Alto | Empezar outreach semana 10, 20 propuestas = funnel realista |
| Big Pickle no disponible | Bajo | Auto-evaluación con rúbrica guardada, peer review opcional |

## Open Questions
- ¿Cuenta con cuenta Make/Integromat activa? (necesaria semana 1)
- ¿Tiene acceso a n8n cloud o prefiere local? (semana 7)
- ¿Cuál es su nicho objetivo para las propuestas semana 9? (define portfolio)
- ¿Horario confirmado 13:00-22:00 o necesita ajuste?

## Daily Tracking Template (para Big Pickle)
```
Fecha: YYYY-MM-DD
Bloque 1 (Teoría): [tema + 1 frase resumen]
Bloque 2 (Práctica): [qué construyó + link/evidencia]
Bloque 3 (Debug/Notas): [errores + soluciones]
Bloque 4 (Proyecto): [avance proyecto actual]
Bloque 5 (Docs/Big Pickle): [qué documentó + preguntas]
Score día (1-10): [auto-evaluación]
```