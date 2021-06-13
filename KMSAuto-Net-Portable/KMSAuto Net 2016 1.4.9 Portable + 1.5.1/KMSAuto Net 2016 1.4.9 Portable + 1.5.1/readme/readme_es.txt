
                        KMSAuto Net 2016 Portable by Ratiborus,
                                       MSFree Inc.

       		                    Requisitos del Sistema: 
                          —————————————————————————————————
Ediciones VL: Windows Vista, 7, Windows 8, 8.1, 10, Server 2008, 2008 R2, 2012,
2012 R2, Office 2010/2013/2016.

       		                         Descripción:
                          —————————————————————————————————
KMSAuto Net - Activador KMS automático para sistemas operativos 
Windows ediciones VL: Vista, 7, 8, 8.1, 10, Server 2008, 2008 R2, 2012,
2012 R2, 2016 así como Office 2010, 2013, 2016.

Adicionalmente, el progrma activa:
	Windows 8.1 Single Language;
	Windows 8.1 Core;
	Windows 8.1 Core N;
	Windows 8.1 Pro WMC;
	Windows Embedded 8.1 Industry Pro;
	Windows Server 2012 R2 Standard;
	Windows Server 2012 R2 Datacenter.
Basado en el KMS Server Service de mikmik38 (MDL).

  
       		                   Uso del programa:
                          —————————————————————————————————
Ejecuta KMSAuto Net.exe como administrador y usa la interfaz. Si necesitas funcionalidades 
adicionales, habilita el Modo Profesional. El botón On/Off del Modo Profesional está
ubicado en la Pestaña "Acerca de".
La manera más fácil de usar el programa es elegir el modo automático. Todo lo que necesitas
hacer es pulsar el botón si quieres activar y aceptar el crear una tarea programada para
reactivación al presionar el botón.

Tip: Primero necesitas activar Windows y Office en modo manual, y sólo entonces, cuando
estés seguro de que se lleva a cabo la activación, puedes crear una tarea programada
para la reactivación de productos cada 25 días.
Si el sistema no quiere activarse en el Modo Profesional ve a "Utilidades" e instala
manualmente una key GVLK para la Edición de Windows apropiada, y luego trata de activar
otra vez.

                               Información Adicional:
                          —————————————————————————————————
							 
Para activar Windows 8.1 el adaptador de red TAP debe estar instalado directamente y
usar la direccion IP 10.3.0.2-254 o usar el driver especial. Todas estas características
están integradas al programa.
Para activar vía LAN, la interfaz TAP no pude ser usada para instalar y activar por la 
dirección de una computadora en la red.
Si reconfiguras el programa y deja de operar correctamente - marcar la casilla 
"Resetear el programa". Todos los ajustes volverán a default. 


		  Parámetros adicionales del programa (switches):
                          —————————————————————————————————
/win=act	- Ejecutar este programa en modo silencioso, activar Windows
		  y salir del programa.
/off=act	- Ejecutar este programa en modo silencioso, activar Office
		  y salir del programa.
/log=yes	- Ejecutar este programa en modo silencioso, crear un archivo ActStatus.log
		  y salir del programa.
/kmsset=yes	- Ejecutar este programa en modo silencioso, instalar el servicio KMS
          	  y salir del programa. Sólo es para el Servicio KMS, sin TAP, WinDivert, Hook.
/kmsdel=yes	- Ejecutar este programa en modo silencioso, remueve el Servicio KMS y 
              salir del programa.
/key=yes	- Ejecutar este programa en modo silencioso, instala la key de Windows y 
              salir del programa.
/task=yes	- Ejecutar este programa en modo silencioso, crear una tarea programada
              para la Activación de Windows y Office cada 25 días y salir.
/taskrun=yes	- Ejecutar este programa en modo silencioso, ejecutar el programador de
                  tareas para la Activación de Windows y Office y salir del programa.
/convert=	- Ejecutar este programa en modo silencioso, preparación para realizar la
              conversión de la versión de Windows y salir del programa.
			  Posibles valores de key: win81pro, win81ent, win81, win81sl, win81wmc
			  Después de usar esta función, necesitas reiniciar tu computadora.	
/sound=yes	- Habilitar sonidos.
/sound=no	- Deshabilitar sonidos.  
		  
                          —————————————————————————————————
La activacion se realizará con los ajustes definidos en la pestaña KMS-Service.


                          —————————————————————————————————
