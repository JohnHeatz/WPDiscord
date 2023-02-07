# WPDiscord

Comparte publicaciones de WP en Discord

Para utilizarlo solo lo primero que debemos tener es acceso directo al servidor donde hostean su página web, ya que ahí debemos entrar por SSH or SFTP y navegar a /wp-content/plugins y ahí crear una nueva carpeta con el nombre que deseen. Puede ser comparte-discord. Dentro de esta carpeta tan solo deben pegar el archivo compartir-discord.php. 

Luego de esto, tan solo deben irse a su portal de administradores de WP y a plugins para activarlo (saldrá con el nombre que le pusieron a la carpeta) para que les aparezca la opción de la integración en el menú de "Ajustes" - "Generales" al hacer scroll hasta abajo de la página, para que agreguen el URL del Webhook que debemos crear en Discord.

¿Cómo crear un webhook en Discord?

Tan solo se van a las opciones del canal en el que quieren compartir las publicaciones, ahí van a "integraciones" y ver "webhooks". Ahí pueden crear uno, le dan el nombre que deseen y le ponen el avatar que quieran. Copian el URL y es el que pegarán en WP.
