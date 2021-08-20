# Historial de Versiones

Historial de versiones de SamitApps

## Version 1.0.0.98
Fecha: 20 de Agosto 2021

### 🔨 Mejoras Aplicadas

- Se agrega control de establecimientos te terceros en las cotizaciones.
- Se muestran los datos del establecimiento en el reporte de la cotización.
- Se modificaron todas las consultas de cuentas por cobrar y pagar para diferenciar fácilmente la cartera vencida de la no vencida.

## Version 1.0.0.97
Fecha: 14 de Agosto 2021

### 🔨 Mejoras Aplicadas

- Se agrega las referencias de los productos en el reporte de la cotización.
- Se agrega los comentarios de los productos en el reporte de la cotización.
- Se agrega el asunto de la cotización en el reporte de la cotización.
- Se agrega el comentario de la cotización en el reporte de la cotización.
- Se mejora el diseño de los totales en el reporte de la cotización.

## Version 1.0.0.96
Fecha: 13 de Agosto 2021

### ✨ Nuevas Funcionalidades

- Nuevo Informe de rentabilidad en el modulo de **"Inventario"**.

### 🔨 Mejoras Aplicadas

- Se mejora las planillas de cotizaciones y el formato por defecto.
- Mejoras en los reportes e informes de cartera.

## Version 1.0.0.93
Fecha: 21 de Julio 2021

### 🔨 Mejoras Aplicadas

- Se agrega validación de licencia para los clientes de SamitCloud.
    > [!NOTE]
    > - Este cambio solo aplica para los clientes que usan la version de SamitCloud.
    > - Se agrega el campo para ingresar el código de la licencia en el menu **"Datos de la empresa"**.
    > - Si no tiene asignada una licencia de SamitCloud, se le notificara al usuario con una notificación al iniciar sesión y se le habilitara unicamente el modulo General.

## Version 1.0.0.91
Fecha: 17 de Julio 2021

### ✔️ Errores Arreglados

- Se ajusto formulario de conceptos de retenciones, para permitir decimales en el porcentaje de retención.
- Se arreglo problema de no poder editar el nombre de una cuenta ya existente.
- Se ajusto el encabezado del Balance de Prueba por Centro de Costos.
- Se habilita condición de fechas en el formulario de Centros de Costos.

### 🔨 Mejoras Aplicadas

- Se agrego auxiliar de cuentas que no son de movimientos en los informes financieros.

## Version 1.0.0.90
Fecha: 14 de Julio 2021

### ✨ Nuevas Funcionalidades

- Se agrega funcionalidad **"Exogena"** en el modulo de **"Contabilidad"**.
- Se agrega funcionalidad **"Facturación Recurrente"** en el modulo de **"Facturación"**.
    > [!NOTE]
    > - Se pueden crear los planes por el menu **"Creación de Planes"**, los planes son los que se le asignan a los clientes por medio de las suscripciones.
    > - Para asignar un plan a aun cliente y crear la suscripción se hace por el menu **"Asignar Planes a Clientes"**.
    > - En el momento que desee hacer los cobros periódicos a los clientes puede ingresar al menu **"Liquidar suscripciones de clientes"**.
    > - Puede asignar planes a un establecimiento de un cliente si asi lo desea.
- Se agrego informe financiero **"Flujo de Efectivo"** en el modulo de **"Contabilidad"**.
- Se agrego menu **"Notas a los Estados Financieros"** en el modulo de **"Contabilidad"**.
- Se agrego menu **"Consulta Documentos Electrónicos"** en el modulo de **"Facturación"**.
    > [!NOTE]
    > - En este menu puede ver las Facturas y Devoluciones electrónicas que se han generado.
    > - En la grilla se muestran indicadores de color para saber que documentos no se enviaron correctamente a la DIAN o que tienen error al subir los adjuntos.
    > - También puede filtrar para ver solo los documentos con errores.

### ✔️ Errores Arreglados

- Se corrige error al agregar campos a productos individualizados en el menu **"Creación de Productos Individualizados"**.
- Se corrige error en el menu de cotizaciones, ahora se carga el comentario de una orden al editarla.
- Se agrega validación en el SamitBúsqueda para evitar error por palabras repetidas.
- Se ajustan los menus de centros de costos y grupos de centros de costos.
- Se corrige error al abrir menu de **"Conceptos y Tipos de Retención"**.
- Se corrige error al guardar un concepto de retención. 