Cuando transfieres el programa a otra computadora, necesitas resetear el Modo Auto.
La activación podría seguir en automático, pero el modo no sería el óptimo para
tu nueva computadora.
Para resetear el modo auto a su estado inicial necesitas cambiar a cualquier otro modo,
y después seleccionar auto otra vez. Todo estará reseteado a su estado inicial.

		    Acerca de cómo activar el programa integrado				
                          —————————————————————————————————
El programa puede realizar la activacion con el Emulador de Servidor KMS de varias maneras 
diferentes. ¿Por qué varias?: el modo estándar de conectar al servidor de activación a través
del host local (127.0.0.2-254) fue blqueado en Windows 8.1. 
Todos los métodos que son previstos para la activación de alguna manera tratan de burlar o 
engañar al sistema, lo hace haciendo pensar que el servidor KMS no está en tu computadora, sino
lejos en la red.

					
		   Resumen acerca de los modos de operación del programa:
                           —————————————————————————————————
Auto	 - el programa trata automáticamente de encontrar el modo que mejor le va a tu sistema
           de activación. Intentos de activar el sistema o a Office son realizados por los modos
           permitidos que tu sistema tiene, y el que el programa elija será el que recuerde.
	       Para resetear al modo inicial, puedes cambiar a cualquier otro modo y después
           seleccionar Auto. Este es el modo seleccionado por default.           	
Hook     - método basado en la sustitución del archivo de sistema cambiado de un modo especial.
           La nueva versión funciona sin reemplazar físicamenete el archivo.
WinDivert- en el sistema un driver es instalado al momento de la activación y se mantiene
	       ejecutado para emular una conexión remota al servidor KMS.	  
NoAuto   - En este modo, no hay automatización, hay necesidad de seleccionar el modo en que
	       trabajará. Está destinado para personas que saben mejor que yo qué, cómo y cuando 
           hacer lo que desea y lo que no. :)	
TAP      - el sistema es un dispositivo virtual. La activación TAP es realizada a través de este
           dispositivo virtual. El programa incluye dos drivers para el adaptador TAP. Si tú ya 
	       instalaste uno de los drivers, el programa usará el otro driver para activar, 
	       resultando en que tu adaptador actual queda intacto.           	   
* Nombres de modos en la pestaña de Sistema - al hacer click en los links con los cuales puedes cambiar 
  algún ajuste.
  
				 Opciones de KMSSS.exe
                          —————————————————————————————————
Parámetros de la Línea de Comandos:
  -Port <Port Value> - Puerto KMS. Rango de 1 a 65535
         -PWin <PID> - Windows PID
         -PO14 <PID> - Office 2010 PID
         -PO15 <PID> - Office 2013 PID
      -AI <Interval> - Intervalo de Activación. Rango de 15 a 43200 minutes
      -RI <Interval> - Intervalo de Renovación. Rango de 15 a 43200 minutes
              -Debug - Detailed info.
                -Log - Log file Habilitado.
		 -IP - Muestra las direcciones IP de las Computadoras Cliente.
         Hwid <HWID> - Machine Hardware Hash.

                          —————————————————————————————————
El programa requiere .NET Framework 4.5
Para que corra apropiadamente, ¡es necesario agregar el archivo KMSSS.exe en las exclusiones
de tu antivirus! O deshabilitar el antivirus durante el proceso de activación.

A veces el KMS-Service no se instala apropiadamente, debido a diferentes razones.
Necesitarás hacer 2 o 3 veces "Remover KMS-Service" y reiniciar tu computadora.
Cuando se trabaja con el programa tiene sentido marcar la opción "Guardar ajustes en la
carpteta del programa". En este caso, el archivo de configuración será almacenado en
la carpeta del programa, y no en C:\Users\username\AppData\Local\MSfree Inc.

                          —————————————————————————————————
Versiones previas del KMS Log Analyzer.xlsm son incompatibles con KMS Server Service v1.1.7
A fin de guardar los registros antiguos deberán ser transferidos al nuevo
KMS Log Analyzer usando la función copiar-pegar.

				"No pude activar!!!"
                          —————————————————————————————————
