# Clinica

### Proyecto - Evaluacion Semana 2 Java

##### Problema:

Se necesita tener control sobre las citas programdas y a programar para la Clinica: **Be The One**
Para esto necesitamos:

1.  Programar nuevas citas
2.  Listar Las citas programadas por los siguientes criterios:
    - Citas por Cliente (puede ser por: codigo de cliente, nombre, telefono)
    - Citas del Dia
    - Citas por Estado
    - Citas por Doctor (puede ser por: codigo del doctor, nomnbre)
    - Citas por fecha especifica
3. Modificar Citas bajo las siguientes criterios:
    - Solo un cliente puede solicitar modificar el dia y hora de la cita
    - La clinia podra modificar el Doctor y Fecha y hora asignado a una cita especifica
    - No se puede eliminar una cita, solo debe cambiar su estado
    - Solo podra modificarse las citas que tengan estado PROGRAMADA


Nota:
- Los estados posibles de una cita son: PROGRAMADA, FINALIZADA, CANCELADA

##### A evaluar
- Debe ser un Api RestFul
- Debe usar un DataSource en codigo
- Preferible usar MySQL
- Si hay datos que deben estar en la BD para el funcionamiento de la API, favor colocar el script SQL(INSERT) en la carpeta del proyecto
- La aplicacion debe correr en el puerto 7004
- El formato de las fechas debe ser dd-MM-YYYY HH:mm (al mostrarla en la respuesta)
- Debe crear una rama con su nombre y apellido ej. (MarioArias)
- Hora final para commit de rama Sabado 14 23:59:59
- Cualquier extra es bienvenido

P.D.
Pueden hacerme consultas por WhatsApp, siempre que sea en horas habiles :) 
