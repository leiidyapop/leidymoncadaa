<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8"  />
    <title>Hola soy Leidy Moncada</title>
    <link rel="icon" type=imagen/ico href="imagenes/favicon.ico" />
    <link href="https://fonts.googleapis.com/css?family=Fjalla+One|Source+Sans+Pro" rel="stylesheet">
    <!----<link rel="stylesheet" href="css/media.css" media="screen and (max-width:768px)"/>-->
    <link rel="stylesheet" href="css/estilos.css">
    <!----<style>
      @media screen and (max-width: 768px) {
        body {
          border: 10px solid blue;
        }
      }
    </style>-->
  <meta name="viewport" content="width=device-width, initial-scale=1">
  </head>
  <body> 
    <header class="header">
      <div class="container">
        <figure class="logo">
          <img src="imagenes/logo.png" height="50" alt="Logo de http://leonidasesteban.com" />
        </figure>
        <nav class="menu">
        <ol>
          <li>
            <a class="link" href="#portafolio">Portafolio</a>
          </li>
          <li>
            <a class="link" href="#eventos">Experiencia</a>
          </li>
          <li>
            <a class="link" href="#contacto">Trabajemos juntos</a>
          </li>
        </ol>
      </nav>
    </div>
  </header>
  <section class="hero">
    <div class="container">
      <h1>
        Hola! Soy <strong>Leidy Moncada</strong> <br/>desarrollador <strong>web</strong> con<br> pasión por la <strong>lectura</strong>
      </h1>
      <img class="hero-imagen" src="imagenes/hero.png" width="500" height="300" alt="imagen principal del sitio">
    </div>
  </section>
  <section id="Portafolio" class="portfolio">
    <div class="container">
        <h2>Portafolio (Proyectos Destacados)</h2>
        <article class="project">
          <div class="project-details">
          <h3 class="project-title">Platzi video</h3>
          <h6 class="project-course">React Navite / React</h6>
          <p class="project-date"><small><strong>Fecha:</strong> 01/07/2018</small></p>
          <p class="project-url"><small><strong>Puedes verlo en:</strong> www.platzi.com/native</small></p>
          <p class="project-description">Platzi Video fue el resultado de 3 meses de trabajo 
            para crear la mejor app para enseñar el funcionamiento 
            de react y React Native. Desde crear un vista-detalle, hasta patrones avanzados de nevegación, este proyecto ha sido el ejemplo de futuros creadores de aplicaciones multiplataforma.</p>
        </div>
        <figure class="project-imageContainer">
          <img class="project-image" width="500" src="imagenes/platzi-video-react-native.png" alt="proyecto del curso de React Native">
        </figure>
        </article>
          <article class="project">
          <div class="project-details">
          <h3 class="project-title">Platzi video</h3>
          <h6 class="project-course">React Navite / React</h6>
          <p class="project-date"><small><strong>Fecha:</strong> 01/07/2018</small></p>
          <p class="project-url"><small><strong>Puedes verlo en:</strong> www.platzi.com/native</small></p>
          <p class="project-description">Platzi Video fue el resultado de 3 meses de trabajo 
            para crear la mejor app para enseñar el funcionamiento 
            de react y React Native. Desde crear un vista-detalle, hasta patrones avanzados de nevegación, este proyecto ha sido el ejemplo de futuros creadores de aplicaciones multiplataforma.</p>
        </div>
        <figure class="project-imageContainer">
          <img class="project-image" width="500" src="imagenes/platzi-video-react-native.png" alt="proyecto del curso de React Native">
        </figure>
      </article>
    </div>

</section>
<div class="container">
  <h2 class="event-list-title">Más sobre mi experiencia</h2>
</div>
<section id="eventos" class="event-list">
  <div class="container">
      <article class="event">
          <figure class="event-imageContainer">
            <img class="event-image" src="imagenes/platziconf.png" width="500"/>
          </figure>
          <div class="event-detail">
              <h3 class="event-title"> PlatziConf México 2018</h3>
              <p class="event-description">El evento más grande sobre gente que quiere aprender más de internet. En este evento te comparto como tener una vida de constante aprendizaje</p>
              <a class="event-url" href="https://www.youtube.com/watch?v=BIS7cWGgJg0" target="_blank">Ver plática</a>
          </div>     
      </article>
      <article class="event">
          <figure class="event-imageContainer">
            <img class="event-image" src="imagenes/platziconf.png" width="500"/>
          </figure>
          <div class="event-detail">
              <h3 class="event-title"> PlatziConf México 2018</h3>
              <p class="event-description">El evento más grande sobre gente que quiere aprender más de internet. En este evento te comparto como tener una vida de constante aprendizaje</p>
              <a class="event-url" href="https://www.youtube.com/watch?v=BIS7cWGgJg0" target="_blank">Ver plática</a>
          </div>     
      </article>
      <article class="event">
          <figure class="event-imageContainer">
            <img class="event-image" src="imagenes/platziconf.png" width="500"/>
          </figure>
          <div class="event-detail">
              <h3 class="event-title"> PlatziConf México 2018</h3>
              <p class="event-description">El evento más grande sobre gente que quiere aprender más de internet. En este evento te comparto como tener una vida de constante aprendizaje</p>
              <a class="event-url" href="https://www.youtube.com/watch?v=BIS7cWGgJg0" target="_blank">Ver plática</a>
          </div>     
      </article>
      <article class="event">
          <figure class="event-imageContainer">
            <img class="event-image" src="imagenes/platziconf.png" width="500"/>
          </figure>
          <div class="event-detail">
              <h3 class="event-title"> PlatziConf México 2018</h3>
              <p class="event-description">El evento más grande sobre gente que quiere aprender más de internet. En este evento te comparto como tener una vida de constante aprendizaje</p>
              <a class="event-url" href="https://www.youtube.com/watch?v=BIS7cWGgJg0" target="_blank">Ver plática</a>
          </div>     
      </article>
  </div>
    
  </section>
  <section id="contacto" class="contact">
    <div class="container">
        <form action="/suscripcion/" class="form-email">
          <h3>¿Creamos algo juntos?</h3>
          <input type="text" placeholder="Déjame tu email" id="email">
          <button>Enviar</button>
        </form>
        <div class="social">
          <a href="https://twitter.com/laleidy_" class="social-link twitter"></a>
          <a href="https://facebook.com/leiidyapop" class="social-link facebook"></a>
          <a href="https://github.com/leonidasesteban" class="social-link github"></a>
          <a href="https://instagram.com/leiidyamoncada" class="social-link instagram"></a>
        </div>
  </div>
  </section>
    <footer class="footer">
      <div class="container">
        <div>
          <p>Curso de Desarrollo web online 2018 <img src="imagenes/platzi.png" width="80" alt="platzi"></p>
          </div>
          <div>
            <p>
              Designed with <3> by <a href="https://twitter.com/thespianartist">@thespianartist</a>
            </p>
          </div>
      </div>
      
    </footer>
  </body>
</html>


