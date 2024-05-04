
<h1>CAPÍTULO III: REQUIREMENTS SPECIFICATION</h1>
<h2>3.1 To-Be Scenario Mapping</h2>
<img src="/imagenes/tobe.png"/>
<h2>3.2 User Stories</h2>
<table>
  <thead>
    <tr>
      <th>Epics</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
     <td>EP01</td>
      <td>Como nuevo usuario de la plataforma, quiero poder crear una cuenta con mi información, acceder y gestionar mi perfil, y tener una experiencia personalizada e intuitiva al ingresar a la plataforma web.</td> 
        </tr>
      <tr>
     <td>EP02</td>
      <td>Como organizador de eventos, quiero poder crear eventos, así como gestionar el proceso de ventas y finanzas de manera eficiente a través de la plataforma.
</td> 
        </tr>
      <tr>
     <td>EP03</td>
      <td>Como comprador de entradas, quiero una plataforma optimizada para acceder a información detallada de los eventos, al proceso de compra, en caso suceda, al reembolso o transferencia de mis entradas y a una comunicación intuitiva.</td> 
        </tr>
      <tr>
     <td>EP04</td>
      <td>Como comprador de entradas frecuente, quiero acceso a beneficios, descuentos y recompensas por mi lealtad en la plataforma al adquirir entradas.</td> 
        </tr>
      <tr>
     <td>EP05</td>
      <td>Como usuario de la plataforma, quiero poder crear un perfil de revendedor que respalde mi integridad para acceder a beneficios unicos.</td> 
        </tr>
       <tr>
     <td>EP06</td>
      <td>Como comprador de entradas, quiero tener acceso a una subscripción premium para acceder a beneficios únicos y personalizables, y contenido exclusivo de la plataforma.</td> 
        </tr>
</tbody>
</table>

<h4>Historias de Usuarios</h4>

<table>
  <thead>
    <tr>
      <th>Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US01</td>
      <td>Autenticación de usuario</td>
      <td>Como usuario Quiero registrarme e iniciar sesión Para acceder a la aplicación MyEvent</td>
      <td>-Dado que el usuario desea crear una cuenta nueva, cuando proporciona su información personal válida, entonces 
      la cuenta se registra con éxito.<br>
      -Dado que el usuario desea iniciar sesión, cuando ingresa su nombre de usuario y contraseña válidos, entonces 
      accede a la aplicación MyEvent.<br>
      -Dado que el usuario intenta iniciar sesión con credenciales incorrectas, entonces recibe un mensaje de error 
      indicando que el inicio de sesión ha fallado.
 </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US02</td>
      <td>Creación de eventos</td>
      <td>Como organizador de eventos Quiero poder crear y publicar eventos en la plataforma Para promover mi evento y vender entradas</td>
      <td>-Dado que el organizador desea crear un evento, cuando completa un formulario con los detalles del evento, 
          entonces el evento se registra en la plataforma.<br>
         -Dado que el organizador ha completado el formulario de creación de eventos, cuando envía el evento para 
         revisión y aprobación, entonces el evento es revisado por el administrador.<br>
         -Dado que el evento ha sido aprobado por el administrador, cuando se muestra en la plataforma, entonces los 
          usuarios pueden ver y acceder al evento para comprar entradas.<br>
          -Dado que un organizador intenta crear un evento pero la plataforma no permite completar el formulario con detalles del evento, el organizador no puede publicar el evento y promoverlo en la plataforma.
</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Exploración de eventos</td>
      <td>Como usuario interesado en eventos Quiero poder buscar y filtrar eventos disponibles Para encontrar eventos que me interesen</td>
      <td>-Dado que el usuario desea explorar eventos, cuando navega por una lista de eventos, entonces encuentra una 
         variedad de opciones disponibles.<br>
         -Dado que el usuario desea encontrar eventos específicos, cuando aplica filtros por categorías como género 
         musical, ubicación y fecha, entonces obtiene resultados relevantes.<br>
        -Dado que el usuario quiere obtener más detalles sobre un evento, cuando hace clic en el evento, entonces puede 
        ver información detallada y decidir si le interesa.<br>
          -Dado que un usuario intenta buscar eventos utilizando filtros por categorías como género musical, ubicación y fecha, pero los resultados no se muestran correctamente o no coinciden con los filtros aplicados, el usuario no puede encontrar eventos que le interesen.
</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US04</td>
      <td>Compra de entradas</td>
      <td>Como comprador de entradas Quiero poder seleccionar y comprar entradas Para asegurar mi participación en eventos</td>
      <td>-Dado que el comprador desea adquirir entradas, cuando selecciona las entradas deseadas y las agrega al carrito, entonces puede continuar con el proceso de pago.<br>
-Dado que el comprador quiere completar la compra, cuando elige un método de pago y completa la transacción, entonces recibe confirmación por correo electrónico.<br>
-Dado que el comprador ha realizado una compra, cuando necesita ayuda o tiene preguntas, entonces puede contactar al servicio de atención al cliente para recibir asistencia.<br>
        -Dado que un comprador intenta seleccionar y comprar entradas, pero al agregar las entradas al carrito se produce un error y no se puede completar el proceso de compra, el comprador no puede asegurar su participación en eventos.
