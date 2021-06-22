## Version 1.0.0.87
Fecha: 18 de Junio 2021

### ✨ Nuevas Funcionalidades

- Se agrega menu **"Mantenimiento de Documentos"** en el modulo de **Inventario**.

### ✔️ Errores Arreglados

- Se corrige error al crear un auxiliar a una cuenta contable en menu **"Creación y Administración de Cuentas"**.
- Ya no se valida como obligatorio la base en las cuentas que manejan retención o iva en el menu **"Ingreso de Comprobantes"**.
    > [!NOTE]
    > Es recomendable cuando el comprobante que se ingresa tiene retención en 0, dejar la base por el valor correspondiente y en el valor del movimiento dejar 0.
    > De esta forma queda el registro de la retención que no se realizo y se puede evidenciar en el certificado de retención.
- Se cambio el comportamiento en el informe diario de ventas en el doble-click de un item, ya no se cierra el popup de los movimientos.
- Validación de unidades de medidas inactivas en la creación del producto.
- Validación al imprimir documentos cuando la impresora seleccionada no esta instalada en el sistema.

### 🔨 Mejoras Aplicadas

- Se agrega columna de establecimiento en la consulta de auxiliares.
- Se agrega procedimiento almacenado para re-contabilizar todos los documentos de inventario.
- Se agrega opción para eliminar una cuenta en menu **"Creación y Administración de Cuentas"**. 
- Se agrega validación de datos del tercero al facturar electrónicamente.
- Ahora se validan los datos "electrónicos" del tercero cuando se le hace una factura electronica y se abre un menu de actualización de datos si no estas completos.