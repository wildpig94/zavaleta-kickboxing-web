# Zavaleta Kickboxing / MMA — sitio web

Sitio de una página para la academia **Zavaleta Kickboxing / MMA**, en Apatzingán,
Michoacán: kickboxing, jiu-jitsu brasileño y MMA, con clases para niños, adultos y
grupo matutino desde 2007.

La página vive en `index.html` y se publica tal cual, sin compilación, en GitHub
Pages: **https://wildpig94.github.io/zavaleta-kickboxing-web/**


## Qué hay

| Archivo | Qué es |
| --- | --- |
| `index.html` | La página completa: estilos y estructura en el mismo archivo |
| `fuentes/` | Las tipografías (Oswald y Barlow), servidas desde aquí y no desde Google |
| `imagenes/` | El logo, la foto del hero y la del área de entrenamiento |
| `favicon-32.png`, `apple-touch-icon.png`, `icono-192.png` | El icono en la pestaña y al guardarlo en el teléfono |
| `og.jpg` | La imagen que se ve al compartir el enlace por WhatsApp o Facebook |

## Cómo se trabaja

El diseño es del dueño del estudio y no se toca desde aquí. Este repositorio guarda
la versión publicable, que salió del archivo original con estos cambios —ninguno
visible en el diseño—:

1. Las tipografías se sirven desde `fuentes/` en vez de pedirlas a Google: se van
   dos dominios de fuera y la página carga sin depender de nadie.
2. Se agregó la descripción para buscadores, los datos para compartir el enlace
   (título, descripción e imagen) y el icono.
3. Se agregó la ficha del negocio en datos estructurados (nombre, dirección,
   teléfono, horarios y calificación de Google), para que Google la lea como ficha
   y no como texto suelto.
4. Las imágenes salieron del HTML a archivos: el documento pasó de 350 KB a 17 KB y
   el navegador puede guardarlas en caché.
5. Las fotos y el logo declaran su tamaño, así la página ya no salta mientras carga.
6. Los enlaces del pie y los iconos del hero llegaron a 44 px de alto: medían 20 y
   22 px, que en un teléfono no se pueden tocar con el pulgar.

## Verificación

Medido sobre la página servida, a 1440, 390 y 320 px de ancho: sin desbordes, sin
texto encimado, sin fallos de contraste, sin errores de JavaScript y sin objetivos
táctiles por debajo de 44 px. El diseño se comparó píxel a píxel contra el archivo
original: la primera pantalla cambia menos del 0.04%, que es la recompresión del
logo.
