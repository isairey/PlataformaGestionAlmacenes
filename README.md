<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/679/679720.png" />

# 🏭 Warehouse Rental Management System

### Plataforma web de renta y administración de almacenes 🚀

<p align="center">
  <b>Warehouse Rental Management System</b> es una plataforma desarrollada para facilitar la administración y renta de almacenes, permitiendo a propietarios ofrecer espacios de almacenamiento y a empresarios encontrar lugares seguros para guardar sus productos.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Warehouse-RentalSystem-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/PHP-FullStack-777BB4?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-Management-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-módulos-del-sistema">Módulos</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Warehouse Rental Management System** es un sistema web diseñado para automatizar la gestión y renta de almacenes, ayudando a propietarios a administrar espacios disponibles y a empresas a encontrar soluciones de almacenamiento eficientes.

La plataforma fue desarrollada para:

- 🏭 Gestionar almacenes
- 👥 Administrar usuarios
- 📦 Gestionar espacios de almacenamiento
- 📅 Controlar rentas
- 💳 Gestionar pagos
- 📊 Supervisar operaciones
- 🔐 Gestionar accesos
- 🌐 Optimizar logística empresarial

---

# ✨ Características

## 🏭 Gestión de almacenes

- 🏢 Registro de almacenes
- 📍 Gestión de ubicaciones
- 📦 Administración de espacios
- 💰 Configuración de precios
- 📋 Información detallada

---

## 👥 Gestión de usuarios

- 👤 Registro de clientes
- 🔐 Inicio de sesión
- 📄 Gestión de perfiles
- ⚡ Administración centralizada
- 📊 Historial de rentas

---

## 📅 Sistema de renta

- 📆 Reservación de espacios
- 💳 Gestión de pagos
- 📋 Contratos de almacenamiento
- ⚡ Confirmaciones rápidas
- 📦 Gestión logística

---

## 📊 Panel administrativo

- 📈 Dashboard administrativo
- 🏭 Gestión de almacenes
- 👥 Administración de usuarios
- 📅 Supervisión de rentas
- 🔐 Gestión de permisos

---

# 👨‍💼 Módulos del sistema

## 🏭 Warehouse Module

Este módulo administra todos los almacenes registrados dentro del sistema.

### Funcionalidades:

- ➕ Registro de almacenes
- 📍 Gestión de ubicaciones
- 📦 Administración de espacios
- 💰 Configuración de tarifas
- 📋 Información detallada

---

## 👤 Client Module

Este módulo es utilizado por empresarios y clientes.

### Funcionalidades:

- 🔐 Inicio de sesión
- 📦 Buscar espacios
- 📅 Reservar almacenes
- 💳 Gestión de pagos
- 📄 Consultar historial

---

## 🛠️ Admin Module

Este módulo funciona como administrador principal del sistema.

### Funcionalidades:

- 👥 Gestión de usuarios
- 🏭 Supervisión de almacenes
- 📊 Dashboard administrativo
- 📅 Administración de contratos
- 🔐 Gestión general

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,bootstrap,js" />
</p>

- HTML5
- CSS3
- Bootstrap
- JavaScript

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=php" />
</p>

- PHP
- Arquitectura MVC
- CRUD System
- Gestión de sesiones

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- Relaciones SQL
- Persistencia de datos
- Gestión logística

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- Git
- GitHub
- Visual Studio Code
- XAMPP / WAMP

---

# 📂 Estructura del proyecto

```bash
WarehouseRentalManagementSystem/
│
├── admin/                    # Panel administrativo
├── warehouses/               # Gestión de almacenes
├── customer/                 # Módulo cliente
├── assets/                   # Recursos frontend
├── uploads/                  # Imágenes y archivos
├── database/                 # Scripts SQL
├── includes/                 # Configuración y conexión
├── index.php                 # Página principal
├── login.php                 # Inicio de sesión
├── register.php              # Registro de usuarios
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- PHP 7+
- MySQL
- Apache
- XAMPP / WAMP
- Navegador moderno

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/WarehouseRentalManagementSystem.git
```

---

## 2️⃣ Mover archivos

Copiar proyecto hacia:

```bash
xampp/htdocs/WarehouseRentalManagementSystem/
```

---

## 3️⃣ Crear base de datos

Crear base:

```bash
warehouse_rental_management
```

---

## 4️⃣ Importar SQL

Importar:

```bash
database/warehouse_rental_management.sql
```

---

## 5️⃣ Configurar conexión

Editar:

```bash
includes/config.php
```

Agregar:

```php
define('DB_HOST','localhost');
define('DB_USER','root');
define('DB_PASS','');
define('DB_NAME','warehouse_rental_management');
```

---

## 6️⃣ Ejecutar proyecto

Abrir:

```bash
http://localhost/WarehouseRentalManagementSystem/
```

---

# 📊 Funcionalidades principales

## 🏭 Gestión logística

- Administración de almacenes
- Gestión de espacios
- Configuración de tarifas
- Control de disponibilidad

---

## 👥 Administración de usuarios

- Registro y autenticación
- Gestión de perfiles
- Roles administrativos
- Historial de contratos

---

## 📦 Gestión de almacenamiento

- Reservas en tiempo real
- Contratos de alquiler
- Gestión de pagos
- Confirmaciones automáticas

---

# 📸 Vista previa

## 🖥️ Interfaces del sistema

<div align="center">

### 🏭 Dashboard principal
![Dashboard](https://images.unsplash.com/photo-1586528116311-ad8dd3c8310d?q=80&w=1200&auto=format&fit=crop)

### 🔐 Inicio de sesión
![Login](https://images.unsplash.com/photo-1522202176988-66273c2fd55f?q=80&w=1200&auto=format&fit=crop)

### 📦 Gestión de almacenes
![Warehouse](https://images.unsplash.com/photo-1553413077-190dd305871c?q=80&w=1200&auto=format&fit=crop)

### 📋 Contratos de renta
![Contracts](https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?q=80&w=1200&auto=format&fit=crop)

### 👥 Administración de usuarios
![Users](https://images.unsplash.com/photo-1521737604893-d14cc237f11d?q=80&w=1200&auto=format&fit=crop)

### 📊 Panel administrativo
![Admin](https://images.unsplash.com/photo-1460925895917-afdab827c52f?q=80&w=1200&auto=format&fit=crop)

### 📅 Gestión de reservas
![Booking](https://images.unsplash.com/photo-1520607162513-77705c0f0d4a?q=80&w=1200&auto=format&fit=crop)

### ⚙️ Configuración del sistema
![Settings](https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?q=80&w=1200&auto=format&fit=crop)

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo web full stack
- Gestión logística
- Bases de datos relacionales
- CRUD administrativos
- Sistemas de autenticación
- Arquitectura web
- Automatización empresarial

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Infraestructura cloud
- 💳 Pasarela de pagos
- 📦 Rastreo de inventario
- 🤖 Automatización inteligente
- 🌐 API REST moderna
- 🔔 Notificaciones en tiempo real

---

# 🔒 Seguridad

Si descubres una vulnerabilidad de seguridad dentro del sistema, puedes reportarla mediante:

📧 **asad_101@outlook.com**

Todas las vulnerabilidades serán revisadas y atendidas rápidamente.

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Asad — Full Stack Developer

Desarrollador apasionado por sistemas empresariales, logística y plataformas de administración 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source orientado al aprendizaje y administración de sistemas de renta de almacenes y logística empresarial.

---

<div align="center">

### 🏭 Warehouse Rental Management System — administración inteligente de almacenes y logística 🚀

</div>
