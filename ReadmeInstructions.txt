App:
- Crear y mantener listado señores
- Conmutar estado selected de señor recibido
- Eliminar señor recibido
- Crear señor recibido

- Seleccionar todos
- Deseleccionar todos

- Calcular valores: 
	· total señores seleccionados
	

- Renderizar componentes: tantos Gentlemen como haya en la lista, los botones, la Info

Info:
- Mostrar valor recibidio en una frase "n gentlemen piniting at u"

SelectButton:
- Si recibe un total de seleccionados igual al total:
	· mostrar el texto Unselect All
	· cuando se hace click, llamar a la acción recibida para deseleccionar todos
- Si recibe un total de seleccionados menor al total:
	· mostrar el texto Select All
	· cuando se hace click, llamar a la acción recibida para seleccionar todos

Gentelman:
- Mostrar la info recibida (name, profes.....)
- Si el selected recibido es true:
	· debe mostrar el icono check
	· la foto debe voltearse

- Si el selected recibido es false: 
	· debe mostrar el icono uncheck
	· la foto debe volver a su posición original

- Si se hace click sobre el icono borrar, debe llamar a una función recibida para eliminar señor q t señala
- Si se hace click sobre el icono añadir, debe llamar a una función recibida para añadir señor