</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US05</td>
      <td>Opción Premium para Revendedores</td>
      <td>Como revendedor Quiero tener una opción premium Para obtener ventajas sobre otros compradores</td>
      <td>-Dado que el revendedor desea acceder a una opción premium, cuando compra una membresía premium, entonces obtiene beneficios adicionales como acceso anticipado y límites de compra más altos.<br>
-Dado que el revendedor tiene la membresía premium, cuando realiza compras, entonces disfruta de ventajas exclusivas como descuentos especiales y prioridad en el servicio al cliente.<br>
-Dado que el revendedor quiere renovar su membresía premium, cuando vence la membresía actual, entonces puede volver a comprarla fácilmente desde su cuenta.<br>
          -Dado que un revendedor intenta comprar una membresía premium con acceso anticipado y límites de compra más altos, pero la plataforma no procesa la compra correctamente o no otorga los beneficios adicionales, el revendedor no puede obtener las ventajas prometidas.
</td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US06</td>
      <td>Transferencia de Entradas</td>
      <td>Como usuario que ya ha comprado entradas Quiero poder transferirlas a otros usuarios Para permitir que otros disfruten del evento</td>
      <td>-Dado que el usuario desea transferir entradas, cuando selecciona las entradas que desea transferir, entonces proporciona la información del destinatario.<br>
-Dado que el usuario ha completado la transferencia, cuando el destinatario recibe las entradas transferidas, entonces ambos usuarios reciben confirmación de la transferencia exitosa.<br>
-Dado que el usuario ha transferido entradas, cuando necesita ayuda o tiene preguntas, entonces puede contactar al servicio de atención al cliente para recibir asistencia.<br>
          -Dado que un usuario que ha comprado entradas intenta transferirlas a otros usuarios, pero el sistema no permite completar la transferencia o muestra un mensaje de error, el usuario no puede permitir que otros disfruten del evento.
</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US07</td>
      <td>Membresía de Descuentos Periódicos</td>
      <td>Como usuario fiel a la plataforma Quiero recibir descuentos especiales periódicamente Para incentivar mi participación continua</td>
      <td>-Dado que el usuario desea obtener descuentos periódicos, cuando adquiere una membresía de descuentos periódicos, entonces recibe notificaciones sobre descuentos disponibles.<br>
-Dado que el usuario tiene la membresía activa, cuando realiza compras, entonces puede aplicar los descuentos durante el proceso de compra.<br>
-Dado que el usuario quiere renovar la membresía, cuando vence la membresía actual, entonces puede volver a comprarla fácilmente desde su cuenta.<br>
          -Dado que un usuario con membresía de descuentos periódicos intenta aplicar un descuento durante el proceso de compra, pero el sistema no aplica el descuento correctamente o no lo reconoce, el usuario no puede disfrutar de los beneficios de su membresía.
</td>
      <td>EP04</td>
    </tr>
        <tr>
      <td>US08</td>
      <td>Membresía de Concursos y Sorteos Exclusivos</td>
      <td>Como miembro de la plataforma, quiero participar en concursos y sorteos exclusivos para ganar entradas gratuitas y experiencias VIP, para disfrutar de beneficios adicionales y experiencias únicas.</td>
      <td>-Dado que el usuario desea participar en concursos y sorteos, cuando accede a concursos y sorteos exclusivos desde su cuenta, entonces puede ver los premios disponibles.<br>
-Dado que el usuario participa en un concurso o sorteo, cuando sigue las instrucciones proporcionadas, entonces recibe notificaciones sobre los resultados.<br>
-Dado que el usuario gana un premio, cuando recibe la confirmación, entonces puede disfrutar de la experiencia VIP o la entrada gratuita obtenida.<br>
          -Dado que un usuario con membresía de concursos y sorteos exclusivos intenta participar en un concurso o sorteo, pero la plataforma no le permite acceder o muestra un error al intentar participar, el usuario no puede disfrutar de las ventajas exclusivas de su membresía.
</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US09</td>
      <td>Membresía de Contenido Exclusivo</td>
      <td>Como suscriptor premium, quiero tener acceso a contenido exclusivo relacionado con eventos, como transmisiones en vivo y entrevistas detrás de escena, para disfrutar de una experiencia más completa y enriquecedora.</td>
      <td>-Dado que el usuario premium desea acceder a contenido exclusivo, cuando inicia sesión en su cuenta premium, entonces puede acceder al contenido especial.<br>

-Dado que el usuario premium ve una transmisión en vivo, cuando participa en comentarios y comparte el contenido, entonces disfruta de una experiencia enriquecedora y participativa.<br>

