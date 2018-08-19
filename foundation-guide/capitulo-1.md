---
title: Funciones y Comandos Comunes
layout: post
author: Yamel Senih
permalink: /capitulo-1/
source-id: 1te5-sglzC4rWpypcP6AwhbF3CbJzbeJsyohiOmJNVpY
published: true
---
1. Funciones y Comandos Comunes

    1. REGISTRO 

Para abrir ADempiere Clic en el icono ADempiere en su escritorio

Cuando no esté conectado a Internet, se le preguntará si desea conectarse  a Internet.  La conexión a Internet se requiere para acceder a los archivos de ayuda en línea en ADempiere. Org,

O Clic OK y se desplegará la siguiente pantalla.

Regístrese como SuperUser o System (sensible a mayúsculas / minúsculas) y la contraseña System. ADempiere recuerda sus entradas y selecciones. Seleccione el Idioma y  Clic OK. 

 La diferencia entre SuperUser y System es la siguiente: Al registrarse como System, puede manejar solamente la Compañía System. Al registrarse como SuperUser,  puede  manejar cualquiera de las Compañías en el sistema incluyendo System. 

 El Idioma que usted seleccione determina el formato de fecha que será usado por el sistema.. 

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_0.jpg)

Figura 1.2 Pantalla de Ingreso a ADempiere

En esta ventana se despliegan los valores utilizados la última vez que se registró en el sistema. Para abrir la Compañía System seleccione System Administrator  como su Rol. Figura 

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_1.jpg)

Figura 1.3 System Administrator

Para propósitos de prueba Usted debería seleccionar GardenAdmin como su rol. La compañía automáticamente tomará el valor de GardenWorld. Figura 1.4.

La Organización tomará el valor predeterminado de HQ y el Almacén el de Standard o HQ Warehouse.

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_2.jpg)

Figura 1.4  GardenWorld Admin

La Fecha tomará el valor de la fecha actual. Ésta es la fecha predeterminada usada para todos los documentos. La impresora debe ser una impresora definida para esta compañía y puede ser una impresora de red. Ésta será la impresora usada para todos los documentos y reportes.

Clic en la pestaña  para usar  la Ayuda en Línea de ADempiere, que  se despliega en la ventana que se muestra en la figura 1.5. 

Clic en el enlace que usted desea para desplegar ya sea la Ayuda en  Línea o la Ayuda en la Configuración del Servidor.

Cambie a la pestaña Conexión para regresar a la pantalla de registro y Clic en OK.

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_3.jpg)

Figura 1.5 Ayuda en Línea de ADempiere

    2. FUNCIONES DE MENÚ

El menú de ADempiere muestra todas las tareas disponibles para el rol que usted seleccionó. En el campo de búsqueda amarillo a la derecha introduzca "Venta" y oprima Enter. El sistema va a través de todas las opciones del menú conteniendo los caracteres "venta"  (insensible a mayúsculas/minúsculas) y la resalta. Oprima Enter nuevamente para  buscar la siguiente opción (por ej. Orden de Venta). Para abrir la opción actual del menú oprima "Shift", "Alt" o "Ctrl" en combinación con la tecla Enter o doble Clic en la opción del menú.

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_4.jpg)

			Figura 1.6 Menú de ADempiere

Pueden definirse vías cortas para opciones de menú usadas frecuentemente tales como Orden de Venta o Reporte de Gasto. Para crear una vía corta en nuestro ejemplo, que será desplegada en el lado izquierdo del menú, haga Clic-derecho en Orden de Venta o Reporte de Gasto en el menú y Clic en Añadir a la Barra. 

La vía corta será creada en el lado izquierdo de la ventana. Para expandir esta área de Barra de Menú, arrastre la ventana hasta el tamaño apropiado cuando el cursor cambie a una flecha doble:

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_5.jpg)

					Figura 1.7 Añadir a la Barra

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_6.jpg)

**Figura 1.8 **Menú ADempiere

        1. Iconos de Menú

2. Cada opción de menú tiene un icono que indica el tipo de función que ejecuta la ventana. 

3. El icono ![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_7.png)  indica una Ventana. Una  ventana es donde se introducen datos o se define un registro  tal como Orden de Venta o Categoría de Impuesto.

4. El icono ![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_8.png) indica la elaboración de un informe. Generará un reporte en pantalla que puede ser modificado y/o impreso, por ejemplo un Sumario de Facturas.

5. El icono ![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_9.png) indica la ejecución de un proceso. Un proceso puede ser pensado como una tarea que corre en la base de datos o en el servidor, como por ejemplo Generar Facturas.

6. El icono ![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_10.png) indica un flujo de trabajo. Un flujo de trabajo indica una serie de pasos necesarios para llevar a cabo una meta.

7. Ventanas, Procesos, Informes y Flujos de Trabajo se cubrirán posteriormente en este documento.

<table>
  <tr>
    <td>Icono</td>
    <td>Descripción</td>
  </tr>
  <tr>
    <td></td>
    <td>Iniciar una ventana  o forma</td>
  </tr>
  <tr>
    <td></td>
    <td>Iniciar un informe</td>
  </tr>
  <tr>
    <td></td>
    <td>Iniciar un proceso</td>
  </tr>
  <tr>
    <td>  </td>
    <td>Iniciar un flujo de trabajo</td>
  </tr>
</table>


8. **Figura 1.9 **Iconos del Menú

    3. COMANDOS Y BOTONES

Cada ventana en ADempiere tiene una apariencia común. Mientras el contenido o los campos de una ventana pueden cambiar, algunas áreas de la ventana permanecerán constantes. Estas áreas incluyen: la Barra de Herramientas, Menú, Contexto (para campos específicos) y Diálogos. Abajo se muestran cinco cuadros con  todos estos comandos:

        2. Barra de Herramientas de la Ventana

<table>
  <tr>
    <td>Comando</td>
    <td>Botón</td>
    <td>Tecla de Función</td>
    <td>Vía Corta</td>
    <td>Menú</td>
    <td>Descripción</td>
  </tr>
  <tr>
    <td>Ignorar</td>
    <td>       </td>
    <td>ESC</td>
    <td></td>
    <td>Editar
- Ignorar Cambios</td>
    <td>Ignorar cambios</td>
  </tr>
  <tr>
    <td>Ayuda</td>
    <td> </td>
    <td>F1</td>
    <td></td>
    <td>Ayuda
-Ayuda</td>
    <td>Obtener más información</td>
  </tr>
  <tr>
    <td>Nuevo</td>
    <td></td>
    <td>F2</td>
    <td>Ctrl-N</td>
    <td>Editar
- Registro nuevo</td>
    <td>Crear un registro nuevo</td>
  </tr>
  <tr>
    <td>Copiar</td>
    <td></td>
    <td>Shift
F2</td>
    <td></td>
    <td>Editar
Copiar</td>
    <td>Copia registro actual
(Únicamente Menú)</td>
  </tr>
  <tr>
    <td>Borrar</td>
    <td>      </td>
    <td>F3</td>
    <td>Ctrl-X</td>
    <td>Editar
- Borrar registro</td>
    <td>Borrar el registro actual</td>
  </tr>
  <tr>
    <td>Guardar</td>
    <td>      </td>
    <td>F4</td>
    <td>Ctrl-S</td>
    <td>Editar
- Guardar cambios</td>
    <td>Guardar el registro actual</td>
  </tr>
  <tr>
    <td>Refrescar</td>
    <td>      </td>
    <td>F5</td>
    <td></td>
    <td>Editar
- Refrescar</td>
    <td>Refrescar los registros</td>
  </tr>
  <tr>
    <td>Buscar registro</td>
    <td>      </td>
    <td>F6</td>
    <td>Ctrl-F</td>
    <td>Ver
