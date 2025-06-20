# UBA CEIA – Trabajos Prácticos de NLP

Este repositorio contiene los notebooks correspondientes a los desafíos prácticos del curso de **Procesamiento de Lenguaje Natural** del CEIA – FIUBA. A continuación, se presenta una descripción de cada notebook y sus objetivos principales.

---

## 📘 Desafío 1 – Análisis de Similaridad entre Documentos

**Archivo:** `Desafio_01.ipynb`

**Resumen:**  
Este trabajo implementa una estrategia para medir la similitud entre documentos utilizando la **similitud del coseno**.  
Pasos principales:

- Se seleccionan 5 documentos al azar del corpus.
- Para cada uno, se calcula la similitud con el resto usando TF-IDF o CountVectorizer.
- Se identifican los 5 documentos más similares y se analizan sus etiquetas para evaluar si la similitud semántica tiene sentido.

**Objetivo:**  
Evaluar la capacidad de los modelos de vectorización para representar similitud semántica entre textos.

---

## 📙 Desafío 2 – Embeddings personalizados con Gensim

**Archivo:** `Desafio_02.ipynb`

**Resumen:**  
Se explora la generación de embeddings de palabras personalizados a partir de letras de canciones en inglés mediante el modelo **Word2Vec de Gensim**.

- Se entrena un modelo Word2Vec con corpus de canciones.
- Se visualizan relaciones semánticas entre palabras de uso frecuente.
- Se realizan experimentos para evaluar la calidad del embedding.

**Objetivo:**  
Comprender cómo el contexto específico de un corpus afecta la representación vectorial de las palabras.

---

## 📗 Desafío 3 – Modelo de Lenguaje con Tokenización por Caracteres

**Archivo:** `Desafio_3_CristianSalinas.ipynb`

**Resumen:**  
Se entrena un modelo de lenguaje basado en **RNNs, LSTM y GRU**, usando tokenización a nivel de carácter sobre letras de canciones.

- Preprocesamiento: limpieza, tokenización y estructuración del dataset.
- Entrenamiento de modelos con distintas arquitecturas recurrentes.
- Generación de texto con estrategias de Greedy Search y Beam Search (determinístico y estocástico).
- Análisis del efecto de la temperatura en la generación de secuencias.

**Objetivo:**  
Desarrollar un modelo generativo de texto y entender el impacto de distintas arquitecturas y estrategias de inferencia.

---

## 📕 Desafío 4 – LSTM Bot QA (Conversational AI)

**Archivo:** `Desafio_4CSalinas.ipynb`

**Resumen:**  
Se construye un modelo basado en LSTM para tareas de **pregunta-respuesta (QA)** utilizando datos del challenge **ConvAI2**.

- Preprocesamiento de datos de conversación.
- Construcción de diccionarios de vocabulario para encoder y decoder.
- Entrenamiento de un modelo encoder-decoder con embeddings y LSTM.
- Preparación de datos para entrenar el modelo de chatbot.

**Objetivo:**  
Crear un modelo secuencia a secuencia (seq2seq) capaz de responder preguntas con una arquitectura tipo chatbot.