-Dado que el usuario premium quiere ver entrevistas detrás de escena, cuando accede al contenido exclusivo, entonces obtiene información adicional sobre eventos y artistas.<br>
-Dado que un usuario con membresía de contenido exclusivo intenta acceder al contenido especial disponible solo para suscriptores premium, pero la plataforma no le permite ver el contenido o muestra un mensaje de error al intentar acceder, el usuario no puede disfrutar de la experiencia completa de su membresía.
</td>
      <td>EP06</td>
    </tr>
    <tr>
      <td>US10</td>
      <td>Membresía de Prioridad en Servicio al Cliente</td>
      <td>Como usuario premium, quiero recibir atención prioritaria en el servicio al cliente, con tiempos de respuesta más rápidos y asistencia personalizada, para sentirme valorado y apoyado como cliente leal.  </td>
      <td>-Dado que el usuario premium desea atención prioritaria, cuando contacta al servicio al cliente, entonces recibe tiempos de respuesta más rápidos y asistencia personalizada.<br>

-Dado que el usuario premium tiene consultas o problemas, cuando utiliza canales exclusivos como líneas telefónicas dedicadas, entonces recibe soporte de manera eficiente.<br>

-Dado que el usuario premium quiere sentirse valorado, cuando recibe seguimiento y atención continua, entonces se siente satisfecho con el servicio al cliente.<br>
-Dado que un usuario premium intenta comunicarse con el servicio al cliente a través de canales exclusivos, como líneas telefónicas o correos electrónicos dedicados, pero no recibe respuestas rápidas o el servicio no está disponible, el usuario no puede recibir la atención prioritaria prometida.
</td>
      <td>EP06</td>
<tr>
  <td>US11</td>
  <td>Membresía de Descuentos en Futuras Compras</td>
  <td>Como usuario habitual de la plataforma, quiero recibir descuentos para futuras compras de entradas Para incentivar mi lealtad y continuar utilizando el servicio</td>
  <td>-Dado que el usuario acumula compras, cuando alcanza un número determinado de entradas compradas, entonces recibe un cupón de descuento para su próxima compra.<br>

-Dado que el usuario tiene un cupón de descuento, cuando realiza la próxima compra, entonces aplica el cupón para obtener un descuento en el precio.<br>

-Dado que el usuario quiere seguir acumulando descuentos, cuando continúa comprando entradas, entonces sigue recibiendo beneficios por su lealtad.
</td>
  <td>EP04</td>
</tr>
<tr>
  <td>US12</td>
  <td>Entradas Gratis para Eventos Seleccionados</td>
  <td>Como usuario frecuente de la plataforma, quiero tener la oportunidad de obtener entradas gratuitas Para disfrutar de eventos sin costo adicional y fomentar mi fidelidad</td>
  <td>-Dado que el usuario acumula un cierto número de compras, cuando alcanza el umbral establecido, entonces recibe una entrada gratuita para un evento específico.<br>
-Dado que el usuario tiene una entrada gratuita, cuando selecciona el evento al que desea asistir, entonces puede canjear la entrada gratuita durante el proceso de compra.<br>
-Dado que el usuario quiere disfrutar de beneficios adicionales, cuando asiste al evento con una entrada gratuita, entonces fortalece su lealtad a la plataforma.<br>
      -Dado que un usuario frecuente intenta canjear una entrada gratuita para un evento específico de su elección, pero la plataforma no permite el canje o muestra un error al intentar seleccionar la entrada gratuita, el usuario no puede disfrutar del beneficio de su lealtad.
</td>
  <td>EP04</td>
</tr>
<tr>
  <td>US13</td>
  <td>Acceso a Preventas Exclusivas</td>
  <td>Como usuario frecuente de la plataforma, quiero tener acceso exclusivo a preventas de eventos populares Para asegurar mi participación en eventos de alto demanda</td>
  <td>-Dado que el usuario acumula acceso a preventas exclusivas, cuando se anuncian eventos populares, entonces puede comprar entradas antes de que estén disponibles para el público general.<br>
-Dado que el usuario tiene acceso a la preventa, cuando realiza la compra durante este período, entonces asegura su participación en eventos con alta demanda.<br>
-Dado que el usuario quiere ser parte de eventos exclusivos, cuando disfruta de la experiencia sin problemas de agotamiento de entradas, entonces aumenta su satisfacción y fidelidad.<br>
      -Dado que un usuario frecuente intenta comprar entradas antes de que estén disponibles para el público en general durante la preventa, pero la plataforma no le permite acceder a la preventa o muestra un mensaje de error al intentar comprar las entradas, el usuario no puede asegurar su participación en eventos populares.
</td>
  <td>EP04</td>
</tr>
<tr>
  <td>US14</td>
  <td>Puntos de Fidelidad o Programa de Recompensas</td>
  <td>Como usuario frecuente de la plataforma, quiero acumular puntos de fidelidad por cada compra de entradas Para canjearlos por descuentos, entradas gratuitas u otros beneficios</td>
  <td>-Dado que un usuario realiza compras de entradas, cuando acumula puntos de fidelidad por cada compra, entonces puede verificar su saldo de puntos desde su cuenta.<br>
