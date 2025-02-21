<div align="center">
  <img src="https://github.com/jserranom27/Good-Seed-Verificaci-n-de-Edad-con-visi-n-artificial./blob/main/Flux_Dev_Genera_una_imagen_digital_impactante_y_sofisticada_qu_1.jpeg" alt="Banner del Proyecto" width="100%">
</div>

# Proyecto de Ciencia de Datos: [**Good Seed – Verificación de Edad con visión artificial**](https://github.com/jserranom27/Good-Seed-Verificaci-n-de-Edad-con-visi-n-artificial./blob/main/vision_para_good_seed.ipynb) 🍇

## Descripción
Good Seed, una cadena de supermercados, busca explorar cómo la ciencia de datos puede ayudar a cumplir las normativas de venta de alcohol, asegurándose de que solo se venda a personas mayores de edad. Este proyecto se centra en construir y evaluar un modelo de visión artificial que, a partir de fotografías capturadas en el área de pago, determine la edad de los clientes. La solución utiliza un conjunto de imágenes faciales y sus etiquetas para entrenar un modelo basado en ResNet50 preentrenado, ajustado para predecir la edad mediante una tarea de regresión.

## Tecnologías Utilizadas
- **Python** ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
- **TensorFlow** ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
- **Pandas** ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
- **Keras** ![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
- **ImageDataGenerator**
- **ResNet50** ![ResNet50](https://img.shields.io/badge/ResNet50-4285F4?style=for-the-badge&logo=google&logoColor=white)

## Análisis del Proyecto
1. **Verificación de la Integridad del Dataset:**  
   Se comprobó que todas las imágenes y etiquetas están presentes en el directorio, garantizando la integridad de los datos.

2. **Preparación y Preprocesamiento de Imágenes:**  
   Se utilizó `ImageDataGenerator` para escalar y normalizar las imágenes, permitiendo un flujo eficiente de datos mediante `flow_from_dataframe` sin necesidad de organizar las imágenes en subcarpetas.

3. **Entrenamiento y Evaluación del Modelo:**  
   Se implementó un modelo de visión artificial basado en ResNet50, adaptado para realizar una tarea de regresión que predice la edad. El modelo fue entrenado en una plataforma GPU, obteniendo resultados consistentes y precisos en la verificación de la edad.

## Imágenes del Análisis
### 1. **Distribución de Edades en el Dataset:**  
Histograma que muestra la diversidad de edades en el conjunto de datos.
![Distribución de Edades](https://github.com/jserranom27/Good-Seed-Verificaci-n-de-Edad-con-visi-n-artificial./blob/main/good_seed%20distribucion%20de%20edades%20en%20el%20conjunto%20de%20datos.png)

### 2. **Muestras de Imágenes con Etiquetas:**  
Ejemplos aleatorios del dataset, cada imagen acompañada de su etiqueta de edad.
![Muestras de Imágenes](https://github.com/jserranom27/Good-Seed-Verificaci-n-de-Edad-con-visi-n-artificial./blob/main/good_seed%20ramdon%20de%2010%20imagenes%20para%20verificacion%20de%20conjunto%202.png)

## Conclusiones
El proyecto demuestra la viabilidad de aplicar técnicas de visión artificial para verificar la edad, asegurando el cumplimiento de las normativas de venta de alcohol. La solución, basada en transfer learning con ResNet50, ofrece una herramienta robusta para identificar de manera precisa a clientes elegibles, garantizando transacciones seguras en entornos comerciales.

## Próximos Pasos
- Refinar el modelo para mejorar la precisión en la predicción de la edad.
- Explorar técnicas de data augmentation para aumentar la diversidad del dataset.
- Integrar la solución en el flujo operativo del supermercado para pruebas en tiempo real.
