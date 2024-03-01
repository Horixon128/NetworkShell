<a name="readme-top"></a>



<div align="center">

<img src="Wolf.png" alt="Wolf" width="140" height="auto" style="border-radius:50%"   />
<br/>
<h3><b>Blog de Documentación GIT </b>

</div>

# ✅ TABLE OF CONTENTS
- [📖 Blog de Documentación](#acerca-del-proyecto)
- [🚩​ Documentation](#Git-Comandos)
  - [⚒️ Codigo ](#Codigo-Fuente)
    - [Stack de Tecnologia](#tech-stack)
    - [shell Features](#shell-features)
 - [🚀 Live Demo](#live-demo)
 - [💻 Getting Started](#getting-started)
   - [Setup](#setup)
   -  [Prerequisites](#prerequisites)
   - [Install](#install)
   - [Usage](#usage)
   - [Run tests](#run-tests)
   - [Deployment](#deployment)
- [👥 Authors](#authors)
- [🕹️ Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐ Show your Support](#support)
- [👏 Acknowledgements ](#ackknowledgements)
- [❓ FAQ ](#faq)
- [📃 License](#license)

# 📖 [Blog de Documentación]<a name="acerca-del-proyecto"></a>

**[Blog de Documentación]** En la siguiente documentación se explica el uso de GIT y SHELL por comando.

## ⚒️ Codigo <a name="Codigo-Fuente"></a>

<p>
Este proyecto utilizo los siguientes lenguajes:
HTML, MARKDOWN AND SHELLSCRIPT, GIT, GITHUB
</p>

### Stack de Tecnologia <a name="tech-stack"></a>

<li> HTML </li>
<li> MARKDOWN </li>
<li> SHELLSCRIPT </li>
<li> GIT </li>
<li> GITHUB </li>

<details>
<summary> Client </summary>
    <ul>
    <li><a href="https://developer.mozilla.org/es/docs/Web/HTML">HTML</a></li>    
    </ul>
</details>

<details>
<summary>Markdown</summary>
<ul>
<li><a href="https://markdown.es/sintaxis-markdown/">Markdown</a></li>
</ul>
</details>


### shell Features <a name="shell-features"></a>
<li> Prueba de Conectividad <li>
<li> Mostrar Configuracion de Red <li>
<li> Tabla de enrutamiento <li>
<li> resolucion de nombres DNS <li>
<li> revisar puertos de la maquina <li>
<li> test de velocidad <li>


<p align="right"><a href="#readme-top">Back to top</a></p>


### [DOCUMENTATION]<a name="Documentación"></a>

<li><b> 1: ¿Que es Git remote ?</b></li>

##

    | Git remote add origin: es un comando de Git utilizado para agregar un nuevo repositorio remoto al que se puede enviar o obtener cambios de un repositorio local.

## 
    | Git remote add upstream url: estás estableciendo una conexión con el repositorio original de desarrollo, lo que te permite recibir actualizaciones y mejoras desde allí. 

## 
    | Git remote set-url Repo_name Nueva_url: Este comando se utiliza para cambiar la dirección URL de un repositorio remoto existente.
## 
 
    | Git remote rename origin mi-repo-url: Este comando se utiliza para cambiar el nombre de un repositorio remoto existente. Puedes cambiar el nombre de "origin" o "upstream
 ## 
    | Git remote rm origin: Este comando se utiliza para eliminar un repositorio remoto existente de tu configuración local
 ## 
    | Git remote show origin: Este comando muestra información detallada sobre los repositorios remotos configurados en tu proyecto actual
 ##

<li><b> 2: ¿Que es Git Bash y GitHub?:</b></li> 

##
    | Git Bash es una herramienta que permite interactuar con Git desde una interfaz de línea de comandos, similar a la de GNU/Linux. Se utiliza para ejecutar comandos de Git. GitHub es una plataforma en la nube que facilita el almacenamiento, colaboración y gestión de proyectos de código abierto o privados utilizando Git. En resumen, Git Bash es una herramienta que ayuda a trabajar con Git, mientras que GitHub es una plataforma donde se almacena y compartiendo el código controlado por Git.
##

<li><b> 3: ¿Que es Git init:</b></li>

##
    | Git Init: es un comando en Git que inicializa un repositorio en una carpeta existente o crea uno nuevo
##
<li><b> 4: ¿Que es Git Clone:</b></li>

    | Git Clone: Clona un repositorio existente en tu computadora. Proporciona la URL del repositorio y el directorio de destino donde se clonará. Esto crea una copia local del repositorio en la carpeta especificada
##
<li><b> 5: ¿Que es Git add:</b></li>

    | Git add: Añade archivos o cambios a la preparación para un commit. Puedes agregar un archivo individual, un directorio o todos los archivos modificados. 
##
<li><b> 6: ¿Que es Git commit:</b></li>

    | Git commit: Confirma los cambios agregados en una preparación. Proporciona un mensaje de commit descriptivo que explica los cambios realizados.
##
<li><b> 7: ¿Que es Git push: </b></li>

    | Git push: Envía los cambios confirmados (commits) desde tu repositorio local hasta el repositorio remoto.
##
<li><b> 8: ¿Que es Git :</b></li>

    | Git Clone: Clona un repositorio existente en tu computadora. Proporciona la URL del repositorio y el directorio de destino donde se clonará. Esto crea una copia local del repositorio en la carpeta especificada
##
<li><b> 9: ¿Que es Git Code .:</b></li>

    | Code.: Es un comando que permite abrir o enlazar un archivo con visual studio
## 
<li><b> 10: ¿Que es Git reset:</b></li>

    | Git Reset: Permite revertir cambios locales, mover el puntero de la rama o deshacer commits.
##
    | Git reset --soft HEAD~1: Revertir los ultimos cambios 
##
    | Git reset HEAD <>: Deshace los cambios no confirmados de un archivo en el working directory. 
## 
    | Git reset --hard commit_id: Rehace todo desde el commit especificado, borrando cambios no confirmados y modificaciones en el working directory y el área de stage.
##
    | Git revert commit_id: es un comando de Git que se utiliza para crear un nuevo commit que contiene cambios inversos a un commit específico. Este comando permite corregir errores o comportamientos indeseables en el historial de commits

<li><b> 11: ¿Que es Git Log: </b></li>

    | Git Log: Muestra la historia de commits del repositorio.
##
    | Git Log --oneline: Muestra la historia de commits en formato one-line, con cada commit mostrado en una sola línea.

##
    | Git Log --s: Muestra la historia de commits con una breve descripción estadística de cambios en cada commit.

<li><b> 12: ¿Que es Git Checkout y Git Branch?: </b></li>


    | Git Checkout :Permite cambiar entre diferentes ramas que fueron creadas de manera remota y tambien Permite cambiar entre diferentes versiones de archivos en el working directory.
##
    | Git Checkout -b <branch_name> : permite crear o generar una nueva rama en el repositorio remoto
##
    | Git Checkout <branch_name>: permite intercambiarse entre ramas de un repositorio externo
##
    | Git Checkout <branch_name>: permite intercambiarse entre ramas de un repositorio externo


<img src="./Capturas/UsuarioEmail.png" alt="remote" width="auto" height="auto" style="border-radius:10%"   />

     | Para utilizar 
    
## 💻 Getting Started <a name="getting-started"></a>


To get a local copy up and running follow these steps:

### Prerequsites 

To run this project you need the following tools:

- [VS Code]
- [Git and GitHub]
- [ShellScript ]

### Setup

Clone this respository  to your desired folder:

```sh
cd NEWTORK-SCRIPT
git clone https://github.com/alyconr/Network-Shell-Script-.git
```
### Install

Install This project with:

```sh
    ./networkScript.sh
```

### Usage 

To run the project, execute the following command:

```sh
./networkScript.sh
```

### Run Test

To run test, run the following command or endpoint:

```sh
python -m unittest test_module.TestClass
```


### Deployment

Deploy using your local enviroment

<p align="right"><a href="#readme-top">Back to top</a></p>

## 👥 Authors <a name="authors"></a>

Jeysson Contreras

🧑🏻‍💻 **Author 1**

 - GitHub: [@alyconr](https://github.com/alyconr)
 - LinkedIn: [LinkedIn](https://www.linkedin.com/in/jeysson-aly-contreras)


## 🕹️ Future Features <a name="future-features"></a>

- [ ] **[Ping]**
- [ ] **[Nslookup]**
- [ ] **[BandWitdth Test]**


## 🤝 Contributing <a name="contributing"></a>


Contributions, issues, and  feature requests are welcome!

Feel free tp check the [issues page](https://github.com/alyconr/Network-Shell-Script-/issues)


## ⭐ Show your Support

Wrrite a message to encourage readers to support your project

If you like this project please give one start

## 👏 Acknowledgements <a name="acknowledgements"></a>

I would like to thank my learning teammates  and Sena Instructor

## 📃 License <a name="license"></a>

This Project is [MIT](./LICENSE.md) licensed

<p align="right"><a href="#readme-top">Back to top</a></p>















