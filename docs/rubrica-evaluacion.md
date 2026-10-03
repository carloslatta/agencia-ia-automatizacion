# Rúbrica de Evaluación Semanal

Cada checkpoint evalúa el entregable de la semana en tres ejes. Cada uno de 1 a 10.

| Eje | Qué se mide |
|---|---|
| **Eficiencia** | ¿La solución hace el trabajo con los pasos mínimos? ¿Hay etapas innecesarias, módulos muerto, o permisos más amplios de lo que necesita? |
| **Manejo de errores** | ¿Qué pasa cuando falla una API, llega un payload vacío, o el cliente manda basura? ¿Hay validación, reintentos, fallback, y una forma de enterarse? |
| **Estructura lógica** | ¿Se entiende leyendo? Nombres coherentes, un responsibility por nodo/paso, reutilizable, y que otro pueda mantenerlo en 6 meses. |

---

## Umbrales

| Nivel | Significado |
|---|---|
| **≥ 8** | Sobresaliente. Sin observaciones relevantes. |
| **7** | Pasa la semana. Hay algo mejorable, no bloqueante. |
| **5 – 6** | Repito el entregable. Hay un problema real. |
| **< 5** | Hay que reconstruir. No solo arreglar. |

**Nunca se infla la nota para hacer avanzar de semana.** Un 6 honesto ahorra tres semanas.

---

## Cómo se aplica

1. Yo entrego el artefacto (capturas, export, código, enlace).
2. Big Pickle evalúa los tres ejes con números y justificación concreta.
3. Si alguna nota queda en **5 o menos**, las observaciones van como **preguntas socráticas**, no como la respuesta. Quiero pensar el arreglo, no copiarlo.
4. Si reintento y vuelvo a fallar lo mismo, entonces sí: me dan la respuesta directa.

---

## Preguntas que hago siempre

Estas son las preguntas que un cliente o un jefe haría al leer el flujo. Si alguna no tiene respuesta clara, el entregable está incompleto:

1. ¿Qué pasa si la API falla dos veces seguidas? ¿Me entero o el flujo muere en silencio?
2. ¿Qué pasa si el mismo email llega dos veces? ¿Genera duplicado?
3. ¿Cuánto me cuesta esto por cada ejecución en la API? ¿Quién paga si el volumen sube 10x?
4. ¿Qué ve el cliente cuando mira el flujo? ¿Entiende qué hace sin que se lo expliquen?
5. Si esto corre en 6 meses y yo no lo toco, ¿otra persona lo puede mantener?
6. **¿Dónde está la capa visual?** Esto es lo que me diferencia del resto.
