# MicroProfile
#### Gómez Aldrete Luis Ignacio
#### 216588253
#
### ¿Qué es Java EE?
Java EE (Java Platform, Enterprise Edition) es una plataforma de desarrollo de aplicaciones empresariales construida sobre la plataforma Java SE (Java Standard Edition). Java EE proporciona un conjunto de especificaciones y APIs (Application Programming Interfaces) para desarrollar aplicaciones escalables, seguras y robustas para empresas.

Java EE ofrece un conjunto de tecnologías y herramientas para desarrollar aplicaciones empresariales, incluyendo el contenedor de servlets, JavaServer Pages (JSP), Enterprise JavaBeans (EJB), Java Persistence API (JPA), Java Message Service (JMS), Java Transaction API (JTA) y Java Naming and Directory Interface (JNDI).

### ¿Qué es Java SE?
Java SE (Java Platform, Standard Edition) es una plataforma de desarrollo de software creada por Oracle Corporation para desarrollar aplicaciones Java de propósito general. Java SE proporciona un conjunto de APIs (Application Programming Interfaces) y herramientas para desarrollar aplicaciones Java para escritorio, móviles, web y servidores.

La plataforma Java SE incluye el Java Development Kit (JDK), que es un conjunto de herramientas para desarrolladores Java, incluyendo el compilador Java, la herramienta de generación de documentación Javadoc, y otras utilidades para crear, depurar y ejecutar aplicaciones Java.

Java SE también incluye la Máquina Virtual Java (JVM), que es un componente fundamental de la plataforma Java que permite que las aplicaciones Java se ejecuten en cualquier plataforma que tenga una JVM instalada, independientemente del sistema operativo y la arquitectura de hardware.

### ¿Qué es Jakarta EE?
Jakarta EE es una plataforma de desarrollo de aplicaciones empresariales de código abierto construida sobre la plataforma Java SE (Java Standard Edition). Jakarta EE es una evolución de Java EE y es liderada por la Eclipse Foundation.

Jakarta EE proporciona un conjunto de especificaciones y APIs (Application Programming Interfaces) para desarrollar aplicaciones escalables, seguras y robustas para empresas. Las principales tecnologías en Jakarta EE incluyen Servlets, JavaServer Pages (JSP), Enterprise JavaBeans (EJB), Java Persistence API (JPA), Java Message Service (JMS), Java Transaction API (JTA), y Java Naming and Directory Interface (JNDI).

Jakarta EE también incluye una serie de herramientas y tecnologías para el desarrollo de aplicaciones web, como JavaServer Faces (JSF), Contexts and Dependency Injection (CDI), y Bean Validation. Jakarta EE se ejecuta en una amplia variedad de servidores de aplicaciones, incluyendo Tomcat, WildFly, GlassFish y WebSphere.

### ¿Qué es MicroProfile?
MicroProfile es una iniciativa de código abierto liderada por un grupo de compañías líderes en el desarrollo de tecnologías Java, incluyendo IBM, Red Hat, Tomitribe, Payara y otros, con el objetivo de ofrecer una plataforma para el desarrollo de aplicaciones empresariales en microservicios basadas en Java.

MicroProfile proporciona un conjunto de especificaciones y APIs (Application Programming Interfaces) para desarrollar aplicaciones Java empresariales que se ejecutan en contenedores y arquitecturas de microservicios. Las tecnologías principales en MicroProfile incluyen:

- JAX-RS (Java API para RESTful Web Services) para desarrollar servicios web RESTful.
* CDI (Contexts and Dependency Injection) para inyección de dependencias y manejo de ciclo de vida de componentes.
+ JSON-P (JSON Processing) para el procesamiento de datos JSON.
- JWT (JSON Web Token) para la seguridad de la autenticación y autorización basada en tokens.
* Metrics para recopilar y exponer métricas de rendimiento y salud de la aplicación.
+ OpenAPI (anteriormente Swagger) para documentar y exponer una API RESTful.

MicroProfile es compatible con Java EE (ahora Jakarta EE) y se integra con varios servidores de aplicaciones Java, incluyendo WildFly, Open Liberty, Payara, TomEE, y otros. La plataforma es muy flexible y escalable, lo que permite a los desarrolladores seleccionar las tecnologías que necesitan para sus aplicaciones y desarrollar aplicaciones empresariales de alta calidad en microservicios basados en Java.

### ¿Qué es Spring boot?
Spring Boot es un marco de desarrollo de aplicaciones Java de código abierto que facilita la creación de aplicaciones de nivel empresarial. Spring Boot se basa en el marco de trabajo Spring y se centra en hacer que la configuración y el arranque de una aplicación Java sean más rápidos y fáciles.