Quizás tengas un producto no VL, no capaz de activación KMS-Service, por ejemplo 
Windows 7 Ultimate no soporta activación KMS, o tu antivirus está bloqueando la activación.
Si un antivirus es el culpable puedes hacer lo siguiente: en la pestaña de "systema" click 
en la etiqueta azul "KMS-Service" y en la ventana que se muestre desmarcar la casilla. 
Luego agrega la carpeta a excepciones en tu antivirus.


                          —————————————————————————————————
Quiero agradecer a mikmik38, sin su trabajo este programa habría sido prácticamente imposible.
A hotbird64, por su KMS Client, Evgeny972 y los amigos de forum.ru-board.com por hacer 
posible la asistencia y pruebas de múltiples versiones del programa.

                                                                 Ratiborus

																 
Changelog:
v1.4.9
-Added Keys for Windows Server 2016 Essentials.
-KMS Server Service v2.0.3.

v1.4.8
 -Added Keys for Windows Server 2016.

v1.4.7
 -New KMS-Service.

v1.4.6
 -Added Keys for Windows 10 and Office 2016.

v1.4.5
 -Fixed minor bugs.

v1.4.4
 -Small changes in program code.

v1.4.3
 -Small changes in program code.

v1.4.2
 -Changes in program for compatibility with antivirus software.

v1.4.0
 -Conversión de Office 2016 Mondo.

v1.3.9
 -Conversión de Office 2016 Word, Excel, Access,
  OneNote, OutLook, PowerPoint, Publisher RETAIL a VL.

v1.3.8
 -Arreglado: mapeo de botones del display cuando la fuente es agrandada al 125%.
 -Agregado: Muestra la fecha de expiración de la licencia (180 días 0 horas 0 minutos).
 -Agregado en "Otras utlilerías" restaurar archivos de sistema desde el disco de 
  tu versión/edición de Windows.

v1.3.7
 -Arreglado: Codificado readme_ru.txt.
 -Agregado readme.txt en idioma Búlgaro.
 -Utilidad para guardar la activación MSActBackUp v1.0.8.

v1.3.6
 -Actualizado ProduKey v1.70 a v.1.80.
 -Arreglado: Colocar keys para Office 2016.
 -Arreglado: Programador de tareas se ejecuta cada 10 días.

v1.3.5
 -ProduKey actualizado de v1.66 a v1.70.
 -Nuevo driver TAP con soporte Windows 10. Una IP aleatoria es usada y cuando la activación 
  falla la casilla es desmarcada.
 -KMS Service re-compilado. De tal suerte que los antivirus no lo detectan como amenaza/falso
  positivo.
 -Utilidad MSActBackUp incluída.
 -Keys añadidas para Windows 10 y Office 2016.
 -Conversión de Office 2016 RETAIL a VL.
 -Si Office no se encuentra instalado, el botón "Activar Office" se deshabilita.
 -En la pestaña "Acerca de" puedes encontrar un link a una página con mis programas.
 -Added program for Windows 10 "Show or hide updates"

v1.3.4
 -Cambios en el programa para compatiblidad con software antivirus.

v1.3.3 
 -El programa, al intentar activar Office 2013 RETAIL convierte el canal de OfficeProPlus, 
  VisioPro, ProjectPro en Windows 7, 8, 8.1, 10 a KMS client.
 
v1.3.2
 -Cambios menores a la interfaz, agregada compatibilidad con Windows Technical Preview.
 -El programa ahora tiene interfaz en idioma Francés, gracias a Coleo.

v1.3.1.b4
 -Agregada la función que corre el script de heos(ru-board.com).
  Este script busca actualizacioines obsoletas e instaladas de Office 2010/2013 
  y hace posible su remoción.

v1.3.1.b3
 -Agregada la función para conmutar el lenguaje de la interfaz.
 
v1.3.1.b2
 -Corregido error cuando se trabaja con parámetros de la consola de comandos creando una tarea
  programada.

v1.3.1.b1
 -Agregado soporte para activar Windows Technical Preview, Windows 10.

v1.3.0
 -Agregado soporte para activar ediciones OEM: "Windows 8.1 Single Language with Bing",
  "Windows 8.1 with Bing" y "Windows 8.1 Pro for Education"
 
v1.2.8
 -Programa ProduKey actualizado de v1.65 a v1.66.
 -SppPatcher reemplazado en el método Hook SECO Injector.
 -Error eliminado que mostraba "Intervalo de activación" en transferencias ES, VI y UA.
 
