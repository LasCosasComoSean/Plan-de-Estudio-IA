# Mes 2: LLMs, Prompt Engineering Avanzado y Agentes

Conectarás Python con la API de OpenAI, usarás frameworks (LangChain) y crearás agentes que automaticen pasos.

---

## Semana 5: Conexión con OpenAI y Prompts Dinámicos

### Objetivo
Conectar Python con la API de OpenAI y entender parámetros como temperature, max_tokens, top_p, etc.

### Contenido Detallado

1. **OpenAI Python Library**  
   - `pip install openai`, configuración de keys en [OpenAI](https://platform.openai.com/account/api-keys).  
   - Parámetros: `temperature`, `max_tokens`, `top_p`.

2. **Prompts Dinámicos**  
   - Uso de f-strings para insertar variables en el prompt.  
   - Parsear respuestas (JSON, texto plano).

3. **Script de Consola**  
   - Pregunta al usuario algo, manda la consulta a GPT, imprime la respuesta.

#### ¿Por qué es importante?
- Base para “hablar” con el modelo desde Python, esencial para automatizaciones o apps web.  
- En Mes 5 podrás generar guiones, letras o copys de redes automáticamente.

#### Ejemplo de Aplicación
- Generar un borrador de un post de redes sociales, pides al usuario un tema y GPT entrega el texto final.

### Recursos (Semana 5)
- **OpenAI Docs**, **openai-cookbook (GitHub)**

---

## Semana 6: LangChain Basics y Cadenas de Prompts

### Objetivo
Explorar frameworks como LangChain y crear cadenas de prompts.

### Contenido Detallado

1. **LangChain Fundamentals**  
   - Cadenas (chains), memory, prompt templates.  
   - Secuencias típicas: “resumir texto → preguntas → formatear resultado”.

2. **Mini Proyecto**  
   - Crear un chain que reciba un texto y realice 2-3 pasos (resumen, Q&A, etc.).  
   - Ajustar parámetros (temperature, top_p).

3. **Automatización**  
   - Integrar con Python scripts para un pipeline (lee un archivo, pasa su contenido a la chain, guarda la salida).

#### ¿Por qué es importante?
- LangChain facilita orquestar múltiples pasos.  
- En Mes 5 podrías usar “chains” para crear un workflow: “Generar letra → base musical → voice cloning”.

#### Ejemplo de Aplicación
- Un pipeline que lea artículos y genere un “resumen + 5 preguntas” para un blog.

### Recursos (Semana 6)
- **LangChain Docs**  
- Videos en YouTube: “LangChain tutorial”

---

## Semana 7: AI Agents y Auto-GPT

### Objetivo
Crear AI Agents que automaticen varias tareas (Auto-GPT, BabyAGI).

### Contenido Detallado

1. **Agentes en LangChain**  
   - Uso de “herramientas” (búsquedas web, calculadoras, etc.).  
   - Razonamiento multi-paso, planeación automatizada.

2. **Auto-GPT / BabyAGI (opcional)**  
   - Exploración de repos en GitHub.  
   - Comprender “auto-loop” (el agente se asigna subtareas hasta cumplir un objetivo).

3. **Proyecto**  
   - Un agente que reciba una meta (p.ej., “Encuentra las últimas noticias de IA”), busque datos y genere un informe final.

#### ¿Por qué es importante?
- La automatización es clave para grandes flujos de trabajo, especialmente en Mes 5 cuando quieras generar contenido en masa.  
- Te muestra cómo la IA se autogestiona pasos.

#### Ejemplo de Aplicación
- Programar un agente que, cada día, lea tendencias de Twitter, las resuma y cree un post listo para publicar.

### Recursos (Semana 7)
- **Auto-GPT (GitHub)**, **BabyAGI (GitHub)**  
- Sección “Agents” en la documentación de LangChain

---

## Semana 8: Prompt Avanzado, Embeddings y Fine-Tuning

### Objetivo
Refinar Prompt Engineering y explorar embeddings/fine-tuning.

### Contenido Detallado

1. **Prompt Engineering Avanzado**  
   - Roles (system, user, assistant), chain-of-thought oculto.  
   - Manejo de la longitud y estilo de la respuesta.

2. **Embeddings / Fine-Tuning**  
   - Búsqueda semántica (Pinecone, Weaviate) para RAG.  
   - Fine-tuning GPT-3 con datos propios (costos, limitaciones).

3. **Caso Práctico**  
   - Almacenar tus descripciones de videos o letras de canciones en una base vectorial y consultarlas con semántica.

#### ¿Por qué es importante?
- En Mes 5, si manejas gran librería de contenido multimedia, embeddings te permiten buscar y reutilizar partes específicas.
- Fine-tuning te ayuda a que el modelo hable con tu estilo de marca.

#### Ejemplo de Aplicación
- Un chatbot que “recuerda” toda tu discografía y sugiere nuevas ideas de colaboración.

### Recursos (Semana 8)
- **OpenAI Cookbook** para embeddings y fine-tuning  
- Pinecone, Weaviate docs

---

**Siguiente**: [Mes 3: Integración Web y Despliegue](Mes-3-Web.md)