### 🔨 Mejoras Aplicadas

- Mejoras en el copiado de datos desde la grilla de SAMIT, se agrego un menu contextual para el copiado.
- Se mejoro el diseño del menu **"Definición de Comprobantes"** y se mejoro la velocidad al abrir este menu.
- Se agrega opción de importación de terceros en el menu **"Informe de Terceros"** en el modulo **"General"**.
- Se creó un elemento visual para indicar de forma interactiva las convenciones de las grillas.

## Version 1.0.0.87
Fecha: 18 de Junio 2021

### ✔️ Errores Arreglados

- Se corrige error al crear un auxiliar a una cuenta contable en menu **"Creación y Administración de Cuentas"**.
- Ya no se valida como obligatorio la base en las cuentas que manejan retención o iva en el menu **"Ingreso de Comprobantes"**.
    > [!NOTE]
    > Es recomendable cuando el comprobante que se ingresa tiene retención en 0, dejar la base por el valor correspondiente y en el valor del movimiento dejar 0, de esta forma queda el registro de la retención que no se realizo y se puede evidenciar en el certificado de retención.
- Se cambio el comportamiento en el informe diario de ventas en el doble-click de un item, ya no se cierra el popup de los movimientos.
- Validación de unidades de medidas inactivas en la creación del producto.
- Validación al imprimir documentos cuando la impresora seleccionada no esta instalada en el sistema.

### 🔨 Mejoras Aplicadas

- Se agrega columna de establecimiento en la consulta de auxiliares.
- Se agrega procedimiento almacenado para re-contabilizar todos los documentos de inventario.
- Se agrega opción para eliminar una cuenta en menu **"Creación y Administración de Cuentas"**. 
- Se agrega validación de datos del tercero al facturar electrónicamente.
- Ahora se validan los datos "electrónicos" del tercero cuando se le hace una factura electronica y se abre un menu de actualización de datos si no estas completos.

## Version 1.0.0.86
Fecha: 17 de Junio 2021

### ✔️ Errores Arreglados

- Se corrige validación al agregar un movimiento sin "Documento de Cruce" con cuenta que detalla en el menu **"Ingreso de Comprobantes"**.
- Se corrige error de validación de resolución de facturación en compras y devoluciones. 

### 🔨 Mejoras Aplicadas

- Mejoras en la grilla en el menu **"Balance de Prueba con Tercero"**.

## Version 1.0.0.85
Fecha: 11 de Junio 2021

### ✨ Nuevas Funcionalidades

- Se agrega menu **"Informe Saldos de Productos"** en el modulo de **Inventario**.
- Se agrega menu **"Saldos de Productos por Talla"** en el modulo de **Inventario**.
- Se agrega menu **"Saldos de Productos por Lote"** en el modulo de **Inventario**.
- Se agrega menu **"Balance de Inventario"** en el modulo de **Inventario**.
- Se agrega menu **"Definición de Comprobantes para Procesos Especiales"** en el modulo de **Contabilidad**.

### ✔️ Errores Arreglados

- Se corrige error del barrio al guardar los establecimientos de un tercero.
- Se arregla problema con las llaves foráneas en la base de datos.
- Se corrige error en campo "Actualizado" al guardar comprobante de contabilidad.
- Se arregla error de oficina diferente al crear una copia de un documento de contabilidad.
- Se arregla error cuando no se define una lista de precios en el menu **"Asignar lista de Precios a Cliente"**.

### 🔨 Mejoras Aplicadas

- Se agrega mensajes de confirmación en los procesos del menu **"Mantenimiento de Contabilidad"**.
- Se mejora proceso de "Validación de Campos" y "Re-Validación de Campos".
- Se cambio el tipo de logo que sale en los informes internos, ahora se usa el logo de la empresa.
- Ahora se tiene en cuenta los dias de pago del tercero en las formas de pago a crédito al facturar.

## Version 1.0.0.84
Fecha: 03 de Junio 2021

### ✨ Nuevas Funcionalidades

