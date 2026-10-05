# Resumen de Sesión — Agencia IA Automatización

## Estado Actual (5 Oct 2026)

### ✅ Completado
- **Repo público**: https://github.com/carloslatta/agencia-ia-automatizacion
- **Make scenario funcional**: Tally webhook → filterRows (dedupe) → Router (validación + dedupe) → 3 rutas paralelas (Telegram, Sheets, Gmail)
- **Caso-insensitive email**: `lower()` en búsqueda, router, guardado
- **Typo arreglado**: "regisstro" → "registro"
- **Telegram parseMode**: HTML
- **Blueprint v12 guardado**: `docs/entregables/semana-01-webhook-enrutador/blueprint-fixed.json`
- **Tally.so** configurado (webhook gratis, 10k respuestas/mes)
- **Bot Telegram propio**: creado en @BotFather, Token en Make
- **Primer contacto real**: José (gym España) → "más adelante" (reformas/permiso)
- **Outreach plantilla**: lista para enviar a 10+ contactos/semana

### 📁 Estructura del Repo
```
cursos/
├── README.md                 # Estado, objetivo, estructura
├── PLAN.md                   # 12 semanas (monetización semana 2)
├── TODO.md                   # Estado actual (S1 done, niche + outreach pendiente)
├── AGENTS.md                 # Reglas del tutor (eval socrática, ≥7, no inflar)
├── .gitignore                # Secretos, .env, exports Make/Tally
├── opencode.jsonc            # Config mínima (omniroute only)
├── docs/
│   ├── rubrica-evaluacion.md     # Eficiencia/Errores/Estructura ≥7
│   ├── certificaciones.md        # Free certs con links/tiempo
│   ├── ofertas-comerciales.md    # Pricing template (needs niche)
│   └── original/                 # Backup plan original
├── bitacora/
│   ├── _plantilla.md             # Template diario
│   └── 2026-10-03-s1-checkpoint.md  # S1 eval (7.3/10 pass)
├── entregables/
│   └── semana-01-webhook-enrutador/  # Blueprint final
├── bitacora/_plantilla.md
└── assets/ (vacío)
```

### 🎯 Próximos Pasos Inmediatos (Semana 1 → 2)

| Prioridad | Acción | Deadline |
|---|---|---|
| **1. Definir nicho** | Elegir 1: gym/dark kitchen, inmobiliaria, clínica dental, e-commerce | HOY |
| **2. Outreach 10 contactos** | IG local + Maps + red cercana → 10 DMs con plantilla | ESTA SEMANA |
| **3. Cerrar 1 piloto** | 14 días gratis → Chat ID + Google access → test real | ESTA SEMANA |
| **4. Certificación n8n** | QS101 (3-5h) → badge gratis | Semana 1 |

### 💰 Pricing Definido (COP)
| Concepto | Precio |
|---|---|
| Setup inicial | $800k - $1.5M |
| Mensualidad | $200k - $400k/mes |
| Piloto | Gratis 14 días |

### 🛠 Stack Técnico Actual
| Herramienta | Uso |
|---|---|
| **Make** | Orquestación principal (webhook → Sheets/Telegram/Gmail) |
| **Tally.so** | Formularios gratis + webhook nativo |
| **Telegram Bot** | Notificaciones instantáneas (bot propio) |
| **Google Sheets** | CRM ligero + dedupe |
| **Gmail** | Email automático con HTML bonito |
| **n8n Academy** | Certificaciones gratis (QS101 → 101 → 102 → 103) |
| **Hugging Face** | MCP Course, AI Agents Course, Context Course |
| **Microsoft Learn** | Applied Skills (Create AI agent) |

### 📋 Contactos Pipeline
| Prospecto | Estado | Seguimiento |
|---|---|---|
| José (gym España) | "Más adelante" (reformas/permiso) | Revisar en 3 meses |
| **Nuevos** | **Vacío** | **URGENTE: 10 contactos esta semana** |

### 🎓 Certificaciones Prioritarias (Free + Badge)
1. **n8n Academy QS101** (3-5h) → Quickstart
2. **n8n Academy n8n101** (3-4h) → Essentials
3. **Hugging Face MCP Course** → Model Context Protocol
4. **Hugging Face AI Agents Course** → smolagents, LangGraph
5. **Microsoft Applied Skills** → "Create an AI agent"

---

## Para Nueva Sesión: Copia Esto

```
Contexto: Agencia IA automatización (Barranquilla, Colombia)
Objetivo: $ primero (piloto 14 días gratis → 150€/mes), carrera dev después
Stack: Make + Tally + Telegram Bot + Sheets + Gmail
Repo: github.com/carloslatta/agencia-ia-automatizacion
Estado: Make scenario v12 funcional, Tally webhook OK, Bot Telegram creado
Bloqueador: Definir nicho + outreach 10 contactos/semana
Próximo: Cerrar 1 piloto 14 días gratis esta semana
```