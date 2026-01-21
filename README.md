# 🤖 Chatbot con Deep Learning (TensorFlow & NLP)

Este proyecto es un **chatbot inteligente desarrollado con Deep Learning**, utilizando **TensorFlow, Keras y técnicas de Procesamiento de Lenguaje Natural (NLP)**.  
El modelo es capaz de reconocer intenciones, responder de forma automática y mostrar el nivel de confianza de cada predicción.

---

## 🚀 Características principales

- 🧠 Modelo de Deep Learning entrenado con TensorFlow
- 🗣️ Procesamiento de lenguaje natural con NLTK
- 📊 Visualización de métricas con Matplotlib y Seaborn
- 🔎 Sistema de confianza en las respuestas
- ❓ Manejo de preguntas no reconocidas (fallback)
- 🖥️ Interacción directa por consola

---

## 🛠️ Tecnologías utilizadas

- Python 3.12
- TensorFlow 2.19
- Keras
- NLTK
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📦 Instalación de dependencias

```bash
pip install tensorflow nltk matplotlib seaborn scikit-learn
Descargar recursos de NLTK:

python
Copiar código
import nltk
nltk.download('punkt')
▶️ Ejecución del proyecto
bash
Copiar código
python chatbot.py
Al iniciar, verás algo como:

bash
Copiar código
✅ Modelo Deep Learning entrenado
🤖 Chatbot Deep Learning
Escribe 'salir' para terminar
💬 Ejemplo de conversación
makefile
Copiar código
Tú: hola
🤖: Hola 👋 ¿en qué puedo ayudarte?
🔎 Confianza del modelo: 1.00
makefile
Copiar código
Tú: mi nombre es darwin
🤖: No estoy seguro de entenderte 🤔
🔎 Confianza del modelo: 0.57
🧠 ¿Cómo funciona?
El texto ingresado se tokeniza y limpia con NLP

Se transforma en vectores numéricos

El modelo neuronal predice la intención

Se selecciona la mejor respuesta según la probabilidad

Si la confianza es baja, se muestra una respuesta genérica

📈 Posibles mejoras futuras
Agregar más intents y frases de entrenamiento

Implementar embeddings (Word2Vec / BERT)

Integración con interfaz web (Flask / FastAPI)

Persistencia de conversaciones

Uso de modelos Transformers

👨‍💻 Autor
Darwin Manuel Ovalles Cesar
Estudiante de Administración, Desarrollo de Software y Ciberseguridad
Apasionado por la Inteligencia Artificial y el Deep Learning 🚀

📜 Licencia
Este proyecto es de uso educativo y experimental.

markdown
Copiar código
