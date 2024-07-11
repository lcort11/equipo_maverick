# bbog-ctm-tokenizacion-ctm

# Mallas de Control-M aplicativo Tokenización

Este repositorio contiene una colección de mallas en Control-M del aplicativo Tokenización

## Contenido

- **Install.txt**: En el archivo install.txt que se encuentra en la raíz de repositorio "bbog-ctm-tokenizacion-ctm". En este archivo se encuentran las instrucciones de ejecución; relacionando el nombre de las mallas de Control M a desplegar, de manera consecutiva (hacia abajo) una seguida de la otra sin dejar espacios.

  Ejemplo:

  TPOSCINK

  TPOTTACT

  TPOMDSFR

  
  **Para NO desplegar una malla** Al colocar el símbolo "#" numeral antepuesto al nombre de la malla (sin espacios) se toma como instrucción: Que la malla no se desplegara.

  Ejemplo:
  
  TPOSCINK

  #TPOTTACT

  TPOMDSFR

  La malla que NO se desplegara para este ejemplo es "TPOTTACT".

- **Carpetas de mallas**: En las carpetas con nombres de las mallas se encuentran los tres archivos .xml correspondientes a las mallas que serán
   desplegadas en los (3) tres ambientes así:

  Nombre carpeta malla: **TPOSCINKQ**
  + **QA** -> Desarrollo, Ejemplo archivo .xml: TPOSCINKQ.xml
  + **Staging** -> Pruebas, Ejemplo archivo .xml: TPOSCINKS.xml
  + **Master** -> Producción, Ejemplo archivo .xml: TPOSCINKM.xml
  
  *README* creado junio 11 de 2024