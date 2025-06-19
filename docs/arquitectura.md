# Arquitectura del Sistema

El sistema HLVS está compuesto por los siguientes módulos principales:

- **Frontend web**: Interfaz para porteros y administradores.
- **Backend API**: Lógica de negocio y gestión de datos.
- **Base de datos**: Almacena registros de accesos y usuarios.
- **Integraciones**: Cámaras, sensores y notificaciones.

```mermaid
flowchart TD
    A[Portería] -->|Registra acceso| B[Backend API]
    B --> C[Base de datos]
    B --> D[Frontend web]
    B --> E[Integraciones]
```

[Volver a la portada](index.md) 