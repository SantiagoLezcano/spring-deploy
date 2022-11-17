##Despliegue de app Spring boot enHEROKU

Crear archivo system.properties en el proyecto:
contenido:

java.runtime.version=17

1. Crear cuenta en Keroku.cOM Y GitHub
2. Tenr configurado git en el ordenador (necesario solo una vez)
   1. git config --global user.name "santiagolezcano"
   2. git config --global user.email santiago.lezcano99@gmailcom
3. Subir el proyecto a github desde IntellijIDEA deade la opcion VCS>Share project on github
4. Desde heroku, crear app y elegir metodo GitHub y buscar el repositorio
5. Habilitar deploy acutomatico y ejecutar el deploy