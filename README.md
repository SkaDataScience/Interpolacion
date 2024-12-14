# Interpolación de Datos con Métodos Avanzados

Este repositorio contiene el código fuente desarrollado para un proyecto de interpolación de datos mediante técnicas avanzadas de aprendizaje automático y series temporales. El objetivo principal es reconstruir datos faltantes y generar nuevas estimaciones utilizando modelos como redes neuronales, GANs (Generative Adversarial Networks) y otros enfoques relacionados.

## Características principales del proyecto

Preprocesamiento de datos: Escalado, transformación y preparación de series temporales.

**Implementación de métodos de interpolación:**

Redes neuronales con LSTM (Long Short-Term Memory).

Redes Generativas Antagónicas (GANs).

Ventanas deslizantes para la generación de subconjuntos de entrenamiento.

** Evaluación del rendimiento:**

Métricas como Mean Squared Error (MSE), Mean Absolute Error (MAE) y coeficiente R2.

Visualización: Comparación entre los datos originales, reconstruidos y generados.

**Contenido del repositorio**

Código fuente: Implementado en Python, incluye todas las etapas desde el preprocesamiento hasta la evaluación y visualización de resultados.

Documentación: Descripción de los pasos seguidos para replicar el proyecto y los modelos implementados.

## Datos

Por razones de confidencialidad, los datos utilizados en este proyecto no se encuentran incluidos en el repositorio. Sin embargo, el código está diseñado para trabajar con series temporales escaladas y formateadas según las especificaciones indicadas en la documentación.

## Requisitos

Python: 3.8 o superior.

**Bibliotecas principales:**

pandas

numpy

matplotlib

sklearn

torch

## Ejecución del proyecto

**Clone este repositorio en su máquina local:**

git clone https://github.com/SkaDataScience/Interpolacion.git

**Instale los requisitos:**

pip install -r requirements.txt (en caso de necesitar ejecutarlo en GitHub)

Prepare el dataset siguiendo las instrucciones en la documentación.

Ejecute los notebooks o scripts según el flujo de trabajo descrito en el archivo principal del proyecto.

## Metodología

Preparación de datos: Se escalan las series temporales y se generan subconjuntos de entrenamiento mediante ventanas deslizantes.

**Diseño de modelos:**

Creación de redes neuronales con LSTM.

Definición de arquitecturas GAN para la interpolación de datos.

**Entrenamiento y evaluación:**

Uso de funciones de pérdida como BCE y MSE.

Validación del rendimiento con métricas como MSE, MAE y R2.

Visualización de resultados: Gráficos de comparación entre datos reales y generados.


## Licencia

Este proyecto está bajo una licencia de uso restringido. Consulte el archivo LICENSE para más detalles.

## Autor

Luis Alberto Baca Guerrero
Universidad San Francisco de Quito
Máster en Ciencia de Datos