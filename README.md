# Flor amarilla

Una carta animada de una sola página: los girasoles crecen, el cielo amanece
y el mensaje se va revelando escena a escena.

Todo vive en `index.html` — HTML, CSS y JavaScript en un solo fichero, sin
dependencias ni compilación. Para verlo basta con abrirlo en el navegador.

## Imágenes

El HTML espera estos ficheros junto a él:

| fichero         | dónde sale                        |
|-----------------|-----------------------------------|
| `flor.jpg`      | la flor hecha a mano, en el epílogo |
| `felicidad.gif` | escena "volver a hablar"          |
| `euforia.gif`   | escena de agradecimiento          |
| `fin.gif`       | escena de despedida               |

Si alguno falta, su marco se queda vacío con un aviso en su sitio; el resto
de la animación sigue funcionando.

## Música

`musica.mp3` suena en bucle infinito. Arranca con el primer toque de la
persona (el botón *Comenzar*), porque ningún navegador deja sonar audio antes
de un gesto, y entra con un fundido de un par de segundos.

Arriba a la izquierda aparece una chapa con cuatro barras que bailan mientras
suena y el nombre de la canción al lado: al pulsarla la música se apaga con
fundido y las barras se quedan planas. A la derecha lleva una barra de
volumen; dejarla en cero es lo mismo que callarla, y subirla con la música
parada la vuelve a poner.

Si cambias de canción, cambia también ese nombre en el HTML (`#btnSonido`).
Si `musica.mp3` no está, la página funciona igual, en silencio.
