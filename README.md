# 🍔 Food by Lu

Sistema web completo de gestión de pedidos de comida desarrollado como Trabajo Integrador utilizando Java + Spring Boot en el backend y TypeScript + Vite en el frontend.

---

# 📌 Descripción del proyecto

Food by Lu es una aplicación web inspirada en plataformas de pedidos de comida online.

El sistema permite:

✅ Registro e inicio de sesión de usuarios  
✅ Diferenciación de roles (ADMIN / CLIENTE)  
✅ Visualización de productos por categorías  
✅ Carrito de compras dinámico  
✅ Checkout y generación de pedidos  
✅ Gestión completa de productos  
✅ Gestión de categorías  
✅ Administración de pedidos  
✅ Cambio de estados de pedidos  
✅ Visualización de pedidos propios por cliente  
✅ Persistencia de datos con base de datos H2  
✅ Diseño responsive y moderno  

---

# 🛠️ Tecnologías utilizadas

## 🔹 Backend
- Java 17
- Spring Boot
- Spring Data JPA
- Hibernate
- H2 Database
- Maven

## 🔹 Frontend
- TypeScript
- Vite
- HTML5
- CSS

---

# 🎨 Características principales

## 👤 Sistema de usuarios
- Registro de clientes
- Inicio de sesión
- Persistencia de sesión con LocalStorage
- Roles diferenciados:
  - ADMIN
  - CLIENTE

---

## 🍟 Gestión de productos
El administrador puede:

- Crear productos
- Editar productos
- Eliminar productos
- Activar / desactivar disponibilidad
- Asignar categorías
- Subir imágenes
- Gestionar stock

---

## 📂 Gestión de categorías
- Creación de categorías
- Asociación de productos a categorías
- Filtros dinámicos por categoría

---

## 🛒 Carrito de compras
- Agregar productos
- Aumentar/disminuir cantidades
- Eliminar productos
- Persistencia en LocalStorage
- Cálculo automático de totales

---

## 📦 Sistema de pedidos
Los clientes pueden:

- Realizar pedidos
- Consultar sus pedidos
- Ver estados de compra

El administrador puede:

- Ver todos los pedidos
- Cambiar estados:
  - PENDIENTE
  - PREPARANDO
  - EN CAMINO
  - ENTREGADO
  - CANCELADO

---

# 🧠 Funcionalidades implementadas

✅ Login y registro  
✅ Protección por roles  
✅ Renderizado dinámico  
✅ CRUD completo  
✅ Modales interactivos  
✅ Toasts de confirmación  
✅ Filtros y buscador  
✅ Ordenamiento de productos  
✅ Vista detalle de producto  
✅ Responsive Design  
✅ Dashboard administrativo  
✅ Persistencia de sesión  
✅ Manejo de estados de pedido  
✅ Manejo de imágenes en productos  

---

# 🎨 Diseño UI/UX

La aplicación fue diseñada con una interfaz moderna utilizando:

- Gradientes
- Glassmorphism
- Sombras suaves
- Paleta violeta personalizada
- Cards responsivas
- Navegación visual intuitiva
- Badges de estados
- Animaciones suaves

---

# 📁 Estructura del proyecto

## Frontend

```txt
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

```txt
src/main/java/com/tuuniversidad/foodstore
│
├── controller
├── model
├── repository
├── service
└── config
```

---

# 🚀 Cómo ejecutar el proyecto

# 🔹 Backend

## 1. Abrir el proyecto backend en IntelliJ

## 2. Ejecutar:

```txt
FoodstoreApplication
```

El backend correrá en:

```txt
http://localhost:8080
```

---

# 🔹 Frontend

## 1. Abrir la carpeta frontend en VS Code

## 2. Instalar dependencias

```bash
npm install
```

## 3. Ejecutar el proyecto

```bash
npm run dev
```

El frontend correrá en:

```txt
http://localhost:5201
```

---

# 🗄️ Base de datos H2

Acceso a consola H2:

```txt
http://localhost:8080/h2-console
```

## Configuración:

```txt
JDBC URL:
jdbc:h2:file:C:/Users/Usuario/Desktop/TFI_P3_MENDEZ LUCIANO/Proyecto-Integrador-Prog3/foodstore-backend/foodstore/data/foodstoredb

User:
sa

Password:
(vacío)
```

---

# 🔑 Usuarios de prueba

## 👑 ADMIN

```txt
Email:
lumen@gmail.com

Password:
lu123
```

---

## 👤 CLIENTE

```txt
Email:
lumendez@gmail.com

Password:
lu1234
```

---

# 📷 Capturas del sistema

## Funcionalidades principales

- Login y registro
- Dashboard administrativo
- Gestión de productos
- Carrito de compras
- Checkout
- Gestión de pedidos
- Vista de pedidos por cliente
- Estados dinámicos

---

# 📚 Aprendizajes obtenidos

Durante el desarrollo de este proyecto se trabajó con:

- Arquitectura cliente-servidor
- APIs REST
- Manejo de estados
- Persistencia de datos
- CRUD completo
- Manejo de eventos
- Organización modular
- Diseño responsive
- Integración frontend-backend

---

# ✅ Estado actual del proyecto

✔️ Proyecto funcional  
✔️ Backend conectado correctamente  
✔️ Frontend responsive  
✔️ Persistencia funcionando  
✔️ Roles implementados  
✔️ CRUD completo  
✔️ Gestión de pedidos funcional  
✔️ Diseño moderno terminado  

---

# 👨‍💻 Autor

## Luciano David Mendez

Trabajo Integrador — Programación III

---

# ⭐ Observaciones

El proyecto fue desarrollado aplicando buenas prácticas de organización, separación de responsabilidades y experiencia visual moderna, buscando simular una aplicación real de pedidos online.

---

# Link del video expositivo:
https://drive.google.com/file/d/1vw7rvn-tSR6unlHKVi9NnyPL69Qihajj/view?usp=sharing 

---

# Link del Trabajo Final en PDF:
https://drive.google.com/file/d/1SqHJFoig8Vtf3e48UK0cKmdkXvt4vHOM/view?usp=sharing
