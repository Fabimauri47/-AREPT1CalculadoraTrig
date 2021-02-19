# ***AREP: 1 Tercio Calculadora Trig***

## Taller de verificación de conocimientos tecnicos GRUPO2

### Introducción al Taller

1. Construir un servicio WEB (puede usar Spark o Sockets) que reciba un número y una cadena de tres caracteres. La cadena puede ser una de tres opciones: "cos", "sin", "tan". El     servicio asume que el número que recibe está en radianes y retorna una estructura JSON con el valor de la función trigonométrica correspondiente. 
2. Construya otro servicio Web (puede usar Spark o Sockets) que sea una fachada del servicios construido en el primer punto. Es decir, este servicio recibe los mismos parámetros      y regresa el mismo resultado, pero para hacer el cálculo debe invocar via http al servicio web que se constuyó en el primer punto.
3. Su diseño debe soportar la composición de nuevas operaciones para modificar servicios existentes o componer nuevos servicios. Por ejemplo, piense que en el futuro podemos          solicitar que se creen nuevos servicios sobre  el API web, es decir,  debe ser fácilmente extensible.
4. El diseño de los servicios WEB debe tener en cuenta buenas prácticas de diseño OO.
5. Despliegue los servicios en Heroku en dynos separados.
6. Construya un cliente JAVA para probar los dos servicios.
7. El cliente y los servicios debe entregarlos en dos proyectos estructurado con Maven. El primero con el servicio fachada y el cliente. Y el segundo con el servicio web             concreto.




### Pre-Requisitos


- [Java 8.0](https://www.java.com/es/) - Codificación
- [Maven](https://maven.apache.org/) - Manejo de Dependencias
- [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git) - Control de Sistemas de veriones.


### Despliegue con Heroku App

>[![Deployed to Heroku](https://www.herokucdn.com/deploy/button.png)](https://sheltered-woodland-90071.herokuapp.com/)



### Guia de Instalación

1. Primero se debe clonar el repositorio, con el siguiente comando descrito:

       git clone https://github.com/Fabimauri47/-AREPT1CalculadoraTrig
    

2. Luego proceda abrir el cmd (Ventana de comandos) en donde tiene el repositorio alojado y ejecute el siguiente comando:

       mvn package
    

3. Ejecutamos el programa con el siguiente comando:

       java -cp target/classes;target/dependency/* edu.eci.arep.controller.CalculatorController
       

4. Gereramos la documentación con el siguiente comando ejecutandolo desde consola:

       mvn javadoc:javadoc
   
 

## Corriendo Pruebas

Para correr las pruebas, usamos el siguiente comando en una terminal CMD o en una terminal GIT:

         mvn test

 

## Construido con

* [Java 8.0](https://www.java.com/es/) - Codificación y Lenguaje de Programacíon.
* [JUnit5](https://junit.org/junit5/) - Programa para ejecutar pruebas de unidad.
* [Maven](https://maven.apache.org/) - Manejo de Dependencias.
* [Heroku](https://devcenter.heroku.com/articles/heroku-cli#download-and-install) - Despligue de Ambiente Web


## Autor

* **Fabián Mauricio Ramirez Pinto** [Fabimauri47](https://github.com/Fabimauri47)


## Licencia

Este proyecto cuenta con la licencia GNU: General Public License - see the [LICENSE.md](https://github.com/Fabimauri47/AREP-Lab1-Calculadora/blob/main/LICENSE.txt) 
