# Documentación de la BASE DE DATOS

### Funcionalidades
- Permite gestionar un inventario de plantas.
- Controla el acceso mediante usuarios registrados.
- Proporciona almacenamiento y consulta eficiente de datos.

### Tablas Principales
- **Usuarios**: Contiene los datos de los usuarios que pueden acceder al sistema.
- **Plantas**: Almacena la información de las plantas registradas.
- **Registros**: Guarda el historial de modificaciones realizadas sobre las plantas.

### Procesos Almacenados
- `sp_AgregarPlanta`: Inserta una nueva planta en la base de datos.
- `sp_ActualizarPlanta`: Modifica los datos de una planta existente.
- `sp_EliminarPlanta`: Elimina una planta del sistema.
- `sp_BuscarPlanta`: Realiza una búsqueda eficiente de plantas.

---