### Paso 1:
Descargar o clonar el proyecto.

### Paso 2:
Crear un entorno virtual => `python -m venv nombre_entorno`

### Paso 3:
Activar el entorno virtual <br>
En windows => `source nombre_entorno/Scripts/activate` <br>
En linux => `source nombre_entorno/bin/activate`

### Paso 4:
Instalar todas las dependencias necesarias para el proyecto a través de => `pip install -r requirements.txt`

### Paso 5:
Crear una carpeta llamada modelos_entrenados en el que guardar los modelos. 
Acceder a la carpeta `cd ./modelos/`
Ejecutar al completo el Notebook RandomForest.ipynb para entrenar al modelo que se usará en Streamlit.
Volver a la carpeta raiz `cd ..`

### Paso 6:
Acceder a la carpeta del proyecto: `cd ./machine_learning/`s

### Paso 7:
Instalar las dependencias para el cliente web: `pip install -r requirements.txt`

### Paso 8:
Iniciar el servidor de streamlit:  `streamlit run "machine_learning\app.py"`

> [!WARNING]  
> En el paso 8 la ruta especificada es la ruta relativa, de no funcionar es necesario especificar la ruta completa al archivo.
> En visual estudio lo puedes hacer con click derecho sobre el archivo y copiar ruta.

> [!NOTE]  
> Se recomienda utilizar una consola gitbash para el correcto funcionamiendo de la configuración del entorno virtual de python.
> 
