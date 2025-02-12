# Análisis y visualización de datos con Python
# 1. Instalación e inicio con Anaconda

## 1.a Instalación de Anaconda

Anaconda es una distribución de software libre y de código abierto diseñada para gestionar paquetes y dependencias en Python. Contiene más de 1,500 paquetes relacionados con ciencia de datos, ingeniería y análisis, siendo ampliamente utilizado en la comunidad de ciencia de datos para administrar y compartir entornos de desarrollo y proyectos. Además, proporciona herramientas para la gestión eficiente de entornos virtuales, permitiendo a los usuarios trabajar con diferentes versiones de paquetes y dependencias sin afectar otros proyectos.

### Pasos para la instalación de Anaconda:

1. Descargar el instalador de Anaconda desde el sitio web oficial (https://www.anaconda.com/products/distribution), seleccionando la versión compatible con su sistema operativo.
2. Ejecutar el instalador descargado y seguir las instrucciones en pantalla.
3. Verificar la instalación 
	a. Abriendo el navegador de Anaconda y asegurándose de que se haya iniciado correctamente.
	b. Desde terminal con el comando `conda list`, la presencia de una lista de paquetes indicará una instalación exitosa.
4. Mantener actualizado Anaconda
	a. Desde el navegador de Anaconda utilizando la opción de actualización
	b. Desde la terminal con el comando `conda update conda`.

Nota: En caso de problemas durante la instalación, consultar la documentación oficial de Anaconda para obtener asistencia adicional.

## 1.b Entornos (environments)

Un entorno de Anaconda proporciona un espacio separado en el sistema que permite gestionar diferentes versiones de paquetes de Python de forma independiente. Esto evita conflictos entre proyectos, garantizando resultados consistentes y reproducibles.

Python esta en constante desarrollo, por lo que es recomendable usar una versión estable. En enero de 2025 esta es Python 3.12.

### Creación de un entorno de Anaconda:

#### Desde la terminal:

1. Abrir una terminal o línea de comandos.
2. Utilizar el comando `conda create --name nombre_del_entorno` para crear un nuevo entorno, sustituyendo "nombre_del_entorno" por el nombre deseado.
3. Confirmar la creación cuando se solicite.
4. Activar el entorno con `conda activate nombre_del_entorno`.
5. Verificar la activación con `conda info` en la terminal.

#### Con el navegador de Anaconda:

1. Abrir el navegador de Anaconda.
2. Hacer clic en "Environments" en la barra lateral.
3. Seleccionar "Create" y proporcionar nombre y versión de Python para el nuevo entorno.
4. Confirmar la creación y verificar la selección en "Environments".

## 1.c Instalación de Librerías

Las librerías de Python son conjuntos de módulos preescritos que facilitan tareas específicas. La instalación de librerías se puede realizar tanto desde la terminal como desde el navegador de Anaconda.

Para este curso se recomiendan inicialmente las librerias: `pandas openpyxl ydata_profiling unidecode numpy matplotlib seaborn`.

### Instalación desde la terminal:

1. Abrir la terminal o línea de comandos.
2. Utilizar el comando `conda install nombre_de_libreria` para instalar la librería deseada.
3. Seguir las instrucciones en pantalla para completar la instalación.

Una alternativa para la instalacción de librerias es utilizar `pip`.

### Instalación desde el navegador Anaconda Navigator:

1. Abrir Anaconda Navigator.
2. Navegar a "Environments" en la barra lateral.
3. Seleccionar el entorno deseado.
4. Hacer clic en "Not Installed" y buscar la librería.
5. Aplicar la instalación y seguir las instrucciones en pantalla.

En ambos casos, es posible que sea necesario actualizar Anaconda o el entorno antes de instalar nuevas librerías.

## 1.d Sobre la Documentación

Al trabajar con funciones específicas en Python, es común encontrarse con opciones y parámetros que pueden variar. En caso de dudas, se recomienda buscar información en recursos como la [documentación oficial de pandas](https://pandas.pydata.org/pandas-docs/stable/), [StackOverflow](https://stackoverflow.com/), o utilizar [ChatGPT](https://chat.openai.com/chat). Recuerde googlear antes de preguntar y verificar la validez de las respuestas, especialmente en el caso de líneas de código, evitando traducirlas automáticamente.

## 1.e Google Colab

Google Colab (https://colab.research.google.com/) es una plataforma en línea que permite crear, ejecutar, almacenar y compartir programas en Python. Es un servicio gratuito de Jupyter Notebook. Para utilizar Google Colab, solo se necesita un navegador y una cuenta de Google. Sin embargo, los recursos de computo son limitados, sobretodo en la versión gratuita. Además de que no es recomendable usarlo con conjuntos de datos sensibles. 

## 1.f Github

GitHub (https://github.com/) es una plataforma en línea que permite a los desarrolladores crear, compartir y colaborar en proyectos de software. 
GitHub se basa en Git, un sistema de control de versiones que registra los cambios en los archivos. 

* Permite almacenar, supervisar y trabajar con proyectos de software
* Facilita el intercambio de archivos de código
* Permite trabajar en proyectos colaborativos de código abierto
* Permite crear repositorios de Git 

GitHub también cuenta con una herramienta de inteligencia artificial llamada GitHub Copilot, que sugiere y autocompleta el código escrito.


## Script de ejemplo

```
conda create --name myenv python=3.12

conda activate myenv
conda install pip -y
pip install -r requirements.txt
pip install jupyterlab numpy pandas openpyxl 
pip install unidecode thefuzz[speedup] ydata-profiling
pip install matplotlib seaborn

```