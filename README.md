# 🎓 Sistema de Gestión de Becas Universitarias

Este proyecto es una aplicación web desarrollada para centralizar, administrar y auditar las postulaciones a los diferentes programas de estímulos y becas de la universidad. Resuelve la problemática de la información dispersa unificando el control de alumnos, requisitos documentales y el estado de las solicitudes en tiempo real.

Integrantes

     Espinal Luque Cristian           N°Lista: 47
     Lia Cortez Renzo Sandro          N°Lista: 61
     Lopez Valero Manfred Omar        N°Lista: 62
     Samuel Walter Mamani Tarquino    N°Lista: 72
---

## 🚀 Características Principales
- **Dashboard Estadístico:** Indicadores dinámicos en el inicio conectados a la base de datos (conteo de becas activas).
- **Control de Alumnos:** Administración del padrón, seguimiento de carreras y validación de promedios acumulados.
- **Módulo de Postulaciones:** Flujo de aprobación, rechazo o evaluación pendiente de solicitudes.
- **Gestión Documental:** Validación y auditoría de los expedientes digitales adjuntos por los postulantes.
- **Sistema de Consultas:** Panel interactivo para filtrado y búsqueda inteligente de beneficiarios.

---

## 🛠️ Tecnologías Utilizadas
- **Backend:** Python 3.x con Flask (Arquitectura limpia y manejo de rutas)
- **Frontend:** HTML5, CSS3, JavaScript (AJAX para modales) y Bootstrap 5 (Diseño Responsivo)
- **Base de Datos:** MySQL (Estructura relacional mediante llaves foráneas)

---

## 📦 Requisitos Previos
Antes de iniciar, asegúrate de tener instalado en tu equipo:
- [Python 3.10 o superior](https://www.python.org/)
- [MySQL Server](https://dev.mysql.com/downloads/installer/) o un entorno local como XAMPP / WampServer.

---

## 💻 Guía de Instalación y Despliegue (Paso a Paso)

Sigue este orden en tu terminal o línea de comandos para poner en marcha el sistema:

### Paso 1: Clonar el repositorio y acceder a la carpeta
Ejecuta estos comandos para descargar el proyecto en tu máquina y situarte dentro de su directorio:

git clone https://github.com/Cristianespinal1/Proyecto3-Sistema-de-Gesti-n-de-Becas-Universitarias
cd Proyecto3-Sistema-de-Gesti-n-de-Becas-Universitarias

### Paso 2: Crear y activar el Entorno Virtual
python -m venv venv
.\venv\Scripts\activate

### Paso 3: Instalar las dependencias del proyecto
pip install -r requirements.txt

### Paso 4: Ejecutar el servidor de desarrollo
python app.py


Credenciales de Acceso
Usuario: admin
Contraseña: 123
