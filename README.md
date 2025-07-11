#  ROOM VIBE

> **Video de navegación del sistema:**  
> 📺 [Ver demo en YouTube](https://youtu.be/ShmZxyqL-6w)  

---

##  Descripción General

Este proyecto está desarrollado utilizando **Jakarta Faces (JSF)** con Facelets para construir una interfaz gráfica funcional, limpia y conectada a la lógica del sistema mediante *managed beans*. Ha sido creado en un entorno educativo como parte de una entrega evaluada en base a diseño, integración, usabilidad y trabajo en equipo.

---

##  Roles del equipo

- **Diseñador de interfaz**: Maquetación de vistas `.xhtml`.
- **Lógica de vista / Controlador**: Implementación de `@Named` y `@ManagedBean`.
- **Coordinador de pruebas**: Validación de flujo y usabilidad.
- **Planificación**: Revisión de requisitos y priorización de pantallas a desarrollar.

---

##  Requisitos del sistema

- Java JDK 21 o superior  
- Maven 
- IDE recomendado: IntelliJ IDEA 
- Navegador actualizado (Chrome, Firefox, etc.)

---

##  Instalación del proyecto

```bash
git clone https://github.com/R0yalCode/Room-Vibe.git
cd Room-Vibe
mvn clean install
```

  ## Requisitos de Sistema
- Java SE 21
- Apache Maven (versión 3.8.x o superior)
- Un navegador web moderno 
- IDE como IntelliJ IDEA para desarrollo
> No es necesario instalar Maven si usas el Maven Wrapper (mvnw, mvnw.cmd).
Asegúrate de tener configurada la variable de entorno JAVA_HOME apuntando a tu instalación de Java.

## Estructura del Proyecto
```bash
room-vibe-web/
 ├── Dockerfile
 ├── mvnw
 ├── mvnw.cmd
 ├── pom.xml
 ├── README.md
 └── src/
     └── main/
         ├── java/
         │   └── edu/
         │       └── unl/
         │           └── cc/
         │               └── jbrew/
         │                   ├── bussiness/
         │                   │   ├── SecurityFacade.java
         │                   │   └── services/
         │                   │       ├── PermissionRepository.java
         │                   │       ├── RoleRepository.java
         │                   │       └── UserRepository.java
         │                   ├── controllers/
         │                   │   ├── AuthenticationBean.java
         │                   │   ├── AuthorizationFilter.java
         │                   │   └── security/
         │                   │       ├── UserHome.java
         │                   │       ├── UserList.java
         │                   │       ├── UserPrincipal.java
         │                   │       └── UserSession.java
         │                   ├── domain/
         │                   │   ├── common/
         │                   │   │   ├── GenderType.java
         │                   │   │   └── Person.java
         │                   │   └── security/
         │                   │       ├── ActionType.java
         │                   │       ├── Permission.java
         │                   │       ├── Role.java
         │                   │       └── User.java
         │                   ├── exception/
         │                   │   ├── CredentialInvalidException.java
         │                   │   ├── EncryptorException.java
         │                   │   └── EntityNotFoundException.java
         │                   ├── faces/
         │                   │   ├── ContactoBean.java
         │                   │   ├── FacesUtil.java
         │                   │   ├── InicioBean.java
         │                   │   ├── RecuperarBean.java
         │                   │   ├── ReservaBean.java
         │                   │   └── ValidatorBean.java
         │                   ├── jakarta/
         │                   │   └── hello/
         │                   │       ├── Hello.java
         │                   │       ├── HelloApplication.java
         │                   │       └── HelloWorldResource.java
         │                   └── util/
         │                       └── EncryptorManager.java
         ├── liberty/
         │   └── config/
         │       └── server.xml
         └── webapp/
             ├── contacto.xhtml
             ├── index.xhtml
             ├── login.xhtml
             ├── recuperar.xhtml
             ├── reserva.xhtml
             ├── servicios.xhtml
             ├── test.xhtml
             ├── images/
             │   ├── fondo.jpg
             │   ├── inicio.jpg
             │   ├── inicio1.jpg
             │   ├── reserva.jpg
             │   ├── restaurante.jpg
             │   ├── room-vibe-logo.jpg
             │   ├── spa.jpg
             │   └── servicios/
             │       ├── desayuno.jpg
             │       ├── estacionamiento.jpg
             │       ├── sala.jpg
             │       ├── seguridad.jpg
             │       ├── spa.jpg
             │       └── wifi.jpg
             ├── security/
             │   ├── userEdit.xhtml
             │   └── userList.xhtml
             └── WEB-INF/
                 ├── web.xml
                 └── templates/
                     ├── base.xhtml
                     └── fragments/
                         ├── footer.xhtml
                         └── topbar.xhtml
```

