# UNPA-ICO

Organización de GitHub de Ingeniería en Computación de la
Universidad del Papaloapan.

## Propósito

Esta organización concentra repositorios de proyectos de software
desarrollados, mantenidos o administrados por Ingeniería en Computación,
con el objetivo de favorecer su continuidad, mantenimiento y transferencia
entre generaciones de desarrolladores.

## Organización de los sistemas

Como estándar, los sistemas institucionales se organizan en repositorios
separados:

- `<sistema>-frontend`: interfaz de usuario.
- `<sistema>-backend`: lógica de negocio, API y acceso a datos.
- `<sistema>-deploy`: configuración y documentación de despliegue.

## Flujo de trabajo

Los cambios deberán desarrollarse en ramas de trabajo y posteriormente
integrarse mediante Pull Requests.

Convenciones principales de ramas:

- `feature/*`: nuevas funcionalidades.
- `fix/*`: correcciones.
- `docs/*`: documentación.
- `chore/*`: mantenimiento y configuración.

La rama `main` representa la versión estable del proyecto.

## Tecnologías institucionales recomendadas

Para nuevos sistemas institucionales se recomienda:

- Angular
- Spring Boot
- MariaDB / MySQL
- Docker
- Git y GitHub

El uso de tecnologías alternativas deberá estar técnicamente justificado.

## Seguridad

Nunca deberán almacenarse en los repositorios:

- contraseñas;
- tokens;
- claves privadas;
- archivos `.env` con credenciales reales;
- certificados privados;
- respaldos de producción;
- datos personales o información institucional sensible.

## Documentación

Cada repositorio deberá incluir un `README.md` que permita comprender
su propósito, requisitos, configuración y procedimiento básico de ejecución.

Los sistemas deberán conservar suficiente documentación para que puedan
ser mantenidos por desarrolladores distintos de sus autores originales.

---

**Ingeniería en Computación**  
**Universidad del Papaloapan**
