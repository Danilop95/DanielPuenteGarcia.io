
<h1 align="center">
  <br>
  <a href="http://www.amitmerchant.com/electron-markdownify"><img src="https://avatars.githubusercontent.com/u/61589509?s=200&v=4" alt="Markdownify" width="200"></a>
  <br>
  Curriculum Daniel Puente García
  <br>
</h1>

<h4 align="center">Programa para pedir vacaciones utilizado en <a href="https://buendiatours.com/es?gclid=Cj0KCQjwuaiXBhCCARIsAKZLt3lRG_r8Ew3BLJN8HEGF7XeUnjfhgxyj14q2gXMABIqemR7e04swMdAaAguzEALw_wcB" target="_blank">Buendía Tours</a>.</h4>


## Como importar estos datos

Configuración servidor correo: app/timeoff-management/config/app.json

Base de datos: app/timeoff-management/db.development.sqlite

Apariencia : app/timeoff-management/views/partials/header.hbs

> **Note**
> Para este proceso necesitas poder usar el terminal de el contenedor, recomiendo cargar una copia de el contenedor en tu Docker desktop, ya que en Synology, docker no deja.

```bash
 # Clona este repositorio 
 $ git clone https://github.com/Danilop95/BackupVacacionesBuendia.git

 # Entra en la carpeta que se ha descargado  
 $ cd BackupVacacionesBuendia/

 # Mover configuración correo 
 $ mv app.json /app/timeoff-management/config/
 # Mover base de datos
 $ mv db.development.sqlite  /app/timeoff-management/
 # Mover apariencia
 $ mv header.hbs /app/timeoff-management/views/partials/

