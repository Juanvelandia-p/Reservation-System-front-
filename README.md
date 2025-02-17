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

# Tareas
1. Como usuario quiero reservar un laboratorio para su uso
2. Como usuario quiero cancelar una reservacion para no hacer uso de la sala

# Solucion
1. Crear un pagina con 8 botones cada uno con la imagen de los laboratorios disponibles
2. Crear una pagina donde ingresar los datos de reserva
3. Crear el panel con los campos de informacion a ingresar
4. Crear cuadro de texto desplegable con las opciones de laboratorios
5. Crear zona de texto con ingreso del email de la persona reservando 
6. Crear zona de texto con el ingreso de Nombre de la persona
7. Crear zona de texto para ingresar el asunto para el uso del laboratorio

1. Creacion de boton "Cancelar resrvacion" en la pagina principal
2. Creacion de panel con los campos de informacion a ingresar
3. Creacion de campo de texto para el token con el cual se hizo la reservacion
4. Creacion de campo de texto para ingresar el email de la persona que hizo la reservacion