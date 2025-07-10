# 🎵 Clasificación de Instrumentos Musicales con CNN y PyTorch

Este proyecto busca entrenar una red neuronal convolucional (CNN) utilizando PyTorch para reconocer instrumentos musicales a partir de espectrogramas generados desde archivos de audio. Es parte de un proceso de aprendizaje práctico en redes neuronales, procesamiento de audio y visión por computadora.

## 🧠 ¿Qué hace este notebook?

- Verifica la disponibilidad de GPU (CUDA)
- Trabaja con un dataset personalizado de espectrogramas de audio
- Carga imágenes como tensores para entrenamiento con PyTorch
- Diseña, entrena y evalúa una red convolucional para clasificación

## 📁 Estructura del proyecto

- `Cnn-isntrument-recognition.ipynb`: notebook principal con todo el pipeline del modelo.
- `/dataset_espectros/`: carpeta (local) donde se almacenan los espectrogramas generados previamente.
- `model.pth`: archivo esperado para guardar el modelo entrenado (no generado aún).
- `outputs/`: (opcional) carpeta sugerida para guardar predicciones, métricas o gráficos.

## ⚙️ Tecnologías utilizadas

- Python 3.x
- PyTorch
- torchvision, torchaudio
- NumPy, Matplotlib
- Jupyter Notebook

## 🎯 Objetivos del proyecto

- Entrenar una CNN simple con imágenes de espectrogramas como entrada
- Evaluar su desempeño en la clasificación de instrumentos musicales
- Aprender a manejar datasets de imágenes creados manualmente a partir de audio

## 🚀 Posibles mejoras

- Automatizar la generación de espectrogramas desde `.wav` usando `torchaudio` o `librosa`
- Implementar augmentación de datos (cambios de brillo, rotación, ruido)
- Aplicar técnicas de regularización y validación cruzada
- Usar modelos preentrenados (como ResNet o EfficientNet)

## 🧪 Estado actual

Este es un proyecto **en desarrollo y exploración**. El foco está puesto en consolidar conocimientos de deep learning aplicado a audio y visión computacional.

## 👨‍💻 Autor

**Mariano Franco**  
[GitHub](https://github.com/mfranco75)

---

💡 *"Este proyecto es parte de mi formación práctica en inteligencia artificial aplicada a datos de audio. Todo feedback es bienvenido."*
