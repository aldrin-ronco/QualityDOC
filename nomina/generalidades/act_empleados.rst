===========================
Administración de Empleados
===========================

Ubicación
=========

:Módulo:
 Nómina

:Grupo:
 Parámetros

:Descripción:
  Administración de empleados

Introducción
============

Use **ESC** para salir de las interfaces principales.

En *Administración de Empleados* podrá crear nuevos empleados, visualizarlos en forma de grilla, eliminarlos o modificar sus datos personales. Cada empleado tiene un código interno asignado y puede buscarlo desde la grilla usando el nombre o documento.

Crear un empleado
=================

Para crear un empleado realice los siguientes pasos:
 	
 	- Ejecute la opción *Administración de empleados*

 		 .. figure:: images/0.png
   			:align: center

 	- En el pie de la ventana pulse sobre el botón |wznew.bmp| *nuevo*

 	- Se desplegará una ventana emergente donde podrá dar cabida a los datos del empleado:


 		- **Datos básicos**: Nombres (si es Régimen Común) o Razón social, teléfonos, dirección
 		- *Estado actual del ciudadano* 
 			- Activo
 			- Inactivo
 		- *Documento de identificación*: Si este número de identificación ha sido usado en algún otro apartado (vendedores, proveedores, etc) entonces el sistema desplegará la información registrada de esta persona.
 		
 		.. NOTE::

 			Datos obligatorios: Primer nombre, primer apellido, departamento, municipio y número de documento.

 		- **Entidades y otros**: Seleccione las entidades y otros perfiles del empleado según convenga, tales como:

 			- Pensión
 			- EPS
 			- ARP
 			- MARGEN
 			- Caja de Compensación
 			- Cesantías
 			- Tipo de Contrato
 			- Centro de Costo
 			- Sección
 			- Cargo que desempeña - Puesto

 		-**Transacciones:** Elija en cuales transacciones este empleado deberá se tomado en cuenta, estas transacciones serán siempre fijas en cada liquidación de nomina. 

 		.. NOTE::

 			Recuerde que en el momento de realizar el pago de la nómina, podrá agregar otras transacciones; estas transacciones agregadas en el momento, no estarán marcadas para el próximo pago, son temporales. 

 		- **Parámetros:** Aquí puede darle valor a las variables personalizadas (diferentes para cada empleado). En la columna 'Nombre del parámetro' aparecerán todas las 'variables personalizadas' y en la columna 'Tipo de valor' podrá elegir para cada parámetro un valor fijo, independiente, o una variable global; en cada lista aparecen todas las variables globales creadas.

 		Use los parámetros para definir variables que serán usadas en las formulas de las transacciones de nómina.

 		-**Contabilización:** Parametrice las cuentas contables que se ven afectadas por las transacciones relacionadas al empleado. Haga click sobre la casilla de la columna 'Cta Contable' que desea cambiar y luego presione Enter.

 		-**Cont aportes y provisiones:** elija las cuentas contables debito y crédito para los aportes y provisiones. Haga click en la casilla correspondiente a la columna débito o crédito, de acuerdo a la naturaleza del movimiento, y luego presione Enter para elegir la cuenta.

 		-**Otros datos:** 
 			- Cuenta Bancaria
 			- Fecha de Nacimiento
 			- Email

 		-**Fechas:** Aquí puede obtener la fecha de ingreso del empleado y la fecha de sus últimas vacaciones.

 			 

	Para guardar el cliente haga click en |save.bmp| *Guardar* o presione F2



Eliminar un empleado
=====================
 	- Ejecute la opción *Administración de Empleados*
 	- Seleccione haciendo click a un empleado en la grilla
 	- Presione el botón |delete.bmp| *eliminar* al pie de la ventana

		 .. figure:: images/2.png
		   :align: center

 	- En el cuadro de confirmación presiones 'Sí'

 	.. Note:
 	No podrá eliminar un empleado que tenga cualquier tipo de transacción adjudicada.


Modificar un empleado
=====================

 	- Ejecute la opción *Administración de empleados*
 	- Seleccione haciendo click a un empleado en la grilla
 	- Presione el botón |wzedit.bmp| *modificar* al pie de la ventana
		 
		 .. figure:: images/3.png
		   :align: center

 	- Aparecerá una ventana donde podrá cambiar los datos del empleados que necesite, y dejar los que considere ya están bien.




--------------------------------------------

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
