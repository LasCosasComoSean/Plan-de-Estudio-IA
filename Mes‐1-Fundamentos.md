# Mes 1: Fundamentos de Python y Conceptos Básicos de IA (Versión Extensa)

En este mes sentamos las bases de Python y una introducción a Machine Learning clásico. Consta de 4 semanas (Semana 1 a 4).

---

## Semana 1: Instalación y Sintaxis de Python

### Objetivo
Instalar y configurar tu entorno de Python; adquirir la base de la sintaxis de Python.

### Contenido Detallado

1. **Instalación y Configuración**  
   - Instala Python 3.x desde [python.org](https://www.python.org/downloads/).  
   - Aprende a crear y activar entornos virtuales con `venv` o `conda` para manejar dependencias.  
   - Familiarízate con un IDE o editor de código: Visual Studio Code, PyCharm o Jupyter Notebooks.

2. **Sintaxis Básica de Python**  
   - Tipos de datos primitivos: `int`, `float`, `str`, `bool`.  
   - Estructuras de control: `if-elif-else`, bucles `for` y `while`.  
   - Introducción a colecciones: `list`, `dict`, `tuple`.

3. **Pequeños Ejercicios**  
   - Crear un “Hola Mundo” y un script que pida al usuario su nombre y lo salude.  
   - Practicar operaciones aritméticas y condicionales.

#### ¿Por qué es importante?
- Python es la base para casi todo en IA (scripts, manejo de datos, APIs).
- Un entorno virtual bien configurado evita conflictos de librerías.

#### Ejemplo de Aplicación
- Un script que pida un texto al usuario y posteriormente se conecte a un LLM (Mes 2).

### Recursos Recomendados (Semana 1)
- **freeCodeCamp (Python)**, **Codecademy: “Learn Python”**, **Kaggle Micro-Courses (Intro a Python)**

---

## Semana 2: Funciones, Módulos y Manejo de Datos

### Objetivo
Profundizar en funciones, módulos y manejo de datos con `pandas`.

### Contenido Detallado

1. **Funciones y Módulos**  
   - Definir funciones con `def`, parámetros, valores de retorno.  
   - Uso de módulos y librerías estándar (`math`, `random`, etc.).  
   - Manejo de errores con `try-except`.

2. **Introducción a `pandas`**  
   - Lectura de archivos CSV (`pd.read_csv()`), exploración con `df.head()`, `df.describe()`.  
   - Seleccionar y filtrar datos, agregaciones simples (mean, count).

3. **Proyecto Pequeño**  
   - Leer un archivo CSV real (por ejemplo, un dataset de Kaggle), mostrar estadísticas de recuento, promedio, máximo, mínimo.  
   - Practicar limpieza de datos (eliminar valores nulos, formatear columnas).

#### ¿Por qué es importante?
- Manejo de datos es esencial para entrenar IA o filtrar datasets.  
- Te servirá en Mes 2 y 5 si necesitas manipular grandes volúmenes de texto o metadatos de audio/video.

#### Ejemplo de Aplicación
- Convertir un CSV de metadatos de canciones en un dataframe `pandas` y más tarde aplicar IA para clasificarlas.

### Recursos Recomendados (Semana 2)
- **Udemy: “Complete Python Bootcamp”**, **Kaggle Micro-Courses: pandas**, **Doc oficial de Python**

---

## Semana 3: ML Esencial con scikit-learn

### Objetivo
Familiarizarse con los conceptos esenciales de ML y ver un ejemplo práctico con `scikit-learn`.

### Contenido Detallado

1. **Conceptos de ML**  
   - Supervisado vs. no supervisado, train/test split, sobreajuste (overfitting).  
   - Métricas: precisión (accuracy), recall, F1-score.

2. **Práctica con `scikit-learn`**  
   - Instalar `scikit-learn` (`pip install scikit-learn`).  
   - Usar el dataset de Iris para entrenar un modelo (ej. `RandomForestClassifier`).  
   - Separar datos en train/test, entrenar, predecir, medir exactitud.

3. **Mini-ejemplo**  
   - Mostrar un confusion matrix si es posible, o al menos la precisión.

#### ¿Por qué es importante?
- Aunque gran parte del plan se oriente a LLMs, entender la base del ML tradicional te enseña a evaluar y medir rendimiento.
- En Mes 5 podrías querer clasificar clips de audio/video.

#### Ejemplo de Aplicación
- Clasificar “clips de audio aptos o no aptos” si tuvieras un dataset etiquetado.

### Recursos Recomendados (Semana 3)
- **Andrew Ng’s “Machine Learning”** en Coursera  
- **fast.ai - “Practical Deep Learning for Coders”**  
- **Documentación de scikit-learn**

---

## Semana 4: Primeros Pasos en Prompt Engineering

### Objetivo
Introducir la Ingeniería de Prompts (Prompt Engineering) con ChatGPT / GPT-4.

### Contenido Detallado

1. **Uso Básico de ChatGPT / GPT-4**  
   - Zero-shot, few-shot, chain-of-thought.  
   - Controlar la longitud de respuesta y estilo.

2. **Prompt Cookbook**  
   - Crear tu propio registro de prompts y resultados.  
   - Experimentar con prompts para resúmenes, reescritura, etc.

3. **Ejercicios**  
   - Pedir a ChatGPT que explique temas de Python o ML con distintos estilos.

#### ¿Por qué es importante?
- En Mes 2 profundizarás en LLMs y en estructurar prompts para alta calidad.  
- La ingeniería de prompts es la base de la automatización con ChatGPT y otras IA.

#### Ejemplo de Aplicación
- Pedirle a ChatGPT que escriba letras de canciones o guiones de video. Sin buenos prompts, la salida será pobre.

### Recursos Recomendados (Semana 4)
- **OpenAI Docs (Prompt Examples)**, **Learn Prompting**  
- Blogs (Medium, dev.to) sobre ejemplos de prompts

---

**Siguiente**: [Mes 2: LLMs y Prompt Engineering](Mes-2-LLMs.md)
