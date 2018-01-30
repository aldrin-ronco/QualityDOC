=========================================
Reversión de cierres de nómina
=========================================

Ubicación
=========

:Módulo:
 Nómina

:Grupo:
 Parámetros

:Descripción:
  Revertir procesos de cierre

Introducción
============

Use **ESC** para salir de las interfaces principales.

El sistema Quality le permite revertir los procesos de liquidación de Nómina (provisiones, parafiscales, quincena, etc). Este proceso se realiza en cascada, ya que los movimientos contables y los saldos dependen de transacciones anteriores: primero se revierten las provisiones, luego las parafiscales y por último las quincenas. 

Esta reversión se puede hacer por mes, por año y por sección; no depende de meses anteriores, es decir, puede ir al mes que desee y hacer la reversión de dicho mes, sin tomar en cuenta los procesos realizados en meses que le siguen o anteponen.

Los procesos revertidos no dejan registro. 

Realizar una reversión de cierre de nómina
==========================================

	- Para realizar una reversión, ejecute la opción *Reversión de cierres de nómina*
	- Elija la sección, el año y el mes en las listas. 
	- En la ventana verá información pertinente acerca del proceso:
		- El botón a la derecha, le indica cual es el proceso que va a revertir (quincena, provisión, etc)
		- En la parte inferior, verá los procesos pertenecientes al mes con un checkbox de solo lectura. Este check indica, si está marcado, que es un proceso vigente. Si el cuadro del check no está marcado, el proceso ha sido revertido.
	- Presione el botón para revertir el último proceso de la cadena (el último que tenga check). Deberá presionar el botón para revertir cada uno de los 4 procesos en el mes.

