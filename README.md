# # bbog-gid-onpfdods-scripts-db

# Artefactos del aplicativo FD ODS capa Base de Datos

Este repositorio contiene scripts para la instalación y compilación de los mismos bajo el SCHEMA ***ods_stag*** para el aplicativo FD ODS capa BD. 

## Estructura del repositorio
El proyecto cuenta con la siguiente estructura de carpetas 

~~~
bbog-gid-onpfdods-scripts-db/
├── ods_stag/
│   ├── Function/
│   ├── Package/
│   ├── PackageBody/
│   ├── Procedure/
│   ├── Scripts/
│   ├── Trigger/
│   ├── View/
│   └── INSTALL.sql 
└── README.md
~~~

  
**INSTALL:sql**: Este script ejecuta:
- Instalacion cambiando SCHEMA actual a ***ods_stag***
- Compilando scripts
- Compilar procedimientos almacenados
- Compilar paquetes modificados
Esto seguún ubicación dada en la línea ***@./&1/ods_stag/***

 *README* creado junio 28 de 2024
