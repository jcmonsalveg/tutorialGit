# Tutorial inicial de GIT & GitHub

Git es un sistema de control de versiones ampliamente usado en el mundo del desarrollo de software :computer: fue ideado por ***Linus Torvals*** :man: (Si... el mismo creador de Linux). Nos permite mantener un historial completo de versiones de nuestro software, identificando los grandes cambios realizados a un proyecto, permitiéndonos navegar por diferentes ramas a la hora de desarrollar nuestros proyectos. Pudiendo volver en cualquier momento a cualquier versión anterior o creando nuevas ramas de un proyecto para probar nuevas funcionalidades, mejoras, etc.  

## Instalar GIT en el pc
Para instalar GIT es necesario acudir al sitio web de la aplicación: https://git-scm.com/downloads desde allí descargar la versión acorde a tu sistema operativo, una vez se cuenta con el archivo en el PC se proceder a instalar.

## Trabajo básico con GIT
- git init    // Inicia un repositorio en el directorio actual
- git add   . // Agrega los archivos al index o Staging area.
- git commit -m "xxxxxx" // Nos permite agregar todos los archivos al head, listos para subir a github. Reemplaza las xxxx por un comentario sobre ese commit. Por ejemplo: "se corrigió el registro de usuarios".
- git remote add origin xxx //  Remplaza las xxx por la URL de tu repositorio en GitHub, solo se realiza una vez en cada proyecto, para vincular el repo local con el repo remoto.
- git push origin master // Sube todos los archivos de la rama master

## Crear un repositorio en GitHub
- Una vez registrado en GitHub das clic en Nuevo repositorio
- Tomas la URL del repo y vuelves a git para agregarla


