HMVC (Hierarchical Model View Controller)

Resultado de una solución presentada en el JavaWorld web site en julio de 2000 por Jason Cai, Ranjit Kapila y Gaurav Pal, dado problemas con aplicaciones que usaban MVC.
El HMVC (Herarchical Model View Controller) es una mejora
del MVC. Su mas grande beneficio de usar este estilo es la “widgetizacion” de la estructura del contenido de una aplicación. Dividir la aplicación en sub-aplicaciones las
cuales contiene una propia terna MVC.
Actualmente es el patrón de diseño mas usado para aplicaciones web e incluido en varios frameworks de desarrollo web.

HMVC Pattern
Ventajas de HMVC
Principales ventajas de implementar HMVC en el ciclo de desarrollo:
Modularización: Reduce las dependencias entre las distintas partes de la aplicación.
Organización: Tener una carpeta para cada una de las ternas relevantes hace una carga de trabajo más ligera.
Reusabilidad: Por la naturaleza del diseño es fácil de reutilizar casi cada pieza de código.
Extensibilidad: Hace la aplicación mas extensible al añadir o remover módulos sin sacrificar la facilidad de mantenimiento.