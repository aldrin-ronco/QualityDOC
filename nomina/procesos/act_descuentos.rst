=====================================
Descuentos de nómina
=====================================

Ubicación
=========

:Módulo:
 Nómina

:Grupo:
 Procesos

:Descripción:
  Descuentos de nómina

Introducción
============

Quality permite la automatización de las deducciones en los pagos de nómina de manera sencilla. Los descuentos que se realizan al trabajador son:

	- `Descuento por préstamo a empleado`_
		- Realizar un comprobante de egreso por concepto de préstamo a empleado
		- Diferir en cuotas un préstamo
		- Re-diferir en cuotas un préstamo / Saltar una cuota
		- Pago por adelantado de una cuota
		- Abonar a la deuda sin saltar una cuota

	- `Descuento por compra a Crédito`_
		- Realizar una factura de compra
		- Diferir en cuotas el pago de la compra
		- Re-diferir el pago de la factura / saltar una cuota
		- Pago por adelantado de una cuota
		- Abonar a la deuda sin saltar una cuota

Descuento por préstamo a empleado
==================================

	Para llevar a cabo los descuentos nominales programados del pago de un empleado, por concepto de préstamos, deberá llevar a cabo el `Comprobante de Egresos  por Concepto predefinido de préstamo a empleado`_ y realizar los dos siguientes dos pasos:

Paso 1: Diferir en cuotas el préstamo
*************************************
	
	Al realizar un comprobante de `Comprobante de Egresos por Concepto predefinido de préstamo a empleado <../../tesoreria/standard/procesos/frm_egresos.html#egresos-a-terceros>`_ podrá elegir el monto de las cuotas y la fecha de comienzo del cobro, a este proceso se le llama "Diferir en cuotas"

		- En el módulo de Tesorería, ejecute la opción "Administrador General de Comprobantes de egresos"
		- Busque el egreso que corresponde al préstamo del empleado
		- En la fila del egreso, haga click en |export1.gif|, y seleccione la opción 'Diferir'
		- En la ventana emergente:
			- Escoja la fecha del primer cobro en la lista 'Iniciar recaudo a partir de la fecha'
			- En el campo 'valor de la cuota' digite el valor de la cuota por cobro, el sistema pondrá una cuota con el mismo valor hasta que el monto sea divisible, la última cuota tendrá el residuo de la división del monto.
			- Haga click en |save.bmp| *guardar*


	Usted podrá `Re-diferir la deuda`_ cuando lo considere necesario, ya sea para saltar una cuota o para redefinir el monto de los descuentos.

Paso 2: Visualizar el préstamo
******************************

	Puede visualizar las cuotas del préstamo para verificar cuales están ya pagadas y cuales restan. Además, desde aquí también puede re-diferir la deuda.

	- En el módulo de Nómina, ejecute la opción "Descuentos programados de nómina"
	- Realice la búsqueda del empleado al cual realizó el diferido en cuotas del paso 1
	- Aquí podrá visualizar todas las deducciones del pago de la quincena próxima, de todas las cuotas e incluso puede, al igual que en la ventana 'Administrador general de comprobantes de egresos', puede re-diferir aquí la deuda.
	

Pago por adelantado de una cuota
--------------------------------

 Si el empleado decide pagar por adelantado una cuota, en vez de esperar a que se haga el descuento automático, entonces debe realizar un recibo de ingreso. Este ingreso de dinero sustituirá la cuota marcada y su valor será el mismo de la cuota.

		- En el módulo de Tesorería, ejecute la opción "Recibos de caja"
		- Haga click en la pestaña 'Recaudo de préstamos a empleados'
		- Localice en la grilla el prestamo/empleado
		- Haga click en los [...] 3 puntos al final de la fila
		- Verá una lista de las cuotas del prestamo, en azul las que ya están cancelada. y en blanco las otras. 
		- Seleccione las cuotas que desea pagar por adelantado (hacer un abono a la deuda) y haga click en  |btn_ok.bmp| *continuar* o presione la tecla F2



Abonar a la deuda sin reducir las cuotas
----------------------------------------

	Si ya ha realizado un `Pago por adelantado de una cuota`_ pero no quiere 'saltar' una o varias cuotas, entonces debe - `Re-diferir la deuda`_ 


Aplazar un descuento de cuota
-----------------------------

- `Re-diferir la deuda`_ 

Descuento por compra a Crédito
==============================

	Para llevar a cabo los descuentos nominales programados del pago de un empleado, por concepto de una compra a crédito, deberá llevar a cabo la `Facturación de una venta `_ a nombre del empleado, y realizar los dos siguientes dos pasos:

