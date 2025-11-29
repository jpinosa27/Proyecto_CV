# Modelo de Reconocimiento de Herramientas

Este repositorio contiene un modelo de reconocimiento de imágenes
entrenado para clasificar herramientas (por ejemplo: candado, llave, destornillador)
usando **TensorFlow** y **MobileNetV2** en Google Colab.

## Contenido
ModeloReconocimiento.ipynb  
  Notebook de Google Colab con todo el flujo:
  - Carga de datos desde Google Drive
  - Creación de datasets de entrenamiento y validación
  - Definición del modelo con Transfer Learning (MobileNetV2)
  - Entrenamiento y evaluación
  - Pruebas con imágenes nuevas

### Docuementos de referencia
  -https://www.tensorflow.org/?hl=es-419
  -https://www.tensorflow.org/api_docs/python/tf/keras/applications/MobileNetV2
  -https://roboflow.com/model/mobilenet-v2-classification#:~:text=MobileNetV2%20es%20un%20modelo%20de%20clasificaci%C3%B3n%20(distinto,de%20ImageNet%20a%20tu%20conjunto%20de%20datos.
