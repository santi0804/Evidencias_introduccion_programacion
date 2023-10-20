<!-- No borrar o modificar -->

[Inicio](./index.md)

## Sesión 10

## Actividad: Propiedades de posicionamiento de CSS

Objetivo:

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

Instrucciones:

Crea un nuevo archivo HTML y CSS.
En el archivo HTML, crea una estructura básica de página web con dos elementos div.
En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.

## Solucion

```

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="stylesheet" href="https://plantillashtmlgratis.com/" />
     <// link de Bootstrap
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN"
      crossorigin="anonymous"
    />
  </head>

  <body>
    <h1>CUADRO 1</h1>
    <div class="div1">
      <div class="div2"></div>
      <div class="div3"></div>
      <div class="div4"></div>
    </div>

    <// dejar este link siempre debajo para que pueda leer todos los archivos
    desde la pagina de Bootstrap.
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL"
      crossorigin="anonymous"
    ></script>
  </body>
</html>

```

```

.div1 {
  background-color: aqua;
  height: 500px;
  width: 500px;
  position: browser;
  top: 250px;
  left: 2000px;
}
.div2 {
  background-color: rgb(17, 20, 20);
  height: 150px;
  width: 150px;
  position: relative;
  top: 70px;
  left: 20px;
  display: block;
}
.div3 {
  background-color: rgb(21, 192, 92);
  height: 150px;
  width: 150px;
  position: relative;
  top: 0px;
  left: 60px;
}
.div4 {
  background-color: yellow;
  height: 150px;
  width: 150px;
  position: relative;
  top: -80px;
  left: 100px;
  z-index: 3;
}


```

### Preguntas:

#### ¿Cuál es la diferencia entre los valores position: absolute y position: relative?

R/= La diferencia fundamental entre position: absolute y position: relative en CSS radica en cómo los elementos se posicionan en relación con sus elementos contenedores y otros elementos en la página.

#### ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?

R/= La propiedad z-index en CSS se utiliza para controlar el orden de apilamiento de elementos posicionados. Es especialmente útil cuando se utilizan propiedades de posicionamiento como position: absolute, position: relative o position: fixed.

Asignar un valor a z-index:

z-index toma valores numéricos, donde un valor mayor indica que el elemento está "encima" de elementos con valores z-index menores.
Cuanto mayor sea el valor de z-index, más adelante estará en el apilamiento.
Aplicar position diferente de static:

Para que z-index tenga efecto, el elemento debe tener un valor de posicionamiento diferente a static. Por lo tanto, los valores de posición comunes son relative, absolute y fixed.

#### ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?

R/= La propiedad display en CSS se utiliza para controlar cómo se muestra un elemento en una página web. Puede cambiar la forma en que un elemento se comporta en el flujo del documento. Aquí hay algunos valores comunes de la propiedad display y cómo afectan a los elementos:

display inline.

Los elementos con esta propiedad no comienzan en una nueva línea y solo ocupan el ancho del contenido. Pueden estar en la misma línea que otros elementos inline.

display inline-block.

Combina las características de inline y block. Un elemento con esta propiedad se comporta como inline, pero puedes especificar un ancho y un alto, y el elemento responde a estas dimensiones.

display none.

Este valor oculta completamente el elemento de la página. No ocupará espacio y no será visible.

display flex.

Introduce un modelo de diseño de caja flexible y permite el control más avanzado del diseño, especialmente en cuanto a alineación, distribución y reordenamiento de elementos.