- Buscar registro</td>
    <td>Despliega la pantalla de búsqueda</td>
  </tr>
  <tr>
    <td>Anexo</td>
    <td>      </td>
    <td>F7</td>
    <td></td>
    <td>Ver
- Anexo</td>
    <td>Entra o despliega un anexo</td>
  </tr>
  <tr>
    <td>Cambio de forma</td>
    <td>            
</td>
    <td>F8</td>
    <td></td>
    <td>Ver
- (Des)Seleccionar matriz de datos</td>
    <td>Cambia entre Matriz de datos</td>
  </tr>
  <tr>
    <td>Registros históricos</td>
    <td>      </td>
    <td>F9</td>
    <td></td>
    <td>Ver
- Registros históricos</td>
    <td>Despliega los registros históricos</td>
  </tr>
  <tr>
    <td>Menú</td>
    <td>      </td>
    <td>F10</td>
    <td></td>
    <td>Ir
- Menú</td>
    <td>Despliega el menú</td>
  </tr>
  <tr>
    <td>Registro padre</td>
    <td>      </td>
    <td></td>
    <td>Alt-Izquierda</td>
    <td>Ir
- Registro padre</td>
    <td>Despliega el registro padre</td>
  </tr>
  <tr>
    <td>Registro detallado</td>
    <td>      </td>
    <td></td>
    <td>Alt-Derecha</td>
    <td>Ir
- Registro detallado</td>
    <td>Despliega el registro detallado</td>
  </tr>
  <tr>
    <td>Primer registro</td>
    <td>      </td>
    <td></td>
    <td>Alt-RePág</td>
    <td>Ir
- Primer registro</td>
    <td>Despliega el primer registro</td>
  </tr>
  <tr>
    <td>Registro previo</td>
    <td>      </td>
    <td></td>
    <td>Alt-Arriba</td>
    <td>Ir
- Registro previo</td>
    <td>Despliega el registro previo</td>
  </tr>
  <tr>
    <td>Próximo registro</td>
    <td>      </td>
    <td></td>
    <td>Alt-Abajo</td>
    <td>Ir
- Próximo registro</td>
    <td>Despliega el próximo registro</td>
  </tr>
  <tr>
    <td>Último registro</td>
    <td>      </td>
    <td></td>
    <td>Alt-AvPág</td>
    <td>Ir
- Último registro</td>
    <td>Despliega el último registro</td>
  </tr>
  <tr>
    <td>Informe</td>
    <td>      </td>
    <td></td>
    <td>Alt-P</td>
    <td>Archivo
- Informe</td>
    <td>Despliega el reporte del registro actual</td>
  </tr>
  <tr>
    <td>Imprimir</td>
    <td>      </td>
    <td></td>
    <td>Ctrl-P</td>
    <td>Archivo
- Imprimir</td>
    <td>Imprime un documento</td>
  </tr>
  <tr>
    <td>Información de Producto</td>
    <td>      </td>
    <td></td>
    <td>Ctrl-I</td>
    <td>Ver
- Información de producto</td>
    <td>Despliega información del producto
</td>
  </tr>
  <tr>
    <td>Flujo de Trabajo </td>
    <td>      </td>
    <td></td>
    <td></td>
    <td>Herramientas
-Flujo de Trabajo Activo</td>
    <td>Despliega flujos de trabajo Activos</td>
  </tr>
  <tr>
    <td>Finalizar ventana</td>
    <td>      </td>
    <td></td>
    <td>Alt-X</td>
    <td>Archivo
- Finalizar ventana</td>
    <td>Finaliza la ventana actual</td>
  </tr>
  <tr>
    <td>Visualiza detalle</td>
    <td>      </td>
    <td></td>
    <td></td>
    <td>Ir
-Visualiza Detalle</td>
    <td>Visualiza detalle de los datos que se están utilizando</td>
  </tr>
  <tr>
    <td>Solicitudes
(De este Documento)</td>
    <td>      </td>
    <td></td>
    <td>Alt-C</td>
    <td>Ir
-Solicitudes (De este Documento)</td>
    <td>Visualiza las solicitudes realizadas con referencia a este documento.</td>
  </tr>
</table>


Figura 1.10

Menú 1 de la Ventana

<table>
  <tr>
    <td>Barra de Menú</td>
    <td>Opción del Menú</td>
    <td>Icono</td>
    <td>Vía Corta</td>
    <td>Descripción</td>
  </tr>
  <tr>
    <td>Archivo</td>
    <td></td>
    <td></td>
    <td>Alt-F</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Imprimir pantalla</td>
    <td>   