-Dado que el usuario tiene suficientes puntos acumulados, cuando decide canjear los puntos por recompensas como descuentos o entradas gratuitas, entonces puede aplicar los puntos durante el proceso de compra.<br>
-Dado que el usuario quiere obtener beneficios adicionales, cuando utiliza sus puntos de fidelidad, entonces disfruta de ventajas exclusivas y se siente incentivado a seguir participando en la plataforma.<br>
      -Dado que un usuario frecuente intenta canjear puntos por descuentos, entradas gratis u otros beneficios, pero la plataforma no registra correctamente los puntos acumulados o muestra un saldo incorrecto, el usuario no puede aprovechar las recompensas de su lealtad.
</td>
  <td>EP04</td>
</tr>
<tr>
  <td>US15</td>
  <td>Niveles de Entrada con Descuento</td>
  <td>Como usuario frecuente de la plataforma, quiero acceder a precios especiales de entrada después de realizar cierto número de compras Para disfrutar de beneficios adicionales y promociones exclusivas</td>
  <td>-Dado que el usuario alcanza niveles de entrada con descuento, cuando realiza un número determinado de compras, entonces accede a precios especiales para ciertos niveles de entrada.<br>
-Dado que un usuario selecciona el nivel de entrada con descuento, cuando completa el proceso de compra, entonces obtiene el beneficio del descuento aplicado.<br>
-Dado que el usuario quiere aprovechar promociones exclusivas, cuando continúa comprando y alcanza nuevos niveles, entonces sigue obteniendo precios especiales y promociones exclusivas.<br>
      -Dado que un usuario frecuente intenta acceder a precios especiales para ciertos niveles de entrada después de realizar cierto número de compras, pero la plataforma no le ofrece los precios especiales o muestra un error al intentar seleccionar el nivel con descuento, el usuario no puede disfrutar de las promociones exclusivas.
</td>
  <td>EP04</td>
</tr>
<tr>
  <td>US16</td>
  <td>Notificaciones de Eventos y Ofertas</td>
  <td>Como usuario de la plataforma, quiero recibir notificaciones sobre eventos nuevos y ofertas especiales Para estar al tanto de las últimas novedades y oportunidades</td>
  <td>-Dado que el usuario desea recibir notificaciones, cuando configura sus preferencias de notificación desde la cuenta, entonces puede optar por recibir notificaciones por correo electrónico o mensajes push.<br>
-Dado que el usuario recibe una notificación sobre un evento nuevo, cuando hace clic en la notificación, entonces accede a detalles adicionales sobre el evento y puede tomar decisiones informadas.<br>
-Dado que el usuario quiere estar al tanto de ofertas especiales, cuando recibe notificaciones sobre descuentos y promociones, entonces puede aprovechar oportunidades exclusivas y mejorar su experiencia en la plataforma.<br>
      -Dado que un usuario desea recibir notificaciones sobre eventos nuevos y ofertas especiales, pero la plataforma no envía las notificaciones o las envía tarde, el usuario no puede estar al tanto de las últimas novedades y oportunidades.
</td>
  <td>EP03</td>
</tr>
<tr>
  <td>US17</td>
  <td>Integración con Redes Sociales</td>
  <td>Como usuario de la plataforma, quiero poder compartir eventos y experiencias en mis redes sociales Para ampliar el alcance de la plataforma y compartir intereses con amigos</td>
  <td>-Dado que el usuario desea compartir eventos, cuando conecta su cuenta de la plataforma con redes sociales como Facebook, Twitter o Instagram, entonces puede compartir detalles de eventos y experiencias.<br>
-Dado que el usuario comparte un evento en redes sociales, cuando sus amigos y seguidores interactúan con la publicación, entonces pueden ver y participar en eventos compartidos.<br>
-Dado que el usuario quiere promover eventos y experiencias, cuando utiliza la integración con redes sociales, entonces amplía el alcance de la plataforma y fortalece la comunidad de usuarios interesados en eventos similares.<br>
      -Dado que un usuario desea compartir eventos y experiencias en redes sociales, pero la plataforma no permite la integración con redes sociales o muestra un error al intentar compartir contenido, el usuario no puede ampliar el alcance de la plataforma ni compartir intereses con amigos.
</td>
  <td>EP03</td>
</tr>
<tr>
  <td>US18</td>
  <td>Soporte Multilingüe</td>
  <td>Como usuario de la plataforma, quiero poder acceder a la aplicación en varios idiomas Para facilitar la navegación y comprensión del contenido</td>
  <td>-Dado que el usuario desea utilizar la plataforma en su idioma preferido, cuando selecciona el idioma desde la configuración de la cuenta, entonces la aplicación se traduce automáticamente.<br>
-Dado que el usuario navega por la aplicación en un idioma específico, cuando todos los textos, botones y mensajes están disponibles en ese idioma, entonces la experiencia de usuario es más intuitiva y fácil de entender.<br>
-Dado que el usuario quiere una experiencia multilingüe, cuando cambia el idioma en cualquier momento, entonces la aplicación se adapta rápidamente sin afectar la funcionalidad y la calidad del contenido.<br>
      -Dado que un usuario desea acceder a la aplicación en varios idiomas, pero la plataforma no ofrece la opción de seleccionar un idioma preferido o no traduce correctamente todo el contenido, el usuario no puede navegar y comprender el contenido de manera efectiva.
