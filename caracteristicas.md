CARACTER�STICAS DE GIT
----------------------
----------------------

Entre las caracter�sticas m�s relevantes se encuentran:

-----> Fuerte apoyo al desarrollo no lineal, por ende rapidez en la gesti�n de ramas y mezclado de diferentes versiones. Git incluye herramientas espec�ficas para navegar y visualizar un historial de desarrollo no lineal. Una presunci�n fundamental en Git es que un cambio ser� fusionado mucho m�s frecuentemente de lo que se escribe originalmente, conforme se pasa entre varios programadores que lo revisan.

-----> Gesti�n distribuida. Al igual que Darcs, BitKeeper, Mercurial, SVK, Bazaar y Monotone, Git le da a cada programador una copia local del historial del desarrollo entero, y los cambios se propagan entre los repositorios locales. Los cambios se importan como ramas adicionales y pueden ser fusionados en la misma manera que se hace con la rama local.

-----> Los almacenes de informaci�n pueden publicarse por HTTP, FTP, rsync o mediante un protocolo nativo, ya sea a trav�s de una conexi�n TCP/IP simple o a trav�s de cifrado SSH. Git tambi�n puede emular servidores CVS, lo que habilita el uso de clientes CVS pre-existentes y m�dulos IDE para CVS pre-existentes en el acceso de repositorios Git.

-----> Los repositorios Subversion y svk se pueden usar directamente con git-svn.

-----> Gesti�n eficiente de proyectos grandes, dada la rapidez de gesti�n de diferencias entre archivos, entre otras mejoras de optimizaci�n de velocidad de ejecuci�n.

-----> Todas las versiones previas a un cambio determinado, implican la notificaci�n de un cambio posterior en cualquiera de ellas a ese cambio (denominado autenticaci�n criptogr�fica de historial). Esto exist�a en Monotone.

-----> Resulta algo m�s caro trabajar con ficheros concretos frente a proyectos, eso diferencia el trabajo frente a CVS, que trabaja con base en cambios de fichero, pero mejora el trabajo con afectaciones de c�digo que concurren en operaciones similares en varios archivos.

-----> Los renombrados se trabajan bas�ndose en similitudes entre ficheros, aparte de nombres de ficheros, pero no se hacen marcas expl�citas de cambios de nombre con base en supuestos nombres �nicos de nodos de sistema de ficheros, lo que evita posibles, y posiblemente desastrosas, coincidencias de ficheros diferentes en un �nico nombre.

-----> Realmacenamiento peri�dico en paquetes (ficheros). Esto es relativamente eficiente para escritura de cambios y relativamente ineficiente para lectura si el reempaquetado (con base en diferencias) no ocurre cada cierto tiempo.