</td>
    <td></td>
    <td>Imprime la Pantalla</td>
  </tr>
  <tr>
    <td></td>
    <td>Copia de la Pantalla</td>
    <td>   </td>
    <td>Shift- Imp
           Pan</td>
    <td>Imprime una Copia de la Pantalla</td>
  </tr>
  <tr>
    <td></td>
    <td>Informe</td>
    <td>  </td>
    <td>Alt-P</td>
    <td>Crear reporte</td>
  </tr>
  <tr>
    <td></td>
    <td>Imprimir</td>
    <td>  </td>
    <td>Ctrl-P</td>
    <td>Imprimir documento</td>
  </tr>
  <tr>
    <td></td>
    <td>Finalizar ventana</td>
    <td>  </td>
    <td>Alt-X</td>
    <td>Cerrar ventana</td>
  </tr>
  <tr>
    <td></td>
    <td>Salida</td>
    <td>  </td>
    <td>Shift-Alt-L</td>
    <td>Salida</td>
  </tr>
  <tr>
    <td></td>
    <td>Salir de la aplicación</td>
    <td>  </td>
    <td>Shift-Alt-X</td>
    <td>Cerrar aplicación</td>
  </tr>
  <tr>
    <td>Editar</td>
    <td></td>
    <td></td>
    <td>Alt-E</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Registro nuevo</td>
    <td>  </td>
    <td>Ctrl-N</td>
    <td>Registro nuevo</td>
  </tr>
  <tr>
    <td></td>
    <td>Guardar cambios</td>
    <td>  </td>
    <td>Ctrl-S</td>
    <td>Guardar cambios</td>
  </tr>
  <tr>
    <td></td>
    <td>Copiar registro</td>
    <td> </td>
    <td>Ctrl-V</td>
    <td>Copiar e insertar registro</td>
  </tr>
  <tr>
    <td></td>
    <td>Borrar registro</td>
    <td>  </td>
    <td>Ctrl-X</td>
    <td>Borrar registro</td>
  </tr>
  <tr>
    <td></td>
    <td>Ignorar cambios</td>
    <td>  </td>
    <td>Escape</td>
    <td>Ignorar cambios</td>
  </tr>
  <tr>
    <td></td>
    <td>Refrescar</td>
    <td>  </td>
    <td>F5</td>
    <td>Refrescar registros</td>
  </tr>
  <tr>
    <td></td>
    <td>Buscar registro</td>
    <td>  </td>
    <td>Ctrl-F</td>
    <td>Buscar registro</td>
  </tr>
  <tr>
    <td>Ver</td>
    <td></td>
    <td></td>
    <td>Alt-V</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Información de producto</td>
    <td>  </td>
    <td>Ctrl-I</td>
    <td>Información de producto</td>
  </tr>
  <tr>
    <td></td>
    <td>Información de socio del negocio</td>
    <td>  </td>
    <td>Shift-Ctrl-I</td>
    <td>Información de socio del negocio</td>
  </tr>
  <tr>
    <td></td>
    <td>Información de cuenta</td>
    <td>  </td>
    <td>Alt-Ctrl-I</td>
    <td>Información de cuenta</td>
  </tr>
  <tr>
    <td></td>
    <td>Información del Programa</td>
    <td>  </td>
    <td></td>
    <td>Despliega la ventana Información del Programa</td>
  </tr>
  <tr>
    <td></td>
    <td>Información de la orden</td>
    <td>  </td>
    <td></td>
    <td>Información de la orden</td>
  </tr>
  <tr>
    <td></td>
    <td>Información de Factura</td>
    <td>  </td>
    <td></td>
    <td>Información de Factura</td>
  </tr>
  <tr>
    <td></td>
    <td>Información de entrega</td>
    <td>  </td>
    <td></td>
    <td>Información de entrega</td>
  </tr>
  <tr>
    <td></td>
    <td>Información de pago</td>
    <td>  </td>
    <td></td>
    <td>Información de pago</td>
  </tr>
  <tr>
    <td></td>
    <td>Información de Efectivo</td>
    <td>  </td>
    <td></td>
    <td>Información de Efectivo</td>
  </tr>
  <tr>
    <td></td>
    <td>Información de la Recurso</td>
    <td>  </td>
    <td></td>
    <td>Información de la Recurso</td>
  </tr>
  <tr>
    <td></td>
    <td>Información de  Activo </td>
    <td>  </td>
    <td></td>
    <td>Información de  Activo </td>
  </tr>
  <tr>
    <td></td>
    <td>Información de l Programa</td>
    <td>  </td>
    <td></td>
    <td>Información de l Programa</td>
  </tr>
  <tr>
    <td></td>
    <td>Anexo</td>
    <td>  </td>
    <td>F7</td>
    <td>Visualiza/Crea un anexo</td>
  </tr>
  <tr>
    <td></td>
    <td>Registros históricos</td>
    <td>  </td>
    <td>F9</td>
    <td>Visualiza registros históricos</td>
  </tr>
  <tr>
    <td></td>
    <td>Chat</td>
    <td> </td>
    <td></td>
    <td>Envia mensajes en Chat</td>
  </tr>
  <tr>
    <td></td>
    <td>(De)Seleccionar matriz de datos</td>
    <td>  </td>
    <td>F8</td>
    <td>(De)Seleccionar matriz de datos</td>
  </tr>
  <tr>
    <td>Barra de Menú</td>
    <td>Opción del Menú</td>
    <td>Icono</td>
    <td>Vía Corta</td>
    <td>Descripción</td>
  </tr>
  <tr>
    <td>Ir</td>
    <td></td>
    <td></td>
    <td>Alt-I</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Primer registro</td>
    <td>  </td>
    <td>Alt-AvPág</td>
    <td>Primer registro</td>
  </tr>
  <tr>
    <td></td>
    <td>Registro previo</td>
    <td>  </td>
    <td>Alt-Arriba</td>
    <td>Registro previo</td>
  </tr>
  <tr>
    <td></td>
    <td>Próximo registro</td>
    <td>  </td>
    <td>Alt-Abajo</td>
    <td>Próximo registro</td>
  </tr>
  <tr>
    <td></td>
    <td>Último registro</td>
    <td>  </td>
    <td>Alt-AvPág</td>
    <td>Último registro</td>
  </tr>
  <tr>
    <td></td>
    <td>Registro padre</td>
    <td>  </td>
    <td>Alt-Izquierda</td>
    <td>Pestaña padre</td>
  </tr>
  <tr>
    <td></td>
    <td>Registro detallado</td>
    <td>  </td>
    <td>Alt-Derecha</td>
    <td>Pestaña detalle</td>
  </tr>
  <tr>
    <td></td>
    <td>Menú</td>
    <td>  </td>
    <td>F10</td>
    <td>Menú</td>
  </tr>
  <tr>
    <td></td>
    <td>Visualiza detalle</td>
    <td>  </td>
    <td></td>
    <td>Visualiza detalle</td>
  </tr>
  <tr>
    <td></td>
    <td>Solicitudes
(De este Documento)</td>
    <td>  </td>
    <td></td>
    <td>Solicitudes
(De este Documento)</td>
  </tr>
  <tr>
    <td></td>
    <td>Archivador  de Documentos</td>
    <td>  </td>
    <td></td>
    <td>Archivador de Documentos</td>
  </tr>
  <tr>
    <td>Herramientas</td>
    <td></td>
    <td></td>
    <td>Alt-H</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Calculadora</td>
    <td> </td>
    <td></td>
    <td>Calculadora</td>
  </tr>
  <tr>
    <td></td>
    <td>Calendario</td>
    <td> </td>
    <td></td>
    <td>Calendario</td>
  </tr>
  <tr>
    <td></td>
    <td>Editor</td>
    <td> </td>
    <td></td>
    <td>Editor de texto</td>
  </tr>
  <tr>
    <td></td>
    <td>Script</td>
    <td> </td>
    <td></td>
    <td>Editor Script</td>
  </tr>
  <tr>
    <td></td>
    <td>Flujo de Trabajo</td>
    <td> </td>
    <td></td>
    <td>Iniciar un flujo de trabajo</td>
  </tr>
  <tr>
    <td></td>
    <td>Preferencia</td>
    <td>  </td>
    <td></td>
    <td>Establece preferencias</td>
  </tr>
  <tr>
    <td>Ayuda</td>
    <td></td>
    <td></td>
    <td>Alt-A</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Ayuda</td>
    <td>  </td>
    <td>F1</td>
    <td>Muestra información de ayuda</td>
  </tr>
  <tr>
    <td></td>
    <td>En línea</td>
    <td>  </td>
    <td></td>
    <td>ADempiere en Línea</td>
  </tr>
  <tr>
    <td></td>
    <td>Enviar Email</td>
    <td>  </td>
    <td></td>
    <td>Envía un Email</td>
  </tr>
  <tr>
    <td></td>
    <td>Acerca de</td>
    <td>  </td>
    <td></td>
    <td>Acerca de ADempiere</td>
  </tr>
</table>


Figura 1.11

Las pestañas tienen Alt-1, Alt-2, ... vías cortas asociadas.

Menú de Contexto

<table>
  <tr>
    <td>Comando</td>
    <td>Botón</td>
    <td>Vía corta</td>
    <td>Descripción</td>
  </tr>
  <tr>
    <td>Acercamiento</td>
    <td>            </td>
    <td></td>
    <td>Le permite ir directamente a la ventana donde esta definida la entidad.</td>
  </tr>
  <tr>
    <td>Refrescar</td>
    <td>            </td>
    <td></td>
    <td>Refresca la lista del campo seleccionado.</td>
  </tr>
  <tr>
    <td>Valores de preferencia</td>
    <td>            </td>
    <td></td>
    <td>Establece valores predeterminados para los campos, por nivel de Cliente, Organización y Ventana.</td>
  </tr>
  <tr>
    <td>Editor</td>
    <td>            </td>
    <td></td>
    <td>Edita un texto (regresa una vista con HTML)</td>
  </tr>
  <tr>
    <td>Script</td>
    <td>           </td>
    <td></td>
    <td>Edita  y prueba un Script</td>
  </tr>
  <tr>
    <td>Ayuda</td>
    <td>           </td>
    <td></td>
    <td>Muestra información de ayuda</td>
  </tr>
  <tr>
    <td>Envía Email</td>
    <td>          </td>
    <td></td>
    <td>Envía un Email</td>
  </tr>
  <tr>
    <td>Archivador  de Documentos</td>
    <td>          </td>
    <td></td>
    <td>Archivador de Documentos y Reportes</td>
  </tr>
  <tr>
    <td>Personalización</td>
    <td>          </td>
    <td></td>
    <td>Establece preferencias</td>
  </tr>
  <tr>
    <td>Imprimir</td>
    <td>          </td>
    <td></td>
    <td>Imprimir documento</td>
  </tr>
</table>


Figura 1.12

Botones de Diálogo

