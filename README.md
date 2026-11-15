## Trabajo práctico INTEGRADOR de la asignatura DCI ##
Este repositorio contiene el trabajo práctico final para la asignatura de Diseño de Circuitos Impresos de la carrera de posgrado de FIUBA.

* Autor: Tomás Taravella
* Título corto del trabajo:  Réplica MXR Distortion+
* Descripción:  El proyecto consiste en un circuito de distorsión para pedales de guitarra, replicando el MXR Distortion+. El objetivo es realizar el PCB para su fabricación casera con el método de la plancha.
* Cursada: OCT-NOV-DIC 2026


## Licencia de este trabajo ##
CERN-OHL-S

## Estructura del TP INTEGRADOR ##

Se utiliza la siguiente estructura:

* doc: Toda la información sobre el circuito, principalmente de autoría o procesamiento propio. Por ejemplo:
  * Notas de ingeniería propias.
  * Notas de aplicación propias.
  * Notas con cálculos.
  * Dibujos adicionales.
  * Fotos de los prototipos.
  * Presupuestos, cotizaciones.
* info: Toda la información recolectada, principalmente de terceros:
  * Hojas de datos.
  * Notas de aplicación.
  * Info de productos comerciales.
  * Info en internet.
* pcb: Archivos de diseño esquemático y pcb.

## Obligatorios para el TP INTEGRADOR ##
* doc/propuesta/README.md (con textos y links, formato markdown, a imágenes que deben estar en el mismo repo. Las imágenes son las que se piden en las pautas de TP).
* info/*.pdf (Se piden solo las hojas de datos de los componentes relevantes como circuitos integrados, conectores particulares, módulos, etc. No es necesario poner hojas de pasivos, discretos comunes, conectores estándar.)
* pcb/* (Acá va el proyecto KiCad, modelos 3D, bibliotecas particulares y archivos generados como BOM, gerbers, etc.). EVITE subir al git archivos temporales de KiCad. Se recomienda usar un .gitignore adecuado.
* El alumnos es libre de agregar otras cosas, pero siempre tenga en cuenta que el repositorio es público. Evitar colocar información personal o documentación confidencial. 
