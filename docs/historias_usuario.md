Historias de Usuario - API de Festivos
#1️ Consultar festivos de un país
Como usuario,
quiero obtener la lista de festivos de un país específico,
para planificar mis actividades con anticipación.

Criterios de Aceptación:
✔ La API debe permitir consultar los festivos de un país enviando el código del país.
✔ Los datos deben incluir el nombre del festivo, la fecha y el año.

#2️ Consultar festivos por año
Como usuario,
quiero consultar los festivos de un año específico,
para saber qué días son festivos en ese periodo.

Criterios de Aceptación:
✔ La API debe permitir filtrar los festivos por año.
✔ Debe retornar la lista de festivos correspondientes a ese año.

#3️ Agregar un nuevo festivo
Como administrador,
quiero registrar un nuevo festivo en la base de datos,
para actualizar la información en la API.

Criterios de Aceptación:
✔ La API debe permitir registrar un festivo con el país, nombre, día, mes y año.
✔ Debe validar que la fecha no esté duplicada en el país.

#4️ Modificar un festivo existente
Como administrador,
quiero editar la información de un festivo,
para corregir errores o actualizar datos en la API.

Criterios de Aceptación:
✔ La API debe permitir modificar cualquier atributo de un festivo.
✔ Si se cambia la fecha, debe validarse que no exista otro festivo en la misma fecha.

#5️ Eliminar un festivo
Como administrador,
quiero eliminar un festivo de la base de datos,
para mantener la información actualizada y evitar datos incorrectos.

Criterios de Aceptación:
✔ La API debe permitir eliminar un festivo por su ID.
✔ Debe asegurarse de que el festivo realmente exista antes de eliminarlo.

#6️ Consultar el próximo festivo
Como usuario,
quiero saber cuál es el próximo festivo en mi país,
para poder planificar actividades con tiempo.

Criterios de Aceptación:
✔ La API debe devolver el próximo festivo basado en la fecha actual.
✔ Debe incluir el nombre del festivo y cuántos días faltan para que ocurra