<table>
  <tr>
    <td>Comando</td>
    <td>Botón</td>
    <td>Vía corta</td>
    <td>Descripción</td>
  </tr>
  <tr>
    <td>Ok - Acepta</td>
    <td>           </td>
    <td>Alt-O</td>
    <td>Acepta y cierra la ventana, frecuentemente se encuentra el botón predeterminado(presionando Enter se ejecuta)</td>
  </tr>
  <tr>
    <td>Cancelar</td>
    <td>           </td>
    <td>Esc, Alt-X</td>
    <td>Cancela y cierra la ventana</td>
  </tr>
  <tr>
    <td>Refrescar</td>
    <td>           </td>
    <td>F5</td>
    <td>Refresca los datos desde la Base de datos</td>
  </tr>
  <tr>
    <td>Historia</td>
    <td>           </td>
    <td>F9</td>
    <td>Despliega los registros históricos</td>
  </tr>
  <tr>
    <td>Acercamiento</td>
    <td>           </td>
    <td>Alt-Z</td>
    <td>Acercamiento – Abre una ventana para editar los datos.</td>
  </tr>
  <tr>
    <td>Proceso</td>
    <td>           </td>
    <td></td>
    <td>Proceso</td>
  </tr>
  <tr>
    <td>Imprimir</td>
    <td>           </td>
    <td></td>
    <td>Imprime información</td>
  </tr>
  <tr>
    <td>Ayuda</td>
    <td>           </td>
    <td></td>
    <td>Despliega ayuda</td>
  </tr>
  <tr>
    <td>Exportar</td>
    <td>           </td>
    <td></td>
    <td>Exportar datos</td>
  </tr>
  <tr>
    <td>Personalizar</td>
    <td>          </td>
    <td></td>
    <td>Configura personalización</td>
  </tr>
</table>


Figura 1.13

        3. Adjuntos

ADempiere posee la capacidad de adjuntar archivos para cualquier registro en el sistema. Usted puede adjuntar uno o varios archivos. Los archivos adjuntos son alojados en la base de datos  así no necesita distribuir el o los archivos. Esto se puede  emplear para adjuntar documentos escaneados para órdenes, facturas o también para incluir esquemas o diagramas para un producto.

Para adjuntar un documento a un registro sencillo seleccione el botón adjuntar en la barra de herramientas.

Se desplegará el siguiente cuadro de diálogo 

					Figura 1.14 Botón Adjuntar

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_11.jpg)

			Figura 1.15 Cuadro de Diálogo para Adjuntar

Seleccione el botón cargar para agregar el archivo o los archivos

Seleccione el archivo que desea adjuntar y seleccione el botón **Abrir**.

El archivo es cargado  y opcionalmente puede agregar texto en el lado derecho del panel.

En este momento usted puede borrar, Guardar a disco o Abrir el archivo adjunto, usted debe tener la aplicación apropiada o el visualizador adecuado para estos archivos.

  Los archivos tipo .pdf .png .gif  y .jpg aparecerán en el lado izquierdo de la ventana. Cualquier otro tipo de archivo requiere la aplicación apropiada para poder visualizarlos.

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_12.jpg)

	

		Figura 1.16 Selección de Archivo para Anexar a una Entidad

  

				Figura 1.17 Anexo

De este modo ha agregado el archivo adjunto deseado, seleccione el botón OK para salvar los archivos adjuntos en la base de datos.

Si un registro tiene un adjunto, el botón adjuntar en la barra de herramientas tendrá un color  de fondo amarillo.

Todos los usuarios que tienen acceso a este registro tendrán acceso al archivo adjunto.

Figura 1.18 

        4. Email a Soporte

Directamente desde la Barra de Herramientas de ADempiere usted puede mandar un email a su equipo de soporte (o a cualquier dirección email válida).

Al seleccionar esto desde el menú, el cuadro de diálogo email es desplegado

La dirección De: es tomada de la dirección de correo definida  para el Usuario ingresado cuando entró al sistema. Seleccione el renglón Para: y podrá observar una lista de todas las direcciones de correo definidas en el Sistema, o simplemente escriba el correo deseado.

Figura 1.19 Icono de e-mail

Figura 1.20 Cuadro de Diálogo e-mail

Los valores del texto son los encontrados en la pestaña Contexto de la ventana Preferencias. Seleccionar un Usuario/Contacto y haga Clic en el botón OK. (Figura 1.21) 

Si desea puede agregar más direcciones separadas mediante una coma (,).

Figura 1.21 Selección Usuario/Contacto 

Figura 1.22  Cuadro de Diálogo de email

Al hacer Clic en el botón OK para enviar el mensaje se desplegará el siguiente mensaje indicando que el mensaje ha sido enviado.

Los emails también pueden ser enviados desde cualquier cuadro de diálogo que es generado en ADempiere. Por ejemplo, un usuario intenta eliminar un registro y recibe el siguiente  mensaje de error.

Figura 1.23  Mensaje de envío

Figura 1.24  Mensaje de error

Entonces el usuario selecciona la opción Archivo desde el mensaje y seleccionar Enviar Email a Soporte

El mismo proceso ocurre, como se mencionó antes; siendo la diferencia que el cuerpo del email contiene el mensaje de error y el contexto de la información.

Los emails también pueden ser enviados desde los documentos. Estos se discute en el Capítulo 13, Información y Reporteo.

Figura 1.25 Opción Archivo 

    4. FLUJO DE TRABAJO

ADempiere tienen 2 tipos de flujos de Trabajo, flujos de trabajo generales y flujos de trabajo de procesos de documentos.  los Flujos de Trabajo Generales se ejecutan vía el Menú.  Ellos son definidos para ayudar al usuario  en avanzar a través de una tarea como la Configuración del Socio del Negocio o la Revisión de la Configuración Inicial de la Compañía.  Los Flujos de Trabajo del Proceso de Documento se inicial cuando se procesa un documento. Estos Flujos de trabajo pueden ser "Invisibles"  para el usuario como en las órdenes de venta, o pueden requerir que el usuario ejecute una acción para completar el proceso.  Ambos pueden definirse en ADempiere, aunque el proceso de definición de flujos de trabajo no se cubre en este manual sino se enfocó en el uso de Flujos de Trabajo .

        5. Flujo de Trabajo General

Un flujo de trabajo es una serie de pasos que tienen que ser seguidos en secuencia. Haga Clic en la pestaña Flujo de Trabajo de la ventana principal para obtener una impresión rápida de los pasos involucrados en una tarea específica. Mire el flujo de trabajo Revisión de Configuración Inicial de Compañía por ejemplo. Usted lo abre con doble Clic en el menú Reglas Generales, Reglas de la Compañía  y  Revisión de Configuración Inicial de Compañía en el menú.

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_13.jpg)

**Figura 1.26 **Flujo del Trabajo General (Menú ADempiere)

El Flujo de Trabajo se  carga. En la mitad superior de la ventana usted ve una ilustración gráfica del Flujo de Trabajo. Usted puede revisar fácilmente los pasos llevados a cabo durante la configuración. En la parte inferior de la ventana usted ve la explicación relevante del paso del flujo de trabajo o nodo. Para navegar a través de los diferentes pasos y abrir la ventana apropiada usted puede, hacer doble Clic en el icono del Flujo de Trabajo específico en la gráfica o usar los botones del Flujo de Trabajo.

<table>
  <tr>
    <td>Comando</td>
    <td>Botón</td>
    <td>Vía corta</td>
    <td>Descripción</td>
  </tr>
  <tr>
    <td>Ir al inicio</td>
    <td>    </td>
    <td></td>
    <td>Inicia otra vez el flujo de trabajo</td>
  </tr>
  <tr>
    <td>Regresar un paso</td>
    <td>    </td>
    <td></td>
    <td>Regresa un paso en el flujo de trabajo</td>
  </tr>
  <tr>
    <td>Próximo paso</td>
    <td>    </td>
    <td></td>
    <td>Próximo paso del flujo de trabajo</td>
  </tr>
  <tr>
    <td>Fin</td>
    <td>    </td>
    <td></td>
    <td>Fin del flujo de trabajo</td>
  </tr>
