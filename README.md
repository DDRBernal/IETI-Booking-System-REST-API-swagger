## Escuela Colombiana de Ingeniería

# IETI-configuracion-inicial-Booking-System-REST-API

***Integrantes***

```
Juan Esteban Cortés
Andrés Felipe Martínez
David Ricardo Otalora 

```

👉 En Ada School promovemos el aprendizaje basado en proyectos, por eso vas a construir un proyecto integrador a lo largo del curso, en el cual deberás aplicar todo lo que vas aprendiendo.
Para esta primera parte deberás completar los siguientes pasos:

Crear un repositorio en Github para tu proyecto.
Crear un proyecto base utilizando Spring Initializr con las siguientes características:
Maven Project.
Language Java.
Última versión de Spring Boot predeterminada.
Java Versión 8.
Agregar en la parte derecha la dependencia de Spring Web.
Crea un nuevo paquete llamado controller.health y adentro crea la clase HealthController con el siguiente código:
import org.springframework.web.bind.annotation.RequestMapping;

import org.springframework.web.bind.annotation.RestController;

@RestController public class HealthController {

   `@RequestMapping("/health")`

   `public String checkAPI(){`

       `return "<h1>The API is working ok!</h1>";`

   `}`
}

Realiza tu primer commit con el código de tu proyecto a tu repositorio.
Correr tu aplicación en tu dispositivo y verifica que funciona correctamente accediendo el siguiente endpoint:
http://localhost:8080/health
Envía el link de tu repositorio:
