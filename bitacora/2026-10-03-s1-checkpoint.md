# 2026-10-03 — Checkpoint S1

## Estado
- Entregable: Webhook → Filter → Router → Sheets + Telegram + Gmail
- Promedio: 5.0 (No pasa) — corregir antes de marcar 1.4 como completo
- Concepto detectado: Router difunde; el filtro protege Gmail pero Telegram y Sheets corren igual

## Explicación corta
- Cuando el webhook llega sin email, Gmail no se ejecuta (tiene filtro). 
- Pero Telegram **sí** se ejecuta. Sheets **sí** se ejecuta. Por eso llega el mensaje y se guarda la fila.
- Solución: valida **ANTES** del Router (un único filtro para el email válido). Así las tres ramas reciben solo datos válidos.

## 3 preguntas respondiendo al usuario
1. Con un webhook sin email, ahora mismo: **Rama Gmail** no corre (filtro). **Rama Telegram** corre. **Rama Sheets** corre.
2. Mejor sitio: **justo después del Webhook, ANTES del BasicRouter**. Un único filtro `email exist AND contains @`. Así una sola validación protege las tres salidas.
3. Duplicados: hay que evitar insertar si ya existe ese email (o ese mensaje). En Make se puede usar un **Search in Google Sheets** buscando ese email y añadir un filtro (sólo si no encuentra resultado) antes de Add a Row. También sirve un hash (timestamp+email) o marcar por evento. Pero la idea clave: **no añadir si ya existe**.

## Reentrega mínima para pasar
Exporta el mismo escenario con:
- Filtro único entre Webhook y Router que valide email con @
- Prevención de duplicados antes de "Add a Row" (Search in Google Sheets + filtro "Total number of bundles = 0")
- (Bonus) validación mínima también para Telegram/Gmail o deja que el filtro central lo controle

## Notas
No es un error de ejecución, es uno de **diseño**. El primer intento está bien para aprender. Esto es lo que se arregla moviendo un solo módulo. 
