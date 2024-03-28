# Pasantia-IA-CNTM
Este repositorio contiene el codigo referente a la pasantia realizada para la carrera de ingenieria informatica en la Universidad Catolica Andres Bello. El mismo consiste en una primera aproximacion al uso de inteligencia artificial para aproximar tiempos en tareas de desarrollo de software

## Como Ejecutar 
Este proyecto fue desarrollado en google colab, esta pensado para trabajar con un conjunto de datos especifico por lo que si se desea aplicar para otro conjunto, se debera modificar el codigo. Ahora si, para ejecutar se debe abrir los cuadernos en google colab y ajustar las rutas a las correspondientes en su ambiente de desarrollo

## Contenido
Este proyecto actualmente contiene 3 archivos de jupyter notebook los cuales se detallan a continuacion

- Pasantia.ipynb: Es el archivo principal en el cual se realiza todo lo relacionado a preprocesamiento de datos, modelado y entrenamiento. Abarca el entrenamiento de 6 modelos y su respectivo guardado. Se presentan metricas y graficas que muestran visualmente los resultados para cada modelo
- cargarModelos.ipynb: Este cuaderno se encarga de cargar un archivo que contenga los valores para poder realizar la prediccion. Genera un excel con los valores predichos
- word2vec: Este es un cuaderno ajeno a los otros 2 el cual busca estimar en base a requerimientos en texto usando procesamiento de lenguaje humano. Esta basado en un metodo llamado Software Effort Estimation Embedding Model [1]

## Referencias
[1] M. De Bortoli, D. Casanova, A. Pimentel. (2020). SE3M: A Model for Software Effort Estimation Using Pre-trained Embedding Models
