📇 Sistema de Contactos
Este es un sistema web CRUD de gestión de contactos desarrollado con Spring Boot, Thymeleaf, JPA/Hibernate y MySQL. Permite listar, agregar, editar y eliminar contactos de manera sencilla.

🧰 Tecnologías utilizadas
Java 24

Spring Boot 3.4.5

Spring Data JPA

Thymeleaf

MySQL

Maven

Lombok

Bootstrap 5 

JavaScript 

🖥️ Funcionalidades
📋 Listar todos los contactos

➕ Agregar nuevos contactos

✏️ Editar contactos existentes

❌ Eliminar contactos

🌐 Interfaz web con HTML, Bootstrap y JavaScript

📂 Estructura del proyecto
├── src/main/java/gm/contactos/
│   ├── modelo/Contacto.java
│   ├── servicio/ContactoServicio.java
│   ├── controlador/ContactoControlador.java
│
├── src/main/resources/
│   ├── templates/
│   │   ├── index.html
│   │   ├── agregar.html
│   │   ├── editar.html
│   ├── application.properties
│
├── pom.xml

⚙️ Configuración
Base de datos
Asegúrate de tener un servidor MySQL en ejecución. La configuración por defecto busca crear (si no existe) una base de datos llamada contactos_db.

Archivo application.properties:
spring.datasource.url=jdbc:mysql://localhost:3306/contactos_db?createDatabaseIfNotExist=true
spring.datasource.username=root
spring.datasource.password=
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

Modifica el usuario y la contraseña según tu configuración local.

Requisitos
Java 17 o superior

Maven

MySQL Server
▶️ Cómo ejecutar
Clona el repositorio:
git clone https://github.com/ivanfr12/Sistema-de-Contactos.git
cd sistema-contactos

Compila y ejecuta el proyecto:
mvn spring-boot:run

Abre tu navegador en: http://localhost:8080

8080

💡 Notas
Se utiliza Bootstrap 5 vía CDN para estilizar la interfaz de usuario.

También se incluye soporte básico con JavaScript vía CDN para funcionalidades dinámicas (como botones o componentes responsivos de Bootstrap).

El sistema usa plantillas con Thymeleaf para renderizar vistas HTML del lado del servidor.

✍️ Autor
Desarrollado por Ivan Rodriguez.


