# web.github.io

# - Al realizar la validación WAI del proyecto, aparecen 35 errores, los cuales no he sido capaz de solventar, aún siguiendo las indicaciones del validador:

# - Error 1: no he podido solventarlo ya que en el desplegable de la barra de búsqueda no puedo incluir un label, puesto que se vería raro.

1.3 Adaptable: Create content that can be presented in different ways (for example simpler layout) without losing information or structure.

Success Criteria 1.3.1 Info and Relationships (A)

Check 91: select element missing an associated label.
Repair: Add a label element that surrounds the control's label. Set the for attribute on the label element to the same value as the id attribute of the control. And/or add a title attribute to the input element. And/or create a label element that contains the input element.
Error Line 77, Column 10:
<select class="input-select">
										<option value="0">Todas</option>
										<option value=" ...

# - Los restantes 34 errores hacen referencia al ratio de contraste entre el texto y el fondo. Igualmente, aún habiendo seguido las indicaciones y acudido a la web https://snook.ca/technical/colour_contrast/colour.html#fg=699BFF,bg=000000 (los dos colores que elijo cumplen todos los estándares, como se puede observar en esta misma página) el validador sigue indicando que no existe suficiente contraste entre ambos colores, por lo que desisto de seguir intentando solventarlo.
