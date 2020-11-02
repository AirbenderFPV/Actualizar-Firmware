# Actualizar Firmware

<img src="https://raw.githubusercontent.com/wiki/betaflight/betaflight/images/betaflight/bf_logo.png">

Para cargar el firmware dentro de la controladora de vuelo, tienes que conectar la placa al Betaflight por medio de un USB.  

Además tienes que estar seguro que este en modo DFU, es el modo donde puedes reprogramar el chip y cargar el firmware.  
Para entrar en modo DFU tenemos que ir a la pantalla de CLI y escribir **bl**.  
Al presionar enter nos tendria que desconectar el quad y mostrar en la parte superior lo siguiente:  

<img src="https://www.midronedecarreras.com/wp-content/uploads/2019/05/DFU_Betaflight.jpg">

Si no nos muestra esto, tendremos que ayudarnos de la herramienta **ImpulseRC** que la ejecutaremos sin desconectar el drone después de ejecutar el **bl**.

Una vez esto tienes seleccionar la placa que quieres flashear y el firmware de betaflight que quieres cargar en la controladora.    
Si tienes dudas de que modelo de placa tienes puedes conectarte previamente y debajo de la versión del configurador de Betaflight en la parte superior izquierda aparecera la versión de firmware de tu controladora y el nombre de esta. 

<img src="https://raw.githubusercontent.com/AirbenderFPV/Betaflight-4.2.0/main/images/tipocontroladoravuelo.PNG">

En este ejemplo la placa controladora usada es la FuryF4OSD.  
Tendriamos que buscar este modelo en el desplegable de versiones y posteriormente poner la version que queramos instalar.    
Tendremos que cargar el firmware primero desde un archivo o desde internet y una vez cargado se nos habilitará el boton de instalar firmware.    

<img src="https://raw.githubusercontent.com/AirbenderFPV/Betaflight-4.2.0/main/images/InstalacionFirmware.PNG">

Recomiendo seleccionar la opción de **borras el chip entero** para borrar toda la información que tiene la placa.  
Al entrar en primera vez en betaflight nos pedirá si queremos importar nuestros ajustes.  
Recomiendo cancelar esa importación i volver a **configurar el quad desde cero**

#### Fuentes de información

[Notas oficiales de la versión] https://github.com/betaflight/betaflight/wiki/4.2-Tuning-Notes  
 
[Midronedecarreras] https://www.midronedecarreras.com/betaflight/#Descarga_el_Configurador_BLHeli_suite_32  

[Airbender_FPV] https://www.instagram.com/airbender_fpv/
