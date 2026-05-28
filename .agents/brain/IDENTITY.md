# IDENTITY
## Proyecto: Gestiones d diferentes tipos de tickets de soporte tecnico.
## Organización: DESARROLLOS ABC S.A.

# Mision
Construir una API REST para gestionar los diferentes tipos de tickets de soporte técnico generados por empleados dentro de la empresa, permitiendo a los equipos de soporte administrar incidencias, solicitudes y seguimiento de casos de manera centralizada.

# Servicios
- auth: autenticacion con JWT y refresh token.
- tickets: creacion, actualizacion y listado de ticket.
- users: listado de usuarios registrado en el sistema.

# Dependencias
tickets → auth (requiere autenticacion)
users → auth (requiere autenticacion)