</table>


Figura 1.27 Botones del Flujo de Trabajo

        6. Flujos de Trabajo de Procesos de Documentos

Los  Flujo de Trabajo de Procesos de Documentos son iniciados cuando un se procesa un documento. En ADempiere un documento  es una Orden de Venta,  Factura, Recibo de Materiales, Asientos Contables, Estado Bancario, etc. Los Flujos de Trabajo de Procesos de  Documento pre-definidos son transparentes básicamente para el usuario. Por ejemplo, hay un flujo de trabajo para el procesamiento de una Orden Punto de Venta (PDV).  Una orden PDV es ingresada y al ser procesada el embarque y las facturas son automáticamente generados. Esto es en contraposición con las  órdenes estándar donde el embarque y la factura son generados en un proceso en lote. El flujo de trabajo definido es el que controla qué documentos son generados y que proceso se realizará con cada uno. En general le sugerimos que usted no  modifique el flujo de trabajo de  los procesos de  documentos existentes más allá de adicionales algunas tareas  (Ej. Aprobar OC por encima de un importe específico).

ADempiere provee unos "patrones" de Flujo de Trabajo de  Procesos de Documento definido por el  usuario. Emplearemos estos a modo de ejemplo de cómo un usuario final puede interactuar con ADempiere cuando los flujos de trabajo están establecidos.

El Flujo de Trabajo Requisición tiene los siguientes Pasos o Nodos.

* Se introduce un  documento de Requisición.

* Si el importe total es mayor de 100 este debe ser aprobado.

* Después de ser aprobado se genera un informe para la requisición.

* El Informe es enviado al usuario que ingresó la requisición.

* El usuario puede dar un acuse de recibo de que el Informe ha sido recibido.

* El usuario revisa la Requisición 

* La requisición puede ser cerrada.

Comenzaremos con la requisición haciendo doble Clic en el menú Requisición a Factura< Requisición 

La ventana Requisición puede ser empleada para ingresar requisiciones de compra. Solamente discutiremos esta ventana de manera general ya que los campos y sus funciones específicas serán discutidos en detalle en Capítulos posteriores.

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_14.jpg)

Figura 1.28 Requisición a Factura < Requisición 

Note que el Usuario/Contacto  es GardenUser. Es la persona responsable para este flujo de trabajo. Ellos recibirán cualquier aviso referente a este flujo de trabajo.

Seleccione Línea Requisición para ingresar los productos requisitados.

Una línea es ingresada por cada producto.

Cuando todas las líneas han sido ingresadas, regrese a la pestaña Requisición y seleccione el botón Completar. Este es el proceso que iniciará el Flujo de Trabajo.

Al finalizar el Proceso, note el estado de nuestra requisición.

El Estado del Documento es en Proceso  y el texto de mensaje muestra un mensaje de Suspendido.

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_15.jpg)

Figura 1.29 Requisición a Factura < Requisición

    			Figura 1.30 Botón Completar. 

Seleccione el botón Flujo de Trabajo en la barra de herramienta para consultar este Flujo de Trabajo.

La ventana Proceso Flujo de Trabajo es desplegada para este Flujo de Trabajo. El Estado del Flujo de Trabajo indica Suspendido.

La Sección Referencia despliega información acerca del responsable de este Flujo de Trabajo y el Usuario/Contacto. Adicionalmente puede agregar un mensaje de Texto si lo desea. Usted puede seleccionar el botón ID de registro para un acercamiento  a la Requisición.

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_16.jpg)

Figura 1.31 Requisición a Factura < Requisición

Figura 1.32 Administrador del Sistema < Reglas Generales < Flujo de Trabajo < 

                     Proceso Flujo de Trabajo 

Seleccionar el botón Manejador de Procesos si desea cambiar el Responsable Flujo de Trabajo, Usuario/Contacto o si usted desea abortar el Flujo de Trabajo.

Seleccione la pestaña Actividad para verificar información sobre actividades específicas para este flujo de trabajo.

El Proceso del Flujo de Trabajo es el  Process_Requisition y el Nodo es la Requisition Approval. El Estado Flujo de Trabajo es Suspendido. Esto indica que el Flujo de Trabajo ha sido Suspendido en el paso o Nodo Aprobación.

	

Figura 1.33  Manejador de Proceso 

Figura 1.34 Administración del Sistema < Reglas Generales < Flujo de Trabajo < 

                     Proceso Flujo de Trabajo

El Usuario/Contacto es GardenAdmin lo cual indica que este es el usuario quien debe aprobar esta Requisición.

Usted puede seleccionar el botón Manejador de Actividades  para cambiar al Responsable del Flujo de Trabajo, Usuario/Contacto o para Abortar la Actividad.

Ahora sabemos que GardenAdmin debe aprobar esta Requisición. Esto se debe a que el Rol de GardenAdmin ha sido definido como se muestra en la figura 1.36

Figura 1.35 Manejador de Actividades 

Figura 1.36 Administración del Sistema < Reglas Generales < Seguridad < Rol 

Para este Rol, El cuadro de verificación Aprobar Documentos Propios no ha sido seleccionado y el supervisor está establecido como GardenAdmin. Cualquier Documento introducido por un usuario con el Rol de GardenUser debe ser aprobado por GardenAdmin.

Para información adicional acerca de Roles y Usuarios, por favor refiérase al Capítulo 19, "Seguridad."

Ahora nos registraremos como GardenAdmin para aprobar la Requisición. El menú para GardenAdmin indica que hay una Actividad de Flujo de Trabajo para GardenAdmin.

Figura 1.37 Menú ADempiere

La segunda pestaña en la parte superior del menú despliega el número de Actividades de Flujo de Trabajo para este Usuario.

El Nodo del Flujo de Trabajo. La Descripción y la Ayuda junto con los registros Históricos. Seleccione una Respuesta de Si y cualquier Mensaje para Aprobar la Requisición.

Usted puede también Reenviar esta Actividad a un Usuario diferente si es lo adecuado.

El botón OK se selecciona para Aprobar (o Rechazar) esta Requisición.

Figura 1.38 Administrador del Sistema < Reglas Generales < Flujo de Trabajo < 

                     Actividades del Flujo de Trabajo 

Usted también puede acceder a cualquier Actividad Abierta asignada a un Usuario a través de seleccionar Actividades del Flujo de Trabajo desde el menú. Si usted tiene los privilegios adecuados también puede ver todas las Actividades del Flujo de Trabajo seleccionando  Actividades del Flujo de Trabajo (todas) desde el menú.

Si regresamos al menú GardenUser:

Figura 1.39 Menú ADempiere 

El botón Aviso en la esquina inferior izquierda indica el número de Avisos para este Usuario. Haga doble Clic en el botón Aviso para abrir la ventana Aviso.

La Descripción indica que este Aviso es un Detalle de Información de una Requisición Abierta.

Seleccione el botón Adjuntar en la barra de herramientas para ver el reporte.

GardenUser puede dar acuse de recibo del reporte seleccionando el cuadro de verificación Acuse de Recibo.

	

Figura 1.40 Administración del Sistema < Reglas Generales < Reglas del Sistema < 

                    Aviso 

Figura 1.41 Botón Adjuntar 

Usted puede tener acceso a cualquier Aviso asignado a un Usuario seleccionando Avisos  desde el menú.

Aún hay una Actividad asignada al Usuario. Seleccione la pestaña Actividad del Flujo de Trabajo en el menú.

Seleccione el botón Verificar Requisición completada para completar el Flujo de Trabajo. Usted puede agregar un mensaje si lo desea.

Figura 1.42 Menú ADempiere – Flujo de Trabajo 

