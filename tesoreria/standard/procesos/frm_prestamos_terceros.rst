====================
préstamos a Terceros
====================

Ubicación
=========

:Módulo:
 Tesoreria

:Grupo:
 Procesos

:Descripción:
  préstamos a Terceros


Introducción
============

Use **ESC** para salir de las interfaces principales.

	En este proceso podrá organizar los préstamos de confianza que hace a un tercero determinado. Una vez ha realizado el egreso puede recurrir a esta interfaz para establecer el número de cuotas y las fechas de recaudo.mbién podrá hacer los abonos a partir de aquí.


Pre-requisitos
==============

		- Tener un tercero creado
		- **El concepto predefinido del egreso "préstamo a terceros" debe tener una cuenta contable asignada**
		- `Haber hecho un egreso usando el concepto predefinido "préstamo a terceros" <../procesos/frm_egresos.html#pagos-por-conceptos-predefinidos>`_


			.. figure:: images/préstamosterceros/a.png
 				 :align: center


Definir pautas de un préstamo a terceros
=========================================

Para organizar un *préstamo a terceros*, realice los siguientes pasos:

	- Ejecute la opción "préstamos a terceros"
	- Seleccione el centro de costo donde se hizo el egreso
	- Haga click en |wznew.bmp| *Nuevo* 

			.. figure:: images/préstamosterceros/1.png
 				 :align: center 

	- Verá una ventana nueva para la modificación de las pautas del préstamo
	- En el campo de texto 'Cédula o NIT' presione Enter para ver el listado del Terceros cuyo préstamo aún no tiene pautas establecidas

			.. figure:: images/préstamosterceros/2.png
 				 :align: center

	- El campo 'Observación' y la cuenta contable, son de solo lectura
	- Una vez elegido podrá entonces proceder a rellenar los campos:
		- Iniciar recuado en esta fecha: es la primera fecha en que el cliente deberá pagar una cuota
		- Intervalo de días: Cuantos días a partir de la fecha inicial se sumarán para la próxima fecha de corte
		- Número de cuotas: Elija en cuantas partes se realizará el cobro de este préstamo
	-  Haga click en |save.bmp| 'Guardar préstamo'

				.. figure:: images/préstamosterceros/4.png
 				 :align: center

Abonar a un préstamo
--------------------

	El abono de un préstamo se realiza a través de un recibo de caja, esta interfaz sirve, más bien, para llevar un control. Cada abono se adjudica a la última fecha de corte en el calendario.

	Siga los siguientes pasos:

	- Ejecute la opción "préstamos a terceros"
	- Seleccione el centro de costo donde se hizo el egreso
	- En la grilla haga click sobre el préstamo al que desea abonar
	- Pulse el botón 'Mostrar detalles del préstamo N #####'



			.. figure:: images/préstamosterceros/5.png
 				 :align: center

	- Verá una pantalla similar a la de creación del préstamo
	- Seleccione la caja o la cuenta, a donde irá el abono
	- Sobre la grilla de las cuotas, escriba el monto del abono en el campo 'Monto total del recaudo'
	- Presione Enter, verá como el monto ahora aparece sumado en la fila de la cuota en la grilla
	- Haga click en 'Guardar recaudo'
	- En la ventana emergente, elija el tipo de pago y presione F2



---------------------------------------------------------


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