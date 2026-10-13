<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Inventario Daniel Osornio</title>
</head>
<body>

  <h2>Inventario</h2>

  <label>Código: <input type="number" id="codigo"></label><br><br>
  <label>Nombre: <input type="text" id="nombre"></label><br><br>
  <label>Cantidad: <input type="number" id="cantidad"></label><br><br>
  <label>Costo: <input type="number" id="costo"></label><br><br>

  <button id="btnAgregar">Agregar</button>
  <button id="btnBuscar">Buscar</button>
  <button id="btnEliminar">Eliminar</button>
  <button id="btnExtraerPrimero">Extraer Primero</button>
  <button id="btnExtraerUltimo">Extraer Último</button>
  <button id="btnListar">Listar</button>
  <button id="btnListarInverso">Listar Inverso</button>

  <h3>Detalles:</h3>
  <div id="detalles">Detalles</div>

  <script src="producto.js"></script>
  <script src="inventario.js"></script>
  <script>
    const inventario = new Inventario();
    const detalles = document.getElementById('detalles');

    document.getElementById('btnAgregar').onclick = () => {
      const codigo = document.getElementById('codigo').value.trim();
      const nombre = document.getElementById('nombre').value.trim();
      const cantidad = document.getElementById('cantidad').value;
      const costo = document.getElementById('costo').value;

      if (!codigo || !nombre || !cantidad || !costo) {
        detalles.innerHTML = "Completa todos los campos.";
        return;
      }

      const p = new Producto(codigo, nombre, cantidad, costo);
      if (inventario.agregar(p)) {
        detalles.innerHTML = "Producto agregado correctamente.";
      } else {
        detalles.innerHTML = "El código ya existe.";
      }
    };

    document.getElementById('btnBuscar').onclick = () => {
      const codigo = document.getElementById('codigo').value.trim();
      if (!codigo) {
        detalles.innerHTML = "Ingresa un código para buscar.";
        return;
      }
      const p = inventario.buscar(codigo);
      detalles.innerHTML = p ? p.infoHtml() : "Producto no encontrado.";
    };

    document.getElementById('btnEliminar').onclick = () => {
      const codigo = document.getElementById('codigo').value.trim();
      if (!codigo) {
        detalles.innerHTML = "Ingresa un código para eliminar.";
        return;
      }
      const p = inventario.eliminar(codigo);
      detalles.innerHTML = p ? `Producto ${codigo} eliminado.` : "Producto no encontrado.";
    };

    document.getElementById('btnExtraerPrimero').onclick = () => {
      const p = inventario.extraerPrimero();
      detalles.innerHTML = p ? "Primer producto extraído: " + p.infoHtml() : "El inventario está vacío.";
    };

    document.getElementById('btnExtraerUltimo').onclick = () => {
      const p = inventario.extraerUltimo();
      detalles.innerHTML = p ? "Último producto extraído: " + p.infoHtml() : "El inventario está vacío.";
    };

    document.getElementById('btnListar').onclick = () => {
      detalles.innerHTML = inventario.listar();
    };

    document.getElementById('btnListarInverso').onclick = () => {
      detalles.innerHTML = inventario.listarInverso();
    };
  </script>

</body>
</html>