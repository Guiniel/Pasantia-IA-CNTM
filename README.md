# Pasantia-IA-CNTM
Este repositorio contiene el codigo referente a la pasantia realizada para la carrera de ingenieria informatica en la Universidad Catolica Andres Bello. El mismo consiste en una primera aproximacion al uso de inteligencia artificial para aproximar tiempos en tareas de desarrollo de software

## Contenido
Este proyecto actualmente contiene 3 archivos de jupyter notebook los cuales se detallan a continuacion

- Pasantia.ipynb: Es el archivo principal en el cual se realiza todo lo relacionado a preprocesamiento de datos, modelado y entrenamiento. Abarca el entrenamiento de 6 modelos y su respectivo guardado. Se presentan metricas y graficas que muestran visualmente los resultados para cada modelo
- cargarModelos.ipynb: Este cuaderno se encarga de cargar un archivo que contenga los valores para poder realizar la prediccion. Genera un excel con los valores predichos
- word2vec: Este es un cuaderno ajeno a los otros 2 el cual busca estimar en base a requerimientos en texto usando procesamiento de lenguaje humano. Esta basado en un metodo llamado Software Effort Estimation Embedding Model [1]
## Como Ejecutar
Este proyecto fue desarrollado en google colab, esta pensado para trabajar con un conjunto de datos especifico por lo que si se desea aplicar para otro conjunto, se debera modificar el codigo. Ahora si, para ejecutar se debe abrir los cuadernos en google colab y ajustar las rutas a las correspondientes en su ambiente de desarrollo. A continuacion se dejan los pasos mas detallados:

1. Descargar los 3 cuadernos de jupyter notebook y cargarlos en el ambiente de google colab, el proceso para realizar esto es como con cualquier cualquier software para editar codigo 
2. Se debe sustituir las rutas de los archivos. Para poder leer los csv y tambien guardar algunos datos, se deben especificar rutas correspondientes. Si no se hace, todo archivo se guardara en la carpeta del proyecto la cual, al ser un ambiente en linea, es volatil. Es recomendable tener todo guardado en drive. Para montar el drive es muy sencillo, en la barra de la izquierda al abrir un archivo veremos varios iconos(indice, llave, una equis, etc). Uno de esos iconos sera una carpeta, nuestra carpeta de trabajo y al hacer click en ella, se nos mostraran 4 iconos y uno de ellos sera una carpeta con el icono de drive. Simplemente se hace click en el icono y se siguen los pasos de conexion con drive. Ya despues de haber montado el drive, pues se sustituyen todas las rutas por las necesarias, en cada archivo hay ejemplos de como se verian las rutas
3. Para el archivo de pasantia.ipynb se debe cargar el archivo .csv con el cual se realiza el entrenamiento, dicho archivo se llama dataset.csv y esta a disposicion en el github. Se guarda en drive y se coloca su direccion en la linea correspondiente
4. Para el archivo cargarModelos.ipynb se debe cargar el archivo Evaluacion.csv, el cual tiene unos datos de prueba para hacer la prediccion.
5. Ya en este punto, es posible correr cualquier archivo. Primero se corre el archivo Pasantia para entrenar y guardar cada modelo y luego el archivo cargarModelos para poder usarlos. Para ejecutar todas las celdas del cuaderno, se puede acceder a traves de la platea de comandos o simplemente presionando ctrl + f9
6. Al ejecutar el archivo cargarModelos con cualquiera de los modelos, se genera la prediccion para el modelo elegido en un excel donde se puede ver claramente todos los valores

## Referencias
[1] M. De Bortoli, D. Casanova, A. Pimentel. (2020). SE3M: A Model for Software Effort Estimation Using Pre-trained Embedding Models
