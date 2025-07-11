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
## Vistas del Sistema
### Vista 1: index.xhtml
<img width="1919" height="969" alt="image" src="https://github.com/user-attachments/assets/7c14623e-d9b8-4c4c-955b-6880326be2af" />

### Vista 2: login.xhtml
<img width="1919" height="967" alt="image" src="https://github.com/user-attachments/assets/b4332f5e-fd39-4952-a536-d22648bdd12d" />

### Vista 3: recuperar.xhtml
<img width="1919" height="973" alt="image" src="https://github.com/user-attachments/assets/b7b6f271-c2cd-4690-9156-acd83a2db41b" />

### Vista 4: reserva.xhtml
<img width="1916" height="939" alt="image" src="https://github.com/user-attachments/assets/537e49b3-12ac-4e32-af02-ceb05ce71e2e" />

### Vista 5: servicios.xhtml
<img width="1919" height="964" alt="image" src="https://github.com/user-attachments/assets/7c62735a-3804-4b47-a78c-fc3abcc78996" />
<img width="1902" height="960" alt="image" src="https://github.com/user-attachments/assets/06c115d6-0ca9-4594-9116-0887f48ec990" />

### Vista 6: contacto.xhtml
<img width="1903" height="960" alt="image" src="https://github.com/user-attachments/assets/a2c055f9-5ef2-44ad-bd9e-7f3a39f7fcad" />

## Autores: 
### [Royel Jima](https://github.com/R0yalCode)
### [Steeven Pardo](https://github.com/Dan1el17)
### [Juan Calopino](https://github.com/JuaaanCalopino)
### [Daniel Saavedra](https://github.com/Dan-San837)


