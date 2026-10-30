# ITSAI Click2SMS
Esta carpeta es autónoma: se puede copiar o publicar entera sin la carpeta padre.

## Abrir
- index.html: landing de suscripción SMS (TSAI al 72300).
- home.html: pantalla previa para escribir el tema; su flecha abre index.html.
- subscribe.html: copia compatible de la landing SMS para conservar enlaces anteriores.
- index.html?lang=en y home.html?lang=en: versiones inglesas.
- terms.html y privacy.html: páginas legales en sueco, con vuelta al paso de origen.

## Archivos
CSS, scripts, logo, imagen del robot y páginas legales están dentro de esta misma carpeta.
No hace falta copiar recursos desde la carpeta padre.
Home-1.jpg contiene el arte espacial utilizado por home.html.
Se conservan los diseños originales como referencias; los textos de la interfaz están en HTML.

## Comportamiento
Precio: 200 SEK al mes.
Tarjeta de ItsAI: gris #595959, verde #A6FF7E, texto del botón negro.
En móvil, Skicka SMS / Send SMS abre el compositor con TSAI al 72300. El visitante revisa y envía el mensaje.
En desktop aparecen instrucciones para continuar desde el móvil y un control para copiar TSAI.
No se envían SMS automáticamente, no se genera contenido real con IA y no se simula una suscripción confirmada.
El tema se conserva solo en sessionStorage de la pestaña si el navegador lo permite.
Se conserva el selector SE/EN y el parpadeo suave del botón.

## Comprobaciones
82 comprobaciones de lógica, idiomas y navegación superadas entre ambos servicios con un DOM simulado.
Todos los recursos locales resuelven dentro de cada carpeta Click2SMS; no hay dependencias ../.
No hay una prueba visual de navegador ni de dispositivo real disponible.
