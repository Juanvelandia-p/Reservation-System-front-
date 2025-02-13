# Reservation-System-front-
# Sprint 1: Configuración General del Proyecto

# Configuración de ambientes (frontend).
En le frontend vamos a hacer uso de react para este

# Scaffolding del proyecto.
Creamos las partes iniciales de la pagina web
- Pagina principal donde vemos los laboratorios existentes y al oprimir sobre ellos vamos a la pagian de reserva
- Pagina de reserva donde se ingresan los datos de la persona que reserva la sala

# Configuración de la base de datos (MongoDB Cloud o archivo de texto plano).
# Definición del modelo de datos (salones y reservas).Modelo de Laboratorio:
- Modelo de laboratorio(Pagina principal):
    Nombre del laboratorio con imagen
    Disponibilidad (puede estar relacionado con las reservas)
- Modelo de Reserva(Pagina de reserva):
    Menu desplegable con los laboratorios
    Correo del usuario haciendo la reserva
    Fecha y hora
    Propósito
    