</td>
  <td>EP01</td>
</tr>
<tr>
  <td>US19</td>
  <td>Integración con Mapas y Direcciones</td>
  <td>Como usuario de la plataforma, quiero tener acceso a información de ubicación y direcciones de eventos Para facilitar la planificación y asistencia a los mismos</td>
  <td>-Dado que el usuario desea obtener información de ubicación, cuando accede a un evento en la plataforma, entonces puede ver la ubicación del evento en un mapa interactivo.<br>
-Dado que el usuario necesita direcciones, cuando selecciona un evento y elige obtener direcciones, entonces recibe rutas recomendadas y opciones de transporte público cercano.<br>
-Dado que el usuario quiere planificar su asistencia, cuando encuentra información detallada sobre la ubicación, incluyendo estacionamientos y servicios cercanos, entonces puede llegar al evento de manera conveniente y segura.<br>
      -Dado que un usuario desea tener acceso a información de ubicación y direcciones de eventos, pero la plataforma no muestra la ubicación del evento en un mapa interactivo o no proporciona direcciones recomendadas, el usuario no puede planificar y asistir a los eventos de manera eficiente.
</td>
  <td>EP03</td>
</tr>
<tr>
  <td>US20</td>
  <td>Calificación y Reseñas de Eventos</td>
  <td>Como usuario de la plataforma, quiero poder calificar y dejar reseñas sobre eventos a los que asistí Para compartir experiencias y ayudar a otros usuarios en su decisión de compra</td>
  <td>-Dado que el usuario desea calificar un evento, cuando accede a la página de detalles de un evento y selecciona una calificación utilizando una escala de estrellas, entonces su calificación se registra correctamente en la plataforma.<br>
-Dado que un usuario desea dejar una reseña detallada sobre su experiencia en un evento, cuando escribe una reseña en el campo designado de la página de detalles del evento, entonces su reseña se guarda y muestra correctamente para otros usuarios.<br>
-Dado que las calificaciones y reseñas son fundamentales para la toma de decisiones de compra, cuando un usuario busca información sobre un evento, entonces puede ver las calificaciones promedio y leer las reseñas detalladas de otros usuarios interesados en el evento.<br>
      -Dado que un usuario desea calificar y dejar reseñas sobre eventos a los que asistió para compartir experiencias y ayudar a otros usuarios en su decisión de compra, pero la plataforma no permite a los usuarios calificar eventos o escribir reseñas, los usuarios no pueden compartir sus experiencias ni proporcionar comentarios útiles para otros usuarios.
</td>
  <td>EP03</td>
</tr>
<tr>
  <td>US21</td>
  <td>Asistencia en Vivo y Chat en Línea</td>
  <td>Como usuario de la plataforma, quiero tener acceso a asistencia en vivo y chat en línea Para resolver consultas rápidamente y recibir ayuda durante la navegación</td>
  <td>-Dado que el usuario necesita asistencia, cuando accede a la plataforma, entonces puede iniciar una sesión de chat en vivo para recibir respuestas rápidas a preguntas sobre eventos, compras de entradas y problemas técnicos.<br>
-Dado que el usuario requiere ayuda durante la navegación, cuando la asistencia en vivo está disponible durante horas específicas, entonces el usuario puede comunicarse de manera efectiva con el equipo de soporte.<br>
-Dado que el usuario valora la atención al cliente, cuando la asistencia en vivo es accesible desde cualquier página de la aplicación, entonces la experiencia de usuario mejora significativamente.<br>
      -Dado que un usuario desea recibir asistencia en vivo y utilizar el chat en línea para resolver consultas rápidamente, pero la plataforma no ofrece asistencia en vivo o el servicio de chat en línea no está disponible, el usuario no puede obtener ayuda durante la navegación.
</td>
  <td>EP03</td>
</tr>
<tr>
  <td>US22</td>
  <td>Estadísticas y Análisis de Participación</td>
  <td>Como organizador de eventos, quiero acceder a estadísticas y análisis detallados sobre la participación en mis eventos Para evaluar su éxito y mejorar la planificación futura</td>
  <td>-Dado que el organizador necesita evaluar la participación, cuando accede a la plataforma de organizador, entonces puede ver datos de participación como el número de entradas vendidas y perfiles de compradores.<br>
-Dado que el organizador busca mejorar la planificación, cuando accede a informes analíticos sobre la satisfacción de los asistentes y la efectividad de las estrategias de marketing, entonces puede tomar decisiones informadas para futuros eventos.<br>
-Dado que el organizador quiere datos en tiempo real, cuando la plataforma presenta estadísticas de manera clara y comprensible, entonces el organizador puede actuar rápidamente para optimizar la experiencia del evento.<br>
      -Dado que un organizador de eventos desea acceder a estadísticas y análisis detallados sobre la participación en sus eventos, pero la plataforma no muestra los datos de participación o los informes analíticos no están disponibles, el organizador no puede evaluar el éxito de sus eventos ni mejorar la planificación futura.
