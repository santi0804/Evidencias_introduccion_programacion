# Actividad: Creando mi primer sitio web

Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

* Index o página de inicio
*  Acerca
*  Contacto

<br>
<br>

## Index.
<br>


```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>PROYECTO FTP</title>
    <link rel="stylesheet" href="style.css" />
   </head>

   <body>
    <header>
      <h1 class="texto">PROYECTO FTP</h1>
    </header>

    <a href="Acerca.html"> Acerca de nosotros</a>
    <a href="Contacto.html"> Nuestro  Contacto</ a>

     <main>
      <p class="pa">
        CONSORCIO FTP, la mejor línea comercial diversificada en inmuebles,
        transporte alimentos entretenimiento y mas. Trabajamos constantemente en
        la vida de nuestros profesionales es nuestro mayor valor. No negociamos
        la Seguridad y Salud en el Trabajo y no la comprometemos con fines de
        lucro o producción. Contamos con estrictos estándares para garantizar
        condiciones de trabajo seguras y saludables, eliminando peligros y
        mitigando riesgos en nuestras operaciones. Garantizamos canales de
        comunicación e iniciativas para la participación y consulta de nuestros
        profesionales, convirtiéndolos en parte integral e indispensable de
        nuestro negocio.
       </p>
      </main>

       <img src="imagenes/img-1.png"

     <footer>Santiago Tamayo Pérez santama.1988@gmail.com Cel.3242013436</footer>
    </body>
</html>

```



## Acerca de.
<br>


```

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ACERCA DE NOSOTROS</title>
</head>

<body>
  <nav>
    <a href="index.html"> Inicio</a>
    <a href="Contacto.html"> Nuestro Contacto</a>
  </nav>


  <section>

    <h2> HISTORIA </h2>
    <p>
      Este proyecto inicia en la ciudad de Medellín-Colombia Julio 07 del año 2016, con el fin de hacer líneas
      comerciales enfocadas en la diversidad de mercados, iniciando con pequeños locales de papelerías y un esquema muy
      completo en la variedad de los servicios implementados de primera mano haciaEl público. Otro departamento fuerte
      en nuestro consorcio seria la línea de supermercados en modalidad de autoservicio. También contamos con línea de
      licoreras, discotecas y transportadora de vehículos pesados a nivel nacional.

    </p>


    <article>
      <h3> MISIÓN </h3>
      ><br>
      Nuestra misión como consorcio es generar Y ejecutar proyectos de alto nivel y complejidad, garantizando la calidad de nuestros productos y servicios, con un enfoque en el cumplimiento de los requisitos legales y demás requisitos aplicables, buscando siempre la satisfacción del cliente y de la comunidad. Con la competencia técnica de nuestros profesionales y el liderazgo activo, promovemos un entorno que fomenta y reconoce la innovación y la mejora continua de procesos.

      <h3> VISIÓN </h3>

       Nuestro papel es dejar un legado socioambiental en todas las regiones donde operamos, siendo un agente transformador comprometido con el desarrollo socioeconómico. Buscamos la perpetuación del negocio; pero, sobre todo del medio ambiente, incluyendo iniciativas para combatir la contaminación, el uso sostenible de los recursos y el derecho a la vida para las generaciones futuras, y la expanción comercial de esta compañia.

    </article>
  </section>

  <footer>
    <p> Copyright - Santiago Tamayo Pérez</p>
  </footer>

</body>

</html>

```

## Contacto.
<br>


```

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CONTACTO</title>
  </head>
  <body>
    <header>
      <h1> CONTACTO</h1>
    </header>

    <a href="index.html"> Inicio</a>
    <a href="Acerca.html"> Acerca de nosotros </a>

      <main> 
        ><form>
          <label for="nombre"> Nombre: </label>
          <input type="text" id="nombre"><br> 
          
          <label for = "email"> Email: </label>
          <input type="email" id="email"><br> 

          <label for="mensaje"> Mensaje: </label><br>
          <textarea id="mensaje"></textarea><br> 

          <input type="submit" value="enviar">

        </form>
        ><aside>

          <h3> Ubicación</h3>

          <div class="mapa"><iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3966.5076846089273!2d-75.558908!3d6.1965478!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8e46829a7cc89143%3A0xa1407845e42e3835!2sCentro%20Comercial%20El%20Tesoro%2C%20El%20Poblado%2C%20Medell%C3%ADn%2C%20El%20Poblado%2C%20Medell%C3%ADn%2C%20Antioquia!5e0!3m2!1ses-419!2sco!4v1692035416997!5m2!1ses-419!2sco" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
          </div><br>

          <p>  Medellín - Colombia - C.C el Tesoro</p>
        </aside>
      </main>
      
      <footer>  
        <p> Copyright - Santiago Tamayo Pérez / 14 agosto </p>
      </footer>
  </body>
</html>

 ```


```
Style

.texto {

   font-style: italic;
   font-weight: 700;
   
}
.pa{

font-style: inherit;
color: rgb(0, 0, 0);
font-weight: 300;

}
 
 ```


