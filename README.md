## Escuela Colombiana de Ingenier铆a

# IETI-configuracion-inicial-Booking-System-REST-API


馃憠 En Ada School promovemos el aprendizaje basado en proyectos, por eso vas a construir un proyecto integrador a lo largo del curso, en el cual deber谩s aplicar todo lo que vas aprendiendo.
Para esta primera parte deber谩s completar los siguientes pasos:

Crear un repositorio en Github para tu proyecto.
Crear un proyecto base utilizando Spring Initializr con las siguientes caracter铆sticas:
Maven Project.
Language Java.
脷ltima versi贸n de Spring Boot predeterminada.
Java Versi贸n 8.
Agregar en la parte derecha la dependencia de Spring Web.
Crea un nuevo paquete llamado controller.health y adentro crea la clase HealthController con el siguiente c贸digo:
import org.springframework.web.bind.annotation.RequestMapping;

import org.springframework.web.bind.annotation.RestController;

@RestController public class HealthController {

   `@RequestMapping("/health")`

   `public String checkAPI(){`

       `return "<h1>The API is working ok!</h1>";`

   `}`
}

Realiza tu primer commit con el c贸digo de tu proyecto a tu repositorio.
Correr tu aplicaci贸n en tu dispositivo y verifica que funciona correctamente accediendo el siguiente endpoint:
http://localhost:8080/health
Env铆a el link de tu repositorio:
