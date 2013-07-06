

## Lista de incidencias

Mientras este repositorio no contenga documentos propios, la única
función va a ser poderlo usar como una lista de distribución de
mensajes sobre el tema de ediciones críticas y ConTeXt. Evidentemente,
no sólo tratará de ediciones críticas, sino de temas de composición
tipográfica de humanidades.

### ¿Por qué la lista?

La finalidad fundamental es tener un espacio de discusión sobre temas
especializados, sin tener que hacerlo en una lista con una finalidad
más general (o sencillamente distinta) como la lista ES-TEX. Sirve
también para la consulta pública posterior, para que alguien usando
un buscador, encuentre algo sobre el tema (además de tener un lugar en
el que poder preguntar).

Uno de los problemas con ConTeXt y las humanidades es que no existe
mucha documentación sobre el tema. Ni ningún lugar específico donde
preguntar en español.

Se me ocurre que con el sistema de incidencias de Github, no siendo ni
una lista de correo ni un foro, se puede conseguir que funcione como
una lista de distribución.

#### Aclaración importante

Por si alguien lo duda, no tengo ningún tipo de relación comercial,
beneficio económico o interés financiero en Github. Soy un simple
usuario gratuito que usa y disfruta de la posibilidad de usar sus
repositorios (sí, sin mucho éxito).

No tengo especial interés en que nadie se suscriba a Github por otros
motivos distintos de que pueda beneficiarse de sus servicios, si le
fuesen útiles.

De la inscripción como usuario de Github, de la inscripción en la
lista (la monitorización de este proyecto) o de la recepción y envío
de los mensajes, así como de todas las acciones personales, es
responsable cada uno (o cada una).

### Modo de inscripción

#### Abrir una cuenta o iniciar sesión

Para usar este sistema hay que
[inscribirse](https://github.com/signup) o [iniciar
sesión](https://github.com/login?return_to=%2Fousia%2Fcontext-critica%2Fissues)
como usuario. Entiendo que no tiene más dificultad que la
particularidad de que está en inglés.

#### Configuración de la recepción de mensajes

Una vez que hemos iniciado sesión, debemos configurar el recibir las
notificaciones, al menos por correo electrónico. Éste es el [enlace
directo](https://github.com/settings/notifications), que nos sitúa
donde la siguiente imagen, en la que hay que marcar dos campos que
muestra la imagen.

![configurar correo](https://raw.github.com/ousia/context-critica/master/img/configura-recibir-correo.png)

De este modo recibiremos las notificaciones en todas las incidencias
de Github en las que se nos nombra (se nos nombra cuando en un mensaje
escriben `@usuario` [con el nombre de usuario de cada cual]).

#### Inscripción en la lista

La opción predeterminada de Github es mandarnos un mensaje cada vez
que nos nombran (como explico en el último párrafo del apartado
anterior).

Para que el sistema de incidencias de este proyecto funcione de una
manera análoga a una lista de correo, para que sea una lista de
distribución, es necesario que «vigilemos» u «observemos» [este
proyecto](https://github.com/ousia/context-critica). Lo muestra la
imagen siguiente.

![configurar
correo](https://raw.github.com/ousia/context-critica/master/img/inscribe-lista.png)

En este caso, seleccionamos que nos informe de todas las
notificaciones. De otro modo, como he advertido, sólo nos llegarían
aquellos mensajes en que alguien nos mencione.

Para cancelar la suscripción lo que hay que hacer es seleccionar
cualquiera de las otras dos opciones que nos muestra la imagen (en
[este proyecto](https://github.com/ousia/context-critica)). Si no se
quiere recibir mensaje alguno de la lista, es necesario seleccionar
_Ignoring_.

<!-- ### Compromiso de participación

En un campo de gran cultivo personal como es el caso de gente que se
dedica las humanidades, supongo que estará de más hacer la siguiente
reflexión. Pero lo aviso para que no haya incomprensiones antes de
empezar.

La participación en esta lista supone un compromiso personal que se
resume en la siguiente palabra:

* Respeto. Es *condición indispensable* para permanecer en la lista.

Espero que esto se traduzca en una comunicación electrónica cordial,
aunque haya las disensiones que pueda haber.

En caso negativo, a la tercera falta de respeto -->

### Funcionamiento

Es importante advertir que todos los mensajes a la lista son públicos
(no pueden ser privados). Por tanto, no tiene sentido mandar
información privada a la lista.

Es necesario abrir una incidencia para poder iniciar un hilo. En
principio, la idea es que las incidencias relacionadas con la lista no
se cierren. Así se pueden retomar en cualquier momento. Aunque una
incidencia esté cerrada, pueden hacerse comentarios (y pedir que se
reabra).

Pueden cerrar una incidencia el administrador o la persona que abrió
la incidencia. Si la cierra el administrador, sólo la puede volver a
abrir él. Si la cierra quien la abrió, también la puede volver a abrir.

Se puede responder por correo electrónico a los mensajes recibidos a
través de correo, aunque no se puedan abrir incidencias así. Si no se
usa la página de Github, es importante observar dos condiciones:

* Si se cita el mensaje original, es importante borrar toda la
información del mensaje original que no citemos directamente.

    En la incidencia se verá el mensaje al que se contesta, porque
    en la página de la incidencia está arriba. Sólo debe dejarse lo
    que sea estrictamente necesario para contestar.

* El fragmento del mensaje original debe citarse primero para permitir
quien lea seguir la coherencia lógica de una respuesta.

Como regla general, creo que es buena idea responder con un mensaje vacío.

### Formato

Github usa una versión de `markdown` que es un código ligero. Si se
responde en la página de Github hay una chuleta con el código.

Para quien no sepa, hago un breve resumen, a su vez, de la chuleta.

Pasajes dentro del párrafo:

* `_Cursiva_` da _cursiva_.

* `**Negrita**` da **negrita**.

* `&#96;Código&#96;` da `código` y se marca con el acento agudo (en el
teclado español hay que pulsar dos veces la tecla para que salga el
carácter).

Si queremos ponerlos, los títulos van del siguiente modo: por cada
nivel es un carácter almohadilla (#), al comienzo de la línea y
separada del título por un espacio.

* `#` es para título de primer nivel.
* `##` es para título de segundo nivel.
* `###` es para título de tercer nivel.
* `####` es para título de cuarto nivel.
* `#####` es para título de quinto nivel.

Cada párrafo se forma no por las líneas en blanco (como sucede en
`markdown` estándar) sino por cada línea nueva.

Los bloques de código se marcan entre dos líneas de al menos tres
acentos agudos (`&#96;&#96;&#96;`).

```
```
```
```
\starttext
Mi primer documento \ConTeXt
\stoptext
```
```
```
```

Tiene como resultado:

```tex
\starttext
Mi primer documento \ConTeXt
\stoptext
```

#### ¿Cómo se incluyen anexos?

Github no permite anexos a los mensajes

https://gist.github.com/

## Contacto

Si tienes alguna pregunta o comentario sobre este repositorio o la lista, [abre una incidencia](https://github.com/ousia/context-critica/issues/new).

