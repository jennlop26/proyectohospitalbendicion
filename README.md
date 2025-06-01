# proyectohospitalbendicion
Proyecto final para curso de programacion III
# 🏥 Sistema de Gestión - Hospital La Bendición

Este es un sistema web que desarrollamos como proyecto final del curso de Programación III. La idea principal es facilitar la gestión de un hospital, permitiendo registrar pacientes, doctores, citas médicas y también recetas. El sistema está dividido en dos partes: el backend (hecho con Spring Boot) y el frontend (HTML, CSS y JavaScript).

## 📂 Estructura del Proyecto
PROYECTO FINAL PROGRAMACION/
├── FrontEnd/
│ └── CLASES/
│ ├── index.html
│ ├── login.html
│ ├── menu.html
│ ├── pacientes.html
│ ├── citas.html
│ ├── doctores.html
│ └── recetas.html
└── hospital_proyecto/ (Backend)
├── src/
├── pom.xml
└── configuración con Spring Boot


## 🔧 Tecnologías que utilicé

### Backend
- Java 17
- Spring Boot (con JPA y Web)
- MySQL
- Maven
- JavaMail (para enviar correos al agendar citas)

### Frontend
- HTML5
- CSS3
- JavaScript (uso de `fetch` para llamar a la API)

## 👥 Roles del sistema

Cada usuario entra al sistema con un rol, y según ese rol se muestran o se ocultan funcionalidades:

- **ADMIN:** puede manejar todo (usuarios, doctores, citas).
- **DOCTOR:** puede ver a sus pacientes y registrar recetas.
- **RECEPCIONISTA:** agenda y gestiona las citas.
- **PACIENTE:** puede ver su historial y recetas.

## 📌 Funciones principales

- Iniciar sesión según el rol del usuario.
- Registrar pacientes, doctores y citas.
- Crear y consultar recetas médicas.
- Visualizar el historial clínico del paciente.
- Enviar correos de confirmación al registrar una cita.
- Interfaz moderna y clara, fácil de usar.

## ▶️ Cómo ejecutar el proyecto

### Requisitos:
- Tener Java 17, Maven y MySQL instalados.
- Un navegador moderno como Chrome o Edge.

### Backend (Spring Boot):
1. Importa el proyecto `hospital_proyecto` en tu IDE.
2. Configura la base de datos en el archivo `application.properties`.
3. Ejecuta la clase `HospitalLaBendicionApplication`.

### Frontend:
1. Abre los archivos `.html` que están en `FrontEnd/CLASES/`.
2. Asegúrate de que el backend esté corriendo para que funcione todo correctamente.

Cualquier duda, sugerencia o mejora es bienvenida. Este proyecto fue realizado como parte de un curso y está abierto a aportes.



Gracias por revisar el proyecto. Fue un gran reto integrarlo todo, pero aprendímos mucho en el proceso.

