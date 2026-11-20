# PlenaGuard

**Sistema de monitoreo y apoyo para el cuidado de pacientes**

PlenaGuard fue un proyecto desarrollado durante el **primer semestre de 2026**. Su propósito fue crear una solución tecnológica de apoyo al cuidado de pacientes, reuniendo una aplicación móvil, un backend, una base de datos y dispositivos de monitoreo para presentar información relevante de manera clara y accesible.

## Objetivo del proyecto

Desarrollar una plataforma que permita consultar información del paciente y visualizar sus registros y alertas desde una aplicación móvil. La solución considera la comunicación entre los distintos componentes del sistema para centralizar la información y facilitar su seguimiento por parte del paciente y su equipo de cuidado.

## Mi participación

Mi participación abarcó tanto la coordinación del trabajo como el desarrollo técnico de la solución:

- **Organización y seguimiento:** apoyé la planificación del trabajo y la coordinación del equipo para procurar el cumplimiento de los tiempos y fechas de entrega establecidos.
- **Desarrollo Full Stack:** participé en el desarrollo de la aplicación móvil, el backend y la base de datos, trabajando en la integración entre estos componentes.
- **Diseño de la aplicación:** me encargué del diseño de la interfaz de usuario, buscando una experiencia clara, coherente y sencilla de utilizar.
- **Organización y presentación de la información:** trabajé para que la información del proyecto se estructurara siguiendo criterios y estándares técnicos, manteniendo la legibilidad lógica y la consistencia con los objetivos definidos. Esto permitió facilitar su exposición y comprensión ante distintas audiencias.

## Componentes de la solución

| Componente | Descripción |
|---|---|
| Aplicación móvil | Interfaz para consultar la información del paciente, revisar el historial y acceder a las opciones de configuración. |
| Backend | Servicios y API encargados de procesar las solicitudes y conectar la aplicación con los datos. |
| Base de datos | Almacenamiento y organización de la información utilizada por la plataforma. |
| Dispositivo de monitoreo | Componente de hardware considerado para obtener y enviar mediciones al sistema. |

## Tecnologías

Las tecnologías utilizadas en el proyecto incluyen:

- **Aplicación móvil:** React Native y Expo.
- **Backend:** Node.js y Express.
- **Base de datos:** PostgreSQL mediante Supabase.
- **Hardware:** ESP32 y sensores de monitoreo.

> La lista describe las tecnologías principales del proyecto. Completa o ajusta esta sección si la versión final utilizó herramientas adicionales.

## Capturas de la aplicación

A continuación se muestra una captura de la interfaz de inicio de sesión. Se pueden agregar más imágenes a esta sección a medida que se preparen nuevas capturas.

### Inicio de sesión

![Pantalla de inicio de sesión de PlenaGuard](docs/screenshots/inicio-sesion.png)

### Creación de cuenta

<!-- Agrega aquí la captura y guárdala como docs/screenshots/crear-cuenta.png -->
<!-- ![Pantalla de creación de cuenta](docs/screenshots/crear-cuenta.png) -->

### Pantalla principal

<!-- Agrega aquí la captura y guárdala como docs/screenshots/inicio.png -->
<!-- ![Pantalla principal de PlenaGuard](docs/screenshots/inicio.png) -->

### Historial y configuración

<!-- Agrega aquí las capturas cuando estén disponibles. -->

## Estructura del repositorio

La estructura puede organizarse por componentes para mantener el código y los recursos separados:

```text
PlenaGuard/
├── plenaguard-app/   # Aplicación móvil
├── backend/          # API y lógica del servidor
├── DB/               # Scripts y recursos de base de datos
├── ESP32/            # Código del dispositivo
├── docs/
│   └── screenshots/  # Capturas para este README
└── README.md
```

Los nombres y directorios deben ajustarse a la estructura real del repositorio.

## Estado del proyecto

Este repositorio documenta el trabajo realizado durante el primer semestre de 2026. Para ejecutar la aplicación o el backend, revisa las instrucciones y variables de entorno correspondientes a cada componente. No publiques credenciales, tokens ni archivos `.env` en el repositorio.

---

**PlenaGuard — Proyecto académico, primer semestre de 2026.**
