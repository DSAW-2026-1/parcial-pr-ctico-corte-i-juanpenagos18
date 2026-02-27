Prompt 1 - Estructura

Primero pedí que me generara la estructura HTML del componente.

Prompt que utilicé:

Crea un archivo index.html usando HTML semántico.
Usa main y dentro un section para el componente.
Debe haber un contenedor de 400px por 300px.
Dentro agrega 8 figuras (4 cuadrados y 4 círculos) ubicadas en las esquinas como en la imagen:
arriba izquierda cuadrado y círculo, arriba derecha círculo y cuadrado, abajo izquierda círculo y cuadrado, abajo derecha cuadrado y círculo.
No uses estilos inline. Usa clases para evitar problemas de especificidad.

⸻

Prompt 2 - Estilos base

Después pedí que agregara los estilos básicos en un archivo CSS externo.

Prompt que utilicé:

Crea un archivo style.css.
Aplica un reset básico y usa box-sizing: border-box.
Usa unidades rem en lugar de px.
Define los colores del fondo azul y de las figuras (cuadrados celestes y círculos rosados).
Aplica correctamente el modelo de caja (content, padding, border, margin).
No uses !important para respetar la cascada.

⸻

Prompt 3 - Layout y alineación

Por último pedí que centrara el contenedor y ubicara las figuras correctamente.

Prompt que utilicé:

Centra el contenedor vertical y horizontalmente usando Flexbox (display: flex, justify-content y align-items).
Usa position: relative en el contenedor y position: absolute en las figuras para ubicarlas exactamente en las esquinas.
Mantén la especificidad baja usando solo clases.
Si es necesario puedes usar alguna pseudo-clase como hover, pero sin cambiar el diseño principal.