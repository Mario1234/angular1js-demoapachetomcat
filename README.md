# angular1js-demoapachetomcat
Pagina web de ejemplo de AngularJS, desplegada en un servidor Tomcat 9

INSTALACION

Instala el servidor Apache 9, en este caso he utilizado el 9.0.6.

Copia los cuatro archivos a la carpeta blablabla\apache-tomcat-9.0.6\webapps\docs\

Modifica el archivo blablabla\apache-tomcat-9.0.6\webapps\ROOT\index.jsp

y añade esta linea debajo de `<h3>Recommended Reading:</h3>`: `<h4><a href="${tomcatDocUrl}angular.html">Angular1JS</a></h4>`

EJECUCION

Ejecuta haciendo doble click el archivo blablabla\apache-tomcat-9.0.6\bin\startup.bat

Accede a localhost:8080

Clica en el enlace Angular1JS
