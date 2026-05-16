# 🔐 Security Policy

<div align="center">

<img width="180" src="./assets/security.png" />

# 🚗 Car Rental System — Security Policy

### Política de seguridad y reporte de vulnerabilidades 🚀

<p align="center">
  <b>Car Rental System</b> es un sistema web de gestión de renta de vehículos desarrollado con PHP y MySQL.  
  Esta política describe cómo reportar vulnerabilidades y las mejores prácticas de seguridad del proyecto.
</p>

</div>

---

# 📌 Supported Versions

Las siguientes versiones del sistema actualmente reciben actualizaciones de seguridad:

| Version | Supported |
|----------|------------|
| 2.x | ✅ |
| 1.x | ⚠️ Mantenimiento limitado |
| < 1.0 | ❌ |

---

# 🛡️ Reportar una Vulnerabilidad

Si encuentras una vulnerabilidad o problema de seguridad, por favor repórtalo de manera responsable.

## 📧 Contacto de Seguridad

- ✉️ Email: `Developer.SR.IRP@gmail.com`
- 👨‍💻 Developer: **Isai Reyes**
- 💻 Full Stack Developer

---

# ⚠️ Recomendaciones de Seguridad

Para ejecutar el sistema de manera segura se recomienda:

- 🔒 Cambiar credenciales por defecto
- 🔑 Utilizar contraseñas seguras
- 🛠 Mantener PHP y MySQL actualizados
- 🚫 No exponer archivos `.env` o configuraciones sensibles
- 🔐 Implementar HTTPS en producción
- 📦 Validar y sanitizar entradas de usuario
- 🧱 Utilizar prepared statements para consultas SQL
- 📂 Restringir permisos de escritura en el servidor
- 🧹 Eliminar archivos innecesarios antes del despliegue

---

# 🔍 Buenas Prácticas Implementadas

El sistema incluye:

- ✅ Autenticación de usuarios
- ✅ Gestión de sesiones
- ✅ Protección básica contra SQL Injection
- ✅ Validación de formularios
- ✅ Arquitectura organizada para backend y frontend
- ✅ Manejo de roles administrativos

---

# 🚨 Vulnerabilidades Conocidas

Actualmente no existen vulnerabilidades críticas conocidas públicamente.

Si detectas una vulnerabilidad:

1. No publiques exploits públicamente.
2. Reporta el problema por correo.
3. Espera confirmación antes de divulgar detalles.

---

# 🧪 Entorno Recomendado

| Tecnología | Versión Recomendada |
|-------------|---------------------|
| PHP | 8.x |
| MySQL | 8.x |
| Apache | 2.4+ |
| XAMPP | Última versión |
| Navegador | Chrome / Edge / Firefox |

---

# 🔐 Configuración Recomendada

## Variables sensibles

```env
DB_HOST=localhost
DB_DATABASE=carrental
DB_USERNAME=root
DB_PASSWORD=your_password

APP_ENV=production
APP_DEBUG=false