v1.2.7
 -Para ver el registro en el programa de activación, ahora KMS Log Analizer.xlsm está integrado.
 -La computadora deberá tener instalada una aplicación capaz de leer archivos .xlms (MS Excel).
 -Trabajo de adaptación el programa para el nuevo formato del archivo de registro hecho por Bort_Nick,
  forum.ru-board.com.
 -Nuevo KMS Server Service (KMSSS.exe) v1.1.7.
 -Lista aumentada de sistemas para la conversión de edición.
 
v1.2.6.1
 -Cambiado el modo como funciona el botón "Información del Programa" en la pestaña "Acerca de".
 -Corregido el botón no funcional "Obtener ePID y Hwid del Servicio KMS".
 
v1.2.6
 -Corregido un problema con la instalación de la key después de ejecutar el comando "slmgr.vbs /upk".
 -Para evitar la detección de módulos antivirus, los archivos de controlador están protegidos
  con contraseña. 
  Además es imperativo agregar a exclusiones las siguientes carpetas:
  %SYSTEMDRIVE%\ProgramData\KMSAuto\*.* 
  %SYSTEMDRIVE%\ProgramData\KMSAutoS\*.* 
  %TEMP%\KMSAuto\*.*
  %TEMP%\PDK\*.*

v1.2.5
 -Cuando la activación falla un mensaje es mostrado y un intento de colocar una key GVLK se hace
  de manera forzada.
 -Agregada la opción de deshabilitar el Programador de Tareas el cual monitorea las acciones del
  usuario.
  
v1.2.4.1
 -Corregido error cuando se trabaja con parámetros de la consola de comandos creando una tarea
  programada.
 
v1.2.4
 -Activando en modo Auto se inicia el uso del método Windivert.
 -En el método TAP el adaptador TAP no se reinstala.
 
v1.2.3
 -Las funciones de activación son optimizadas para Windows y Office.
 -Corregidos algunos errores menores.
 -Cambios en la pestaña "Utilidades". Agregado "KMS Client by Hotbird64"
 -Nuevo KMSSS.exe que soporta la instalación del Hwid KMS-Server.

v1.2.2
 -Corregida la fecha y hora mostrada en formato hexadecimal en el archivo de registro. 
 
v1.2.1
 -Agregada la utilidad de ShowHideControls miXOnIN. Para convertir las Ediciones de Sistemas. 
 -En Modo Profesional, pestaña Avanzado, el botón "Convertir Office RETAIL a VL".
  Corre en Windows 8-8.1, ¡no funciona en Windows 7!
 -Nuevo KMSSS.exe para soportar la instalación de Hwid KMS-Server.
 
v1.2.0
 -Cambios en la pestaña "Ajustes".
 
v1.1.9.b1
 -Programa actualizado para ProduKey v1.62 v1.65
 -Agregado escoger los intervalos de activación cada 10 y 20 días.
 -Instalación de Key GVLK en la pestaña "Utilidades", funciona a traves de slmgr.vbs.
 -Cambiada la función de instalar key para "Producto no soportado" (si así lo reporta WMI OS).
 -Agregado el programa KMS Log Analyzer, para fácil vista y conservación de la 
  información del archivo log del Servicio KMS. La computadora debe tener instalada
  una aplicación para trabajar con archivos .xlsm (MS Excel). ¡No lista aún!

v1.1.7 ÷ v1.1.8
 -Cambios menores a la interfaz del programa. Agregado un link a un video.
 -En el modo "Auto" el programa inicia la búsqueda de una solución con la dirección IP correcta.
 -Arreglado un bug que raramente ocurre relacionado con el borrado de los archivos 
  "Injector by deagles". El programa podría colgarse con el mensaje "Instalación Hook, 
  Injector by deagles"
 -Las funciones de activación son optimizadas para Windows y Office.
 -En la pestaña Utilidades un botón fue agregado "Reseteando el sistema no es válido."
  ¡Lee cuidadosamente el mensaje que aparece cuando presionas el botón!

v1.1.6
 -Agregada la habilidad del programa para resetear a los valores por default.
 -Nuevos contenedores para los módulos. Desempaque de módulos y drivers es más veloz.
 -El Programador de Tareas crea tareas a nivel Administrador.
 -El borrado de direcciones del servidor KMS funciona apropiadamente.
 -Arreglados algunos bugs menores.
  *** ¡Feliz Año Nuevo 2014! ***

