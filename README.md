# Manual de Usuario
## Proyecto Hélix — Sabotaje Corporativo

---

### Sobre el juego

*Proyecto Hélix* es un juego de detectives en el navegador, inspirado en **Clue**, ambientado en un thriller corporativo. El prototipo más valioso de **TechCore Industries** ha sido robado a doce horas de su lanzamiento oficial, y el edificio está sellado con cinco sospechosos dentro. Tu misión: descubrir **quién**, **con qué herramienta** y **desde qué ubicación** se ejecutó el sabotaje. Cada partida es distinta: el culpable, la herramienta y el lugar se eligen al azar.

---

### Objetivo

Identificar correctamente los tres elementos del sabotaje:

1. **¿Quién?** — uno de los 5 empleados sospechosos
2. **¿Con qué?** — una de las 5 herramientas de espionaje
3. **¿Dónde?** — una de las 5 ubicaciones del edificio

Tienes **una sola acusación**. Elige con precisión.

---

### Cómo iniciar

1. Abre el archivo `index.html` en tu navegador *(o entra a la URL si está publicado en GitHub Pages / itch.io)*.
2. Pulsa **"Iniciar Investigación"**.
3. Lee el expediente del caso y pulsa **"Acceder al Sistema"**.

---

### Cómo jugar

#### Paso 1 — Analizar las ubicaciones
En la pantalla principal verás el **Mapa del Edificio** con las 5 ubicaciones (Sala de Servidores, Oficina del CEO, Laboratorio de I+D, Cafetería, Archivo de Documentos). **Haz clic en cualquier ubicación** para investigarla. Aparecerá una ventana con las evidencias encontradas allí.

> Cada ubicación se puede analizar **una sola vez**. Las ya revisadas quedan marcadas como `◉ ANALIZADO`.

#### Paso 2 — Revisar el Registro de Evidencias
A la derecha de la pantalla está el **panel de evidencias**. Allí se acumulan todos los hallazgos por ubicación.

Hay tres tipos de evidencias:
- **Coartadas** → descartan a un sospechoso *("X estuvo en la Cafetería toda la noche según el badge")*
- **Herramientas descartadas** → confirman que un dispositivo no se usó
- **Punto de extracción** → revela en qué ubicación se ejecutó el sabotaje

#### Paso 3 — Deducir
Por eliminación, identifica:
- El sospechoso que **no tiene coartada**
- La herramienta que **nadie descartó**
- La ubicación marcada como **punto de extracción**

>  No es obligatorio analizar las 5 ubicaciones antes de acusar, pero **se recomienda** para tener toda la información.

#### Paso 4 — Formalizar la acusación
Cuando estés listo, pulsa **"Formalizar Acusación"**. Selecciona un sospechoso, una herramienta y una ubicación, y pulsa **"Confirmar Acusación"**.

---

###  Resultados

- **✅ Acertaste** → "CASO RESUELTO". Se revela el motivo del saboteador y su confrontación final.
- **❌ Fallaste** → "ACUSACIÓN ERRÓNEA". El verdadero culpable escapa con el prototipo, pero descubres quién era.

Cada uno de los 5 sospechosos tiene su **propia historia y motivo único** (codicia, traición, espionaje industrial, venganza, chantaje), así que hay **5 finales distintos** que puedes descubrir jugando varias veces.

---

###  Controles

| Acción | Cómo |
|--------|------|
| Analizar una ubicación | Clic sobre la tarjeta |
| Cerrar una evidencia | Botón "Confirmar" |
| Seleccionar en la acusación | Clic sobre la opción |
| Reiniciar partida | Botón "Iniciar Nuevo Caso" al final |

Solo se necesita **ratón** (o pantalla táctil en móvil). No requiere teclado.

---

###  Los Sospechosos

- **Marcus Reed** — Director Ejecutivo
- **Dra. Sofía Aranza** — Ingeniera Principal
- **Daniel Vega** — Pasante
- **Viktor Drakos** — Inversor Rival
- **Helena Cross** — Jefa de Seguridad

###  Las Herramientas

- USB no rastreable
- Clonador de tarjetas magnéticas
- Malware en portátil
- Micrófono direccional
- Código fuente impreso

###  Las Ubicaciones

- `LOC-01` Sala de Servidores
- `LOC-02` Oficina del CEO
- `LOC-03` Laboratorio de I+D
- `LOC-04` Cafetería
- `LOC-05` Archivo de Documentos

---

###  Consejos para investigadores

- 📋 **Lee todas las evidencias antes de acusar.** El registro las guarda todas.
- 🚪 **Analiza todas las ubicaciones.** Con 4 análisis ya tienes información suficiente, pero el quinto confirma la respuesta.
- 🎲 **Cada partida es nueva.** El saboteador, la herramienta y la ubicación cambian al reiniciar.
- 🎬 **Juega varias veces** para descubrir los 5 finales distintos.

---

###  Información técnica

- **Plataforma:** Navegador web (Chrome, Firefox, Edge, Safari)
- **Tecnología:** HTML5, CSS3, JavaScript
- **Conexión a internet:** No requerida después de cargar
- **Dispositivos:** Computadora, tablet y celular

---

*El reloj corre, detective. El amanecer no espera.*
