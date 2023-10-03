# Actividad: Diseñar un formulario de pedido de un producto

<br>
<br>
<br>

Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

Instrucciones:

1. Crear un nuevo documento HTML.

2. Crear un formulario con los siguientes campos:
  * Nombre del producto:
  * Cantidad
  * Precio unitario
  * Precio total
  * Dirección de envío
  * Información de contacto (nombre, correo electrónico, número de teléfono)

3. Agregar los siguientes campos relacionados al 
   formulario:

  * Método de pago
  * Fecha de entrega
  * Comentarios

4. Utilizar las etiquetas HTML apropiados para cada campo.

<br>
<br>
<br>

## Formulario sesion 5
<br>
<br>



```

<!DOCTYPE html>
<html lang="es">


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FORMULARIO</title>
</head>


<body>
    <h1>FORMULARIO ACTIVIDAD 5</h1>

    <div>
        <label for="nombre">Nombre del producto; </label>
        <input type="text" name="nombre" placeholder="Nombre" id="nombre">
    </div>
    <br>
    <br>

    <div>
        <label for="number">Cantidad:</label>
        <input type="number" name="?" placeholder="0">
    </div>
    <br>
    <br>


    <div>
        <label for="precio">Precio Unitario:</label>
        <input type="number" step="0.01" min="0.01" placeholder="$" name="precio" id="precio" required>
    </div>
    <br>
    <br>


    <form>
        <label for="precioTotal">Precio Total:</label>
        <input type="text" id="precioTotal" name="precioTotal" readonly>
    </form>
    <br>
    <br>

    <div>
        <input type="datetime-local" name="fecha_hora" id="fecha_hora">
        <label for="fecha_hora">Fecha y hora</label>
    </div>
    <br>
    <br>

    <form>

        <label for="direccion">Dirección:</label>
        <textarea id="direccion" name="direccion"></textarea><br><br>

        <label for="ciudad">Ciudad:</label>
        <input type="text" id="ciudad" name="ciudad"><br><br>

        <label for="estado">Estado:</label>
        <input type="text" id="estado" name="estado"><br><br>

        <label for="codigo-postal">Código Postal:</label>
        <input type="text" id="codigo-postal" name="codigo-postal"><br><br>

        <label for="pais">País:</label>
        <select id="pais" name="pais">
            <option value="us">Estados Unidos</option>
            <option value="ca">Canadá</option>
            <option value="mx">México</option>
            <option value="mx">Colombia</option>
            <option value="mx">Reino unido</option>
        </select>
        <br>
        <br>
    </form>

    <br>

    <div>
        <label for="teléfono">Teléfono:</label>
        <input type="tel" name="teléfono" placeholder="Teléfono" id="teléfono">
    </div>
    <br>
    <br>

    <!-- Ejemplo de control de entrada de URL con placeholder -->
    <div>
        <label for="sitio_web">Sitio web:</label>
        <input type="url" name="sitio_web" placeholder="Sitio web" id="sitio_web">
    </div>
    <br>
    <br>


    <form>
        <label for="metodoPago">Selecciona el método de pago:</label>
        <select id="metodoPago" name="metodoPago">
            <option value="tarjeta">Tarjeta de crédito</option>
            <option value="paypal">PayPal</option>
            <option value="transferencia">Transferencia bancaria</option>
            <option value="Efectivo">Efectivo</option>
        </select>
    </form>
    <br>
    <br>

    <label for="fechaEntrega">Fecha de Entrega:</label>
    <input type="date" id="fechaEntrega" name="fechaEntrega">

    <br>
    <br>

    <div>
    <label for="textarea" >Comentarios:</label>
    <input type="text" id="nombre" name="nombre">
     </div>

    <br>
    <br>

    <div>
      <input type="submit" value="Enviar" id="enviar">
    </div>

</body>

</html>

```

