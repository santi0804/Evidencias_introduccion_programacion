<!-- No borrar o modificar -->

[Inicio](./index.md)

## Sesión 8

### Actividad: Aplicando estilos con selectores CSS

<br>
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado <header>
- Tres párrafos <p>
- Una imagen <img>
- Un pie de página <footer>

Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"

Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"

Aplica los siguientes estilos usando seleccionadores descendientes:

- Color gris a los párrafos dentro de un <div>
- Centrar el contenido de la sección <section>

# Solucion

<br>

```

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>ACTIVIDAD SESION 8 CSS"</title>
    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <div .text-color>
      <h1>Robert Oppenheimer</h1>
      <h2>HISTORIA</h2>
    </div>
    <br />

    <div>

      <div class="destacado">
        <p>
        J. Robert Oppenheimera​ (Nueva York, 22 de abril de 1904-Princeton,
        Nueva Jersey; 18 de febrero de 1967) fue un físico teórico</div>
        estadounidense y profesor de física en la Universidad de California en
        Berkeley. Es una de las personas a menudo nombradas como «padre de la
        bomba atómica» debido a su destacada participación en el Proyecto
        Manhattan, el proyecto que consiguió desarrollar las primeras armas
        nucleares de la historia, durante la Segunda Guerra Mundial. La primera
        bomba nuclear fue detonada el 16 de julio de 1945 en la Prueba Trinity,
        en Nuevo México, Estados Unidos. Oppenheimer declararía más tarde que le
        vinieron a la mente las palabras del Bhagavad-gītā: «Ahora me he
        convertido en la muerte, el destructor de mundos».4​b​ Oppenheimer
        siempre expresó su pesar por el fallecimiento de víctimas inocentes
        cuando las bombas nucleares fueron lanzadas contra los japoneses en
        Hiroshima y Nagasaki en agosto de 1945.
      </p>
      <br />

      <p>
        Después de la guerra ocupó el cargo de asesor jefe en la recién creada
        Comisión de Energía Atómica de Estados Unidos y utilizó su posición para
        abogar por el control internacional del poder nuclear, evitar la
        proliferación de armamento nuclear y frenar la carrera armamentística
        entre Estados Unidos y la Unión Soviética. Después de provocar la ira de
        numerosos políticos por sus opiniones públicas se le acabaron retirando
        sus pases de seguridad, perdiendo el acceso a los documentos militares
        secretos de su país, y se le acabó despojando de su influencia política
        directa durante una muy publicitada audiencia en 1954. En esa década
        Estados Unidos vivía en el macartismo y todas aquellas personas
        sospechosas de simpatizar con el comunismo o simplemente de ser
        disidentes fueron perseguidas por el gobierno; Oppenheimer pudo
        continuar escribiendo, trabajando en física y dando conferencias. Nueve
        años después de la audiencia, los presidentes John F. Kennedy y Lyndon
        B. Johnson le concedieron y otorgaron respectivamente el Premio Enrico
        Fermi como un gesto de rehabilitación de su figura.
      <div id="principal">Datos Curiosos</div>
      </p>
      <div class="grande">Uno de los hombres mas importantes de la historia</div>
      <br/>
      <h3>¿Que es el Proyecto Manhattan?</h3>
      <p>
        Con el estallido de la Segunda Guerra Mundial y la creciente
        preocupación sobre el avance de la investigación nuclear en Alemania, el
        gobierno de los Estados Unidos inició el Proyecto Manhattan en 1939.
        Este proyecto tenía como objetivo desarrollar una bomba atómica antes de
        que lo hicieran los nazis. En 1942, Oppenheimer fue seleccionado para
        liderar el laboratorio de Los Álamos en Nuevo México, donde se llevó a
        cabo gran parte del trabajo crucial en el desarrollo de la bomba. Bajo
        su dirección, se reunieron algunos de los mejores científicos del mundo,
        y el proyecto avanzó a un ritmo asombroso.
        </p>
      </div>
    </div>
    <br>

    <img src="img/img-1.jfif" height="200">
  </body>
  <section>
  <div id="contenedor">
    <p>Posiciones políticas
      Durante la década de 1920, Oppenheimer se mantuvo alejado de los acontecimientos del mundo. En algún momento afirmó no haberse enterado de la crisis financiera de 1929 hasta más tarde (Oppenheimer en lo personal no tenía muchas preocupaciones financieras debido a su herencia familiar). Fue solamente al relacionarse con Jean Tatlock, hija de un profesor de literatura de Berkeley, en 1936, cuando se interesó en la política. Al igual que muchos intelectuales de la década de 1930 apoyó las ideas comunistas y, gracias a su capital heredado (más de 300.000 dólares, cantidad enorme en la época), podía financiar muchos esfuerzos políticos de izquierda. La mayoría de estos aportes estuvieron dedicados a financiar recolecciones de fondos a favor de los republicanos en la guerra civil española y otras actividades antifascistas. Nunca se inscribió oficialmente en el Partido Comunista de los Estados Unidos (su hermano Frank sí lo hizo, en contra de la opinión de Robert), aunque historiadores como Gregg Herken afirman haber encontrado evidencias de que Oppenheimer tuvo relaciones con el partido comunista en las décadas de 1930 y 1940. En noviembre de 1940, se casó con Katherine Puening Harrison, una estudiante "radical" de Berkeley, y en mayo de 1941 tuvieron a Peter, su primer hijo.</p>
    <p>Trinity

      Oppenheimer bautizó la primera prueba nuclear como Trinity.
      El trabajo colectivo de los científicos en Los Álamos tuvo su primer éxito en la primera explosión nuclear cerca del pueblo de Alamogordo (Nuevo México) el día 16 de julio de 1945. Oppenheimer bautizó la prueba como Trinity (Trinidad); más tarde explicó que se basó en un verso del poeta John Donne (1572-1631). Según el historiador Gregg Herken, es posible que este nombre aludiera a Jean Tatlock, quien le dio a conocer la obra de Donne cuando eran pareja en los años 1930. Tatlock se había suicidado solo unos meses antes, para consternación de Oppenheimer. Después recordó que mientras presenciaba la explosión, pensó en un verso de un texto hindú, el Bhagavad-Guitá:</p>

    </section>

</div>
  <footer .mi-id>
    <div class="container">
      <div class="row">
        <div class="col-md-6">
        <div class="col-md-6">
          <div id="sombras">
          <h3>Contacto.</h3>
          <p>Dirección:  Bello - Antioquia.</p>
          <p>Teléfono: (+57) 3242013436</p>
          <p>Email: santama.1988@gmail.com</p></div>
        </div>
      </div>
    </div>
  </footer>
</html>

```

```

h1 {
    color: red;
  }
  h2 {
    color: red;
  }
  h3 {
    color: red;
  }
  div {
    text-align: center;
    font-size: 20px;
  }

  .mi-id {
    color: greenyellow;
  }

  p {
    color: rgb(98, 169, 226);
  }
  body {
    background-color: white;
  }

  .text-color {
    color: black;
    text-align: center;
  }
  img {
    border: solid 10px; 10px;
    display: block;
    margin-left: auto;
    margin-right: auto;
  }
  .destacado {
    color: green;
    background-color: green;
  }
  .grande {
    font-size: 50px;
}
#principal {
    background-color: yellow;
}
#sombras {
    box-shadow: 4px 4px 4px rgba(0, 0, 0, 0.4);
}
#contenedor p {
    color: grey;
}
section {
    text-align: center;
    margin: 0 auto;
}

```