Finalmente, use el botón Acercamiento para tener un acercamiento a la Requisición y cerrarla si lo desea.

Seleccione el botón Cerrar para cerrar esta Requisición.

Este flujo de trabajo es un ejemplo de cómo los flujos de trabajo pueden ser definidos. Como su Compañía usa  los flujos de trabajo y cómo los usuarios interactúan con ellos dependerá de su definición.

ADempiere se asegura de que dos usuarios no podrán iniciar el mismo flujo de trabajo de proceso de documento. Si un usuario intenta iniciar un flujo de trabajo que ya ha sido iniciado se desplegará el mensaje siguiente.

El Mensaje indica que un Flujo de Trabajo existe y en qué etapa está. Este mensaje fue cuando un Usuario intentó procesar la Requisición introducida que estaba esperando Verificación por GardenUser.

Figura 1.43 Requisición a Factura < Requisición 

Figura 1.44 Aviso Requisición 

    5. FUNCIONES DE AYUDA

        1. Pantalla de Ayuda 

ADempiere proporciona Ayuda en la ventana en la que se encuentre trabajando. Sólo abra el Menú Ayuda en cualquier ventana y seleccione Ayuda o presione F1.

Una ventana  Ayuda se abre y despliega toda la información acerca de la ventana en la que usted se encuentra, en este caso la ventana Rol. La Ventana Ayuda incluye información sobre la ventana, las pestañas y los campos. Usted puede utilizar la barra de desplazamiento en la ventana de Ayuda o Clic directamente en los enlaces.

Figura 1.45 Administración del Sistema < Reglas Generales < Seguridad < Rol 

La información de la ventana muestra una descripción corta de la ventana y provee enlaces a las diferentes Pestañas.  Con Clic en los enlaces de Pestaña se despliega la información correspondiente a esa pestaña, por ejemplo Acceso a Flujo de trabajo:

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_17.jpg)

Figura 1.46 Ventana Ayuda Rol

Usted estará enlazado a la pestaña  Acceso a Flujo de trabajo,  lo que despliega una descripción corta de la pestaña y proporciona enlaces a los diferentes Campos. Clic en los enlaces de los Campos para obtener la información del Campo correspondiente, por ejemplo Lectura Escritura:

La información del Campo despliega una descripción corta del campo seleccionado.

Figura 1.47 Ventana Ayuda Acceso a Flujo de Trabajo 

        7. Ayuda en Línea

ADempiere también proporciona Ayuda en Línea sobre cada ventana en la que se encuentre. Abra el menú Ayuda en cualquier ventana y seleccione En Línea:

Figura 1.48 Gestión de Materiales < Reglas de Gestión de Materiales < Producto 

Esto llamará a la Página Principal de ADempiere donde encontrará muchas fuentes de información, por ejemplo Forums, Q&A, Telephone Support, etc. El  menú Search  en el lado izquierdo le proporcionará las respuestas correctas:

    6. **FUNCIONES DE VENTANA**

ADempiere soporta diferentes funciones en el contexto de ventana, esto le permite introducir información muy fácilmente desde la ventana en la que se encuentre. En nuestro ejemplo, buscamos una orden de venta. Usted abre la ventana **Orden de Venta  **presionando Ctrl-Enter (Alter-Enter o Shift-Enter) en el campo de búsqueda, haciendo doble Clic en la opción del árbol del menú o Clic en la opción en la vía corta en su menú.

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_18.jpg)

Figura 1.51 Cotización a Factura < Orden de Venta < Orden de Venta 

        2. Valor de Preferencia

La función Valor de Preferencia en el menú de contexto le permite establecer sus preferencias directamente desde la ventana en la que se encuentre.

La ventana Orden de Venta aparece con las preferencias/valores predeterminados que usted establece para su Compañía (Garden World) y Organización (HQ). Los campos opcionales tienen un fondo azul, los campos obligatorios tienen un fondo resaltado, Los campos rojizos son campos obligatorios que aún requieren un valor.

Para establecer sus preferencias llene el campo o seleccione el valor deseado desde la lista de selección (por ejemplo, cambie el campo Tipo Documento Destino  de Orden Estándar a Orden PDV), después use el botón derecho del Ratón y seleccione Valor de Preferencia desde el menú.

Figura 1.52  Cotización a Factura < Orden de Venta < Orden de Venta 

Seleccione el alcance (Compañía para todos, Organización específica, Usuario y Ventana) y presione OK. Su nuevo valor predeterminado será ahora Orden PDV en la ventana Orden de Venta.

El nivel para el cual un usuario puede fijar preferencias del valor se define en el rol.

Para información adiciona acerca de roles, por favor refiérase al Capítulo 2, " Implementación y Configuración Básica".

Figura 1.53 Valor de Preferencia 

        8. Nuevo Registro

La función Nuevo Registro en el menú de contexto le permite crear un nuevo Socio del Negocio directamente desde la ventana en que se encuentre. Usted normalmente crearía un nuevo Socio del Negocio importándolo  o introduciéndolo en la ventana Socio del Negocio. Ocasionalmente es necesario al introducir un documento dar de alta un nuevo Socio del Negocio rápidamente.

En el campo Socio del Negocio, use el botón derecho del ratón y seleccione Nuevo Registro:

Figura 1.54   Cotización a Factura < Orden de Venta < Orden de Venta

Introduzca la información del cliente. Para introducir la información de dirección, Clic en el botón Localización junto al campo Localización/Dirección:

Se despliega la ventana Entre nueva Localización/Dirección. Introduzca la información de la dirección:

Clic OK en ambas ventanas. La Orden de Venta se actualiza automáticamente con la nueva información.

![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_19.jpg)

**Figura 1.55 **Ventana Localización del Cliente 

**Figura 1.56 **Ventana Entre Nueva Localización / Dirección

Los valores del resto de los campos  para el nuevo socio del negocio son tomados de los valores predeterminados para los Socios del Negocio definidos para esta compañía. Estos pueden ser modificados directamente en la ventana **Socio del Negocio.**

**Figura 1.57 **Cotización a Factura < Orden de Venta < Orden de Venta

        9. **Acercamiento**

La función Acercamiento en el menú de contexto le permite ir directamente a la ventana donde está  definida la entidad. Usted puede entonces determinar que valor quiere usar o puede crear otro registro.

En el campo opcional **Proyecto,** use el botón derecho del ratón y Clic en **Acercar**:

**Figura 1.58 **Gestión de Proyecto < Proyecto 

La ventana **Proyecto** se abre. Si el campo "Acercamiento" tiene una selección, la ventana **Acercamiento** consultaría el registro seleccionado automáticamente. Si el campo "Acercamiento" está en blanco, un nuevo registro se abre automáticamente en la ventana Proyecto.

Figura 1.59 Gestión de Proyectos < Proyecto 

Introduzca un nombre de proyecto en el campo obligatorio Nombre. 

Clic en el botón ![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_20.png) Guardar en la Barra de Herramientas y cierre la ventana. Use ya sea el botón X en la esquina superior derecha de la ventana  (con lo que los cambios pendientes serían ignorados) o Clic en el botón ![image alt text]({{ site.url }}/public/4jYjlGLdKGhPcRnNPrw_img_21.png) en el extremo derecho de la Barra de Herramientas, lo que automáticamente guardará sus cambios:

Figura 1.60 Gestión de Proyecto < Proyecto 

        10. Refrescar

Atrás en su ventana Orden de Venta, el nuevo proyecto no está aún disponible. Clic-derecho en el campo Proyecto y seleccione Refrescar:

**Figura 1.61 **Cotización a Factura < Órdenes de Venta < Orden de Venta 

### Búsqueda e Info 

Búsqueda se usa cuando hay un gran número de registros y usted quiere reducir la lista de registros que serán devueltos.

