# 🚀 MVP Planner con IA

Convierte cualquier idea de proyecto en un plan de trabajo completo, estructurado bajo metodologías ágiles y listo para ejecutar con tu equipo desde el primer día.

---

## ¿Qué problema resuelve?

Cuando un equipo quiere construir algo con IA, el mayor obstáculo no es la tecnología: **es la falta de estructura**.

Sin un backlog claro, los sprints se llenan de tareas mal definidas, los criterios de éxito son ambiguos y el equipo pierde tiempo en reuniones que podrían evitarse.

El MVP Planner aplica los principios de **Scrum** y **Agile** para transformar una descripción de producto en un plan ejecutable en minutos.

---

## ¿Qué genera?

Le describes tu producto y produce automáticamente toda la estructura de trabajo:

| Elemento | Descripción | Marco Ágil |
|----------|-------------|------------|
| **Épicas** | Grandes áreas funcionales del producto | SAFe / Scrum |
| **Historias de Usuario** | `Como [rol] quiero [acción] para [beneficio]` | Scrum / XP |
| **Criterios de Aceptación** | Condiciones verificables para dar algo por terminado | BDD / ATDD |
| **Tareas y Sub-tareas** | Trabajo concreto estimado en horas | Kanban / Scrum |
| **Story Points** | Estimación relativa por historia (escala Fibonacci) | Planning Poker |
| **Sprints** | Iteraciones de 2 semanas con objetivos claros | Scrum |
| **Definition of Done** | Checklist de calidad por categoría | Scrum |
| **KPIs y Métricas** | Velocidad, cobertura de tests, latencia API | Agile Metrics |

---

## ¿Cómo se usa?

1. **Describe tu producto** — qué hace, para quién es y qué integraciones tiene
2. **Define tu equipo** — nombres de los miembros para asignación de tareas
3. **Elige la duración** — número de sprints (por defecto: 6 sprints de 2 semanas)
4. **Recibe el plan completo** — backlog estructurado + Excel de gestión listo para usar

> Si ya tienes un PRD o documento de requisitos, puedes compartirlo directamente y el planner lo leerá para extraer épicas, flujos y reglas de negocio automáticamente.

---

## Estructura del Backlog

El backlog sigue la jerarquía estándar de Scrum:

```
Épica (EP-01)
  └── Historia de Usuario (HU-001)
        ├── Tarea (T-001-01)
        │     └── Sub-tarea (ST-001-01-01)
        └── Tarea (T-001-02)
```

### Priorización
Cada ítem se clasifica con una prioridad explícita:

- 🔴 **Critical** — bloqueante, sin esto no hay producto
- 🟠 **High** — core del MVP, entra en los primeros sprints
- 🟡 **Medium** — importante pero no urgente
- 🟢 **Low** — nice-to-have, se planifica si hay capacidad

### Estimación con Fibonacci
Los story points siguen la escala de Fibonacci para reflejar la incertidumbre real:

| Puntos | Complejidad |
|--------|-------------|
| 1 – 2 | Tarea simple, bien definida |
| 3 – 5 | Historia estándar con algo de incertidumbre |
| 8 – 13 | Historia compleja o con dependencias |
| 21+ | Demasiado grande — se divide antes de planificar |

---

## Velocidad del equipo

El planner calcula la distribución de sprints en base al tamaño del equipo:

| Tamaño del equipo | Velocidad estimada |
|-------------------|-------------------|
| 2 – 3 personas | 25 – 35 pts / sprint |
| 4 – 6 personas | 35 – 50 pts / sprint |

Se aplica un **buffer del 15%** por sprint para imprevistos, deuda técnica y revisiones.

---

## ¿Qué incluye el Excel de gestión?

Un archivo con 5 hojas interconectadas con fórmulas dinámicas:

| Hoja | Contenido |
|------|-----------|
| 📊 **Dashboard** | Resumen ejecutivo: épicas, historias, puntos totales y progreso |
| 📋 **Backlog** | Todas las historias y tareas con dropdowns de estado, prioridad y asignación |
| 🗓 **Sprints** | Checklist por sprint con objetivo, ítems y capacidad |
| 📈 **Métricas** | Velocidad real vs planificada, KPIs de calidad y performance |
| ✅ **DoD** | Definition of Done por categoría con estado por sprint |

### Definition of Done (DoD)
Cada sprint se cierra evaluando estas categorías:

- 🔁 **Proceso** — PR revisado, rama mergeada, ticket actualizado
- 🧪 **Testing** — cobertura ≥ 80%, pruebas unitarias e integración pasando
- 🔒 **Seguridad** — sin vulnerabilidades críticas, datos sensibles protegidos
- ⚡ **Performance** — latencia API P95 < 500ms, carga de página < 2s
- 📱 **UX / Accesibilidad** — flujos validados, responsive en móvil
- 📋 **Documentación** — endpoints documentados, decisiones registradas
- 🚀 **Deploy** — desplegado en ambiente de staging o producción

---

## Ceremonias Scrum sugeridas

El plan generado está diseñado para alinearse con el ciclo estándar de Scrum:

| Ceremonia | Frecuencia | Duración sugerida |
|-----------|------------|-------------------|
| Sprint Planning | Inicio de cada sprint | 2 – 4 horas |
| Daily Standup | Todos los días hábiles | 15 minutos |
| Sprint Review | Fin de cada sprint | 1 hora |
| Sprint Retrospective | Fin de cada sprint | 1 hora |
| Backlog Refinement | Mid-sprint | 1 – 2 horas |

---

## Ejemplo real

> **Proyecto:** Plataforma de fútbol amateur (Perú)
> **Equipo:** 3 desarrolladores · 6 sprints · 12 semanas
>
> **Resultado generado:**
> - 7 épicas · 11 historias de usuario · 104 tareas · 38 sub-tareas
> - 225 story points totales distribuidos en 6 sprints
> - KPIs definidos: tasa de éxito de pagos > 85%, latencia < 500ms

---

## ¿Por qué estructurar antes de construir?

> *"La IA bien estructurada no es magia. Es método."*

Cuando le das contexto claro a la IA — roles, flujos, criterios de aceptación — el output es preciso y accionable. Sin estructura, genera ruido.

El MVP Planner no reemplaza al equipo. Lo prepara para arrancar con claridad desde el día uno.

---

*Todo el contenido se genera en español. Compatible con Jira, Notion, Linear y cualquier herramienta que importe CSV o Excel.*