</td>
  <td>EP02</td>
</tr>
<tr>
  <td>US23</td>
  <td>Integración con Plataformas de Streaming</td>
  <td>Como usuario de la plataforma, quiero tener acceso a transmisiones en vivo y contenido exclusivo de eventos Para disfrutar de experiencias virtuales y ampliar mi participación en eventos</td>
  <td>-Dado que el usuario desea acceder a transmisiones en vivo, cuando busca eventos con esta opción en la plataforma, entonces puede disfrutar de experiencias virtuales desde cualquier ubicación.<br>
-Dado que el usuario quiere contenido exclusivo, cuando accede a contenido relacionado con eventos como entrevistas, sesiones acústicas y contenido detrás de escena, entonces enriquece su experiencia en la plataforma.<br>
-Dado que el usuario busca una experiencia inmersiva, cuando la plataforma integra servicios de streaming populares, entonces el usuario puede participar en eventos de manera virtual y ampliar su participación en eventos de alto interés.<br>
    -Dado que un usuario desea tener acceso a transmisiones en vivo y contenido exclusivo de eventos a través de la plataforma, pero la integración con plataformas de streaming no funciona correctamente o el contenido no está disponible para su visualización, el usuario no puede disfrutar de experiencias virtuales ni ampliar su participación en eventos.  
</td>
  <td>EP03</td>
</tr>
<tr>
  <td>US24</td>
  <td>Verificación de Identidad para Revendedores</td>
  <td>Como revendedor de entradas, quiero completar un proceso de verificación de identidad Para garantizar la legitimidad de mis transacciones y proteger la integridad de la plataforma</td>
  <td>-Dado que el revendedor desea realizar transacciones seguras, cuando proporciona información de identificación oficial como documento de identidad o pasaporte, entonces inicia el proceso de verificación de identidad.<br>
-Dado que la plataforma verifica la identidad, cuando se confirma la legitimidad del revendedor, entonces se habilitan funciones avanzadas como la compra anticipada y límites de compra más altos.<br>
-Dado que el revendedor valora la confidencialidad, cuando la verificación de identidad se realiza de manera segura y cumple con las regulaciones de protección de datos, entonces se fortalece la confianza en la plataforma.<br>
      -Dado que un revendedor de entradas desea completar un proceso de verificación de identidad, pero la plataforma no permite enviar la información de identificación o la verificación no se procesa correctamente, el revendedor no puede garantizar la legitimidad de sus transacciones ni proteger la integridad de la plataforma.
</td>
  <td>EP05</td>
</tr>
<tr>
  <td>US25</td>
  <td>Integración con Plataformas de Pago Internacionales</td>
  <td>Como usuario internacional de la plataforma, quiero poder utilizar diferentes métodos de pago Para facilitar la compra de entradas desde cualquier parte del mundo</td>
  <td>-Dado que el usuario internacional desea pagar de manera conveniente, cuando selecciona su método de pago preferido entre opciones internacionales, entonces puede completar la compra de entradas sin problemas.<br>
-Dado que la plataforma integra pasarelas de pago seguras, cuando admite tarjetas de crédito, transferencias bancarias y monederos electrónicos, entonces los usuarios internacionales tienen opciones flexibles para pagar.<br>
-Dado que el usuario quiere transacciones simplificadas, cuando los pagos se procesan en la moneda local del usuario, entonces se evitan complicaciones relacionadas con las tasas de cambio y conversiones.<br>
      -Dado que un usuario internacional desea utilizar diferentes métodos de pago para facilitar la compra de entradas desde cualquier parte del mundo, pero la integración con plataformas de pago internacionales no está disponible o no admite ciertos métodos de pago, el usuario no puede completar la compra de entradas.
</td>
  <td>EP03</td>
</tr>
<tr>
  <td>US26</td>
  <td>Reserva de Entradas</td>
  <td>Como usuario de la plataforma, quiero tener la opción de reservar entradas para eventos populares Para garantizar mi participación antes de la venta general</td>
  <td>-Dado que el usuario desea asegurar su participación, cuando realiza una reserva para un evento popular, entonces confirma su interés en asistir antes de que las entradas estén disponibles para la venta general.<br>
-Dado que la reserva se confirma mediante un pago inicial, cuando el usuario completa el proceso de reserva y realiza el pago requerido, entonces garantiza su participación en el evento.<br>
-Dado que el usuario busca claridad en el proceso de reserva, cuando recibe instrucciones claras sobre los plazos de pago y las condiciones de la reserva, entonces puede realizar la reserva de manera informada y segura.<br>
      -Dado que un usuario desea reservar entradas para eventos populares antes de la venta general, pero el sistema no permite realizar la reserva o muestra un error al intentar pagar la reserva inicial, el usuario no puede asegurar su participación en eventos de alto interés.