Paso 1: Diferir en cuotas el préstamo
*************************************
	
	Al realizar una factura a crédito podrá elegir el monto de las cuotas y la fecha de comienzo del cobro, a este proceso se le llama "Diferir en cuotas"

		- En el módulo de Ventas, ejecute la opción "Consulta general de Facturación"
		- Busque la factura a crédito del empleado
		- En la fila del egreso, haga click en |export1.gif|, y seleccione la opción 'Diferir'
		- En la ventana emergente:
			- Escoja la fecha del primer cobro en la lista 'Iniciar recaudo a partir de la fecha'
			- En el campo 'valor de la cuota' digite el valor de la cuota por cobro, el sistema pondrá una cuota con el mismo valor hasta que el monto sea divisible, la última cuota tendrá el residuo de la división del monto.
			- Haga click en |save.bmp| *guardar*


	Usted podrá `Re-diferir la deuda`_ cuando lo considere necesario, ya sea para saltar una cuota o para redifinir el monto de los descuentos.

Paso 2: Visualizar el préstamo
******************************

	Puede visualizar las cuotas del préstamo para verificar cuales están ya pagadas y cuales restan. Además, desde aquí también puede re-diferir la deuda.

	- En el módulo de Nómina, ejecute la opción "Descuentos programados de nómina"
	- Realice la búsqueda del empleado al cual realizó el diferido en cuotas del paso 1
	- Aquí podrá visualizar todas las deducciones del pago de la quincena próxima, de todas las cuotas e incluso puede, al igual que en la ventana 'Consulta general de facturación', puede re-diferir aquí la deuda.

Pago por adelantado de una cuota
--------------------------------

 Si el empleado decide pagar por adelantado una cuota, en vez de esperar a que se haga el descuento automático, entonces debe realizar un recibo de ingreso. Este ingreso de dinero sustituirá la cuota marcada y su valor será el mismo de la cuota.

		- En el módulo de Tesorería, ejecute la opción "Recibos de caja"
		- Haga click en la pestaña 'Recaudo de préstamos a empleados'
		- Localice en la grilla el prestamo/empleado
		- Haga click en los [...] 3 puntos al final de la fila
		- Verá una lista de las cuotas del prestamo, en azul las que ya están cancelada. y en blanco las otras. 
		- Seleccione las cuotas que desea pagar por adelantado (hacer un abono a la deuda) y haga click en  |btn_ok.bmp| *continuar* o presione la tecla F2



Abonar a la deuda sin reducir las cuotas
----------------------------------------

	Si ya ha realizado un `Pago por adelantado de una cuota`_ pero no quiere 'saltar' una o varias cuotas, entonces debe - `Re-diferir la deuda`_ 


Aplazar un descuento de cuota
-----------------------------

- `Re-diferir la deuda`_ 

Re-diferir la deuda
-------------------

	- En el módulo de Tesorería, ejecute la opción "Administrador General de Comprobantes de egresos"
	- Busque el egreso que corresponde a la deuda del empleado
	- En la fila de la deuda, haga click en |export1.gif|, y seleccione la opción 'Re-Diferir'

	También

	- En el módulo de Nómina, ejecute la opción "Novedades y liquidación de nómina"
	- Realice la búsqueda del empleado 
	- En la fila del empleado, haga click en |export1.gif|, y seleccione la opción 'Re-Diferir'	


--------------------------------------------

.. |export1.gif| image:: /_images/generales/export1.gif
.. |pdf_logo.gif| image:: /_images/generales/pdf_logo.gif
.. |excel.bmp| image:: /_images/generales/excel.bmp
.. |codbar.png| image:: /_images/generales/codbar.png
.. |printer_q.bmp| image:: /_images/generales/printer_q.bmp
.. |calendaricon.gif| image:: /_images/generales/calendaricon.gif
.. |gear.bmp| image:: /_images/generales/gear.bmp
.. |openfolder.bmp| image:: /_images/generales/openfold.bmp
.. |library_listview.bmp| image:: /_images/generales/library_listview.png
.. |plus.bmp| image:: /_images/generales/plus.bmp
.. |wzedit.bmp| image:: /_images/generales/wzedit.bmp
.. |buscar.bmp| image:: /_images/generales/buscar.bmp
.. |delete.bmp| image:: /_images/generales/delete.bmp
.. |btn_ok.bmp| image:: /_images/generales/btn_ok.bmp
.. |refresh.bmp| image:: /_images/generales/refresh.bmp
.. |descartar.bmp| image:: /_images/generales/descartar.bmp
.. |save.bmp| image:: /_images/generales/save.bmp
.. |wznew.bmp| image:: /_images/generales/wznew.bmp
