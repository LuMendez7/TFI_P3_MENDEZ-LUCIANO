# 🍔 Food by Lu

Sistema web completo para la gestión de pedidos de comida desarrollado como Trabajo Práctico Integrador de Programación III utilizando **Java 17 + Spring Boot** para el backend y **TypeScript + Vite** para el frontend.

---

# 📌 Descripción del proyecto

Food by Lu es una aplicación web inspirada en plataformas de pedidos online que permite a clientes realizar compras de comida y a administradores gestionar completamente el sistema.

El proyecto implementa una arquitectura Cliente–Servidor mediante una API REST desarrollada con Spring Boot, aplicando buenas prácticas de organización del código, reutilización, separación de responsabilidades y persistencia de datos.

---

# 🏗️ Arquitectura del sistema

```
Frontend (TypeScript + Vite)
            │
            ▼
      API REST (Spring Boot)
            │
            ▼
 Controller → Service → Repository
            │
            ▼
      Spring Data JPA
            │
            ▼
        Base de datos H2
```

El backend fue desarrollado utilizando una arquitectura en capas, separando claramente las responsabilidades entre controladores, servicios y repositorios.

---

# 🚀 Funcionalidades principales

## 👤 Usuarios

- Registro de clientes
- Inicio de sesión
- Persistencia de sesión mediante LocalStorage
- Roles diferenciados:
  - ADMIN
  - CLIENTE

---

## 🍔 Productos

El administrador puede:

- Crear productos
- Editar productos
- Eliminar productos
- Activar o desactivar disponibilidad
- Asignar categorías
- Gestionar imágenes
- Gestionar stock

Los clientes pueden:

- Visualizar productos
- Buscar productos
- Filtrar por categorías
- Consultar detalles del producto

---

## 📂 Categorías

- Creación de categorías
- Asociación de productos
- Filtros dinámicos

---

## 🛒 Carrito

- Agregar productos
- Modificar cantidades
- Eliminar productos
- Persistencia mediante LocalStorage
- Cálculo automático del total

---

## 📦 Pedidos

Los clientes pueden:

- Realizar pedidos
- Consultar únicamente sus pedidos
- Visualizar estado de compra

El administrador puede:

- Ver todos los pedidos
- Consultar detalle completo
- Modificar el estado del pedido

Estados disponibles:

- PENDIENTE
- PREPARANDO
- EN CAMINO
- ENTREGADO
- CANCELADO

---

# 🧠 Funcionalidades implementadas

- ✅ Login
- ✅ Registro
- ✅ Protección por roles
- ✅ CRUD completo
- ✅ Gestión de productos
- ✅ Gestión de categorías
- ✅ Gestión de pedidos
- ✅ Cambio de estados
- ✅ Visualización de pedidos por cliente
- ✅ Dashboard administrativo
- ✅ Renderizado dinámico
- ✅ Persistencia de sesión
- ✅ Persistencia de datos con H2
- ✅ Responsive Design
- ✅ DTO para creación de pedidos
- ✅ Arquitectura en capas
- ✅ BaseEntity reutilizable
- ✅ BaseRepository genérico
- ✅ Relaciones JPA
- ✅ Manejo transaccional mediante @Transactional
- ✅ Contraseñas encriptadas con BCrypt
- ✅ Documentación automática mediante Swagger/OpenAPI

---

# 🛠️ Tecnologías utilizadas

## Backend

- Java 17
- Spring Boot
- Spring Data JPA
- Hibernate
- H2 Database
- Gradle
- Lombok
- BCrypt
- Swagger / OpenAPI

---

## Frontend

- TypeScript
- Vite
- HTML5
- CSS3
- Fetch API
- LocalStorage

---

# 🗄️ Base de datos

El proyecto utiliza una base de datos H2 persistente.

Acceso a la consola:

```
http://localhost:8080/h2-console
```

Configuración:

```
JDBC URL

jdbc:h2:file:C:/Users/Usuario/Desktop/TFI_P3_MENDEZ LUCIANO/Proyecto-Integrador-Prog3/foodstore-backend/foodstore/data/foodstoredb

User

sa

Password

(vacío)
```

