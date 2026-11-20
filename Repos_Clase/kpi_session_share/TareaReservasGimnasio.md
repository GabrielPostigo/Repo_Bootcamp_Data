

\------------------------------------------

## ***NORTHSTAR***

\-----------------------------------------

**Clientes que reservan y asisten a menudo**





\------------------------------------------------

## ***VANIDAD/PALANCA***

\------------------------------------------------

**-Frecuencia con la que la gente repite**

**-Número de reservas**

**-Ratings positivos**

**-Intención general de volver (Se recoge gracias a sistema de métrica)**

**-Lista de espera (representa que no se da a vasto, aunque es algo en lo que trabajar para no perder clientes a futuro)**

**-Flujo de nuevos clientes**



\----------------------------------------------------------------------------

## ***ACTIVACIÓN, CALIDAD Y RECURRENCIA***

\----------------------------------------------------------------------------

**-Activación:** Primera clase reservada, primer rating a clases, descuentos y promociones para nuevos integrantes

**-Calidad**: Grado de satisfacción por clases, Grado de satisfacción Por docente, Calidad de las instalaciones, facilidad y 

efectividad del método de reserva, sistema de rating, buen estado de las instalaciones, cantidad y calidad de promociones.

**-Recurrencia:** Media de personas que asisten de forma diaria/semanal, tiempo medio de permanencia en el gimnasio alto, intención general de regresar a clases. Promociones adicionales por antigüedad, promociones por regresar



\-----------------------------------------

## ***QUE HACE CADA COSA***

\----------------------------------------

**Booking\_id:** Primary key. Número de registro para identificar datos.

**\*Months\_as\_member:** Meses en los que ha sido miembro

**Weight:** Peso de la persona

**\*Days\_before:** Dias de antelación de reserva

**time:** SI vino por la mañana o tarde (AM/PM)

**\*Category:** Categoría de entrenamiento

**\*\*attended:** SI asistió a la reserva

**\*Days\_before\_num:** Hace cuantos días de la última vez que vino

**\*Day\_of\_week:** Dia de la semana

**Ternure group:** Rango de asistencia



**filas\_origen:** Total de entradas de la base de datos

**reservas\_con\_target\_valido:** Reservas válidas

**reservas\_sin\_target\_valido:** Reservas fallidas

**ids\_duplicados:** Bookings duplicados

**nulos\_antiguedad:** Entradas que no registraron antiguedad

**nulos\_anticipacion:** Entradas que no registraron anticipacion

**nulos\_categoria:** Entradas sin una categoría

**nulos\_dia\_normalizado:** No tengo claro



#### **\[EL BOOKING\_ID ES EL UNICO DATO QUE SIEMPRE CAMBIA]**

\-------------------------------------









