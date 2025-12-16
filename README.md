# Examen Mínimo 2 - Backend

**Ejercicio:** 5

## Implementación

### 1. Backend
- **Nueva Ruta:** Implementado `GET /events/{id}/users`.
- **Lógica:** Devuelve una lista simulada de usuarios inscritos en un evento, incluyendo:
    - Nombre
    - Apellidos
    - URL de imagen
- **Traza:** Muestra un log en la consola del servidor confirmando la recepción de la petición.

### 2. Android
- **Modelo:** Creada clase `UserEvent.java`.
- **Retrofit:** Añadida la llamada `GET` correspondiente en la interfaz `ApiService`.
- **UI (Interfaz):**
    - Creada nueva Activity `EventUsersActivity` junto con su layout XML.
    - La nueva actividad es la que se encarga de recibir la lista y visualizarla.
- **Navegación:**
    - Añadido un botón "Evento" en el menú principal (visible tras el login) que navega a la nueva funcionalidad.

## Estado del Proyecto
- [x] El Backend compila y responde JSON correctamente.
- [x] La App Android muestra el listado de usuarios sin errores.