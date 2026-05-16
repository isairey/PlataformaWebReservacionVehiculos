<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/741/741407.png" />

# 🚗 Car Rental System

### Plataforma web de gestión y reservación de vehículos 🚀

<p align="center">
  <b>Car Rental System</b> es un sistema completo de administración de renta de automóviles desarrollado para automatizar reservas, gestión de flota, usuarios y operaciones administrativas desde una plataforma moderna y centralizada.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CarRental-ManagementSystem-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/PHP-FullStack-777BB4?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-Academic-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Car Rental System** es una plataforma web desarrollada para automatizar procesos de renta de vehículos mediante un sistema completo de administración de flota, reservaciones y usuarios.

El proyecto fue desarrollado como un mini proyecto académico enfocado en:

- 🚗 Gestión de vehículos
- 📅 Reservaciones online
- 👤 Administración de usuarios
- 📊 Dashboard administrativo
- 🧾 Control de rentas
- 📂 Gestión de contenido
- 🔐 Autenticación segura
- 🗄️ Bases de datos relacionales

Además, el proyecto fue publicado como artículo académico en IJRASET, demostrando la aplicación práctica de sistemas gestores de bases de datos y arquitectura web full stack.

---

# ✨ Características

## 🚘 Gestión de vehículos

- 🚗 Catálogo completo de vehículos
- 🏷️ Gestión de marcas
- 📸 Imágenes de automóviles
- 📋 Especificaciones detalladas
- 💰 Administración de precios

---

## 📅 Sistema de reservaciones

- 📆 Reservación online
- 🔍 Consulta de disponibilidad
- 📊 Seguimiento de reservas
- ⚡ Confirmación automática
- 🧾 Historial de rentas

---

## 👤 Gestión de usuarios

- 🔐 Registro e inicio de sesión
- 👥 Gestión de clientes
- 🔑 Recuperación de contraseña
- 📄 Historial de reservaciones
- 👨‍💼 Administración de perfiles

---

## 🛠️ Panel administrativo

- 📊 Dashboard administrativo
- 🚘 Administración de flota
- 📈 Estadísticas del sistema
- 📋 Gestión de reservaciones
- 👥 Control de usuarios

---

## 📂 Gestión de contenido

- 📰 Administración de páginas
- ❓ Gestión de FAQs
- 📧 Manejo de consultas
- ⭐ Testimonios de usuarios
- 📢 Administración de contenido dinámico

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,bootstrap,js,jquery" />
</p>

- HTML5
- CSS3
- Bootstrap 3
- JavaScript
- jQuery

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=php" />
</p>

- PHP 7.x
- Arquitectura procedural
- CRUD administrativo
- Gestión de sesiones

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- Relaciones SQL
- Gestión de reservas
- Persistencia relacional

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github" />
</p>

- Git
- GitHub
- Apache
- XAMPP / WAMP

---

# 📂 Estructura del proyecto

```bash
CAR-RENTAL-SYSTEM/
│
├── docs/                      # Documentación técnica
├── Mini-Project/              # Recursos académicos
├── Source Code/
│   ├── admin/                 # Panel administrativo
│   ├── assets/                # Recursos frontend
│   ├── includes/              # Configuraciones
│   ├── sqlfile/               # Base de datos SQL
│   ├── index.php              # Página principal
│   ├── profile.php            # Gestión de usuarios
│   └── vehicle-details.php    # Información de vehículos
│
├── LICENSE
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

- PHP 7+
- MySQL
- Apache
- XAMPP / WAMP
- Navegador web moderno

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/Amey-Thakur/CAR-RENTAL-SYSTEM.git
```

---

## 2️⃣ Mover archivos

Copiar contenido de:

```bash
Source Code/
```

Hacia:

```bash
xampp/htdocs/carrental/
```

---

## 3️⃣ Crear base de datos

Crear base de datos:

```bash
carrental
```

Importar archivo:

