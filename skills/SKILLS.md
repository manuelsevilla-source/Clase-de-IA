---
name: eli5-ai-web
description: Diseña y genera páginas web interactivas autocontenidas (.html) que explican conceptos complejos de Inteligencia Artificial de forma didáctica y accesible usando analogías cotidianas, SVGs ilustrados, simuladores y quizzes.
triggers:
  - "/eli5-ai"
  - "crear web explicativa de IA"
  - "explicar IA de forma sencilla"
---

# Skill: Creador de Páginas Web Didácticas de IA (ELI5)

Esta habilidad fusiona el rigor pedagógico de simplificación de conceptos (*ELI5 Conceptual*) con la arquitectura de páginas web explicativas, visuales e interactivas (*ELI5 Visual Web*). Su objetivo específico es generar **páginas web interactivas** (`.html` en un solo archivo) que expliquen **Inteligencia Artificial** a cualquier persona de forma intuitiva, visual y sin tecnicismos innecesarios.

---

## 🎨 Principios de Diseño Pedagógico para IA

### 1. Diccionario de Analogías de Inteligencia Artificial

| Concepto de IA | Jerga técnica habitual | Analogía Cotidiana y Didáctica |
|---|---|---|
| **Modelo de Lenguaje (LLM)** | Predicción probabilística autoregresiva de secuencias de tokens | Un lector intuitivo que completa frases adivinando qué palabra tiene más sentido a continuación |
| **Token / Tokenización** | Segmentación de subpalabras / ids numéricos | Piezas de construcción o letras de sopa de letras con las que se arman palabras y frases |
| **Embeddings / Vectores** | Proyección en espacio euclidiano multidimensional | Un mapa conceptual donde los objetos con significado similar se guardan en el mismo casillero |
| **Mecanismo de Atención** | Matriz de auto-atención softmax(QK^T / sqrt(d_k)) | Una linterna que ilumina las palabras clave para comprender el contexto general |
| **Entrenamiento (Training)** | Optimización estocástica por gradiente descendente y backpropagation | Practicar tiros a portería: tras cada intento fallido, se ajusta un poco la puntería hasta acertar |
| **Red Neuronal** | Grafos de capas densas con funciones de activación | Un equipo coordinado en filas que se van pasando pistas hasta llegar a una conclusión |
| **RAG (Recuperación aumentada)** | Retrieval de chunks en vector DB + inyección en prompt | Un asistente que consulta un archivador antes de responder para ofrecer datos verificados |
| **Alucinación** | Generación no fundamentada por sampling probabilístico | El modelo respondiendo con inventiva cuando no tiene la información precisa |

---

## 🛠️ Estructura de la Página Web Generada (`.html`)

Cada entrega debe ser un archivo `.html` autocontenido (HTML + CSS + JS inline, sin dependencias externas obligatorias para que funcione offline o con un simple doble clic):

1. **Header / Hero Atractivo y Claro**:
   - Título amigable (Ej: *"¿Cómo aprende un modelo de IA? Los secretos de los LLM"*).
   - Botón *"¡Empezar a explorar!"*.

2. **La Narrativa Central (Analogía Clave)**:
   - Tono cercano, accesible y estimulante.
   - Textos cortos y directos (máximo 2 a 3 líneas por párrafo).

3. **Ilustraciones Visuales (SVG integrados)**:
   - Gráficos limpios y armónicos con formas geométricas claras.
   - Etiquetas directas y tipografía legible.

4. **Laboratorio Interactivo / Simulador en Vivo (JS)**:
   - Demostraciones interactivas donde el usuario interactúa con botones o deslizadores para experimentar el concepto en tiempo real.

5. **Glosario Secreto (Tooltips en etiquetas `<span class="term">`)**:
   - Al pasar el ratón (o tocar en móvil), se abre una burbujita explicando qué es la palabra técnica real.

6. **Mini Quiz de Preguntas Divertidas**:
   - 3 preguntas con 3 opciones.
   - Al seleccionar la respuesta correcta: confeti o mensaje alegre ("¡Genial! 🌟").
   - Al seleccionar la incorrecta: pista amigable ("Casi... ¡recuerda el ejemplo de la linterna!").

---

## 🚀 Guía de Ejecución

Cuando el usuario pida explicar un tema de IA:
1. **Identificar el concepto** (ej. *Diffusion Models / Generación de imágenes*).
2. **Seleccionar la metáfora clave** (ej. *Un pintor que empieza con una pizarra llena de arena o ruido y la va limpiando con un cepillo hasta que aparece un gatito*).
3. **Construir el archivo web** directamente en la carpeta del proyecto (ej: `web/diffusion-eli5.html`).
4. **Proporcionar al usuario el enlace/ruta** para que lo abra en su navegador de inmediato.

