# Programación Web - Evaluación 1

Estudiante: Vexayng Verenzuela

## Paso 1: Crear repositorio

El primer paso es crear un repositorio público en Github, en este caso, con el nombre de "proweb_Verenzuela".
![Screenshot_969](https://github.com/user-attachments/assets/db966809-c357-4303-859b-27fb98b76a44)

## Paso 2: Crear carpeta del proyecto

Ahora ceamos la carpeta con el nombre "proweb_Verenzuela", está será la carpeta donde se alojará el proyecto.
Posteriormente abriremos esta carpeta con la terminal Git Bash, esto dando click derecho sobre ella y seleccionando "Open Git Bash here".
![Screenshot_973](https://github.com/user-attachments/assets/32f1ee42-ae9c-406e-8a69-7529553e8e54)

## Paso 3: Inicializamos git en el proyecto

Usamos el comando **$ git init** para indicarle a git que haga seguimiento a esta carpeta. Esto creará una carpeta .git oculta.
![Screenshot_974](https://github.com/user-attachments/assets/b0340245-f93a-4a21-b1a1-7d47b1d544dd)

## Paso 4: Configurar usuario

Sincronizamos nuestro usuario para poder trabajar con la plataforma Github, esto lo hacemos por medio de los comandos
**$ git config --global user.name "Nombre_de_usuario"** y **$ git config --global user.email "email_de_usuario"**
![Screenshot_987](https://github.com/user-attachments/assets/b914192b-ed11-4f7a-9596-146b39cdcd79)

## Paso 5: Preparar Primer commit

Para poder crear las ramas (Branch) primero debemos realizar un commit, para esto, creamos un archivo cualquiera en la carpeta "proweb_Verenzuela", en este caso, un "index.html".
Ahora, usaremos el comando **$git status** para ver el estado actual del directorio, esto nos muestra qué archivos existen en el directorio, a cuales se les está haciendo seguimiento, y cuales no tienen seguimiento. Como vemos, el archivo "index.html" no está siendo respaldado por git, por tanto, usaremos el comando **$ git add nombre_archivo** para comenzar a hacerle seguimiento.

![Screenshot_978](https://github.com/user-attachments/assets/8b83d650-cfb5-45e5-ac03-b1cb861ca0ad)

## Paso 6: Realizar Primer commit

Ahora realizaremos el primer commit, utilizando el comando **$ git commit**.
Esto nos abrirá nuestro editor de código para que insertemos el mensaje de commit.

![Screenshot_979](https://github.com/user-attachments/assets/cd936781-fbe4-4401-a89e-d9479673ab1f)

Escribimos el mensaje, en este caso "primer commit", y cerramos el archivo para que la terminal detecte el mensaje y realice el commit.

![Screenshot_981](https://github.com/user-attachments/assets/d569a19a-4a55-45b7-b721-936bb6d4852c)

Y con esto, el commit se habrá realizado con exito. Podemos verificarlo usando de nuevo el comando **$ git status**

![Screenshot_983](https://github.com/user-attachments/assets/645bdd6c-b9c0-4ea4-abb0-952d6bdffc65)

## Paso 7: Creación de Branchs (Ramas)

Al realizar el primer commit, automaticamente se crea la Rama principal master (Equivalente a Main).
Podemos verificar que ramas existen en nuestro repositorio por medio del comando **$ git branch**

![Screenshot_984](https://github.com/user-attachments/assets/d6a2ff26-4db5-47b0-bbd6-74414b761d65)

Podemos crear nuevas ramas utlizando el comando **$ git branch nombre_rama**
De este modo, crearemos las ramas "develop" y "staging".

![Screenshot_985](https://github.com/user-attachments/assets/28b62f2e-6175-480a-ba78-81bb4bcaf4ea)

## Paso 8: Sincronizar con Github

Ahora debemos sincronizar el repositorio local con el repositorio en línea de GitHub.
Esto lo haremos por medio del comando **$ git remote add origin link_repositorio**

![Screenshot_986](https://github.com/user-attachments/assets/3d18e1c8-0c0b-4c61-8405-72e00ecf1af7)

## Paso 9: Subir rama master (Push master)

Ahora subiremos la rama master al repositorio de github por medio del comando **$ git push -u origin master**

![Screenshot_988](https://github.com/user-attachments/assets/ede6307b-4f12-4f1d-ab4f-7399fcd750f7)

Y con esto, nuestra rama principal se encontrará subida al Github.

![Screenshot_989](https://github.com/user-attachments/assets/8cc2ccf0-12d2-409c-8905-2e26e1b7e0af)

## Paso 10: Subir ramas develop y staging

Por último, debemos subir las ramas secundarias "develop" y "staging" al repositorio GitHub.
Para ello, utilizaremos el comando **$ git swicth nombre_rama** para cambiar a la rama secundaria a subir, y luego utilizando el comando **$ git push -u origin nombre_rama**

### Rama develop
![Screenshot_990](https://github.com/user-attachments/assets/d6ef6c39-e50e-4b8b-bb4b-e0fbcfe78c93)

### Rama Staging
![Screenshot_991](https://github.com/user-attachments/assets/a374b64a-cb0a-49dd-b97f-86ce1e0c5937)

## Paso 11: Verificar Github

Ahora verificaremos si el push de las ramas secundarias se realizó correctamente, para esto iremos al repositorio Github y seleccionaremos este botón.
![Screenshot_994](https://github.com/user-attachments/assets/7e5c2d21-8558-47d8-975d-f77f3e89ae77)

Y con esto habremos finalizado la creación del repositorio con los requerimientos específicados en la evaluación.

Una vez seleccionado, nos mostrará las ramas existentes en el repositorio.
![Screenshot_993](https://github.com/user-attachments/assets/627d727a-65cd-4fd1-b188-44179d3fbc1d)
