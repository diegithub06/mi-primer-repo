1. ¿Qué diferencia hay entre preparar un archivo y confirmarlo?

Preparar un archivo significa seleccionarlo para incluirlo en el próximo commit. Confirmarlo significa guardar esos cambios en el historial de Git.

2. ¿Cuándo puedes usar Descartar cambios y qué riesgo tiene?

Se puede usar cuando quieres deshacer cambios que has hecho y ya no necesitas y el riesgo es perder el trabajo realizado si no lo has guardado en otro sitio.

3. ¿Qué pasa con tu trabajo cuando cambias de una rama a otra?

Git cambia los archivos para mostrar la versión de la rama a la que te cambias. Los cambios que no hayas confirmado pueden mantenerse, pero también pueden impedir cambios si hay conflictos.

4. ¿Por qué no hubo conflicto al fusionar rama-a pero sí al fusionar rama-b?

Porque rama--a al ser la primera no habia problema en sustituir el h1 pero al fusionar rama--b como ya estaba el h1 de la rama--a hubo un conflicto 

5. ¿Para qué sirve crear una rama de experimento, aunque luego se borre?

Sirve para probar cosas sin afectar al trabajo principal. Aunque después se borre, permite experimentar con tranquilidad y volver atrás si algo sale mal.

6. Si descubres hoy un error cometido hace cinco commits, ¿qué haces para arreglarlo?

Buscar el error, corregir el archivo y hacer un nuevo commit con la solución. Así se mantiene el historial y queda registrado el arreglo sin modificar los commits anteriores.