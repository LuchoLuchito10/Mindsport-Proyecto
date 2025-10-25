🧠 MindSport - Sistema de Evaluación y Seguimiento Psicológico Deportivo










🎯 Problemática que aborda

El proyecto MindSport nace como respuesta a una problemática creciente en el ámbito deportivo profesional y formativo, donde los factores psicológicos influyen directamente en el rendimiento, la permanencia y la salud integral del futbolista.

Principales desafíos identificados:

Alta tasa de abandono deportivo derivada de factores psicológicos no tratados a tiempo.

Bajo rendimiento deportivo asociado a una débil fortaleza mental, falta de concentración o gestión emocional ineficiente.

Ausencia de un seguimiento psicológico integral que acompañe la evolución del deportista a lo largo del tiempo.

Dificultad para la detección temprana de síntomas de estrés, ansiedad o depresión.

Falta de herramientas digitales específicas para integrar evaluación psicológica y datos de rendimiento deportivo.

⚙️ Características principales
Funcionalidad	Estado	Beneficio
Autenticación JWT	✅ MVP	Acceso seguro y diferenciado
Gestión de Roles	✅ MVP	Control de accesos específicos (Entrenador / Futbolista)
Tests IED/IPED	✅ MVP	Evaluación psicológica estandarizada
MongoDB Cloud	✅ MVP	Almacenamiento seguro de datos
API REST documentada	✅ MVP	Integración robusta con frontend
Dashboard de Entrenador	🔄 En desarrollo	Seguimiento del equipo y alertas
Sistema de Alertas	🔄 En desarrollo	Detección temprana de indicadores psicológicos
Reportes Automáticos	🔄 En desarrollo	Análisis de progreso y rendimiento
🏗️ Arquitectura del Sistema

El sistema está basado en una arquitectura moderna orientada a microservicios, con un frontend React que se comunica con un backend en Spring Boot mediante JWT para autenticación y MongoDB Atlas como base de datos en la nube.

Esquema general:

Frontend (React)

Backend (Spring Boot + Spring Security)

MongoDB Atlas (Base de datos)

JWT Service (Autenticación y autorización)

💻 Tecnologías Utilizadas
Capa	Tecnologías	Propósito
Frontend	React, React Router, JWT	Interfaz de usuario y consumo de API
Backend	Spring Boot, Spring Security	Lógica de negocio y servicios REST
Base de Datos	MongoDB Atlas	Almacenamiento de evaluaciones y perfiles
Seguridad	JWT, BCrypt	Autenticación y autorización segura
Desarrollo	Git, GitHub, VS Code	Control de versiones y entorno de desarrollo
📁 Estructura del Proyecto

mindsport/
├── backend/ — API REST en Spring Boot
│ ├── controllers/ → Controladores REST
│ ├── models/ → Modelos de datos
│ ├── services/ → Lógica de negocio
│ ├── security/ → Configuración JWT y filtros de seguridad
│ └── pom.xml → Dependencias Maven
│
├── frontend/ — Aplicación React
│ ├── src/
│ │ ├── components/ → Componentes reutilizables de interfaz
│ │ ├── pages/ → Páginas principales (Login, Dashboard, Tests)
│ │ └── services/ → Conexión con la API REST
│ └── package.json → Dependencias npm
│
└── README.md — Documentación del proyecto

📊 Estado de Desarrollo
✅ MVP Funcional

Autenticación y autorización JWT

Gestión de roles (Entrenador / Futbolista)

Registro y login de usuarios

Almacenamiento en MongoDB

API REST documentada

Protección de rutas según rol

Manejo de errores y validaciones robustas

🔄 En Desarrollo

Implementación de tests psicológicos digitales (IED, IPED, etc.)

Dashboard de entrenador con visualización de métricas

Sistema de seguimiento y alertas automáticas

Generación de reportes de progreso y rendimiento mental

🎯 Casos de Uso
👨‍🏫 Entrenadores

Registro y seguimiento psicológico de futbolistas.

Evaluación integral del equipo.

Análisis comparativo del progreso por jugador.

⚽ Futbolistas

Realización de tests psicológicos digitales.

Visualización de su progreso personal.

Acceso a recomendaciones y planes de mejora.

🧩 Administración

Gestión de usuarios y roles.

Control centralizado de evaluaciones.

Generación de reportes de rendimiento mental y emocional.

🌍 Impacto y Propósito

MindSport busca impulsar una cultura deportiva más humana y sostenible, donde el desarrollo mental y emocional tenga el mismo valor que el físico.
A través de tecnología ética y transparente, promueve el bienestar psicológico, la prevención del abandono deportivo y la optimización del rendimiento de los atletas.

📘 “Un deportista fuerte no solo entrena su cuerpo, también entrena su mente.”
