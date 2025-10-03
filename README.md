# audio-to-text-conversion

## Transcripción y Diarización de Audio Segura y Offline, Optimizada para CPU con Python y Open Source

[![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Este proyecto es una prueba de concepto de un sistema de transcripción de voz a texto con diarización básica de hablantes, diseñado para operar de forma **totalmente offline** y **optimizado para sistemas basados en CPU**. Desarrollado con Python y librerías open source, este script aborda la crítica necesidad de procesar información sensible de audio sin comprometer la privacidad ni depender de servicios en la nube o hardware especializado (GPUs).

Fue concebido como una demostración clave para equipos de seguridad empresarial, asegurando la confidencialidad de los datos del cliente y sentando las bases para futuros proyectos de análisis de texto (text mining) en conversaciones de atención al cliente.

---

### ✨ Características Principales

*   **Operación 100% Offline:** Garantiza la máxima privacidad y seguridad al no enviar datos de audio a servicios externos.
*   **Optimizado para CPU:** Diseñado para funcionar eficientemente en hardware estándar, sin requerir GPUs costosas.
*   **Transcripción de Audio:** Convierte conversaciones habladas en texto legible.
*   **Diarización Básica de Hablantes:** Identifica y etiqueta los segmentos de texto de hasta dos interlocutores ("Persona_01", "Persona_02").
*   **Basado en Open Source:** Utiliza librerías de Python ampliamente reconocidas y mantenidas.
*   **Conversión MP3 a WAV:** Incluye un preprocesamiento robusto para manejar diversos formatos de audio.
*   **Preparado para Análisis:** La salida estructurada facilita la integración con pipelines de NLP y text mining.

---

### 🚀 Tecnologías Utilizadas

*   **Python 3.x**
*   [`openai-whisper`](https://github.com/openai/whisper): Modelo de vanguardia para transcripción de voz a texto.
*   [`librosa`](https://librosa.org/): Herramienta para el análisis de audio y extracción de características.
*   [`pydub`](https://github.com/jiaaro/pydub): Para la manipulación y conversión de formatos de audio.
*   [`numpy`](https://numpy.org/): Soporte para operaciones numéricas eficientes.
*   [`scikit-learn`](https://scikit-learn.org/): Utilizado para algoritmos de clustering en la diarización.
*   `argparse`: Para la gestión de argumentos de línea de comandos.

---

### ⚙️ Instalación

Sigue estos pasos para configurar y ejecutar el proyecto en tu entorno local:

1.  **Clonar el repositorio:**
    ```bash
    git clone https://github.com/tu_usuario/audio-to-text-conversion.git
    cd audio-to-text-conversion
    ```
    *(Asegúrate de reemplazar `tu_usuario` con tu nombre de usuario de GitHub real)*

2.  **Crear y activar un entorno virtual (recomendado):**
    ```bash
    python -m venv venv
    # En Linux/macOS:
    source venv/bin/activate
    # En Windows:
    .\venv\Scripts\activate
    ```

3.  **Instalar las dependencias:**
    ```bash
    pip install -r requirements.txt
    ```

---


