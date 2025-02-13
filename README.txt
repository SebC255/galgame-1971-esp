Galaxy Game (1971): Parche de traducción al español
Por Seb
Edición Febrero 2025

SOBRE EL JUEGO:

Galaxy Game (el Juego de la Galaxia) es un juego de simulación de combate espacial desarrollado por los
estudiantes universitarios Bill Pitts y Hugh Tuck, y exhibido por primera vez a fines de noviembre de 1971,
aunque antiguamente se creyó que fue en septiembre.

Aunque el juego nunca se comercializó y todas las versiones producidas se consideraron prototipos,
de todos modos se le considera el segundo videojuego para arcades de la historia
(en este caso habría que especificar VIDEOjuego como se le entiende hoy en día).

Fue superado por Computer Space, un juego de concepto similar exhibido en agosto y octubre del mismo año,
y finalmente lanzado en noviembre/diciembre, ganándose el título de primer videojuego comercial.

Ambos juegos fueron creados con la misma idea en mente: Traer el popular juego "Spacewar!" (1962) al público en general
(hasta entonces, los videojuegos solo existían en computadoras de universidades y laboratorios).
Entre los dos, Galaxy Game es el más fiel a su inspiración (aunque al costo de que su producción fuese demasiado cara),
pero también se le agregó nuevas opciones que se pueden configurar antes de cada partida.

Una segunda versión del juego fue construida en junio de 1972 con nuevas opciones, y está actualmente
preservada en el Museo de la Historia de la Computación; pero al momento de crear este parche,
la única versión disponible en internet está basada en la original (o al menos una recreación),
y por ende es la que esta traducción toma en cuenta.

SOBRE EL PARCHE:

Este parche traduce todo el texto del juego menos el título.
Uno de los caracteres sin usar de la versión original (un espacio resaltado) es reemplazado por la letra "Á"
Hacer cambios más drásticos en el código (tales como textos más largos) parece fácil en teoría,
pero no se han podido aplicar debido a falta de experiencia modificando el archivo.

CÓMO USAR EL PARCHE:

1. Ubica el paquete ROM del juego. (galgame.zip o galgame.7z)
1.1. De preferencia hazle una copia de respaldo.
2. Extrae su único archivo, una transcripción del código fuente restaurado. (sw97.lst)
2.1. Si quieres asegurarte de que todo esté en orden, fíjate de que el CRC del archivo sea 838018A5
3. Ejecuta el parche con el programa que prefieras.
4. Mueve al archivo parchado de vuelta al paquete para reemplazar al original (quizás necesites tener el paquete abierto).
4b. Alternativamente, comprime el archivo parchado en un nuevo paquete, quita el original y renombra el nuevo.
5. Asegúrate de que el archivo parchado y/o el nuevo paquete tengan los mismos nombres que los originales.

Recomendaría que el paquete final tenga la extensión .7z para que pese menos,
pero el juego de por sí es bastante pequeño así que no importa tanto (28,1 KB vs. 18,5 KB).

CÓMO JUGAR EN MAME:

El emulador normalmente rechaza cualquier ROM modificada si intentas abrirlas desde el menú principal. Esto es a propósito.
Pero ya que fue originalmente desarrollado para usarse desde el intérprete de comandos, es posible cargar ROMs
directamente desde ahí y, aunque el emulador igual te advertirá, podrás iniciar el juego sin problemas.

Puedes simular este proceso simplemente creando un archivo de acceso directo con un poco de configuración extra.

1. Crea un acceso directo para el emulador.
2. Abre la ventana de Propiedades del acceso directo.
	En la sección "Destino", verás la ruta donde se encuentra el emulador.
3. Agrega lo siguiente al destino (NO borres lo que ya está ahí):
	 -rp C:\arpeta\donde\esté\la\ROM\parchada galgame
Toma en cuenta que si tus rutas contienen espacios deben ir entre comillas.
No te preocupes por que estos parámetros cambien la configuración usual de tu emulador, solo se activarán desde el acceso directo.
4. Aplica los cambios. Ya puedes salir de la ventana de Propiedades.

Ahora puedes darle al acceso directo el nombre que quieras y colocarlo en cualquier parte de tu PC.
¡Disfruta el juego!
