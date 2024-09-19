# Práctica 8

1. ¿Cómo se inicializa un repositorio en Git?
    - Se inicializa escribiendo el comando escrito abajo en una terminal git bash ya que tienes la carpeta con la que quieres iniciar el repositorio abierta.
    ```bash
    git init
    ```

1. ¿Cómo creas un repositorio en GitHub?
    - Tienes que estar en la página de GitHub, después te vas a la sección de repositorios y das click en el boton de "NEW", le pones el nombre y lo configuras como lo quieras y le pones en crear.

1. ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?
    - Tienes que tener un repositorio de GitHub ya creado, en tu repositorio local te tienes que ir a la terminal y escribir los siguientes comandos:
    ```bash
    git remote add origin URL_del_repositorio_de_GitHub
    ```
    ```bash
    git branch -M main
    ```
    ```bash
    git push -u origin main
    ```
    Tu repositorio local ya debe de estar inicializado Git.

1. ¿Cuál es el flujo básico de trabajo en Git y GitHub?
    - Abres o clonas la carpeta de tu repositorio
    - Modificas lo que tengas que  hacer
    - Agregas los cambios con el siguiente comando:
    ```bash
    git add .
    ```
    - Ya que se agregaron los cambios haces el commit con este comando:
    ```bash
    git commit -m "Mensaje diciendo que cambios estas subiendo"
    ``` 
    - Ya que realizas el commit tienes que hacer el push con el siguiente comando:
    ```bash
    git push
    ```

1. ¿Para qué sirve el archivo .gitignore?
    - Sirve para ignorar los archivos que pongas dentro de él.

1. ¿Cuál es el propósito de una rama?
    - Te ayuda a facilitar el trabajo en equipo, ya que cada integrante del equipo puede trabajar en ramas diferentes para que de esta forma no se altere lo que estan haciendon tus compañeros.
    - También las ramas pueden servir para hacer cambios o pruebas ya que lo que hagas en las ramas no afecta la rama "main" a menos que hagas una fusión.

1. ¿Qué es una fusión?
    - La fusión junta 2 ramas, se realiza situandote en la rama a la que le juntaras la otra rama y escribes en la terminal este comando:
    ```bash
    git merge Nombre_de_la_rama
    ```

1. Explica los diferentes tipos de fusión que existen.
    - El primero es una fusión automatica, esto significa que la fusión se hace sin ningun problema el cual tengas que resolver.
    - La segunda es una forma manual ya que al hacer la fusión hay problemas de contenido que esta encimado, por lo que tienes que corregir esto manualmente.

1. ¿Cómo puedes ver el historial de tu repositorio?
    - Para ver el historial en la terminal de tu repositorio local tienes que escribir el siguiente comando:
    ```bash
    git log
    ```
    - Este comando te da todo el historial del repositorio incluyendo todos los datos como el autor o la fecha.

1. ¿Cuál es el propósito de una etiqueta?
    - Las etiquetas sirven para ayudar a marcar distintas secciones en tu repositorio, como por ejemplo para diferenciar versiones.
