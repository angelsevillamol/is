# Análisis de requisitos

## Actores

## Datos

El sistema debe permitir un registro histórico de alumnos que gestione la siguiente información: dni, nombre, apellidos, teléfono, e-mail, dirección postal, curso más alto matriculado, fecha de nacimiento, número de equipo, y si es líder o no del equipo.

## Requisitos

### Requisitos funcionales

Los requisitos funcionales son características que debe cumplir el sistema y que expresan la funcionalidad y/o el comportamiento específico que debe tener el sistema ante determinadas situaciones. Estos se codifican con las siglas *RF*, seguidas de un guión y del número de requisito.

* **RF-1:** 
* **RF-2:** 
* **RF-3:** 
* **RF-4:** El sistema permite que el usuario pueda buscar alumnos.
	* **RF-4.1:** La búsqueda de alumnos debe poder filtrarse a partir del dni, de los apellidos o del equipo al que pertenece.
	* **RF-4.2:** La búsqueda debe devolver todas las coincidencias obtenidas.
* **RF-5:** El sistema permite que el usuario pueda acceder a la información de uno o varios alumnos.
	* **RF-5.1:** El usuario puede ordenar el mostrado en orden alfabético, por dni, o por curso más alto matriculado.
	* **RF-5.2:** El orden puede ser ascendente o descendente.
* **RF-6:** 
* **RF-7:**

### Requisitos no funcionales

Los requisitos no funcionales son característicos del proceso de desarrollo, del servicio prestado o de cualquier otro aspecto del desarrollo, que debe cumplir el sistema y que indican las restricciones del mismo. Estos se codifican con las siglas *RNF*, seguidas de un guión y del número de requisito.

* **RNF-1:** El lenguaje de programación es C++.
* **RFF-2:** El lenguaje de documentación será Markdown.
* **RNF-3:** Si se hace uso de un IDE, éste será Eclipse.
* **RFF-4:** El proyecto se realizará haciendo uso del sistema de control de versiones Git y la plataforma GitHub para el almacenamiento del repositorio de forma remota.
* **RNF-5:** El historial de cambios queda guardado en las cuentas de Git por lo que la evaluación será incremental y no servirá subir los ficheros de un día para otro en Git.
* **RNF-6:** El sistema debe funcionar en Linux.
* **RNF-7:** El formato de salida de los listados de usuarios debe ser html o Markdown.
* **RNF-8:** El sistema solo puede admitir como máximo a 150 alumnos.
* **RNF-9:** Debe poderse cargar o guardar los datos del registro histórico de alumnos en ficheros binarios.
* **RNF-10:** Todos los datos de un alumno son necesarios, excepto el número de grupo y el liderazgo.
* **RNF-11:** Un alumno solo puede ser líder de un grupo si forma parte de un grupo.
* **RNF-12:** Como máximo puede haber un solo líder por grupo.
* **RNF-13:** En el mostrado, aquellos usuarios que sean líderes de un grupo deben verse remarcados.
* **RNF-14:** Los atributos identificadores de un alumno son el dni, el e-mail, y el agregado que forma el número de grupo y la condición de líder.