</td>
  <td>EP03</td>
</tr>
<tr>
  <td>US27</td>
  <td>Reembolso y Política de Devoluciones</td>
  <td>Como usuario de la plataforma, quiero conocer la política de reembolso y devoluciones Para tomar decisiones informadas sobre mis compras de entradas</td>
  <td>-Dado que el usuario desea información transparente, cuando la plataforma proporciona detalles claros sobre las condiciones de reembolso y devoluciones, entonces el usuario puede tomar decisiones informadas.<br>
-Dado que el usuario puede solicitar un reembolso dentro de ciertos plazos, cuando la política de reembolso y devoluciones se comunica de manera transparente, entonces se garantiza la satisfacción del cliente.<br>
-Dado que el usuario valora la protección de sus compras, cuando las condiciones de reembolso y devoluciones cumplen con las expectativas del usuario, entonces se fortalece la confianza en la plataforma.<br>
      -Dado que un usuario desea conocer la política de reembolso y devoluciones para tomar decisiones informadas sobre sus compras de entradas, pero la plataforma no proporciona información clara sobre las condiciones de reembolso o no procesa las solicitudes de reembolso adecuadamente, el usuario no puede sentirse seguro al realizar compras en la plataforma.
</td>
  <td>EP03</td>
</tr>

</tr>
  </tbody>
</table>

<h4>Historias Técnicas</h4>
<table>
  <thead>
    <tr>
      <th>Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TS01</td>
      <td>Configuración de datos de Usuarios</td>
      <td>Como desarrollador, necesito configurar un archivo JSON para almacenar la información de cada usuario, como su nombre, correo y contraseña deseada.</td>
      <td>- Se debe poder almacenar correctamente la información de cada usuario en un archivo JSON.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>TS02</td>
      <td>Implementación del Registro de Usuarios</td>
      <td>Como desarrollador, debo implementar la funcionalidad que permita a los usuarios registrarse, incluyendo diseño e interfaz atractivo para ingresar la información al archivo JSON.</td>
      <td>- Los usuarios pueden completar el registro proporcionando su información personal válida.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>TS03</td>
      <td>Desarrollo del Módulo de Inicio de Sesión</td>
      <td>Como desarrollador, debo implementar la funcionalidad que permita a los usuarios iniciar sesión con sus credenciales registradas.</td>
      <td>- Los usuarios pueden iniciar sesión con éxito usando su correo electrónico y contraseña válidos.<br>- Los usuarios reciben un mensaje de error claro si intentan iniciar sesión con credenciales incorrectas.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>TS04</td>
      <td>Manejo de Errores de Inicio de Sesión</td>
      <td>Como desarrollador, debo implementar una lógica que informe a los usuarios sobre errores al intentar iniciar sesión con credenciales incorrectas.</td>
      <td>- Se muestra un mensaje de error claro cuando las credenciales de inicio de sesión son incorrectas.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>TS05</td>
      <td>Muestreo de contraseñas</td>
      <td>Como desarrollador, debo implementar una funcionalidad que permita a los usuarios ver u ocultar su contraseña mientras la ingresan en el registro o inicio de sesión.</td>
      <td>- Los usuarios pueden optar por mostrar u ocultar su contraseña mientras la ingresan.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>TS06</td>
      <td>Implementación Repetir contraseña</td>
      <td>Como desarrollador, debo implementar una lógica que requiera que los usuarios ingresen su contraseña dos veces durante el registro para confirmación.</td>
      <td>- Durante el registro, los usuarios deben ingresar su contraseña dos veces y ambas deben coincidir para confirmación.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>TS07</td>
      <td>Configuración de datos de Eventos</td>
      <td>Como desarrollador, necesito configurar un archivo JSON para almacenar la información de cada evento, incluyendo nombre, fecha, ubicación, descripción, etc.</td>
      <td>- Se debe poder almacenar correctamente la información de cada evento en un archivo JSON.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>TS08</td>
      <td>Diseño e Implementación del Formulario de Creación de Eventos</td>
      <td>Como desarrollador, debo diseñar e implementar un formulario de interfaz de usuario para que los organizadores completen los detalles de un nuevo evento.</td>
      <td>- Los organizadores pueden completar todos los detalles del evento en el formulario de creación de eventos.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>TS09</td>
      <td>Validación de Datos del Formulario</td>
      <td>Como desarrollador, debo implementar la validación de datos para asegurar que los detalles ingresados en el formulario de creación de eventos sean correctos y completos.</td>
      <td>- Se valida que todos los campos requeridos en el formulario estén completos y sean válidos antes de enviar los datos del evento.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>TS10</td>
      <td>Envío de datos</td>
      <td>Como desarrollador, debo implementar la lógica para enviar los datos del nuevo evento creado al archivo JSON.</td>
      <td>- Los datos del evento son enviados y almacenados correctamente en el archivo JSON de eventos.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>TS11</td>
      <td>Diseño e Implementación de la Interfaz de Usuario para Explorar Eventos</td>
      <td>Como desarrollador, debo diseñar e implementar una interfaz de usuario que permita a los usuarios explorar y visualizar los eventos registrados.</td>
      <td>- Los usuarios pueden navegar y ver los eventos disponibles en la interfaz de exploración de eventos.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>TS12</td>
      <td>Implementación del Proceso de Pago</td>
      <td>Como desarrollador, debo implementar el proceso de pago para que los usuarios puedan comprar entradas utilizando diferentes métodos de pago.</td>
      <td>- Los usuarios pueden completar la compra de entradas usando métodos de pago como American Express, PayPal, BCP, etc.<br>- Se presenta un formulario para que los usuarios ingresen la información necesaria para el pago.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>TS13</td>
      <td>Implementación de Visualización de Detalles de Eventos</td>
      <td>Como desarrollador, debo implementar la funcionalidad que permita a los usuarios ver detalles completos de un evento individual.</td>
      <td>- Los usuarios pueden hacer clic en un evento para ver sus detalles completos, incluyendo descripción, fecha, ubicación, categoría, etc.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>TS14</td>
      <td>Implementación de Transacción</td>
      <td>Como desarrollador, debo implementar una interfaz que muestre a los usuarios los detalles de una transacción después de completar la compra.</td>
      <td>- Después de realizar una compra, los usuarios pueden ver los detalles de la transacción, incluyendo estado, nombre del comercio, fecha y hora de pago, ID de transacción, método de pago utilizado y costo total.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>TS15</td>
      <td>Manejo de datos de la transacción</td>
      <td>Como desarrollador, debo implementar una lógica que proporcione información precisa sobre las transacciones a los usuarios.</td>
      <td>- Los datos de las transacciones se manejan correctamente y se muestran de manera clara para los usuarios.</td>
      <td>EP03</td>
    </tr>
  </tbody>