---

# 📑 Documentación de la API

El proyecto incorpora documentación automática mediante Swagger/OpenAPI.

Acceso:

```
http://localhost:8080/swagger-ui/index.html
```

Desde Swagger es posible:

- visualizar todos los endpoints
- consultar modelos
- probar peticiones
- verificar respuestas del backend

---

# 📁 Estructura del proyecto

## Frontend

```
src
│
├── pages
│   ├── admin
│   ├── auth
│   ├── client
│   └── store
│
├── utils
├── types
├── style.css
└── main.ts
```

---

## Backend

```
src/main/java/com/tuuniversidad/foodstore
│
├── controller
├── dto
├── exception
├── model
├── repository
├── service
│    └── impl
├── config
└── FoodstoreApplication
```

---

# 🚀 Cómo ejecutar el proyecto

## Backend

Abrir el proyecto en IntelliJ IDEA.

Ejecutar:

```
FoodstoreApplication
```

El backend iniciará en:

```
http://localhost:8080
```

---

## Frontend

Abrir la carpeta frontend en Visual Studio Code.

Instalar dependencias:

```bash
npm install
```

Ejecutar:

```bash
npm run dev
```

El frontend iniciará en:

```
http://localhost:5174
```

---

# 🔑 Usuarios de prueba

## Administrador

Email

```
lumen@gmail.com
```

Contraseña

```
lu123
```

---

## Cliente

Email

```
lumendez@gmail.com
```

Contraseña

```
lu1234
```

---

# 📷 Capturas sugeridas

- Login
- Registro
- Página principal
- Productos
- Carrito
- Checkout
- Pedidos del cliente
- Panel administrativo
- Gestión de productos
- Gestión de pedidos
- Detalle del pedido
- Swagger
- Consola H2

---

# 📚 Aprendizajes obtenidos

Durante el desarrollo del proyecto se aplicaron conocimientos sobre:

- Arquitectura Cliente–Servidor
- API REST
- Spring Boot
- Spring Data JPA
- Hibernate
- Relaciones entre entidades
- Arquitectura en capas
- CRUD completo
- DTO (Data Transfer Objects)
- BaseEntity y herencia
- BaseRepository genérico
- Manejo transaccional mediante @Transactional
- Persistencia con H2
- BCrypt para encriptación de contraseñas
- Swagger/OpenAPI
- Integración Frontend–Backend
- Responsive Design
- Organización modular del código

---

# ✅ Estado actual del proyecto

- ✔ Proyecto completamente funcional
- ✔ Backend conectado al frontend
- ✔ Persistencia mediante H2
- ✔ CRUD completo
- ✔ Gestión de productos
- ✔ Gestión de categorías
- ✔ Gestión de pedidos
- ✔ Roles implementados
- ✔ Seguridad mediante BCrypt
- ✔ Documentación con Swagger
- ✔ Arquitectura en capas
- ✔ BaseEntity y BaseRepository implementados
- ✔ DTO para pedidos
- ✔ Interfaz moderna y responsive

---

# 👨‍💻 Autor

**Luciano David Méndez**

Trabajo Práctico Integrador — Programación III

---

# ⭐ Observaciones

El proyecto fue desarrollado aplicando buenas prácticas de programación orientada a objetos y una arquitectura en capas basada en Controller–Service–Repository. Se incorporaron mecanismos de reutilización mediante BaseEntity y BaseRepository, documentación automática con Swagger/OpenAPI, manejo transaccional con @Transactional, uso de DTO para la creación de pedidos y encriptación de contraseñas mediante BCrypt. El objetivo fue simular el funcionamiento de una aplicación real de pedidos de comida, priorizando tanto la organización interna del código como una experiencia de usuario moderna e intuitiva.

---

# Link del video expositivo:
https://drive.google.com/file/d/1OKBUJuMc2pcepL2MmJXJhyjF-krqtMqP/view?usp=sharing

---

# Link del Trabajo Final en PDF:
https://drive.google.com/file/d/1Q55gM9gxMIlWMn4HJRQ7QnBOcoevbQVJ/view?usp=sharing
