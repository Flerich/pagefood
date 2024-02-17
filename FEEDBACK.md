# Feedback

## Demo Web

1. Carpeta Assets esta muy pesada.

- Aconsejo usar un compresor de fotos o (idealmente) subir las fotos en un servicio como https://cloudinary.com/ y usar el link.
- Las fotos .png, .jpg o archivos binarios no deberian de ser agregados en el repositorio, aparte de su peso, por el mismo hecho de que son archivos binarios, al momento de actualizar alguno de estos Git no puede optimizar su versionamiento y hace una copia completa al hacer un commit, y como Git se encarga de almacenar todo el historial el repositorio .git se embasura muy rapido.

2. Mejorar el title y colocar un favicon.

3. Espaciados incorrectos

- El padding que esta aplicado no es el correcto, apoyarse en el Figma y ubicarse en la pagina de **Ajustes y Beakpoints** para ubicar el diseño del homepage.
- Ubicada el diseño del homepage, podemos aprecial que el padding que tiene, por ejemplo, el logo MLC gatrobar, si seleccionamos el logo, podemos revelar las medidas manteniendo presionado el boton Option/Alt, asi nos muestra unas lineas rojas con las medidas exactas.
- Las medidas en diseño son padding-top: 128, padding-left: 112, las medidas encontradas fueron padding: 40px 5% 0px;
- Mismas observaciones errores de espaciado se aprecian alrededor del proyecto.

4. Logo utiliza un span + backgorund-image

- las imagenes siempre deben de ser mostradas con una etiqueta <img/>
- Las excepciones a esta regla son imagenes destinadas para ocupar el espacio detras del contenido, cosa correcta que ocurre en .header_container

5.  Falta de efectos tipo :hover en los botones.

- El proyecto cuenta con un prototype, al usar la combinacion de teclas en **Windows: Ctrl + Alt + Enter** o ubicando el **boton de play** en la esquina superior derecha, nos abre el prototype donde podemos aprecias estos efectos dentro del diseño.
- Hay veces que estos efectos no estan mostrados en diseños, sin embargo, es bueno agregarlo si no los vemos.
- Recomendaciones de efecto hover seria Opacidad o Cambio de color.

6. Seccion Chef

- La seccion de chef esta incorrecta en muchos sentidos, espaciado, maquetacion y efectos
- el diesño indica que las tarjetas deben de estar situadas a la izquierda en armonia con el titulo, descripcion.
- el diseño indica que el contenido debe de estar situada a la izquierda del contenedor, actualmente esta en el medio.

7. Seccion Marcas

- Sin comentarios, esta bien.

8. Seccion de Reserva

- La seccion de reserva esta incorrecta en muchos sentidos, espaciado, maquetacion y efectos.

9. Seccion de Contacto

- Imagen de fondo no ocupa todo el espacio de la seccion.
- Titulo y tarjeta si estan en armonia pero la ubicacion no.
- Maquetacion no respeta el diseño.

10. Seccion de Reseñas

- Las tarjetas estan bien pero mal ubicadas.
- El fondo no se aprecia de la misma manera que el diseño.

11. Pie de Pagina (Footer)

- Espacios incorrectos, sabores, vive la experiencia, acerca de nosotros estan uno sobre el otro en vez de uno al lado del otro.

## Demo Tablet

1. El menu movil

- En el telefono no tenemos acceso al efecto hover, solo podemos pulsar con el dedo, debido a esto es completamente inaccesible en un dispositivo real.
- Cambiar efecto hover con click y manejar un estado de abierto/cerrado.

2. Seccion Principal

- Mejoro el espaciado

3. Seccion Chef

- Errores de maquetado/medidas/espacion, pero son menos en comparacion con la version desktop.
- Recomiendo el uso de la propiedad CSS -webkit-line-clamp: 2. Esta regla se encarga de colocar elipsis (...) al final del texto en el caso que el texto sea muy largo, permitiendonos colocar el texto completo en el HTML y el CSS se encargara de hacer que se vea bien.

4. Seccion Marcas

- Sin comentarios, esta bien.

5. Seccion de Reserva

- La seccion de reserva esta incorrecta en muchos sentidos, espaciado, maquetacion y efectos.

6. Seccion de Contacto

- Si luce bien y esta mejor, pero el diseño coloca la tarjeta al lado izquierdo de la seccion, no centrado.
- Mi opinion personal es, como tu lo dejaste (en el centro) esta mejor, pero nosotros debemos de seguir el diseño a menos que podamos estar en contacto con el diseñador.
- Igual, esta seccion esta bien.

7. Seccion de Reseñas

- Estan bien.

8. Pie de Pagina (Footer)

- Espacios incorrectos, sabores, vive la experiencia, acerca de nosotros estan uno sobre el otro en vez de uno al lado del otro.

## Demo Mobile

1. Seccion principal

- Esta bien, se acerca mucho a como esta en el diseño.
- Igual aqui esta el mismo problema del menu, no se puede abrir en disponsitivo real.
- Adicional, el encabezado en Tablet y Mobile deberia de usar position: fixed para acompañar al usuario durante su visita (esto no esta en el prototype).

2. Seccion Chef

- Es la mejor iteracion entre las 3 versiones, mi observacion es que las tarjetas deben estar un poco mas grandes para igualar el diseño

3. Seccion de Marcas

- Esta bien.

4. Seccion de Reserva

- La seccion de reserva esta incorrecta en muchos sentidos, espaciado, maquetacion y efectos.

6. Seccion de Contacto

- Esta bien ya que iguala al diseño.
- Personalmente yo lo haria centrado todo, pero como iguala el diseño esta como debe ser.

7. Seccion de Reseñas

- Estan bien.

8. Pie de Pagina (Footer)

- Esta version movil si igual el diseño