</table>



<h2>3.3 Impact Mapping</h2>
  <img src="./imagenes/impactMapping/Impact Mapping.jpg"/>


<h2>3.4 Product Backlog</h2>
<table>
  <thead>
    <tr>
      <th># Orden</th>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>EP01</td>
      <td>Autenticación de usuario</td>
      <td>Como usuario quiero registrarme e iniciar sesión Para acceder a MyEvent</td>
      <td>3</td>
    </tr>
    <tr>
      <td>2</td>
      <td>EP02</td>
      <td>Creación de eventos</td>
      <td>Como organizador de eventos Quiero poder crear y publicar eventos en la plataforma Para promover mi evento y vender entradas</td>
      <td>5</td>
    </tr>
    <tr>
      <td>3</td>
      <td>EP03</td>
      <td>Exploración de eventos</td>
      <td>Como usuario interesado en eventos Quiero poder buscar y filtrar eventos disponibles Para encontrar eventos que me interesen</td>
      <td>3</td>
    </tr>
    <tr>
      <td>4</td>
      <td>EP04</td>
      <td>Compra de entradas</td>
      <td>Como comprador de entradas Quiero poder seleccionar y comprar entradas Para asegurar mi participación en eventos</td>
      <td>8</td>
    </tr>
    <tr>
      <td>5</td>
      <td>EP05</td>
      <td>Opción Premium para Revendedores</td>
      <td>Como revendedor Quiero tener una opción premium Para obtener ventajas sobre otros compradores</td>
      <td>5</td>
    </tr>
    <tr>
      <td>6</td>
      <td>EP06</td>
      <td>Transferencia de Entradas</td>
      <td>Como usuario que ya ha comprado entradas Quiero poder transferirlas a otros usuarios Para permitir que otros disfruten del evento</td>
      <td>3</td>
    </tr>
    <tr>
      <td>7</td>
      <td>EP07</td>
      <td>Membresía de Descuentos Periódicos</td>
      <td>Como usuario fiel a la plataforma Quiero recibir descuentos especiales periódicamente Para incentivar mi participación continua</td>
      <td>2</td>
    </tr>
    <tr>
      <td>8</td>
      <td>EP08</td>
      <td>Membresía de Concursos y Sorteos Exclusivos</td>
      <td>Como miembro de la plataforma, quiero participar en concursos y sorteos exclusivos para ganar entradas gratuitas y experiencias VIP, para disfrutar de beneficios adicionales y experiencias únicas.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>9</td>
      <td>EP09</td>
      <td>Membresía de Contenido Exclusivo</td>
      <td>Como suscriptor premium, quiero tener acceso a contenido exclusivo relacionado con eventos, como transmisiones en vivo y entrevistas detrás de escena, para disfrutar de una experiencia más completa y enriquecedora.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>10</td>
      <td>EP10</td>
      <td>Membresía de Prioridad en Servicio al Cliente</td>
      <td>Como usuario premium, quiero recibir atención prioritaria en el servicio al cliente, con tiempos de respuesta más rápidos y asistencia personalizada, para sentirme valorado y apoyado como cliente leal.</td>
      <td>3</td>
    </tr>
  </tbody>
</table>

    