Spring Boot proporciona un conjunto de herramientas y características para ayudar a los desarrolladores a crear aplicaciones rápidas y escalables, incluyendo:

- Configuración automática: Spring Boot utiliza la reflexión para detectar las bibliotecas y configuraciones que están presentes en una aplicación y las configura automáticamente.
* Contenedor de servlets integrado: Spring Boot incluye un contenedor de servlets incorporado, lo que significa que no es necesario configurar uno externamente.
+ DevTools: Spring Boot incluye una serie de herramientas de desarrollo que ayudan a los desarrolladores a iterar rápidamente y a mantener su flujo de trabajo.
- Actuator: Spring Boot Actuator proporciona información detallada sobre el estado de la aplicación, lo que ayuda a los desarrolladores a diagnosticar y solucionar problemas de forma más eficaz.
* Integración con bases de datos: Spring Boot se integra con una variedad de bases de datos, incluyendo MySQL, PostgreSQL y MongoDB.

Spring Boot es muy flexible y se puede utilizar para construir aplicaciones web, aplicaciones de línea de comandos y otros tipos de aplicaciones empresariales.

### ¿Qué es Quarkus?
Quarkus es un marco de trabajo (framework) de código abierto para el desarrollo de aplicaciones Java diseñado para ser liviano, rápido y optimizado para la nube. Quarkus se enfoca en la eficiencia en recursos y tiempo de inicio, lo que lo hace ideal para desarrollar aplicaciones nativas de la nube.

Quarkus proporciona un conjunto de características y herramientas que permiten a los desarrolladores crear aplicaciones escalables y seguras, incluyendo:

- Soporte para múltiples lenguajes y frameworks: Quarkus admite una variedad de lenguajes de programación y marcos de trabajo, incluyendo Java, Kotlin, Scala, Spring, y otros.
* Tiempo de inicio rápido: Quarkus utiliza una combinación de técnicas de optimización de memoria y compilación nativa para lograr un tiempo de inicio ultrarrápido.
+ Eficiencia en recursos: Quarkus utiliza una arquitectura optimizada y técnicas de optimización de recursos para garantizar que las aplicaciones se ejecuten de manera eficiente y escalable.
- Integración con tecnologías de la nube: Quarkus se integra con tecnologías populares de la nube, como Kubernetes, OpenShift y AWS Lambda.
* Experiencia de desarrollo unificada: Quarkus proporciona una experiencia de desarrollo unificada que permite a los desarrolladores crear aplicaciones en un solo entorno.

Quarkus es una plataforma de desarrollo de aplicaciones moderna y flexible que se adapta a las necesidades de los desarrolladores que buscan crear aplicaciones rápidas y escalables en la nube. 

### ¿Qué es Maven?
Maven es una herramienta de gestión de proyectos de código abierto que se utiliza para construir, administrar y distribuir software. Maven se basa en la idea de que un proyecto de software debe ser construido utilizando un conjunto definido de convenciones y una estructura de directorios estandarizada.

Maven proporciona un conjunto de características y herramientas que facilitan el desarrollo y la gestión de proyectos de software, incluyendo:

- Gestión de dependencias: Maven maneja automáticamente las dependencias del proyecto, descargando y administrando las bibliotecas y dependencias requeridas por el proyecto.
* Construcción de proyectos: Maven se utiliza para construir, probar y empacar el software en diferentes formatos, como JAR, WAR, y otros.
+ Estructura del proyecto: Maven utiliza una estructura de directorios estandarizada para organizar el código fuente, los recursos y otros elementos del proyecto.
- Plugins y extensiones: Maven es altamente extensible y se puede ampliar mediante el uso de plugins y extensiones.
* Integración continua: Maven se integra con herramientas de integración continua, como Jenkins y Bamboo, lo que permite la integración continua y la entrega continua de software.

Su uso puede mejorar la eficiencia y la calidad del software y facilitar el trabajo en equipo y la colaboración en el desarrollo de proyectos de software.

### ¿Qué es Gradle?
Gradle es una herramienta de automatización de construcción de código abierto que se utiliza para construir, administrar y distribuir software. Gradle utiliza un lenguaje de construcción basado en Groovy o Kotlin para definir la estructura del proyecto, las dependencias y las tareas de construcción.

Gradle proporciona un conjunto de características y herramientas que facilitan el desarrollo y la gestión de proyectos de software, incluyendo:

