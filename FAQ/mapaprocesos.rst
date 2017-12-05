================
Mapa de procesos
================


Registrar una factura de compra a un proveedor en el sistema
============================================================

    - Todos los productos que aparecen en la factura de compra deben haber sido registrados anteriormente en el sistema en el Módulo de Inventario, opción `Crear un producto <..inventario/generalidades/act_maestroinsumos.html#productos-servicios>`_ 
    - La Mercancía será recibida en un centro de costo. Cree el centro de costo en el módulo de configuración, opción: `Crear un centro de costo <../config/generalidades/act_almacenes.html#crear-un-centro-de-costo>`_. Este centro de costo deberá tener marcada la propiedad: `Este almacén realiza compras <../config/generalidades/act_almacenes.html#propiedades-de-un-centro-de-costo>`_.
    
        .. NOTE::
            El Sistema Qality le permite ingresar una **factura de compra** que reuna varias *entradas de mercancía*. Siempre es posible que su proveedor envíe la mercancía en varios lotes, pero realice una sola factura tiempo después. Puede mantener su inventario actualizado ingresando al sistema todas las 'entradas de mercancía por compras' que necesite, hasta que tenga la factura en su poder. 

    - Ingrese mercancía, correspondiente a una compra, a inventario en el módulo Inventario, opción: `Entradas, Salidas, y transferencia de mercancías: Entradas <../inventario/standard/procesos/frm_inventario.html#entradas-de-mercancias>`_
    
        .. NOTE::

            El proceso de 'Radicar una factura' le permite elegir cuales entradas de mercancía corresponden a una única factura. Este es el proceso mediante el cual registra la factura en el sistema.
    
    - Para radicar una factura, a la que pertenecen una o más entradas de mercancía, diríjase al módulo Proveedores, opción: `Radicación de factura <../proveedores/procesos/frm_radica_cxp.html#radicar-una-factura>`_

Para pago a proveedor
---------------------

    -  Diríjase al módulo Tesorería, opción: `Comprobantes de Egresos, pestaña: 'pago de facturas a proveedores <../tesoreria/standard/procesos/frm_egresos.html#pago-de-facturas-a-proveedores>`_

 .. figure:: images/compra.png
 	    :align: center    

Registrar una venta a un cliente en el sistema
==============================================

    - Todos los productos a la venta deben haber entrado por inventario (En cualquier forma de entrada)
    - Debe haber creado un vendedor, configurado una `lista de precios <../ventas/generalidades/frm_listas_precios_post.html#crear-una-lista-de-precios>`_, creado una `resolución de facturación <../ventas/generalidades/act_resoluciones.html#crear-una-resolucion-de-facturacion>`_
    - La resolución la puede configurar en el momento de la facturación

        .. NOTE::

            No se puede vender un producto que no tenga precio. En la pestaña 'Otros' de la las propiedades de la Lista de Precios, puede permitir al cajero cambiar el precio en el momento en que realiza la facturación.
    
    - Para procesar la venta, diríjase al módulo Ventas, opción: `Procesar una venta <../ventas/standard/procesos/frm_facturacion.html#crear-una-factura-procesar-una-venta>`_
    - La venta puede ser pagada por el cliente a contado o a crédito

Para cobro a cliente (crédito)
------------------------------

    -  Diríjase al módulo Tesorería, opción: `Recibos de caja: Recaudos de cartera <../tesoreria/standard/procesos/frm_reciboscaja.html#crear-un-recibo-de-caja-por-recaudos-de-cartera-pago-de-venta-a-credito>`_

 .. figure:: images/venta.png
 	    :align: center 