En la ventana Orden de Venta cambie a la pestaña Línea de la Orden con Clic.

En el campo Producto, introduzca %Bush (usted está buscando un producto con "bush" ,ignorando mayúsculas/minúsculas, en la clave de búsqueda) y presione Enter:

**Figura 1.62 **Cotización a Factura < Órdenes de Venta < Orden de Venta 

Usted puede ver la disponibilidad del producto y su precio basado en una  lista de precio. Usted puede realizar búsquedas basadas en el Nombre del producto, UPC/EAN o UM Almacenamiento. 

Seleccione un producto a través de un Clic en él y Clic OK o sólo doble Clic en la línea:

Figura 1.63 Información de Producto 

Si la lista de opciones es larga, se usa un campo de Búsqueda general en vez de una lista de selección. Por ejemplo, bajo Cotización a Factura < Consulta a Profundidad de Orden usted encuentra abierta la ventana Info Orden:

Si usted introduce un criterio de búsqueda único en el campo Búsqueda (por ej. introducir  C&W en el campo de búsqueda Socio del negocio), la búsqueda devuelve  solamente un registro C&W Construction (la ventana de búsqueda actual no se abre)

Figura 1.64 Información de la Orden 

Si usted usa un comodín en el campo de búsqueda la ventana de búsqueda se abre desplegando una lista de todos los Socios del Negocio:

O Clic en el icono a la derecha del campo de búsqueda Socio del Negocio en la ventana Info Orden e introduzca su criterio de búsqueda en esta ventana:

Usted puede realizar búsquedas basadas en la Clave de Búsqueda del Socio del Negocio, Nombre, Contacto, Email, Teléfono o C.P. Seleccione el cuadro de verificación Solo Clientes si usted solo desea desplegar Socios del Negocio que han sido definidos como Clientes, Seleccione el cuadro de verificación búsqueda difusa  si usted desea que la búsqueda use la lógica "o"  cuando existan múltiples búsquedas  (Ej. cuando el nombre es %fam% o el C.P. Es 04456).

Figura 1.65 Información de la Orden 

Figura 1.66 Información de la Orden 

        11. Ventanas de Alto Volumen

Algunas ventanas en ADempiere están diseñadas como ventanas de Alto Volumen. Éstas incluyen Socios del Negocio y Productos. Como usted puede tener miles de registros para estas ventanas. ADempiere desplegará una ventana de Encontrar Registro cuando se seleccione uno de estas opciones de menú.

Figura 1.67 Gestión de Materiales < Reglas de Gestión de Materiales < Producto 

Seleccione el botón Registros Nuevos si desea desplegar la ventana en modo registros nuevos conteniendo solamente los valores predeterminados. 

Usted puede también seleccionar la pestaña Avanzado  para introducir más  criterios de búsqueda 

Todos los campos definidos para el registro (en este ejemplo Producto) están disponibles para búsqueda. seleccione la Columna, Operador y Valor de Consulta.

 Seleccione el campo A Valor a Consultar si se selecciona un rango en Operador. Si desea añadir más criterios de búsqueda seleccione el botón Salvar para salvar la primer línea de consulta y seleccione el botón Registro Nuevo para añadir el criterio adicional. Todas las líneas serán evaluadas usando la lógica "y", de tal manera que todas las condiciones deben ser alcanzadas.

Seleccione el botón OK para ejecutar la búsqueda y regresar a la ventana Producto con los registros que alcancen el criterio de búsqueda.

Seleccione el botón Cancelar para cancelar la búsqueda y regresar todos los registros.

Figura 1.68 Gestión de Materiales < Reglas de Gestión de Materiales < Producto 

        12. Info Registro 

Cada ventana en ADempiere le proporciona información del registro actual. En la parte inferior derecha de la ventana usted encuentra un campo que despliega dos valores (Figura 1.69 y 1.70) 

Un + en el frente del valor indica que el registro fue insertado, un * indica que  el registro fue cambiado.

Doble o Clic derecho en esos valores para desplegar la persona que creó y/o actualizó este registro y cuando lo hizo (figura 1.71)

Figura 1.69 Administración del Sistema < Reglas Generales < Seguridad < Usuario 

Figura 1.70 Campo de Valores

Esta ventana puede también desplegar seguimiento de auditoría acerca de que campos fueron cambiados, junto con el Rol que actualizó el registro y la fecha.

Esta funcionalidad puede ser habilitada a nivel de Tabla o de Rol. Para habilitar a nivel de Tabla seleccione el cuadro de verificación Mantener Histórico de Cambios para la tabla(s) deseada.

En este ejemplo, cualquier cambio hecho a la tabla Client por cualquier usuario será mantenido en el histórico.

Figura 1.71 Información del Registro 

Figura 1.72

Para habilitar en el nivel de Rol seleccione el cuadro de verificación Mantener Histórico de Cambios para el Rol(es) deseado.

En este ejemplo cualquier actualización hecha por un usuario registrado en ADempiere con el Rol de GardenAdmin mantendrá un registro histórico.

Si usted esta registrando los cambios, éstos pueden ser des-aplicados y re-aplicados usando la Auditoría de Cambios y la ventana Auditoría de Sesión.

 Figura 1.73 Administración del Sistema < Reglas Generales < Seguridad < Rol

    7. PREFERENCIAS DE USUARIO

Las preferencias de usuario le permiten determinar el despliegue de la Compañía y como reaccionará a acciones específicas de usuarios. Se puede acceder a Preferencias de usuario seleccionando Herramientas < Preferencia en el menú Principal.

        13. Pestaña Preferencia

Guardar  Automáticamente

Si usted selecciona el cuadro de verificación Guardar Automáticamente, sus cambios son automáticamente guardados al navegar dentro de  una sola  pestaña. Al cambiar de pestaña usted debe confirmar la acción sin importar este ajuste.

Mantenimiento del  Diccionario

Este cuadro de verificación no  debe ser seleccionado, solamente es empleado para el desarrollo de ADempiere.

Figura 1.74 Herramientas < Preferencias (Menú Principal de ADempiere)

Entrada Automática al Sistema

Si selecciona el cuadro de verificación Entrada Automática al Sistema, la ventana de ingreso no se desplegará al iniciar ADempiere. Esto empleará el Usuario, Contraseña, Rol, Compañía y Organización proporcionados en el ingreso previo. Si desea cambiar alguno de estos valores usted debe re ingresar, deseleccionando este cuadro de verificación al salir de ADempiere. La siguiente ocasión usted será presentado en la ventana  de inicio y podrá ingresar los valores deseados.

Guardar Contraseña 

Si selecciona el cuadro de verificación Guardar Contraseña, ADempiere recordará  el Nombre de Usuario y Contraseña ingresado para el ingreso  previo. Estos valores pueden ser sobre escritos si es necesario.

Mostrar Pestañas de Contabilidad / Mostrar Pestaña de Traducción

Si selecciona el cuadro de verificación Mostrar Pestañas de Contabilidad / Mostrar Pestaña de Traducción, ADempiere mostrará estas pestañas en cada ventana según sea apropiado. El Administrador de Sistema muy probablemente tendrá seleccionado este cuadro de verificación. 

Mostrar Pestañas Avanzadas

Si selecciona el cuadro de verificación Mostrar Pestañas Avanzadas, ADempiere mostrará estas pestañas en cada ventana según sea apropiado. Estas pestañas aparecerán en ventanas como Ordenes, Entregas/Recibo, Facturas, Pagos e Inventario. Las pestañas son de sólo lectura y proporcionan información generalmente necesaria al intentar resolver un problema. La mayoría de los usuarios no lo tendrán deshabilitado mientras los desarrolladores pueden.

Registro Nuevo  Automático

