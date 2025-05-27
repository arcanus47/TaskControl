# 🤖 Asistente Virtual con ChatGPT (OpenAI API)

Este es un **asistente virtual por voz** desarrollado en Python que combina el poder de la **API de ChatGPT (OpenAI)** con reconocimiento y síntesis de voz para ofrecer una experiencia interactiva fluida y natural.

---

## 🧠 ¿Qué hace?

- 🎤 Escucha tu voz usando `speech_recognition`
- 🧠 Envía tu pregunta a la API de ChatGPT
- 💬 Te responde en voz alta usando `pyttsx3`
- 🕒 Espera y repite el ciclo automáticamente

---

## 🛠 Tecnologías y Librerías

- [`openai`](https://pypi.org/project/openai/) – conexión con ChatGPT
- [`speech_recognition`](https://pypi.org/project/SpeechRecognition/) – convierte voz a texto
- [`pyttsx3`](https://pypi.org/project/pyttsx3/) – convierte texto a voz
- `time` – para pausas entre ciclos

---

## 📦 Requisitos

Antes de ejecutar el asistente, instala las dependencias necesarias:

```bash
pip install openai speechrecognition pyttsx3

