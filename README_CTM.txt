# equipo_maverick
# bbog-ctm-opencard-ctm

# Mallas de Control-M aplicativo OpenCard

Este repositorio contine una colección de mallas en control-M del aplicativo OpenCard

## Contenido

- **Install.txt**: En el archivo install.txt que se encuentra en la raíz de repositorio "bbog-ctm-opencard-ctm". En este archivo se encuentran las instrucciones de ejecución; relacionando el nombre de las mallas de Control M a desplegar, de manera consecutiva (hacia abajo) una seguida de la otra sin dejar espacios.

  Ejemplo:

  OPESWTKN

  OPEDTRFA

  OPEDDCAF

  
  **Para NO desplegar una malla** Al colocar el símbolo "#" numeral antepuesto al nombre de la malla (sin espacios) se toma como instrucción: Que la malla no se desplegara.

  Ejemplo:
  
  OPESWTKN

  #OPEDTRFA

  OPEDDCAF

  La malla que NO se desplegara para este ejemplo es "OPEDTRFA".

- **Carpetas de mallas**: En las carpetas con nombres de las mallas se encuentran los tres archivos .XML correspondientes a las mallas que serán
   desplegadas en los (3) tres ambientes así:

  Nombre carpeta malla: **OPESWTKN**
  + **QA** -> Desarrollo, Ejemplo archivo .XML: OPESWTKNQ.xml
  + **Staging** -> Pruebas, Ejemplo archivo .XML: OPESWTKNS.xml
  + **Master** -> Producción, Ejemplo archivo .XML: OPESWTKNM.xml
  
  *README* actualizado abril 01 de 2024