Si selecciona el cuadro de verificación Registro Nuevo Automático cuando usted se mueve de una pestaña padre a una pestaña hijo en una ventana y no existe registro, ADempiere desplegará los valores predeterminados para un registro nuevo. Si este cuadro de verificación no es seleccionado, deberá seleccionar entre Editar/Nuevo, Ctrl N o el botón Nuevo en la barra de herramientas para crear  un registro nuevo.

Perfil de Conexión

En el menú desplegable Perfil de Conexión seleccionar el perfil de conexión adecuado (este también se puede ajustar al ingresar a ADempiere).

LAN: No abre el Túnel http. No crea objetos en el servidor. No crea procesos en el servidor.

WAN: Abre el Túnel http. Crea objetos en el servidor. Crea procesos en el servidor. (Esto reducirá el tráfico en la red. Los Objetos creados en el servidor requerirán gran cantidad de recursos del servidor.)

SERVIDOR TERMINAL: Similar a LAN pero hay algunas limitantes en la interfase de usuario opciones del tema. 

VPN: No abre el Túnel http. Crea objetos en el servido. Crea procesos en el servidor. (Esto reducirá el tráfico en la red. Los Objetos creados en el servidor requerirán gran cantidad de recursos del servidor.)

Caché de Ventanas

Si selecciona el cuadro de verificación Caché de Ventanas. ADempiere almacenará cada ventana que es abierta. Esto debe ser empleado si las mismas ventanas son abiertas y cerradas varias veces durante una sesión de usuario. La memoria caché puede ser borrada en cualquier momento mediante la ejecución del proceso Restaurar Caché.

Nivel de Seguimiento  

El nivel de seguimiento indica el  contexto del mensaje del depurador que serán generados mediante ADempiere. Seleccione un valor de Apagado, Severo, Precaución, Informe, Fino, Mas Fino, Finísimo o Todo. En la mayoría de los casos Severo o Precaución será suficiente. Usted puede ser solicitado para modificar esta configuración en la solicitud de soporte para un problema específico.

Archivo de Seguimiento

Seleccionar el cuadro de verificación Archivo de Seguimiento si desea que los mensajes del depurador sean guardados en un archivo. Este archivo estará en el directorio logs. Debe estar seguro que el directorio cuenta con los permisos de lectura/escritura correspondientes. 

Impresora

El campo Impresora le permite seleccionar la impresora a emplear en la impresión de Documentos y Reportes. Esto anulará los valores ingresados al iniciar ADempiere.

Siempre Ver Borrador de la Impresión 

Si selecciona el cuadro de verificación Siempre Ver Borrador de la Impresión  ADempiere siempre desplegará en pantalla la vista preliminar de cualquier Documento. Reporte o Pantalla. Esto es altamente recomendable si usted está creando nuevos reportes o formatos de impresión.

Fecha

El campo Fecha le permite seleccionar una fecha a ser empleada en los documentos. Esto anulará los valores ingresados al iniciar ADempiere.

Las Preferencias de Usuario solamente pueden ser configuradas mediante un Usuario en un Rol con Nivel de Preferencia ajustado a la Compañía. Usted puede prevenir la actualización de las preferencias mediante la configuración apropiada de Nivel de Seguridad.

Para información+ adicional acerca de Roles, refiérase al Capítulo 2, "Implementación y Configuración Básica."

Para información+ adicional acerca de Seguridad, refiérase al Capítulo 19, "Seguridad."

Pestaña Tema Interfase de Usuario

La pestaña Tema Interfase de Usuario le permite seleccionar la apariencia de ADempiere. Usted puede seleccionar diferentes estilos y colores así como también podrá previsualizar sus selecciones antes de ser salvadas.

Pestaña Información

La Pestaña de Información provee una sinopsis del ambiente en el cual se encuentra el usuario. El Hosts, Base de Datos, Rol, etc. Esto es útil si hay preguntas respecto al ambiente en el cual el usuario está trabajando.

        14. Pestaña de Contexto

La Pestaña de Contexto proporciona información sobre la información+ con la cual cuenta el sistema. Esto se emplea generalmente si usted está desarrollando sus propias ventanas o procesos en ADempiere.

Figura 1.75 Pestaña Tema Interfase de Usuario  

        15. Pestaña de Errores

La pestaña de errores muestra cualquier error que  ha sido generado. Al seleccionar  esta pestaña únicamente se mostrarán errores.

Se despliega la Hora, Nivel, Método de Clase y el  error. Si da Clic en el botón Solamente Errores para deseleccionar este verá todo el mensaje de nivel de seguimiento. El nivel de los mensajes desplegados es dictado por el Nivel de Seguimiento definido en Preferencias de Usuario. 

Porque el nivel de seguimiento fue ajustado a Fino, un número largo de mensajes son desplegados. En operaciones normales usted podría ajustar su Nivel de Seguimiento a Severo. 

Seleccione el botón Restaurar para limpiar todos los mensajes.

Seleccionar el botón Enviar Email para enviar el mensaje seleccionado como cuerpo de un correo electrónico.

Seleccionar el botón Guardar a Archivo para  guardar todos los errores en un archivo. El archivo  contactará al dato de contexto.

Figura 1.76 Pestaña Errores. 

    8. **CAMPOS COMUNES**

Algunos campos en ADempiere se despliegan con frecuencia y usted debe saber para que se usan:

        16. **Activo**

        17. Un campo común es el cuadro de verificación Activo. Hay dos métodos para hacer que los registros no estén disponibles en el sistema: Uno es eliminar el registro, el otro es desactivarlo. Un registro desactivado no está disponible para selección, pero está disponible para reportes. Hay dos  razones para desactivar un registro y no para eliminarlo:

1. El sistema requiere el registro para propósitos de auditoria

2. El registro está referenciado por otros registros. P. ej. usted no puede eliminar un Socio del Negocio si existen facturas para este socio del negocio. Usted desactiva el socio del negocio y evita que este registro sea usado en futuras entradas.

        18. Compañía

Esta es la Compañía para esta instalación. Una Compañía es una empresa o entidad legal

        19. Predeterminado 

El cuadro de verificación Predeterminado indica si este registro será utilizado como un valor predeterminado.

        20. Descripción

La Descripción es una descripción opcional corta del registro. La descripción se limita a 255 caracteres.

        21. No. de Documento

El No. de Documento es usualmente generado automáticamente por el sistema a través del tipo de documento. Si el documento no se salva, el número preliminar se despliega entre < >.

Si el tipo de documento de su documento no tiene definida una secuencia de documento automático, el campo se encuentra vacío cuando usted crea un documento nuevo. Esto tiene utilidad cuando se trabaja con documentos que usualmente tienen un número externo (como facturas de proveedor). Si usted deja el campo vacío el sistema generará un No. de documento por usted.

La secuencia de documento usada para este número se define en la ventana Secuencia de Documentos bajo Análisis de desempeño < Reglas contables < Secuencias de Documentos. Su nombre es DocumentNo_ donde TableName es el nombre actual de la tabla (por ej. C_Order):

        22. Nombre

El Nombre es el identificador alfanumérico de la entidad. El Nombre de una entidad (registro) se usa como una opción de búsqueda predeterminada adicionalmente a la clave de búsqueda. El nombre está formado de hasta 60 caracteres.

        23. Organización

Ésta es la entidad organizacional dentro de la compañía. Una Organización es una unidad de su Compañía o entidad legal, por ej. tiendas, departamentos, etc.

        24. Nivel Sumario

El cuadro de verificación Nivel Sumario indica que la entidad es una entidad Sumaria. Las entidades sumarias se usan en los árboles de Producto y solamente para propósitos de reporte. No tienen valores asociados con ellas y no aparecerían en listas de precios, reabastecimiento de almacén, etc.

        25. Traducido

        26. El cuadro de verificación traducido indica si esta columna está traducida.

Figura 1.77 Análisis de Desempeño < Reglas Contables < Secuencia de Documentos 

