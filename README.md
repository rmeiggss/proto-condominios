# Sistema de Gestión Villa Alameda Sur - Prototipos UI

Este repositorio contiene la maqueta visual y prototipos HTML estáticos que sirven de **referencia visual oficial** para la construcción del frontend del sistema de gestión del condominio.

## Arquitectura de Composición
- **Tecnologías:** HTML5 estático y CSS (TailwindCSS).
- **Enfoque:** Maquetación sin lógica de negocio, utilizada exclusivamente como referencia de diseño, paleta de colores, tipografía, espaciados y responsive design para el equipo de Frontend.
- **Estructura:** Páginas autocontenidas (ej. `DashboardFinancieroV2.html`, `PortalAdministrador.html`) que representan el layout real de 1440px y móvil. Contienen datos de ejemplo y nombres ficticios para proteger datos personales.

## Arranque en Entorno Local
No se requiere servidor de desarrollo, empaquetador ni instalación de dependencias. Para visualizar las pantallas localmente:
1. Clonar el repositorio.
2. Abrir cualquier archivo `.html` (ej. `index.html`) directamente en un navegador web.

## Estructura a Nivel de Nube (Azure)
- **Hospedaje:** Repositorio público con deploy automático hacia Azure para compartir fácilmente el progreso visual con la junta directiva y equipo sin requerir autenticación.
- **Seguridad:** Al ser público, **nunca** debe contener datos reales de los residentes (nombres reales, deudas, teléfonos, etc.). Todo el contenido es ficticio.
