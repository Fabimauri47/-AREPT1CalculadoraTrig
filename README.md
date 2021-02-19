# ***AREP 1 Tercio Calculadora Trig***

## Introducción Del Proyecto



### Pre-Requisitos


    * [Java 8.0](https://www.java.com/es/) - Codificación
    * [Maven](https://maven.apache.org/) - Manejo de Dependencias
    * [JUnit](https://junit.org/junit5/) - Pruebas de Unidad
    * [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git) - Control de Sistemas de veriones.
    * [Heroku](https://devcenter.heroku.com/articles/heroku-cli#download-and-install) - Despligue de Ambiente Web


### Despliegue con Heroku App

>[![Deployed to Heroku](https://www.herokucdn.com/deploy/button.png)](https://sheltered-woodland-90071.herokuapp.com/)



### Guia de Instalación

1. Primero se debe clonar el repositorio, con el siguiente comando descrito:

       git clone https://github.com/Fabimauri47/-AREP-Lab3-CLIENTES-Y-SERVICIOS
    

2. Luego proceda abrir el cmd (Ventana de comandos) en donde tiene el repositorio alojado y ejecute el siguiente comando:

       mvn package
    

3. Ejecutamos el programa con el siguiente comando:

       mvn exec:java -D "exec.mainClass"="edu.escuelaing.demo.NanoSparkWebDemo"
   

4. Gereramos la documentación con el siguiente comando ejecutandolo desde consola:

       mvn javadoc:javadoc
   
 

## Corriendo Pruebas

Para correr las pruebas, usamos el siguiente comando en una terminal CMD o en una terminal GIT:

         mvn test

 

## Construido con

* [Java 8.0](https://www.java.com/es/) - Codificación y Lenguaje de Programacíon.
* [JUnit5](https://junit.org/junit5/) - Programa para ejecutar pruebas de unidad.
* [Maven](https://maven.apache.org/) - Manejo de Dependencias.
* [IntelliJ IDEA](https://www.jetbrains.com/es-es/idea/) - Programa usado para la Codificacíon.


## Autor

* **Fabián Mauricio Ramirez Pinto** [Fabimauri47](https://github.com/Fabimauri47)


## Licencia

Este proyecto cuenta con la licencia GNU: General Public License - see the [LICENSE.md](https://github.com/Fabimauri47/AREP-Lab1-Calculadora/blob/main/LICENSE.txt) 
