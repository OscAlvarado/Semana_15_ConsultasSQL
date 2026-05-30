# Semana_15_ConsultasSQL

## Descripción

Este repositorio contiene el archivo SQL correspondiente a la creación y gestión de una base de datos para un sistema de alojamiento tipo Airbnb. El script incluye la definición de la estructura de la base de datos, relaciones entre tablas y consultas SQL para la manipulación y recuperación de información.

## Motor de Base de Datos Utilizado

- PostgreSQL

## Archivo Principal

- `db_Consultas_Alojamiento_Airbnb.sql`

## Esquema de la Base de Datos

La base de datos se denomina:

```sql
gestion_airbnb
```

### Tablas Principales

| Tabla | Descripción |
|---------|-------------|
| propietarios | Almacena la información de los propietarios de los alojamientos. |
| alojamientos | Contiene los datos de las propiedades disponibles para alquiler. |
| huespedes | Registra la información de los huéspedes. |
| reservas | Gestiona las reservas realizadas por los huéspedes. |
| pagos | Almacena los pagos asociados a las reservas. |
| resenas | Guarda las calificaciones y comentarios de los huéspedes. |

### Relaciones

- Un propietario puede tener varios alojamientos.
- Un alojamiento puede recibir múltiples reservas.
- Un huésped puede realizar múltiples reservas.
- Cada reserva puede tener un pago asociado.
- Los huéspedes pueden dejar reseñas sobre los alojamientos reservados.

## Autor

Desarrollado como actividad académica de consultas SQL.