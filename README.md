# Avisos de AgendaBus

Este repositorio existe solo para publicar `aviso.json`, que la app lee al abrirse para
saber si hay una versión nueva o si hay algún comunicado.

No contiene código de la app.

## Cómo se edita

Se abre `aviso.json` aquí mismo en GitHub, se le da al lápiz, se cambia lo que sea y se
guarda. En unos minutos lo ven todos.

| Campo        | Para qué |
|--------------|----------|
| `version`    | La última versión publicada, "1.74". Si es mayor que la del móvil, avisa. |
| `mensaje`    | Qué trae, en dos o tres líneas. |
| `recado`     | Un comunicado: "mañana empieza la temporada de invierno". |
| `recadoId`   | El nombre de ese comunicado. Cámbialo para mandar el siguiente. |
| `urlAndroid` | Enlace a Google Play. |
| `urlIos`     | Enlace a la App Store. |

Cada aviso se enseña una sola vez a cada conductor. Si el archivo no está o no se
entiende, la app sigue igual y no enseña nada.