```bash
sqlfile/carrental.sql
```

---

## 4️⃣ Configurar conexión

Editar:

```bash
includes/config.php
```

Agregar:

```php
define('DB_HOST','localhost');
define('DB_USER','root');
define('DB_PASS','');
define('DB_NAME','carrental');
```

---

## 5️⃣ Ejecutar proyecto

Abrir:

```bash
http://localhost/carrental/
```

---

# 📊 Funcionalidades principales

## 🚗 Administración de flota

- Registro de vehículos
- Control de inventario
- Gestión de marcas
- Seguimiento de disponibilidad

---

## 📅 Gestión de reservas

- Reservaciones online
- Confirmación de solicitudes
- Administración de fechas
- Control de disponibilidad

---

## 👥 Administración de usuarios

- Registro de clientes
- Historial de actividades
- Gestión de perfiles
- Recuperación de contraseñas

---

## 📈 Dashboard administrativo

- Estadísticas generales
- Reportes de reservas
- Gestión de usuarios
- Supervisión del sistema

---

# 📸 Vista previa

## 🧠 Diagramas y arquitectura

<div align="center">

### 📌 Use Case Diagram
![UseCase](Mini-Project/Figures/Fig.%20%281%29%20Use%20Case%20Diagram.png)

### 📌 Data Flow Diagram
![DFD](Mini-Project/Figures/Fig.%20%282%29%20Data%20Flow%20Diagram.png)

### 📌 Sequence Diagram
![Sequence](Mini-Project/Figures/Fig.%20%283%29%20Sequence%20Diagram.png)

### 📌 Entity Relationship Diagram
![ERD](Mini-Project/Figures/Fig.%20%284%29%20ER%20Diagram.jpg)

</div>

---

## 🖥️ Interfaces del sistema

<div align="center">

### 🏠 Página principal
![Home](Mini-Project/Figures/Fig.%20%286%29%20Home.jpg)

### 🚘 Listado de vehículos
![Cars](Mini-Project/Figures/Fig.%20%287%29%20Cars.jpg)

### 📞 Contacto
![Contact](Mini-Project/Figures/Fig.%20%288%29%20Contact%20Us.jpg)

### 🔐 Inicio de sesión
![Login](Mini-Project/Figures/Fig.%20%289%29%20Sign%20In.jpg)

### 👤 Registro de usuario
![Register](Mini-Project/Figures/Fig.%20%2810%29%20Make%20My%20Account.jpg)

### 🔑 Recuperación de contraseña
![Password](Mini-Project/Figures/Fig.%20%2811%29%20Password%20Recovery.jpg)

### 👨‍💼 Perfil de usuario
![Profile](Mini-Project/Figures/Fig.%20%2812%29%20My%20Profile.jpg)

### 📅 Historial de reservaciones
![Bookings](Mini-Project/Figures/Fig.%20%2813%29%20My%20Booking.jpg)

</div>

---

# 🎓 Publicación académica

## 📄 Investigación y paper

El proyecto fue publicado en:

- 📚 IJRASET Volume 9 Issue 7
- 🧠 Investigación académica DBMS
- 📑 Preprint en viXra
- 🏅 Certificación oficial

---

# 🧠 Objetivos del proyecto

## 🎯 Aprender y practicar

- Bases de datos relacionales
- PHP Full Stack
- CRUD administrativos
- Arquitectura web
- Sistemas empresariales
- Gestión de reservaciones
- Desarrollo académico

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Infraestructura cloud
- 💳 Pagos electrónicos
- 📊 Dashboard avanzado
- 🔔 Notificaciones en tiempo real
- 🤖 Automatización inteligente
- 🌐 API REST moderna

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

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por sistemas administrativos, arquitectura web y plataformas empresariales modernas 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source bajo licencia MIT para fines educativos y administrativos.

---

<div align="center">

### 🚗 Car Rental System — gestión inteligente de reservaciones y vehículos 🚀

</div>