- Se agregan los menús de **"Cierre Definitivo"** y **"Consulta de Cierres"** en el modulo de **Contabilidad**.
    > [!NOTE]
    > - Si se quiere hacer nuevamente el Cierre Definitivo se debe anular el Cierre Definitivo VIGENTE
    > - Para anular un Cierre Definitivo se debe hacer desde el menu de **"Consulta de Cierres"**
    > - Tampoco se podrán hacer Cierres Parciales después de hacer un Cierre Definitivo
- Se agrega menu de **"Mantenimiento de Contabilidad"** en el modulo de **Contabilidad**.

### ✔️ Errores Arreglados

- Se corrige calculo de Saldo Anterior al escoger un solo día en los auxiliares de cuentas.
- Se ajusto el guardado en las fechas de los documentos de contabilidad para evitar incoherencias de fecha.

### 🔨 Mejoras Aplicadas

- Se mejora la validación de numero de comprobante en el guardado de documentos de inventario para evitar advertencia de prefijos repetidos. 
- Se implementan bloqueos de contabilidad _(Ingreso de comprobantes, contabilización de facturas, etc...)_ cuando se hace un Cierre Definitivo.
- Los documentos que hacen parte de un Cierre Definitivo ya no se pueden editar, anular o recuperar en ningún caso.

## Version 1.0.0.82
Fecha: 27 de Mayo 2021

### ✨ Nuevas Funcionalidades

- Se agregan los menús **"Resumen de Iva"** y **"Resumen de Retenciones"** en el modulo de **Contabilidad**.

### ✔️ Errores Arreglados

- Se arregla error de tercero repetido en la tabla de terceros al hacer un cierre parcial 

### 🔨 Mejoras Aplicadas

- Se ajusto reporte de comprobantes de egreso, se retira la cuenta de la cabecera del reporte
- Se ajusto consulta de informe de estado de resultados
    > [!NOTE]
    > - Antes se apreciaba diferencia en los saldos cuando las cuentas no tenían la naturaleza bien definida
    > - Ahora se ignora la naturaleza de la cuenta para hacer los cálculos
- Mejoras visuales en la grilla del estado de resultados

## Version 1.0.0.81 
Fecha: 21 de Mayo 2021

### ✨ Nuevas Funcionalidades

* Se agrego un parámetro de personalización para que se pueda establecer el tamaño y la fuente del texto de las facturas.
    > [!NOTE]
    > - El Tipo y Tamaño de fuente predeterminadas es **Arial** al tamaño **7.0**
    > - Si se cambia el tipo de fuente se debe probar con distintos
    tamaños hasta encontrar el que mejor ajuste al tipo de letra
    > - El nuevo parámetro se encuentra en el menu **"Definición de Comprobantes"** en la pestaña **Parámetros de Facturación**.\
    > ![Cambio Tipo Letra](_images/versions/1.0.0.81/CambioTipoLetra.png)  

    > [!ATTENTION]
    > - No se recomienda subir el tamaño por encima de 8.5
    > - Los tamaños 7.5 y 8.0 son los más indicados para la factura

- Se agrega menu **"Listar Documentos"** en el modulo de **Contabilidad**.

### ✔️ Errores Arreglados

- En el menu **"Ingreso de Comprobantes"** se ajusto el comportamiento del campo de la cuenta contable para que se ajuste el formulario recién se selecciona la cuenta.

### 🔨 Mejoras Aplicadas

- En el menu **"Movimientos por Comprobantes"** se habilito la opción para imprimir todos los comprobantes de la lista ademas de solo el que se encuentra seleccionado.
- Se optimizo el proceso de envió de facturas electrónicas, ahora se enviá en dos pasos.
- Se cambio la notificación que se muestra al enviar la factura electronica.

## Version 1.0.0.80
Fecha: 10 de Mayo 2021

### ✨ Nuevas Funcionalidades

- Se agrego un parámetro de personalización para que se muestre el total de items y productos en las facturas de venta.
    > [!NOTE]
    > - El nuevo parámetro se encuentra en el menu **"Definición de Comprobantes"** en la pestaña **Parámetros de Facturación**.

### ✔️ Errores Arreglados

- Arreglos menores