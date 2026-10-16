---
title: Política de privacidad de Friends Fighters
---

# Política de privacidad de Friends Fighters

Última actualización: 2026-10-16

Otros idiomas: [English](https://fberbert.github.io/friends-fighters-legal/privacy-en.html) | [Português (Brasil)](https://fberbert.github.io/friends-fighters-legal/privacy-pt-BR.html)

Friends Fighters ("el juego") es un juego para Android de Fábio Berbert de Paula ("nosotros"). Esta política explica qué hace el juego con las fotos y la demás información que pones en él, y qué guarda nuestro servidor cuando inicias sesión con una cuenta de Google. En resumen: tus fotos, recortes de cabeza, máscaras y grabaciones de voz se quedan en tu dispositivo y nunca se suben a nuestro servidor; solo salen de tu dispositivo cuando decides compartir un archivo de luchador o un video del combate. Nuestro servidor guarda solo lo necesario para contar tus creaciones gratuitas y desbloquear el juego completo: el identificador de tu cuenta de Google, los registros de tus creaciones y los registros de tus compras. El juego no tiene anuncios ni analíticas.

## 1. Lo que el juego envía por internet

- El juego se conecta solo a su propio servidor, `api.friendsfighters.automatizando.dev`, y a Google para iniciar sesión y para las compras de Google Play. Todas las conexiones están cifradas (HTTPS).
- Los luchadores incluidos, todos los modos de juego y los combates funcionan sin conexión y sin cuenta.
- El juego no tiene publicidad, analíticas, servicio de reporte de fallos ni copia de tus luchadores en la nube.
- El juego nunca envía fotos, recortes de cabeza, máscaras, grabaciones de voz ni nombres de luchadores a nuestro servidor ni a Google. Solo salen de tu dispositivo cuando tú los compartes (sección 7).
- Abrir esta política desde Ajustes abre tu navegador.

## 2. Fotos y caras

- Para crear un luchador, eliges una foto con el selector de fotos de Android o tomas una con tu app de cámara. El juego no pide permiso de almacenamiento ni de cámara: Android le entrega solo la foto que elegiste.
- El juego copia esa foto, reducida a 2048 píxeles como máximo, a su almacenamiento privado como imagen PNG sin metadatos (por ejemplo, datos de ubicación GPS).
- La eliminación del fondo, que encuentra la cabeza en la foto, se hace por completo en tu dispositivo con un modelo de Google MediaPipe incluido en el juego. El juego no identifica a las personas y no crea datos de reconocimiento facial.
- Para cada luchador, el juego guarda en tu dispositivo la copia de la foto, el recorte de la cabeza, sus máscaras automática y retocada, tus ajustes de encuadre y edición, una pequeña imagen de vista previa y las grabaciones de voz, si las hay (sección 3).
- Cuando confirmas un luchador, el juego envía a nuestro servidor un código SHA-256 de la imagen de la cara confirmada (sección 5). El código se calcula en tu dispositivo; no es posible reconstruir la imagen a partir de él, y los códigos nunca se comparan entre cuentas.
- Usa solo fotos de personas que aceptaron convertirse en luchadores y nunca uses el juego para burlarte de nadie. El juego te pide esta confirmación antes de tu primera importación de foto.

## 3. Grabaciones de voz

- Si grabas una voz para un luchador, el juego pide el permiso de micrófono en ese momento. Puedes rechazarlo; todo lo demás sigue funcionando.
- Un luchador puede tener hasta seis grabaciones (por ejemplo, para un nocaut o una victoria). Cada una dura como máximo 2 segundos y se guarda en la carpeta privada del luchador en tu dispositivo.
- Las grabaciones nunca se envían a nuestro servidor. Solo salen de tu dispositivo dentro de un archivo de luchador o de un video del combate que decidas compartir (sección 7).
- Puedes revocar el permiso de micrófono en cualquier momento en los ajustes de Android.

## 4. Información guardada en tu dispositivo

- Nombres y apariencia de los luchadores; tus ajustes (idioma, volumen de efectos y de la música, dificultad, vibración, controles y reducir movimiento); tu respuesta a la pregunta de consentimiento de las fotos; la configuración de tu último combate; estadísticas de combates, incluidos los enfrentamientos directos entre luchadores; tu progreso en la Escalada; y los logros.
- Cuando inicias sesión: el ID de tu cuenta en el juego, una clave de sesión y el registro firmado de tus creaciones gratuitas y del desbloqueo, además de los registros de tus creaciones con los códigos de las caras y los luchadores que esperan confirmación.
- Para identificar la cuenta de Google conectada en Ajustes, el juego también guarda el nombre y el correo que proporciona Google y una pequeña foto de perfil opcional, descargada de Google por HTTPS. Estos datos se quedan en el dispositivo en una caché local separada y no se agregan a las solicitudes a nuestro servidor. Cerrar sesión, cambiar de cuenta o eliminar la cuenta desde el juego borra esta caché. Sin foto se muestran las iniciales; una sesión existente puede actualizar los datos de la cuenta sin gastar una creación gratuita. El ID completo de la cuenta del juego sigue disponible en Ajustes en Información para soporte.
- Todo se queda en el almacenamiento privado del juego, que otras apps no pueden leer. Estos datos quedan excluidos de las copias de seguridad en la nube de Android y de las transferencias entre dispositivos.

## 5. Tu cuenta en el juego

- Solo necesitas una cuenta para crear tus propios luchadores y para comprar o restaurar el juego completo. El juego te pide que continúes con Google la primera vez que confirmas un luchador, y también puedes iniciar sesión desde Ajustes. Puedes negarte y seguir jugando con los luchadores incluidos.
- La confirmación de inicio de sesión de Google, que el juego pasa a nuestro servidor, también contiene tu nombre, tu dirección de correo electrónico y tu foto de perfil. El servidor solo verifica la confirmación y guarda el identificador de la cuenta de Google; nunca guarda tu nombre, tu correo ni tu foto.
- Para tu cuenta, nuestro servidor guarda: el identificador de la cuenta de Google; un ID aleatorio de la cuenta, que se muestra en Ajustes para el soporte; la fecha en que se creó la cuenta; tus sesiones, como códigos SHA-256 de las claves de sesión; los registros de tus creaciones (fecha, tipo de creación: luchador nuevo, duplicado o cambio de cara, y el código SHA-256 de la imagen de la cara confirmada); la cantidad de creaciones gratuitas otorgadas y usadas, incluidas las creaciones extra que otorga el soporte; el estado del desbloqueo y las fechas de su registro firmado; y los registros de tus compras (sección 6).
- Tu dirección IP llega al servidor solo para limitar la cantidad de solicitudes, en memoria. El servidor no la guarda ni la registra.
- Usamos estos datos solo para gestionar las creaciones gratuitas, el bloqueo de la cara y el desbloqueo, para restaurar tu compra, para evitar abusos de las creaciones gratuitas y para responder a las solicitudes de soporte. No vendemos estos datos, no los usamos para publicidad y no los compartimos con nadie más que los proveedores de servicios de la sección 8.

## 6. Compras y Google Play

- El juego es gratis para descargar. El desbloqueo completo es una compra única y opcional en Google Play. Google procesa el pago según la Política de Privacidad de Google (https://policies.google.com/privacy); nunca recibimos los datos de tu pago.
- Al comprar, el juego le da a Google Play el ID aleatorio de tu cuenta en el juego, para que la compra quede vinculada a ella. El juego no le da a Google Play tus luchadores ni tus fotos.
- Nuestro servidor recibe de Google Play el registro de la compra del desbloqueo (token de la compra, producto, número de pedido, estado (comprada, pendiente, cancelada o reembolsada), tipo de compra y fechas) y lo vincula a tu cuenta en el juego, para que el desbloqueo funcione en tus dispositivos y vuelva con Restaurar compras, en la pantalla Desbloquea el juego completo.
- Android y Google Play pueden recopilar estadísticas de fallos y diagnóstico según la configuración de tu dispositivo y las políticas de Google. El juego en sí no envía nada de eso.

## 7. Compartir siempre es tu decisión

- Tarjetas para compartir: el juego crea una imagen del resultado de un combate solo cuando tocas Compartir.
- Archivos de luchador: el juego exporta un luchador con todos sus datos, incluidas las fotos y las grabaciones de voz, solo cuando tocas Exportar luchador. Importa solo un archivo que eliges en Importar luchador o que abres con el juego.
- Videos del combate: el juego crea un video de un combate, con las caras y los sonidos de los luchadores, solo cuando tocas Video del combate y confirmas.
- Stickers: el juego ofrece el paquete de stickers de un luchador a WhatsApp solo cuando tocas Stickers para WhatsApp y luego Agregar a WhatsApp; después, WhatsApp lee el paquete desde el juego.
- La app que elijas recibe la imagen, el archivo o el video mediante el menú para compartir de Android y los trata según su propia política de privacidad. Nosotros no recibimos una copia.

## 8. Proveedores de servicios

- Nuestro servidor funciona en Amazon Web Services (EC2), en la región de Oregón, Estados Unidos. Por eso, los datos de las secciones 5 y 6 se guardan y se tratan fuera de Brasil, en los Estados Unidos.
- Google proporciona el inicio de sesión, los pagos de Google Play, la verificación de las compras y los avisos de compra. En tu dispositivo, el inicio de sesión usa los servicios de Google Play (el Administrador de credenciales de Android) y las compras usan Google Play Billing; estos componentes se comunican directamente con Google, según las políticas de Google.
- Estos proveedores tratan los datos solo para prestarnos su servicio.

## 9. Cuánto tiempo guardamos los datos

- Tu cuenta, los registros de tus creaciones y el estado del desbloqueo: hasta que elimines la cuenta.
- Sesiones: 30 días después de cada inicio de sesión.
- Después de que elimines tu cuenta, guardamos durante 365 días, solo para evitar abusos de las creaciones gratuitas, la cantidad de creaciones gratuitas que usaste, con el ID aleatorio de la cuenta y las fechas de creación y eliminación de la cuenta, bajo un código seudónimo calculado a partir del identificador de tu cuenta de Google con una clave secreta. Si vuelves a iniciar sesión con la misma cuenta de Google en ese plazo, la nueva cuenta empieza con esa cantidad y este registro se borra.
- Registros de compra: 365 días después de que se elimine la cuenta, sin vínculo con tu cuenta en el juego, para reembolsos y prevención de fraudes.
- Los registros de acciones del soporte (por ejemplo, una creación gratuita extra) guardan el ID aleatorio de la cuenta, la acción, quién la hizo y la fecha durante 365 días después de la acción; sus notas se borran cuando se elimina la cuenta.
- Las copias de seguridad de la base de datos se borran en un plazo de 14 días.

## 10. Cómo borrar tus datos

- Elimina un luchador en la galería de luchadores para quitar del dispositivo todos sus archivos.
- Desinstalar el juego, o borrar su almacenamiento en los ajustes de Android, elimina todos los datos del juego en el dispositivo. Como las copias de seguridad están desactivadas, un juego reinstalado empieza vacío.
- Elimina tu cuenta del juego desde el juego (Ajustes, Cuenta, Eliminar cuenta) o en la página https://api.friendsfighters.automatizando.dev/delete-account, donde inicias sesión con Google. Esa página carga el script de inicio de sesión de Google, así que Google recibe tu dirección IP y datos de tu navegador según la Política de Privacidad de Google; nuestro servidor no los registra. Si no puedes iniciar sesión, escríbenos con el ID de la cuenta que se muestra en Ajustes. La eliminación borra el identificador de la cuenta de Google, las sesiones, los registros de creaciones con sus códigos de cara y el registro del desbloqueo; la sección 9 indica lo que se conserva. Tus luchadores se quedan en tu dispositivo, y tu compra sigue en Google Play: vuelve a iniciar sesión y usa Restaurar compras.

## 11. Niños

El juego está pensado para jugadores de 13 años o más. No está dirigido a niños menores de 13 años.

## 12. Tus derechos

Según la Ley General de Protección de Datos de Brasil (LGPD) y leyes similares, puedes pedirnos que confirmemos si tratamos tus datos, que te demos acceso a ellos, que los corrijamos o eliminemos, que te los entreguemos en un formato portable y que te informemos sobre los proveedores que los tratan. Envía tu solicitud con el ID de la cuenta que se muestra en Ajustes; respondemos en un plazo de 15 días. También puedes eliminar tu cuenta tú mismo, como se describe en la sección 10.

## 13. Cambios en esta política

Si el juego cambia la forma en que trata los datos, actualizaremos esta política, cambiaremos la fecha de arriba y describiremos el cambio en las notas de la versión en Google Play.

## 14. Contacto

Fábio Berbert de Paula
Correo electrónico: contato@automatizando.dev
