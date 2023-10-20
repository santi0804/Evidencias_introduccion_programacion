<!-- No borrar o modificar -->

[Inicio](./index.md)

## Sesión 9

### Actividad: Propiedades de espaciado y unidades de medida

Objetivo:

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

Crea un nuevo archivo HTML y CSS.
En el archivo HTML, agrega el siguiente código:
<br>

### Preguntas:

¿Qué es la propiedad margin?

¿Qué es la propiedad padding?

¿Qué es la propiedad border?

¿Qué es la propiedad border-radius?

¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?

## Solucion

```

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>

```

En el archivo CSS, agrega el siguiente código:

```

.contenedor {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}

.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}

.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}


.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}

.elemento {
    margin-top: 10px;
    margin-right: 20px;
    margin-bottom: 10px;
    margin-left: 20px;
}

.elemento {
    margin: 10px;
}

.elemento {
    padding-top: 10px;
    padding-right: 20px;
    padding-bottom: 10px;
    padding-left: 20px;
}

.elemento {
    padding: 10px;
}
.elemento {
border-width: 2px;
border-style: solid;
border-color: #333;
border-radius: 5px;
}

```

### ¿Qué es la propiedad border-radius?

La propiedad “border-radius” en el contexto del diseño web se utiliza para controlar el radio de las esquinas de un elemento HTML, lo que permite que los bordes tengan esquinas redondeadas en lugar de ser completamente cuadradas. Esto agrega un toque de suavidad y estilo a la apariencia de un elemento en una página web.

La propiedad “border-radius” se usa para establecer los radios de las esquinas de los elementos, como divs, imágenes o párrafos. Se pueden definir uno o varios valores para especificar los radios de las esquinas de diferentes maneras:

Si se define un solo valor, se aplica a todas las esquinas, lo que da como resultado esquinas redondeadas idénticas.

En este caso, las esquinas superiores izquierda y derecha tendrán un radio de 10 píxeles, mientras que las esquinas inferiores izquierda y derecha tendrán un radio de 20 píxeles.

Se pueden definir cuatro valores para especificar los radios de cada esquina en un orden específico (superior izquierda, superior derecha, inferior derecha, inferior izquierda).

### ¿Qué es la propiedad margin?

La propiedad “margin” en el contexto del diseño web se utiliza para controlar el espacio en blanco alrededor de un elemento HTML, como un elemento de bloque (por ejemplo, un div) o un elemento de línea (por ejemplo, un párrafo). Esta propiedad afecta el espacio entre el borde del elemento y los elementos adyacentes.

La propiedad “margin” se puede definir de varias maneras, especificando diferentes valores para controlar el margen en los cuatro lados del elemento (superior, derecho, inferior e izquierdo). Aquí tienes un ejemplo de cómo se puede usar:

### ¿Qué es la propiedad padding?

La propiedad “padding” en el contexto del diseño web se utiliza para controlar el espacio entre el contenido de un elemento HTML y su borde. Es decir, afecta la separación entre el contenido del elemento y su borde. El “padding” se aplica a elementos de bloque y elementos de línea.

La propiedad “padding” se puede definir de varias maneras, especificando diferentes valores para controlar el relleno en los cuatro lados del elemento (superior, derecho, inferior e izquierdo). Aquí tienes un ejemplo de cómo se puede usar:

La propiedad “padding” es útil para controlar la apariencia y el espacio alrededor del contenido dentro de un elemento HTML, como divs, párrafos, encabezados, etc. Ayuda a separar el contenido del borde del elemento y es útil para lograr un diseño más limpio y estilizado en una página web.

### ¿Qué es la propiedad border?

La propiedad “border” en el contexto del diseño web se utiliza para definir los bordes de un elemento HTML, como un div, una imagen o un párrafo. Esta propiedad controla la apariencia y estilo de los bordes del elemento, como su grosor, tipo de línea, color y radios de esquina (si se aplican). La propiedad “border” se puede dividir en varias subpropiedades para definir estos aspectos.

### ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?

En las propiedades de espaciado, como “margin”, “padding”, y “border-width,” puedes utilizar varias unidades de medida para definir valores. Algunas de las unidades de medida más comunes incluyen:

Píxeles (px): Esta es una unidad de medida fija que representa un píxel en la pantalla. Es comúnmente utilizada y proporciona una forma precisa de especificar el tamaño.

Em (em): El “em” es una unidad relativa que se basa en el tamaño de fuente actual del elemento padre. Un valor de 1em es igual al tamaño de fuente actual del elemento. Puedes utilizar “em” para definir el espaciado en relación con el tamaño de fuente.

Porcentaje (%): Las unidades de porcentaje se utilizan para especificar el espaciado en relación con el tamaño del elemento padre. Por ejemplo, puedes establecer un margen del 10% y eso será el 10% del ancho del elemento padre.

Centímetros (cm), milímetros (mm), y pulgadas (in): Estas unidades de medida son absolutas y se utilizan para definir el espaciado en términos de centímetros, milímetros o pulgadas. Son menos comunes en el diseño web, pero todavía se pueden utilizar.

Puntos (pt) y picas (pc): Estas son unidades de medida absolutas comúnmente utilizadas en impresión, pero a veces se emplean en el diseño web para tareas específicas.

Rem (root em): Similar a “em”, pero en lugar de basarse en el tamaño de fuente del elemento padre, se basa en el tamaño de fuente del elemento raíz (normalmente el tamaño de fuente del elemento HTML).
Vh y vw: Estas unidades relativas se basan en el tamaño de la ventana del navegador. “1vh” es igual al 1% de la altura de la ventana, y “1vw” es igual al 1% del ancho de la ventana.

La elección de la unidad de medida dependerá de tus necesidades de diseño y del contexto de tu proyecto. Algunas unidades son más apropiadas que otras según la situación, por lo que es importante seleccionar la que mejor se ajuste a tus objetivos de diseño.