v1.1.4
 -Los ajustes del programa pueden guardarse en la carpeta que contiene el programa.
 -Todos los módulos del programa pueden funcionar desde ProgramData o de la carpeta que contiene
  al programa.
 -Fixed minor bugs.

v1.1.2.b8
 -El programa ProduKey está integrado dentro del archivo ejecutable.

v1.1.2.b7
 -Arreglado un bug para accesar la carpeta.

v1.1.2.b6
 -Arreglado un bug en el Programador.

v1.1.2.b4
 -En el modo Auto, puedes deshabilitar cualquier método de activación.
 
v1.1.2.b3 
 -El método Hook usa un SECO Injector modificado. Funciona en los inervalos de Activación y Renovación
  y fija su propia ePID.

v1.1.2b2
 -Opción para conectarse al Servidor KMS en donde el modo Hook funciona sin reemplazar archivos.
 -Agregada la opción en el programador de tareas para crear la tarea en la ruta ProgramData\KMSAutoS.
 
v1.1.1
 -Agregado el método de activación con una sustitución temporal de archivos de 8.1.
 
v1.0.9.1
 -Eliminating annoying bug with non-removed service TunMirror.

v1.0.9
 -El programa requiere .NET Framework 4.5 otra vez, a petición de los usuarios.
 -El diálogo para cambiar la key de producto aparece sólo una vez por sesión con el programa.
 -Cuando la tarea programada se ejecuta, el Servicio KMS no se remueve más del sistema,
  si fue instalado la primera vez.
 -Agregada nueva opción NoAuto option para deshabitar la carga automática del Servicio KMS
  durante la activación.  Por consiguiente, si se aplica NoAuto entonces todo es NoAuto.
 -En modo auto cuando el switch de configuración es agregado, el análisis del sistema
  siempre comenzará desde la posición de inicio, y no de la previamente almacenada.
  Esto es bastante conveniente si el programa se usa en diferentes computadoras.
 -Antes de activar la edición del sistema es definida y si es 8.1 entonces el clásico modo
  de activación del host local es excluído.
 -Agregado un segundo tipo de adaptador TAP para resolver el conflicto con la ya establecida
  TAP VPN.
 -WinDivert v1.1 ha sido implementado, así que no hay "incidentes" que resulten en BSOD en
  plataformas x86.
 -Elimina errores cuando en la ruta de archivo un signo "&" está presente.
 
v1.0.8
 -Agregado el ajuste para remover el WinDivert driver. Para evitar un posible crasheo de tu
  sistema en una BSOD, la remoción incondicional puede ser encendida.
  Por default, la remoción se realiza tras el reinicio.
 -Agregada la habilidad de correr el programa con switches en la línea de comando.
 
v1.0.8.b5
 -El programa combina tres modos de conectarse al servidor KMS, prueba primero entrar en modo
  automático.

v1.0.7
 -Nuevo servicio KMS Server (KMSSS.exe). Agregada la función de mostrar la dirección IP
  de la computadora cliente en el archivo log. Más en KMSSS.txt
  
v1.0.6
 -Nuevo Servicio KMS Server (KMSSS.exe). Más en KMSSS.txt
 -Cambios cosméticos a la interfaz.
 
v1.0.5
 -Archivo log que incluye información acerca de la versión del SO
 -Arregla el problema con la definición de una carpeta Sysnative
 
v1.0.4
 -Nuevo KMSSS.exe, Servicio KMS Server.
 -Registro log del Servicio KMS en la carpeta especificada
 -Arreglados algunos bugs menores :)
 
v1.0.3
 -Se aplica un KMS-Service modificado. Permite el uso en cada producto tu propio ePID. 
  Incluyendo CSVLK de la key actual.
 -Cambios en la instalación y remoción del TunMirror.
 -Cambios en la instalación y remoción de la interaz TAP.
 -Soporte agregado para la activación de Core, Embedded Industry, Single Language, etc...

v1.0.2
 -Cambios en el ajuste de la interfaz TAP.
 -Nueva funcionalidad de Respaldo / Restauración de la activación.
 -Cambios cosméticos a la interfaz.
 -Habilidad agregada para crear una tarea en el programador de tareas para activar.

v1.0.1
 -Agregadas keys GVLK para Server R2.
 -Cambios cosméticos a la interfaz.

v1.0.0
 -Primer release.



