# bbog-gid-onpods-copy-batch

# Artefactos del aplicativo FD ODS

Este repositorio contiene un conjunto de scripts de copia por lotes (batch) que se utilizan para ejecutar, respaldar y restaurar datos para el aplicativo ODS (On-Premise Data Store).

# Estructura del repositorio

~~~
bog-gid-onpods-copy-batch/
F:
├── SCRIPTS/
│   ├── ODS/
│   │   ├── AUTDWI/
│   │   ├── BBSDWI/
│   │   ├── BPM/
│   │   ├── CANDWI/
│   │   ├── CASTIGOS/
│   │   ├── CRMDWI/
│   │   ├── DISDWI/
│   │   ├── ENDEUDAMIENTO/
│   │   ├── IVRDWI/
│   │   ├── MC/
│   │   └── SARC/
├──LOGS_PRODUCCION/
│  └──ODS/
│     └── HIS/
└── README.md
~~~

## Carpetas y rutas
  
**SCRIPTS**: Contiene los scripts de copia por lotes.
~~~
ODS: Contiene los scripts específicos para cada módulo de ODS.
AUTDWI: Ruta: F:/SCRIPTS/ODS/AUTDWI
BBSDWI: Ruta: F:/SCRIPTS/ODS/BBSDWI
BPM: Ruta: F:/SCRIPTS/ODS/BPM
CANDWI: Ruta: F:/SCRIPTS/ODS/CANDWI
CASTIGOS: Ruta: F:/SCRIPTS/ODS/CASTIGOS
CRMDWI: Ruta: F:/SCRIPTS/ODS/CRMDWI
DISDWI: Ruta: F:/SCRIPTS/ODS/DISDWI
ENDEUDAMIENTO: Ruta: F:/SCRIPTS/ODS/ENDEUDAMIENTO
IVRDWI: Ruta: F:/SCRIPTS/ODS/IVRDWI
MC: Ruta: F:/SCRIPTS/ODS/MC
SARC: Ruta: F:/SCRIPTS/ODS/SARC
~~~
  
**LOGS_PRODUCCION**: Contiene los archivos de registro.
~~~
ODS: Ruta: F:/LOGS_PRODUCCION/ODS
HIS: Ruta: F:/LOGS_PRODUCCION/ODS/HIS
~~~
 *README* creado junio 28 de 2024
