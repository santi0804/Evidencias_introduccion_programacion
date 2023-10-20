<!-- No borrar o modificar -->

[Inicio](./index.md)

## Sesión 11

# Actividad: Propiedades CSS, SeudoClases, SeudoElementos y Reglas @css

<br>

Crear un documento HTML y probar cada uno de los ejemplos de la sesión 11

```

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <input type="color" value="#de2020" />
    <link rel="stylesheet" href="Style.css" />
    <p>Suscribete a este canal</p>
    <button class="joinBtn">Subscribe</button>
    <p>Paginas visitar:</p>
    <ul>
      <li>
        <a href="https://developer.mozilla.org">MDN Web Docs</a>
      </li>
      <li>
        <a href="https://www.youtube.com/YouTube">Google</a>
      </li>
    </ul>
    <p>Historial de pagina:</p>
    <ul>
      <li>
        <a href="https://developer.mozilla.org/missing-3">Random MDN page</a>
      </li>
      <li>
        <a href="https://example.com/missing-3">Random Example page</a>
      </li>
      <p>
        Nikola Tesla (Smiljan, actual Croacia, 1856 - Nueva York, 1943) Físico
        estadounidense de origen serbio. Estudió en las universidades de Graz
        (Austria) y Praga. Después de haber trabajado en varias industrias
        eléctricas en París y en Budapest, se trasladó a Estados Unidos (1884),
        donde trabajó a las órdenes de Thomas A. Edison, entonces partidario de
        la corriente eléctrica continua
      </p>
    </ul>
    <textarea></textarea>
    <table border="1">
      <p>:-moz-arrastrar-sobre</p>
      <tr>
        <td width="100px" height="100px">Clia aqui para arrastrar</td>
      </tr>
    </table>
    <div></div>
    <p>
      Cuando el usuario visite el enlace por primera vez, tendrá un fondo rojo.
      Cuando el usuario haga clic en el enlace, tendrá un fondo verde.
    </p>
    <a href="#">Enlace</a>
    <p>
      Ejemplos Este ejemplo altera la apariencia del fondo de un cuadro
      dependiendo de si su ventana está activa o no.
    </p>
    <div id="mybox">
      <p>CAJA</p>
    </div>
    <p>EJEMPLO</p>

    <input type="range" min="0" max="100" step="5" value="50" />
    <div>
      <video src="video/168787 (1080p).mp4" controls></video>
      <video controls preload="metadata">
        <source src="video/star_-_6962 (540p).mp4" type="video/mp4" />
        <source src="video.webm" type="video/webm" />
        <track
          label="English"
          kind="subtitles"
          srclang="en"
          src="subtitles.vtt"
          default
        />
      </video>
    </div>
  </head>

  <body></body>
</html>



```

#### Codigos de CSS

```

input[type="color"]::-moz-color-swatch {
    border-radius: 10px;
    border-style: none;
  }

  .joinBtn {
    width: 10em;
    height: 5ex;
    background-image: linear-gradient(135deg, #f34079 40%, #fc894d);
    border: none;
    border-radius: 5px;
    font-weight: bold;
    color: white;
    cursor: pointer;
  }

  .joinBtn:active {
    box-shadow: 2px 2px 5px #fc894d;
  }


  p {
    font-weight: bold;
  }

  a:any-link {
    color: forestgreen;
    text-decoration-color: hotpink;
  }

  textarea:blank {
    border: 3px solid red;
  }

  td:-moz-drag-over {
    color: red;
  }

  div {
    border: 4px solid red;
  }

  :-moz-only-whitespace {
    border-color: rgb(4, 246, 4);
  }

  p {
    background-color: white;
  }

  p:hover {
    background-color: gray;
  }

  #mybox {
    background: linear-gradient(to bottom, yellow, cyan);
    width: 200px;
    height: 200px;
  }

  #mybox:-moz-window-inactive {
    background: cyan;
  }

  input[type="range"]::-moz-range-progress {
    background-color: green;
    height: 1em;
  }

  :current(p, span) {
    background-color: yellow;
  }

  video {
    height: 300px;
    margin-bottom: 40px;
}

```
