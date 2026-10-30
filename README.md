# ITSAI Click2SMS — variante adicional
Abrir index.html, o ../click2sms.html desde la carpeta principal.

Flujo:
1. index.html: pantalla del tema con ilustración espacial y consejos.
2. subscribe.html: pantalla de suscripción por SMS.
3. El visitante pulsa Skicka SMS / Send SMS para abrir el compositor nativo: TSAI al 72300.
El sitio no envía mensajes automáticamente y no simula una suscripción confirmada.

Idiomas: sueco por defecto; ?lang=en para inglés. El selector de la primera pantalla traduce la interfaz al idioma elegido.
El precio visible y las condiciones compartidas mantienen la última instrucción: 200 SEK al mes, aunque las imágenes de referencia muestran 100 SEK.
La palabra de alta es TSAI; la baja mostrada en este flujo es STOP ITSAI+, según el diseño Click2SMS.
Se reutilizan los términos, privacidad, logo, robot y estilos comunes de la carpeta principal.
El fondo espacial se muestra con CSS a partir de Home-1.jpg, sin modificar el original ni convertir los textos del diseño en una imagen de página completa.
En desktop el CTA abre instrucciones para usar el móvil y permite copiar TSAI. La copia muestra éxito solo si el navegador confirma el acceso al portapapeles.
En móviles se usa un URI sms: con cuerpo TSAI; iOS y otros dispositivos usan separadores distintos. La compatibilidad con cada app de mensajes debe verificarse en un dispositivo real.

El tema se conserva solo en sessionStorage de la pestaña cuando el navegador lo permite; no se incluye en URL ni se envía a servidores.
Esta versión no genera contenido con IA ni conecta la suscripción a un backend.

Los documentos legales aceptan from=writer y from=c2s para regresar al paso correcto.
La landing MSISDN/PIN principal conserva sus pantallas y el modo de prueba.
Los archivos se han preparado localmente; no se ha creado ni actualizado un repositorio remoto.

## Verificación
82 comprobaciones de lógica, idiomas, navegación legal y destino SMS superadas entre ambos servicios con un DOM simulado. Enlaces, recursos e identificadores verificados. Sin prueba visual en navegador ni prueba en dispositivo real disponible.

## Tarjeta SMS actualizada
Estilos aislados en sms-card.css, cargados al final: fondo sólido, colores, espaciados y botón según Frame 1.png. Se mantiene 200 SEK al mes.
