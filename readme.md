¿Qué es un control de versiones?

Sistema de seguimiento relacioando a a todas las acciones realizadas dentro de un proyecto, premitiendo la recuperación de versiones específicas previas a su alteración. 

----

¿Cuáles son los problemas al no usar un controlador de versiones?

- Pueden haber conflictos con versiones anteriores (ex: dos archivos .html con el mismo nombre, y luego unidos en la rama principal)
- No hay manera de tener control sobre qué partes del proyecto están disponibles para hacerse cambios, o cuales ya son las definitivas.
- Los cambios aplicados en un proyecto, al momento de trabajar con un equipo grande, no están catalogados ni tampoco se podrían analizar de manera competente. Sin mencionar que al momento de unir las piezas individuales podría existir la posibilidad de que se hayan repetido etiquetas o cambios. Sin un control sobre el proyecto cualquier usuario tendría el poder de borrar/reemplazar o sobre-escribir sobre algún punto vital.
- Actualizar un proyecto conllevaría horas de acuerdo entre diversas parte además de que entorpecería el flujo de trabajo.

----

¿Cuáles son los beneficios?

- Ayuda a mantener un récord/historial de acciones realizadas en un proyecto. 
- Previene problemas de conflictos entre versiones.
- El concepto y creación de ramas como elementos que permiten el flujo de trabajo en simultaneo para diferentes secciones.
- Se pueden recuperar versiones anteriores, elementos como imágenes o estructuras de diseño.
- Si es aplicado de manera eficiente, soporta todos los flujos de trabajo, independientemente del estilo de 
  trabajo de cada programador.
- Cada miembro del equipo en el proyecto cuenta con una versión básica, la cual puede servir de back-up en el futuro.
- El más utlilizado de manera universal es GIT, y todos los cambios se suben a la Nube sin necesidad de paga (para trabajos más pequeños o locales) excesiva.

----

¿Qué tipos de control de version existen?

- Locales: 
  Todas las versiones locales del proyecto son almacenados en una base de datos única. Esto elimina la posibilidad de mal interpretar la versión del proyecto, ya que para acceder al archivo deseado tendría que hacerse uso del sistema de control. Este método, sin embargo, es poco eficiente ya que no
  permite compartir el código entre varios miembros de un equipo de manera fluida.

- Centralizados:
  Los elementos del proyecto, en lugar de almacenarlos en un disco duro o base de datos única, se colocan dentro de un servidor (database). Estos impiden que se alteren áreas de trabajo que no han sido aprobadas previamente por un supervisor (ex: hacer una rama nueva requiere de permisos). Solo sería eficiente en proyectos pequeños que no requieran constante actualización.

- Distribuidos:
  Cada miembro del proyecto cuenta con su propio repositorio. Existe un repositorio (core) o principal, sobre el cual las otras
  piezas pueden ser sincronizadas cuando eventualmente llegue el momento de visualizar el trabajo como una sola unidad.

  Ejemplos de Sistemas de Control de Versiones conocidos: GIT, CVS, Mercurial, Baazar.