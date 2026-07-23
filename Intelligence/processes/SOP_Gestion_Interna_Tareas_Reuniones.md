# ⚙️ SOP: Gestión Interna de Reuniones y Tareas

Este documento define el estándar de cómo nos organizamos como equipo para que las ideas no queden en la nada y se transformen en trabajo ejecutable.

---

## 1. El Flujo de Trabajo (Workflow Base)

El proceso de la empresa funciona como una cadena de montaje:

1. **Ideación (La Reunión):** Nos reunimos los martes a las 18hs. Se graba la reunión.
2. **Documentación (La Minuta):** El audio se pasa por una IA (Fathom, Otter.ai, o Whisper+ChatGPT) para generar un resumen automático. Este resumen se pega en la `Plantilla_Minutas_Reunion.md` de Obsidian.
3. **Asignación (El Tablero):** Cualquier "Action Item" o decisión tomada en la reunión se convierte inmediatamente en una tarjeta en nuestro gestor de tareas. **Si no está en el tablero, no existe.**
4. **Ejecución (Asíncrona):** Durante la semana, cada socio entra al tablero, ve qué tiene asignado, y mueve las tarjetas según su progreso. Se comunica cualquier traba por Discord/Slack.

---

## 2. Metodología Kanban (Teoría para usar Trello)

Para arrancar vamos a usar **Trello**. Trello se basa en el método **Kanban**, un sistema visual inventado por Toyota para gestionar el trabajo en progreso.

La idea central de Kanban es que **el trabajo tiene que fluir de izquierda a derecha** a través de un tablero de columnas.

### Estructura base de columnas recomendada:

*   📋 **Backlog (Caja de Ideas):** Acá tiramos todo lo que queremos hacer algún día pero que todavía no tiene fecha ni prioridad. Es el "congelador".
*   🎯 **To Do (Para Hacer):** Las tareas que acordamos hacer *esta semana*. Si algo entra acá, sí o sí tiene que tener un Responsable asignado y una Fecha límite.
*   🏃 **Doing (Haciendo):** Las tareas en las que estamos trabajando HOY. 
    *   *Regla de Oro de Kanban (WIP Limit):* Nadie debería tener más de 2 tareas en esta columna al mismo tiempo. Si tenés 5, estás perdiendo el foco.
*   ⛔ **Blocked (Bloqueado):** Empezaste la tarea pero te trabaste porque necesitás la respuesta de un cliente, una contraseña de un socio, o que se solucione un bug. Se pone acá para que todos vean el "cuello de botella".
*   ✅ **Done (Hecho):** La tarea se terminó y fue validada. Sentimiento de victoria.

*Anatomía de una buena tarjeta en Trello:*
- Título claro usando verbos (Ej: *"Redactar propuesta para cliente X"*, no *"Cliente X"*).
- Responsable asignado.
- Etiqueta de prioridad (Alta, Media, Baja).

---

## 3. ⚠️Alternativas a Trello (Para investigar a futuro)

A medida que la empresa crezca y tengan procesos de desarrollo de software más complejos, Trello se puede quedar corto. Aquí dejamos registradas las alternativas para investigar en los próximos meses:

*   **Linear:** 
    *   *Por qué investigarlo:* Es el estándar de oro actual para empresas de software. Es ultra rápido, minimalista y está diseñado para trabajar en "Ciclos" (Sprints) de una o dos semanas. Todo se hace con el teclado. Tiene integraciones nativas con repositorios de código.
*   **ClickUp:** 
    *   *Por qué investigarlo:* Es un "todo en uno". Sirve si queremos tener las tareas, los clientes, los tiempos, los presupuestos y hasta documentos en un solo lugar. Es muy potente pero su curva de aprendizaje es más pronunciada y puede ser un poco burocrático al principio.
*   **Notion:** 
    *   *Por qué investigarlo:* Si decidimos que no queremos usar Obsidian y Trello por separado, Notion permite crear bases de datos personalizadas. Podemos tener el CRM, las notas y el Kanban interconectados en el mismo software. El contra: suele ponerse lento cuando las bases de datos crecen mucho y requiere conexión a internet constante.
