# Heroku PHP

Aplicación web básica para publicar en Heroku.

Pasos para crear y publicar un sitio nuevo:

1. Crear una cuenta en [Heroku](https://www.heroku.com).
1. Instalar [Heroku Toolbelt](https://toolbelt.heroku.com/).
1. Clonar este repositorio y colocar en la carpeta [web](./web/) el contenido a publicar.
1. Iniciar sesión:

  ```bash
  $ heroku login
  ```
  Nos pedirá el usuario y contraseña de Heroku. Si tenemos habilitada la autenticación en dos pasos, tendremos que introducir también el token temporal.
  
1. Crear la aplicación:

  ```bash
  $ heroku create
  ```
  Esto nos da una URL para la nueva aplicación, a través de la cual podemos ver el sitio web. Por ejemplo, este repositorio está publicado en [https://limitless-river-47823.herokuapp.com](https://limitless-river-47823.herokuapp.com/).
  
1. Utilizando Git, creamos un *commit* con los cambios.
1. Publicamos el proyecto:

  ```bash
  $ git push heroku local
  ```

Cuando hagamos modificaciones, basta con volver a confirmar los cambios y repetir la publicación.
