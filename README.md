# HOMEFIX

## Descripción del proyecto

HomeFix es una plataforma web diseñada para conectar empleadores con trabajadores domésticos y de servicios para el hogar. La aplicación permite a los usuarios registrarse, iniciar sesión, buscar oportunidades laborales, gestionar solicitudes y mantener comunicación entre las partes involucradas.

## Objetivo

Facilitar la contratación de trabajadores para servicios del hogar mediante una plataforma segura, organizada y fácil de usar.

## Funcionalidades principales

### Empleado

* Crear cuenta.
* Iniciar sesión.
* Recuperar contraseña.
* Crear y editar perfil.
* Buscar trabajos disponibles.
* Enviar postulaciones.
* Aceptar trabajos.
* Cancelar trabajos.
* Comunicarse con empleadores.
* Gestionar agenda de actividades.
* Consultar historial de trabajos.

### Empleador

* Crear cuenta.
* Iniciar sesión.
* Recuperar contraseña.
* Crear perfil.
* Publicar ofertas de trabajo.
* Buscar empleados.
* Revisar postulaciones.
* Contratar empleados.
* Cancelar solicitudes.
* Comunicarse con empleados.
* Calificar trabajadores.

### Administrador

* Gestionar usuarios.
* Gestionar publicaciones.
* Supervisar la plataforma.
* Resolver reportes.
* Generar estadísticas.
* Administrar permisos.

## Tecnologías utilizadas

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* FastAPI

### Base de datos

* PostgreSQL

## Estructura del proyecto

```text
HOMEFIX
│
├── login.html
├── registro.html
├── dashboard_empleado.html
├── css/
├── js/
├── assets/
│   ├── imagenes/
│   └── iconos/
│
├── backend/
│   ├── main.py
│   ├── models.py
│   ├── database.py
│   └── routers/
│
└── README.md
```

## Requisitos

* Navegador web actualizado.
* Visual Studio Code.
* Python 3.10 o superior.
* PostgreSQL.

## Instalación

1. Clonar el repositorio.

```bash
git clone https://github.com/usuario/homefix.git
```

2. Ingresar al proyecto.

```bash
cd homefix
```

3. Instalar dependencias.

```bash
pip install fastapi uvicorn sqlalchemy psycopg2-binary
```

4. Configurar la base de datos PostgreSQL.

5. Ejecutar el servidor.

```bash
uvicorn main:app --reload
```

6. Abrir el navegador y acceder a:

```text
http://localhost:8000
```

## Módulos implementados

* Inicio de sesión.
* Registro de usuarios.
* Dashboard para empleados.
* Gestión de trabajos.
* Agenda.
* Notificaciones.
* Mensajería básica.

## Autores

* Ronald Stiven Verano Sosa
* Johan Esteban Olaya Falla

## Instructor

Eduardo Foglia

## Institución

SENA - Centro de Gestión de Mercados, Logística y Tecnologías de la Información (CGMLTI)

## Fecha

2026
