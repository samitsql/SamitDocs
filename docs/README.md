# Historial de Versiones

Historial de versiones de SamitApps

## Version 1.0.0.83
Fecha: 03 de Junio 2021

### ✨ Nuevas Funcionalidades

- Se agregan los menus de **"Cierre Definitivo"** y **"Consulta de Cierres"** en el modulo de **Contabilidad**.
    > [!NOTE]
    > - Si se quiere hacer nuevamente el Cierre Definitivo se debe anular el Cierre Definitivo VIGENTE
    > - Para anular un Cierre Definitivo se debe hacer desde el menu de **"Consulta de Cierres"**
    > - Tampoco se podran hacer Cierres Parciales despues de hacer un Cierre Definitivo
- Se agrega menu de **"Mantenimiento de Contabilidad"** en el modulo de **Contabilidad**.

### ✔️ Errores Arreglados

- Se corrige calculo de Saldo Anterior al escoger un solo día en los auxiliares de cuentas.
- Se ajusto el guardado en las fechas de los documentos de contabilidad para evitar incoherencias de fecha.

### 🔨 Mejoras Aplicadas

- Se mejora la validacion de numero de comprobante en el guardado de documentos de inventario para evitar advertencia de prefijos repetidos. 
- Se agregan bloqueos de contabilidad _(Ingreso de comprobantes, contabilizacion de facturas, etc...)_ cuando se hace un Cierre Definitivo.
- Los documentos que hacen parte de un Cierre Definitivo ya no se pueden editar, anular o recuperar en ningun caso.

## Version 1.0.0.82
Fecha: 27 de Mayo 2021

### ✨ Nuevas Funcionalidades

- Se agregan los menus **"Resumen de Iva"** y **"Resumen de Retenciones"** en el modulo de **Contabilidad**.

### ✔️ Errores Arreglados

- Se arregla error de tercero repedito en la tabla de terceros al hacer un cierre parcial 

### 🔨 Mejoras Aplicadas

- Se ajusto reporte de comprobantes de egreso, se retira la cuenta de la cabecera del reporte
- Se ajusto consulta de informe de estado de resultados
    > [!NOTE]
    > - Antes se apreciaba diferencia en los saldos cuando las cuentas no tenian la naturaleza bien definida
    > - Ahora se ignora la naturaleza de la cuenta para hacer los calculos
- Mejoras visuales en la grilla del estado de resultados

## Version 1.0.0.81 
Fecha: 21 de Mayo 2021

### ✨ Nuevas Funcionalidades

* Se agrego un parámetro de personalización para que se pueda establecer el tamaño y la fuente del texto de las facturas.
    > [!NOTE]
    > - El Tipo y Tamaño de fuente predeterminadas es **Arial** al tamaño **7.0**
    > - Si se cambia el tipo de fuente se debe probar con distintos
    tamaños hasta encontrar el que mejor ajuste al tipo de letra
    > - El nuevo parametro se encuentra en el menu **"Definición de Comprobantes"** en la pestaña **Parametros de Facturacion**.\
    > ![Cambio Tipo Letra](_images/versions/1.0.0.81/CambioTipoLetra.png)  

    > [!ATTENTION]
    > - No se recomienda subir el tamaño por encima de 8.5
    > - Los tamaños 7.5 y 8.0 son los más indicados para la factura

- Se agrega menu **"Listar Documentos"** en el modulo de **Contabilidad**.

### ✔️ Errores Arreglados

- En el menu **"Ingreso de Comprobantes"** se ajusto el comportamiento del campo de la cuenta contable para que se ajuste el formulario recien se selecciona la cuenta.

### 🔨 Mejoras Aplicadas

- En el menu **"Movimientos por Comprobantes"** se habilito la opción para imprimir todos los comprobantes de la lista ademas de solo el que se encuentra seleccionado.
- Se optimizo el proceso de envio de facturas electronicas, ahora se envia en dos pasos.
- Se cambio la notificacion que se muestra al enviar la factura electronica.

## Version 1.0.0.80
Fecha: 10 de Mayo 2021

### ✨ Nuevas Funcionalidades

- Se agrego un parámetro de personalización para que se muestre el total de items y productos en las facturas de venta.
    > [!NOTE]
    > - El nuevo parametro se encuentra en el menu **"Definición de Comprobantes"** en la pestaña **Parametros de Facturacion**.

### ✔️ Errores Arreglados

- Arreglos menores