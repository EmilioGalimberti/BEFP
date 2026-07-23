# 🧠 BEFP — Cerebro de la Consultora

> **Objetivo:** Que la empresa no dependa de la memoria de los socios. Todo lo que importa vive acá.

Este vault en Obsidian es el sistema operativo de nuestra consultora. Centraliza contexto, proyectos, inteligencia de mercado, recursos y el día a día del equipo.

---

## 🗂️ Mapa del Vault

```
BEFP/
├── 📥 Contexto/          → El ADN de la empresa (quiénes somos, a dónde vamos)
├── 📅 Daily/             → Minutas de reuniones semanales
├── 🏢 Departments/       → Operaciones por área interna
├── 🔍 Intelligence/      → Inteligencia competitiva, mercado y decisiones
├── 📋 Kanban/            → Gestión de tareas (espejo del tablero en Miro)
├── 🚀 Projects/          → Proyectos activos con clientes
├── 📚 Resources/         → Material de apoyo: prompts, templates, herramientas, archivo
└── 🤖 Skills(IA)/        → Habilidades y flujos de IA para el equipo
```

---

## 📁 Descripción de cada carpeta

### 📥 `Contexto/` — El ADN de la empresa
La fuente de verdad sobre quiénes somos. Antes de tomar cualquier decisión estratégica, acá está el contexto.

| Archivo | Contenido |
|---|---|
| `INBOX.md` | Bandeja de entrada temporal. Revisar semanalmente y mover. |
| `brand.md` | Identidad de marca: nombre, colores, tono de comunicación. |
| `stakeholders.md` | Mapa de stakeholders: socios, contactos clave, aliados. |
| `team.md` | Perfil del equipo: quién hace qué, fortalezas, disponibilidad. |
| `pain-points.md` | Problemas reales que resolvemos para nuestros clientes. |
| `strategy.md` | Estrategia general, visión, misión y objetivos de la consultora. |

---

### 📅 `Daily/` — Minutas de reuniones
Una nota por reunión semanal de socios. Se generan a partir de la transcripción de audio usando la plantilla estándar.

**Formato de nombre:** `DD-MM-AA.md`
**Plantilla:** [`Resources/templates/Plantilla_Minutas_Reunion.md`](Resources/templates/Plantilla_Minutas_Reunion.md)

| Archivo | Contenido |
|---|---|
| `20-7-26.md` | Reunión del 20/07/26 — Miro, redes sociales, proyecto Bruno, documental. |

---

### 🏢 `Departments/` — Operaciones internas
El motor de la empresa organizado por área. Acá viven los SOPs y el know-how operativo de cada departamento.

```
Departments/
├── _guide.md       → Guía de uso de la sección
├── Finance/        → Costos, márgenes, rentabilidad, facturación
├── Marketing/      → Estrategia de contenido, redes, campañas, pitch
└── Systems/        → Herramientas internas, automatizaciones, tech stack
```

> **Regla:** Si hacés algo más de dos veces, documentalo como SOP acá.

---

### 🔍 `Intelligence/` — Inteligencia estratégica
Todo lo que nos ayuda a entender el mercado, la competencia y a tomar mejores decisiones.

```
Intelligence/
├── _guide.md           → Guía de uso de la sección
├── competitors/        → Análisis de competidores directos e indirectos
├── decisions/          → Registro de decisiones importantes (con contexto y razonamiento)
├── market/             → Tendencias, oportunidades y nichos del mercado
├── meetings/           → Reuniones con clientes, prospectos o aliados externos
└── processes/
    └── SOP_Gestion_Interna_Tareas_Reuniones.md  → Cómo gestionamos tareas y reuniones
```

---

### 📋 `Kanban/` — Gestión de tareas
Espejo en texto del tablero en Miro. Los Action Items de cada reunión se vuelcan acá.

```
Kanban/
├── TRELLO.md   → Link/referencia al tablero externo
└── tasks/
    └── Seguir mejorando obsidian.md  → Tarea activa: iteración del vault
```

> **Flujo:** Action Item en reunión → anotado en Daily → movido al Kanban → ejecutado → tachado.

---

### 🚀 `Projects/` — Proyectos con clientes
*(Carpeta vacía — lista para el primer proyecto activo)*

Cada proyecto es una subcarpeta con su nombre. Cuando se cierra, se archiva en `Resources/archive/`.

**Estructura sugerida por proyecto:**
```
Projects/
└── NombreCliente_NombreProyecto/
    ├── brief.md
    ├── propuesta.md
    └── entregables/
```

---

### 📚 `Resources/` — Biblioteca de la consultora
Todo el material de apoyo reutilizable: plantillas, prompts, herramientas y el archivo histórico.

```
Resources/
├── _guide.md       → Guía de uso de la sección
├── archive/        → Transcripciones crudas de audio de reuniones
│   ├── 20-07-26.md     (transcripción de Whisper)
│   └── 20-07-26.mp3    (audio original)
├── companies/      → Fichas de empresas (prospectos / clientes)
├── frameworks/     → Metodologías y marcos de trabajo que usamos
├── prompts/        → Biblioteca de prompts IA para tareas recurrentes
│   └── 💡Ideas_Implementacion_Avanzada.md
├── templates/      → Plantillas reutilizables
│   └── Plantilla_Minutas_Reunion.md
└── tools/          → Documentación de herramientas (Miro, Canva, Make, etc.)
```

---

### 🤖 `Skills(IA)/` — Habilidades de IA
*(Carpeta vacía — en construcción)*

Flujos, tutoriales y prompts especializados para tareas concretas con IA (transcripción con Whisper, resumen con Claude, automatización con Make.com, etc.).

---

## ⚙️ Flujo de trabajo semanal

```
1. REUNIÓN  →  Se graba el audio
2. AUDIO    →  Se transcribe con Whisper → guardado en Resources/archive/
3. TRANSCRIPCIÓN →  Se completa la minuta en Daily/ usando la plantilla
4. ACTION ITEMS  →  Se mueven al Kanban y al tablero de Miro
5. IDEAS SUELTAS →  Se mueven a Contexto/INBOX.md para procesar
```

---

## 📌 Reglas de Oro

1. **Si no está escrito, no existe.** Bajen la info de su cabeza al vault.
2. **Un lugar para cada cosa.** Antes de crear una nota nueva, verifiquen en qué carpeta va.
3. **Usá enlaces de Obsidian.** `[[Nombre de la nota]]` conecta el conocimiento. La magia está en los links.
4. **El INBOX es temporal.** `Contexto/INBOX.md` se vacía cada semana.
5. **Iterá sin miedo.** Esta estructura no es un dogma. Si algo no funciona, lo cambiamos.
6. **Las transcripciones crudas van en `Resources/archive/`.** Las minutas procesadas van en `Daily/`.

---

## 👥 Equipo

| Socio | Rol actual |
|---|---|
| Emilio | Sistemas, IA, documentación, diseño |
| Bruno | Proyecto cliente principal, estrategia |
| Facu | Prospección, contacto sector agropecuario |
| Pato | Redes sociales, presencia digital |

---

*Última actualización: 22-07-26*
