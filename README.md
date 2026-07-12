# 🧠 Clasificador de Dígitos Manuscritos con CNN

Red neuronal convolucional entrenada sobre el dataset MNIST alcanzando 99% de accuracy. Incluye interfaz interactiva con Gradio donde el usuario dibuja un número y obtiene la predicción en tiempo real.

## 🏗️ Arquitectura
- Capas Conv2D + MaxPooling para extracción de features
- Capa densa final con activación Softmax

## 📊 Resultados
- **Accuracy:** 99% en conjunto de test
- **Dataset:** MNIST (70.000 imágenes de dígitos manuscritos)
- **Interfaz:** Gradio 5.x con Sketchpad interactivo

## 🛠️ Stack
`Python` `TensorFlow` `Keras` `Gradio` `Google Colab`
