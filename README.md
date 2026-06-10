# 🏠 HOMEFIX

## Plataforma de Intermediación para Servicios del Hogar

---

## 📖 Descripción General

**HomeFix** es una plataforma web desarrollada para facilitar la conexión entre empleadores y trabajadores especializados en servicios domésticos y mantenimiento del hogar.

La aplicación permite publicar ofertas laborales, buscar personal calificado, gestionar postulaciones y establecer una comunicación directa entre las partes, ofreciendo una experiencia segura, organizada y eficiente.

---

## 🎯 Objetivo del Proyecto

Desarrollar una solución tecnológica que simplifique la contratación de personal para servicios del hogar, permitiendo una gestión rápida, confiable y accesible tanto para empleadores como para trabajadores.

---

## 🚀 Funcionalidades del Sistema

### 👷 Empleado

- Crear cuenta.
- Iniciar sesión.
- Recuperar contraseña.
- Crear y editar perfil.
- Buscar trabajos disponibles.
- Enviar postulaciones.
- Aceptar trabajos.
- Cancelar trabajos.
- Comunicarse con empleadores.
- Gestionar agenda de actividades.
- Consultar historial de trabajos.

### 🏡 Empleador

- Crear cuenta.
- Iniciar sesión.
- Recuperar contraseña.
- Crear perfil.
- Publicar ofertas de trabajo.
- Buscar empleados.
- Revisar postulaciones.
- Contratar empleados.
- Cancelar solicitudes.
- Comunicarse con empleados.
- Calificar trabajadores.

### ⚙️ Administrador

- Gestionar usuarios.
- Gestionar publicaciones.
- Supervisar la plataforma.
- Resolver reportes.
- Generar estadísticas.
- Administrar permisos.
- Monitorear actividad del sistema.

---

## 🛠 Tecnologías Utilizadas

### Frontend

- HTML5
- CSS3
- JavaScript

### Backend

- FastAPI

### Base de Datos

- PostgreSQL

### Herramientas

- Visual Studio Code
- Git
- GitHub

---

## 📂 Estructura del Proyecto

```text
HOMEFIX
│
├── frontend/
│   ├── login.html
│   ├── registro.html
│   ├── dashboard_empleado.html
│   ├── dashboard_empleador.html
│   ├── perfil_empleado.html
│   ├── perfil_empleador.html
│   │
│   ├── css/
│   │   └── style.css
│   │
│   ├── js/
│   │   └── app.js
│   │
│   └── assets/
│       ├── imagenes/
│       └── iconos/
│
├── backend/
│   ├── main.py
│   ├── database.py
│   ├── models.py
│   ├── schemas.py
│   ├── crud.py
│   │
│   └── routers/
│       ├── usuarios.py
│       ├── empleos.py
│       ├── postulaciones.py
│       └── mensajes.py
│
├── database/
│   └── homefix.sql
│
├── requirements.txt
│
└── README.md
```

---

## 💻 Requisitos

Antes de ejecutar el proyecto asegúrate de tener instalado:

- Python 3.10 o superior.
- PostgreSQL.
- Visual Studio Code.
- Git.
- Navegador web actualizado.

---

## ⚡ Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/usuario/homefix.git
```

### 2. Ingresar al proyecto

```bash
cd homefix
```

### 3. Crear entorno virtual

```bash
python -m venv venv
```

### 4. Activar entorno virtual

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### 5. Instalar dependencias

```bash
pip install fastapi uvicorn sqlalchemy psycopg2-binary python-dotenv
```

### 6. Configurar PostgreSQL

Crear la base de datos:

```sql
CREATE DATABASE homefix;
```

Modificar los datos de conexión en:

```python
database.py
```

Ejemplo:

```python
DATABASE_URL = "postgresql://postgres:123456@localhost/homefix"
```

### 7. Ejecutar el servidor

```bash
uvicorn main:app --reload
```

### 8. Abrir la aplicación

Frontend:

```text
http://localhost
```

Backend:

```text
http://localhost:8000
```

Documentación FastAPI:

```text
http://localhost:8000/docs
```

---

## 📋 Módulos Implementados

- ✅ Registro de usuarios.
- ✅ Inicio de sesión.
- ✅ Recuperación de contraseña.
- ✅ Gestión de perfiles.
- ✅ Publicación de ofertas laborales.
- ✅ Búsqueda de trabajadores.
- ✅ Gestión de postulaciones.
- ✅ Dashboard para empleados.
- ✅ Dashboard para empleadores.
- ✅ Agenda de actividades.
- ✅ Sistema de notificaciones.
- ✅ Mensajería interna.
- ✅ Administración de usuarios.

---

## 🔒 Seguridad

El sistema implementa:

- Autenticación de usuarios.
- Control de acceso por roles.
- Validación de formularios.
- Protección de datos.
- Gestión de sesiones.

---

## 📈 Beneficios

- Facilita la contratación de trabajadores.
- Reduce el tiempo de búsqueda de empleo.
- Organiza la gestión de servicios.
- Permite comunicación directa entre usuarios.
- Centraliza la información laboral.
- Mejora la experiencia de contratación.

---

## 👨‍💻 Autores

- Ronald Stiven Verano Sosa
- Johan Esteban Olaya Falla

---

## 👨‍🏫 Instructor

Eduardo Foglia

---

## 🏫 Institución

**SENA**  
Centro de Gestión de Mercados, Logística y Tecnologías de la Información (CGMLTI)

---

## 📅 Fecha

Junio 2026

---

## 📄 Licencia

Proyecto académico desarrollado como evidencia de formación para el programa ADSO del SENA.

© 2026 HomeFix. Todos los derechos reservados.
