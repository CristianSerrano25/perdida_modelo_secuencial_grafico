# Predicción con TensorFlow.js

Este proyecto implementa un modelo de regresión lineal simple utilizando
TensorFlow.js. La aplicación permite:

- Entrenar un modelo de regresión en el navegador
- Visualizar la pérdida (loss) durante el entrenamiento
- Predecir múltiples valores simultáneamente

## Características

- **Entrenamiento del modelo**: Entrena un modelo de regresión utilizando
  TensorFlow.js directamente en el navegador.
- **Visualización de pérdida**: Gráfica interactiva que muestra cómo el error
  disminuye durante el entrenamiento.
- **Predicción múltiple**: Permite ingresar varios valores separados por comas
  para obtener predicciones simultáneas.
- **Interfaz sencilla**: Diseño limpio y fácil de usar.

## Requisitos

No se requiere instalación de dependencias extras ya que todas las bibliotecas
se cargan desde CDNs:

- TensorFlow.js
- Plotly.js

## Cómo ejecutar

1. Instala la extensión "Live Server" en Visual Studio Code
2. Abre el archivo `index.html` en VS Code
3. Haz clic derecho sobre el archivo y selecciona "Open with Live Server"
4. La aplicación se abrirá automáticamente en tu navegador predeterminado

## Uso de la aplicación

1. Abre la aplicación en tu navegador
2. Haz clic en el botón "Entrenar Modelo" para entrenar la red neuronal
3. Observa cómo disminuye la pérdida en la gráfica durante el entrenamiento
4. Ingresa los valores para predecir en el campo de texto (separados por comas)
5. Haz clic en el botón "Predecir" para obtener los resultados
