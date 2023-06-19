# Laboratorio: Introducción al uso de Git localmente y publicación en GitHub
## Introducción
En este laboratorio, aprenderemos los conceptos básicos del sistema de control de versiones Git y cómo utilizarlo localmente en tu máquina. Además, exploraremos cómo publicar un repositorio Git en GitHub, una plataforma popular para alojar proyectos de código abierto y colaborar con otros desarrolladores.

## Objetivos
Al finalizar este laboratorio, serás capaz de:

- Comprender los conceptos básicos de Git y su flujo de trabajo.
- Configurar Git en tu máquina local.
- Iniciar un repositorio Git localmente.
- Realizar cambios, crear commits y administrar el historial de versiones.
- Publicar un repositorio local en GitHub.
- Requisitos previos
- Antes de comenzar este laboratorio, asegúrate de tener instalado Git en tu máquina local. Puedes descargar la última versión de Git desde https://git-scm.com/downloads y seguir las instrucciones de instalación para tu sistema operativo.

## Paso 1: Configuración inicial
Antes de comenzar a utilizar Git, es importante configurar tu nombre de usuario y dirección de correo electrónico. Estos datos se utilizarán para identificar los cambios que realices en los repositorios.

Abre una terminal o línea de comandos en tu máquina.

Ejecuta los siguientes comandos, reemplazando "Tu Nombre" y "tu@email.com" con tus propios datos:

```
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
git config --list --show-origin
```
## Paso 2: Inicializar un repositorio local
Ahora que hemos configurado Git, vamos a crear un repositorio local y comenzar a realizar cambios en él.

Crea una carpeta en tu máquina donde deseas almacenar tu repositorio. Puedes llamarlo "mi-repositorio" o cualquier otro nombre relevante.

Abre una terminal o línea de comandos y navega hasta la ubicación de la carpeta que acabas de crear.

Ejecuta el siguiente comando para inicializar un nuevo repositorio Git:

```
git init
```
Esto creará un nuevo repositorio vacío en la carpeta seleccionada.

## Paso 3: Realizar cambios y crear commits
Ahora que hemos inicializado un repositorio, podemos comenzar a realizar cambios en nuestros archivos y guardarlos como commits en la historia del repositorio.

Crea un archivo llamado archivo.txt dentro de la carpeta del repositorio.

Abre archivo.txt en tu editor de texto preferido y agrega algún contenido.

Vuelve a la terminal o línea de comandos y ejecuta el siguiente comando para ver el estado actual del repositorio:

```
git status
```

Esto mostrará los archivos modificados en tu repositorio.

Agrega archivo.txt al área de preparación ejecutando el siguiente comando:

```
git add archivo.txt
```
Esto prepara el archivo para ser incluido en el siguiente commit.

Crea un commit con los cambios realizados ejecutando el siguiente comando:

```
git commit -m "Agregado archivo.txt con contenido inicial"
```
Asegúrate de proporcionar un mensaje descriptivo para el commit.

## Paso 4: Publicar el repositorio en GitHub
Hasta este punto, hemos trabajado localmente con nuestro repositorio. Ahora, vamos a aprender cómo publicar el repositorio en GitHub y sincronizar los cambios realizados.

Abre tu navegador web y ve a https://github.com.

Inicia sesión en tu cuenta de GitHub o crea una cuenta nueva si aún no tienes una.

Haz clic en el botón `"New"` (Nuevo) para crear un nuevo repositorio en GitHub.

Proporciona un nombre para tu repositorio y, opcionalmente, una descripción.

Haz clic en el botón `"Create repository"` (Crear repositorio) para crear el repositorio en GitHub.

En la siguiente página, verás las instrucciones para conectar tu repositorio local con el repositorio remoto en GitHub. Sigue las instrucciones bajo la sección `"…or push an existing repository from the command line"` (…o sube un repositorio existente desde la línea de comandos).

En tu terminal o línea de comandos, ejecuta los comandos proporcionados en la página de GitHub. Esto vinculará tu repositorio local con el repositorio remoto en GitHub.

Una vez que hayas ejecutado los comandos, actualiza la página de GitHub y verás los archivos y commits que has realizado en tu repositorio local.

¡Listo! Has creado tu laboratorio de introducción al uso de Git localmente y has publicado tu repositorio en GitHub.

Conclusión
En este laboratorio, hemos aprendido los conceptos básicos de Git y cómo utilizarlo localmente en nuestra máquina. También hemos explorado cómo publicar un repositorio en GitHub y sincronizar los cambios entre nuestro repositorio local y el remoto.

Git es una herramienta poderosa para el control de versiones y el trabajo colaborativo. Te animamos a explorar más a fondo los comandos y características de Git para aprovechar al máximo esta tecnología en tus proyectos futuros.