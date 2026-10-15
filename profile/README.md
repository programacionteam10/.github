<div align="center">

# 📱 ContactApp - Programación IV
### Universidad Dr. Andrés Bello (UNAB)

[![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)](https://developer.android.com/studio)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![API REST](https://img.shields.io/badge/API-RESTful-green?style=for-the-badge)](https://github.com/programacionteam10)

*Aplicación móvil nativa para Android sincronizada con una API RESTful centralizada para la gestión de contactos.*

</div>

---

## 📄 Descripción del Proyecto

**ContactApp** es una solución móvil cliente-servidor desarrollada como proyecto principal para la asignatura **Programación IV**. La plataforma está compuesta por una aplicación cliente para dispositivos Android (desarrollada en Java) que consume una API REST alojada en el servidor (desarrollada en Python) para procesar, sincronizar y almacenar la información de los contactos en tiempo real.

---

## 📋 Historias de Usuario (User Stories)

| ID | Historia de Usuario | Criterios de Aceptación |
| :---: | :--- | :--- |
| **HU-01** | **Autenticación de Usuario:** Como usuario, quiero registrarme e iniciar sesión para proteger la privacidad de mis contactos. | • Formulario de registro/login.<br>• Autenticación mediante tokens de sesión JSON/HTTP. |
| **HU-02** | **Creación de Contacto:** Como usuario, quiero agregar un nuevo contacto con nombre, teléfono y correo electrónico para guardarlo en la nube. | • Validación de campos obligatorios en cliente y servidor.<br>• Envío exitoso mediante petición HTTP `POST`. |
| **HU-03** | **Listado de Contactos:** Como usuario, quiero ver la lista completa de mis contactos guardados con su información principal. | • Visualización en `RecyclerView` optimizado.<br>• Obtención de datos mediante petición HTTP `GET`. |
| **HU-04** | **Búsqueda y Filtrado:** Como usuario, quiero buscar contactos por nombre o número telefónico de forma rápida. | • Filtrado en tiempo real dentro del buscador en Android.<br>• Actualización dinámica del adaptador. |
| **HU-05** | **Gestión y Modificación (CRUD):** Como usuario, quiero editar o eliminar la información de un contacto existente. | • Diálogo modal de confirmación antes de borrar.<br>• Peticiones HTTP `PUT` (actualizar) y `DELETE` (eliminar). |

---

## 🛠️ Tecnologías y Herramientas

* **Cliente Móvil (Android):**
  * **Entorno de Desarrollo:** Android Studio
  * **Lenguaje:** Java
  * **Componentes HTTP:** Retrofit 2 / Volley (Consumo de API REST)
  * **Interfaz:** Material Design, XML, `RecyclerView`
* **Servidor (Backend):**
  * **Lenguaje:** Python
  * **Formato de Intercambio:** JSON
* **Control de Versiones:** Git y GitHub (`programacionteam10`)

---

## 👥 Integrantes del Equipo

| Integrante | Correo Institucional | Rol / Responsabilidad |
| :--- | :--- | :--- |
| **Jaime Fernando Berrios Ortiz** | `bo0310042024@unab.edu.sv` | Desarrollo Backend / API REST |
| **Alexis Sebastian Castro Ramirez** | `cr03642024@unab.edu.sv` | Desarrollo Frontend Android & UI/UX |
| **Andrea Patricia Nolasco Ortega** | `no0882042024@unab.edu.sv` | Consumo de API & Lógica en Java |
| **Carlos Alberto Campos Santos** | `cs1209042018@unab.edu.sv` | Pruebas de Integración & Documentación |

---

## 🚀 Repositorios del Proyecto

* 🔗 [**App-Contactos-Android**](https://github.com/programacionteam10/App-Contactos-Android) — Código fuente de la aplicación nativa en Android Studio (Java).
* 🔗 [**api-contactos**](https://github.com/programacionteam10/api-contactos) — Servicios y endpoints del servidor backend (Python).

---

<div align="center">
<sub>Proyecto Académico • Universidad Dr. Andrés Bello (UNAB)</sub>
</div>