- Gestión de dependencias: Gradle maneja automáticamente las dependencias del proyecto, descargando y administrando las bibliotecas y dependencias requeridas por el proyecto.
* Construcción de proyectos: Gradle se utiliza para construir, probar y empacar el software en diferentes formatos, como JAR, WAR y otros.
+ Estructura del proyecto: Gradle utiliza una estructura de directorios estandarizada para organizar el código fuente, los recursos y otros elementos del proyecto.
- Plugins y extensiones: Gradle es altamente extensible y se puede ampliar mediante el uso de plugins y extensiones.
* Integración continua: Gradle se integra con herramientas de integración continua, como Jenkins y Bamboo, lo que permite la integración continua y la entrega continua de software.

Es especialmente popular en el mundo de Android y también se utiliza para construir proyectos de software en Java, Kotlin y otras plataformas. Su uso puede mejorar la eficiencia y la calidad del software y facilitar el trabajo en equipo y la colaboración en el desarrollo de proyectos de software.

# Tolerancia a fallas con MicroProfile y Quarkus

Para realizar el ejemplo de tolerancia a fallas, se tuvieron que instalar los componentes necesarios. Estos componentes son: JDK y Maven.

Para JDK solo hace falta ir a la página de [Java](https://www.oracle.com/mx/java/technologies/downloads/#jdk20-windows) y descargar el paquete para el SO correspondiente.

![image](https://user-images.githubusercontent.com/80866790/232260187-64bfcefb-58d5-44e0-9a78-3c5cacdff409.png)

Y para Maven igual se tiene que ir a la página de [Apache Maven](https://maven.apache.org/download.cgi), descargar el archivo de la sección *Binary zip archive* y descomprimirlo en un directorio fácil de recordar.

![image](https://user-images.githubusercontent.com/80866790/232260313-95a86e58-e0cb-4bca-b587-5be5c1af6791.png)

En mi caso guarde el componente en una carpeta llamada *Maven* justo en el directorio C
> C:\maven\apache-maven-3.9.1-bin

Una vez instalados ambos componentes, tienen que ser agregados a las variables del sistema.

![image](https://user-images.githubusercontent.com/80866790/232260458-e55aa145-5153-46ef-bf15-7452b71aaf22.png)

Y además agregar esta variable al *path* de las variables del sistema.

![image](https://user-images.githubusercontent.com/80866790/232260522-546365f1-915c-4ee3-b3ac-b4c83941303c.png)

Ahora para crear el proyecto con Quarkus, simplemente se tiene que ir a la página de [Quarkus](https://code.quarkus.io/) y configurar con las extensiones con las que se va a configurar el proyecto, en este caso fueron 3: RESTEasy Reactive, RESTEasy Reactive JSON-B y SmallRye Fault Tolerance.

Ya con el proyecto configurado, se descarga como un ZIP.

![image](https://user-images.githubusercontent.com/80866790/232260938-bcd5d783-ff0a-40d4-9d38-c2f2b0623df0.png)

Una vez descargado, se descomprime y se ubica la carpeta descomprimida del proyecto en el lugar que se desee, en mi caso fue dentro de una carpeta de actividades de esta asignatura.

Se abre el proyecto con el IDE de preferencia (VS Code en mi caso), este se configura de manera autómatica y posteriormente se abre una terminal para arrancar el porjecto con Quarkus con el siguiente comando: 

``` cmd
mvn compile quarkus:dev
```

Ahora con una GET request de POSTMAN a ```localhost:8080/hello```, es posible ver que el mensaje de saludo que viene por defecto en el proyecto funciona de manera adecuada.

![image](https://user-images.githubusercontent.com/80866790/232261169-33c3b31c-5533-4242-a0b9-3c63eaa8d3f7.png)

Este mensaje y la request están programadas en el GreetingResource.java.

``` java
package org.NachoGmz;

import javax.ws.rs.GET;
import javax.ws.rs.Path;
import javax.ws.rs.Produces;
import javax.ws.rs.core.MediaType;

@Path("/hello")
public class GreetingResource {

    @GET
    @Produces(MediaType.TEXT_PLAIN)
    public String hello() {
        return "Hello from RESTEasy Reactive";
    }
}
```

Ahora para mostrar la tolerancia a fallas se omitira el uso de este *GreetingResource* y se creara una clase para definir personas, dicha clase contará con solo:

- id
* nombre
+ correo

La clase *Person* es la siguiente:

```java
package org.NachoGmz.model;

public class Person {
    private Long personId;
    private String name;
    private String email;

    public Person(){
    }
    public Person(Long personId, String name, String email){
        this.personId = personId;
        this.name = name;
        this.email = email;
    }

    public Long getPersonId() {
        return personId;
    }

    public void setPersonId(Long personId) {
        this.personId = personId;
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public String getEmail() {
        return email;
    }

    public void setEmail(String email) {
        this.email = email;
    }
}
```

Y cuenta con un controlador llamado *PersonController*:
