<h1>CAPÍTULO V: PRODUCT IMPLEMENTATION</h1>
<h2>5.1 Software Configuration Management</h2>
<h3>5.1.1 Software Development Environment Configuration</h3>
<p class="justificado">En la siguiente sección se detalla la ruta de acceso de cada uno de los productos de software, facilitando a cualquier miembro del equipo el desarrollo de cada aspecto del trabajo:</p>
<p>Visual Studio Code: Entorno de desarrollo.</p>
<img src="./imagenes/logo-visual.png"/>
<p>HTML5: Lenguaje de marcado para la elaboración de páginas web.</p>
<img src="./imagenes/logo-html.png"/>
<p>CSS3: Tecnología para dar estilo a nuestras páginas web.</p>
<img src="./imagenes/logo-css.png"/>
<p>JavaScript: Lenguaje de programación orientado a objetos utilizado para implementar funcionalidades en nuestra Landing Page.</p>
<img src="./imagenes/logo-js.png"/>
<p>GitHub: Repositorio colaborativo en la nube.</p>
<img src="./imagenes/logo-github.png"/>
<p>GitHub Pages: Plataforma que facilita implementar despliegues sencillos para nuestras páginas web.</p>
<img src="./imagenes/logo-githubpages.png"/>
<p>LucidChart: Aplicación web dedicada a la elaboración de Wireflows, User Flows y diagramas de clases.</p>
<img src="./imagenes/logo-lucidchart.png"/>
<p>Vertabelo: Plataforma colaborativa para la creación de diagramas de base de datos.</p>
<img src="./imagenes/logo-vertabelo.png"/>
<p>Figma: Herramienta colaborativa que permite elaborar wireframes y mockups.</p>
<img src="./imagenes/logo-figma.png"/>
<h3>5.1.2 Source Code Management</h3>
<p>
Link del Landing Page: https://stxfxno.github.io/MyEvent/myevent.html
    
<p>Trabajamos con tres ramas principales:</p>  
<p>Main: Es nuestra rama principal donde presentaremos nuestras publicaciones oficiales.
<p>Dev: Esta rama es nuestro entorno de desarrollo, donde probamos e integramos las funcionalidades trabajadas antes de ser implementadas en la rama principal.</p>    
<p>Feat: Esta rama se descompone en ramas individuales por cada funcionalidad o feature trabajada, permitiendo un enfoque más específico y organizado en el desarrollo de cada aspecto del proyecto.</p>

<h3>5.1.3 Source Code Style Guide & Conventions</h3>
<p>HTML:</p>
<p>En HTML se aplicó la nomenclatura en inglés, por ello en cada DIV su class va estar declarado en este idioma, también podemos observar esto en los inputs y en la clase de span.</p>
<p>div class="search">/div</p>
<img src="./imagenes/html-img1.png"/>
<p>div class="destination__container">/div</p>
<img src="./imagenes/html-image2.png"/>
<p>CSS:</p>
<p>En CSS se mantuvo el mismo trabajo de como se realizó en el HTML.</p>  
<img src="./imagenes/css-img1.png"/>
<img src="./imagenes/css-img2.png"/>
<p>JS:</p>
<p>Con respecto al desarrollo del JS las variables usadas también se aplico la nomenclatura en inglés:</p>
<img src="./imagenes/js-img1.png"/>
<p>Con la primera función creada en JS de const showHideIcons se espera que cada vez que fuera a la izquierda o derecha se ocultara el icono de navegación:</p>
<p>Icono de la izquierda oculto:</p>
<img src="./imagenes/js-ejemplo1.png"/>
<p>Icono de la derecha oculto:</p>
<img src="./imagenes/js-ejemplo2.png"/>
<p>Con respecto a la segunda función, nos da la posibilidad de navegar en el carrusel de arrastrando las imágenes de manera horizontal, ya sea para la derecha o izquierda.</p>
<img src="./imagenes/js-ejemplo3.png"/>
<h3>5.1.4 Software Deployment Configuration</h3>
<p class="justificado">Primero: Subimos todos los archivos necesarios para que github.pages funcione correctamente, entre ellos podemos observar el index.html, styles.css y las demás carpetas que están en formato html.</p>
<img src="./imagenes/paso1.png"/>
<p>Segundo: Recordemos que para funcione la página correctamente la implementación de nuestro landing page debe de tener la siguiente nomenclatura:</p>  
<p>Nombre del proyecto.github.io en este caso se uso el nombre de stxfxno para el nombre del proyecto.</p>
<img src="./imagenes/paso2.png"/>
<p>Tercero: Verificamos que la pagina se haya subido de manera correcta a GitHub Pages , por ello entramos a settings y vamos al apartado de page. </p>
<img src="./imagenes/paso3-parte1.png"/>
<p>Una vez ya en Pages, asegurarnos que en Branch este seleccionado el de main y luego darle en save, esperamos unos minutos para que cargue la página.</p>
<img src="./imagenes/paso3-parte2.png"/>
<p>Luego de esperar cierto tiempo, esperamos a que nuestra página este subida a GitHub Pages, si sale para visitar nuestro sitio web es porque lo hicimos correctamente.</p>
<img src="./imagenes/paso3-parte3.png"/>
<h2>5.2 Product Implementation & Deployment</h2>
<h3>5.2.1. Sprint 1
<h3>5.2.1.1 Sprint Planning 1</h3>
 <table>
            <thead>
                <tr>
                    <td>Sprint #</td>
                    <td>Sprint 1</td>
                </tr>
                <tr>
                    <td colspan="2">Sprint Planning Background</td>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Date</td>
                    <td>10/04/2024</td>
                </tr>
                <tr>
                    <td>Time</td>
                    <td>10:00 am</td>
                </tr>
                <tr>
                    <td>Location</td>
                    <td>Google Meet</td>
                </tr>
                <tr>
                    <td>Prepared By</td>
                    <td>Luis Alejandro Zárate Gamarra</td>
                </tr>
                <tr>
                    <td>Attendees (to planning meeting)</td>
                    <td>/ / Quispe Tipo, Godofredo / Luis Mario, Gonzales Anaya / Jeremi Jose, Antonio Fretel / Luis Alejandro, Zárate Gamarra //</td>
                </tr>
                <tr>
                    <td>Sprint n – 1 Review Summary</td>
                    <td>Debido a que es el primer sprint, no hay reviews de un sprint anterior.</td>
                </tr>
                <tr>
                    <td>Sprint n – 1 Retrospective Summary</td>
                    <td>Siendo el primer sprint, se mencionará la expectativa de los miembros del equipo: Terminar las actividades antes de la crítica. </td>
                </tr>
                <tr>
                    <td colspan="2">Sprint Goal & User Stories</td>
                </tr>
                <tr>
                    <td>Sprint 1 Goal</td>
                    <td>Diseñar e implementar una landing page, realizar el CRUD de adquisicion de boletos u entradas.</td>
                </tr>
                <tr>
                    <td>Sprint 1 Velocity</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>Sum of Story Points</td>
                    <td>13</td>
                </tr>
            </tbody>
        </table>

<h3>5.2.1.2 Sprint Backlog 1</h3>
<P>En este primer Sprint Backlog el grupo se enfoco en realizar la landing page y el diseño del Front de la aplicación web junto con el CRUD de la venta de boletas. Para el registro de cada tarea utilizamos Trello</P>
<table>
   <tr>
    <th>Sprint #</th>
    <th>Sprint 1</th>
  </tr>
   <tr>
    <th>User Story</th>
    <th></th>
    <th>Work-Item/Task</th>
  </tr>
  <tr>
    <th>Id</th>
    <th>Title</th>
    <th>Id</th>
    <th>Title </th>
    <th>Description</th>
    <th>Estimation(Hours)</th>
    <th>Assigned To</th>
    <th>Status (To-do / InProcess / ToReview / Done)</th>
  </tr>
  <tr>
    <th>US-01</th>
    <th>Visualizar una landing page intuitiva</th>
    <th>W-01</th>
    <th>Diseño </th>
    <th>Como visitante, quiero ver una landing page intuitiva, atractiva y sencilla para que pueda entender rápidamente el propósito del sitio web.</th>
    <th>2 hours</th>
    <th>Mario</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US-02</th>
    <th>Visualizar una sección de MyEvent</th>
    <th>W-02</th>
    <th>Sección quienes somos</th>
    <th>Como visitante, quiero ver una sección en el landing page que muestre los proximos eventos que auspicia la empresa.</th>
    <th>2 hours</th>
    <th>Luis</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US-03</th>
    <th>Visualizar una sección de Nosotros</th>
    <th>W-03</th>
    <th>Sección Nosotros</th>
    <th>Como visitante, quiero ver una seccion en el landing page que hable acerca de la empresa y su motivación.</th>
    <th>2 hours</th>
    <th>Jeremi</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US-04</th>
    <th>Visualizar una sección de contacto</th>
    <th>W-04</th>
    <th>Sección de contacto</th>
    <th>Como usuario, quiero una seccion donde pueda observar tarjetas de presentacion de personas con las cuales pueda comunicarme relacionadas con la empresa.</th>
    <th>3 hours</th>
    <th>Godofredo</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US-05</th>
    <th>Visualización de elementos Call to Action</th>
    <th>W-05</th>
    <th>Elementos call to action</th>
    <th>Como visitante, quiero poder observar dentro de la landing page algun elemento que pueda dirijirme directamente a la descarga o uso de la aplicacion que promueve esta landing page</th>
    <th>30 minutes</th>
    <th>Luis</th>
    <th>Done</th>
  </tr>
</table>

<h3>5.2.1.3 Development Evidence for Sprint Review</h4>
<table>
   <tr>
    <th>Repository</th>
    <th>Branch</th>
    <th>Commit ID</th>
    <th>Commit Message</th>
    <th>Commit ed on (Date)</th>
  </tr>
  <tr>
    <th>https://github.com/stxfxno/stxfxno.github.io </th>
    <th>main</th>
    <th>ed1a4aedcf00c8febefdd9616cb2422c7d7d3cb8</th>
    <th>"Archivos del landing page”</th>
    <th>Thu Apr 4 21:32:48 2024</th>
  </tr>
  <tr>
    <th>https://github.com/stxfxno/stxfxno.github.io</th>
    <th>main</th>
    <th>d7d8cdff3b4cf3f7351146fa01146efa0a45df8c</th>
    <th>"Seccion inicial”</th>
    <th>Sat Apr 6 00:42:24</th>
  </tr>
   <tr>
    <th>https://github.com/stxfxno/stxfxno.github.io</th>
    <th>main</th>
    <th>0f7c42fef72c8655ed7db2102ddd9d453cded3e1</th>
    <th>"Seccion MyEvent</th>
    <th>Sat Apr 6 00:42:24 2024</th>
  </tr>
  </tr>
   <tr>
    <th>https://github.com/stxfxno/stxfxno.github.io</th>
    <th>main</th>
    <th>ae044b664c4600f8be9812ac9821ad944ef6e5b5</th>
    <th>"Seccion Nosotros</th>
    <th>Thu Apr 4 21:32:48 2024</th>
  </tr>
  </tr>
   <tr>
    <th>https://github.com/stxfxno/stxfxno.github.io</th>
    <th>main</th>
    <th>7f4da2115b0aae7ff749db20cbed7486cddb06e4</th>
    <th>"Seccion Contacto</th>
    <th>Wed Apr 10 23:38:13 2024</th>
  </tr>
  </table>
<h3>5.2.1.4 Testing Suite Evidence for Sprint Review</h4>
<p>Como nos encontramos en una etapa de diseño de la pagina web, aun no podemos realizar los respectivos Tests. Pero se están
realizando las validaciones para ir mejorando en nuetra pagina web</p>
<h3>5.2.1.5 Execution Evidence for Sprint Review.</h3>
<p>Registro de usuario:</p>
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/9a4fbf95-c832-4e19-a6df-9a0c013722e8>
<p>Ingreso de usuario:</p>
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/da88db46-8844-4c7c-b92b-4e7dcda6371e>
<p>Ingreso de fecha de publicacion del evento:</p>
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/0ccf3c98-e90d-4dbc-9167-7f0ec1626e00>
<p>Añadiendo evento:</p>
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/8185c700-0e34-43ec-9905-9f0765532e80>
<p>Descripcion del Evento:</p>
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/ad5b917f-4805-4f87-a254-c9088fe44ee8>
<p>Registro de Evento Confirmado:</p>
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/b09fc6ee-54e3-4aa6-aae4-59b89f049ff1>

<h3>5.2.1.6 Services Documentation Evidence for Sprint Review.</h3>
<p>Para este primer sprint no fue contemplada la evidencia de documentacion de los servicios.</p>
<h3>5.2.1.7 Software Deployment Evidence for Sprint Review.</h3>
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/1b3fa686-0854-43de-a750-e5e8c0b8171f>
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/cfb530ba-637b-4770-9689-82b60e77ce3b>
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/1ecb7c71-631f-4456-a070-ea9f0de0eba9>
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/a883a101-fe73-4215-9798-7e88ab721427>
<h3>5.2.1.8 Team Collaboration Insights during Sprint.</h3>
<img src="./imagenes/commits.png">
<img src="./imagenes/insights.png">

<h3>5.2.2 Sprint 2</h3>
<h3>5.2.1.1 Sprint Planning 2</h3>
 <table>
            <thead>
                <tr>
                    <td>Sprint #</td>
                    <td>Sprint 2</td>
                </tr>
                <tr>
                    <td colspan="2">Sprint Planning Background</td>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Date</td>
                    <td>25/04/2024</td>
                </tr>
                <tr>
                    <td>Time</td>
                    <td>10:00 am</td>
                </tr>
                <tr>
                    <td>Location</td>
                    <td>Discord</td>
                </tr>
                <tr>
                    <td>Prepared By</td>
                    <td>Luis Alejandro Zárate Gamarra</td>
                </tr>
                <tr>
                    <td>Attendees (to planning meeting)</td>
                    <td>/ / Quispe Tipo, Godofredo / Luis Mario, Gonzales Anaya / Jeremi Jose, Antonio Fretel / Luis Alejandro, Zárate Gamarra //</td>
                </tr>
                <tr>
                    <td>Sprint n – 2 Review Summary</td>
                    <td>El primer sprint se centró en establecer la base para el diseño de la aplicación web y la implementación del CRUD de boletos. Se completaron todas las tareas asignadas, y se logró el objetivo del sprint, con todas las secciones de la landing page diseñadas e implementadas.</td>
                </tr>
                <tr>
                    <td>Sprint n – 2 Retrospective Summary</td>
                    <td>En retrospectiva del Sprint anterior, el equipo ha logrado un progreso significativo en el desarrollo de la landing page y el diseño del Front de la aplicación web, así como en la implementación del CRUD de la venta de entradas.</td>
                </tr>
                <tr>
                    <td colspan="2">Sprint Goal & User Stories</td>
                </tr>
                <tr>
                    <td>Sprint 2 Goal</td>
                    <td>Implementar el frontend, con varios componentes.</td>
                </tr>
                <tr>
                    <td>Sprint 2 Velocity</td>
                    <td>8</td>
                </tr>
                <tr>
                    <td>Sum of Story Points</td>
                    <td>12</td>
                </tr>
            </tbody>
        </table>

<h3>5.2.2.2 Sprint Backlog 2</h3>
<table>
    <tr>
     <th>Sprint #</th>
     <th>Sprint 2</th>
   </tr>
    <tr>
     <th>User Story</th>
     <th></th>
     <th>Work-Item/Task</th>
   </tr>
   <tr>
     <th>Id</th>
     <th>Title</th>
     <th>Id</th>
     <th>Title </th>
     <th>Description</th>
     <th>Estimation(Hours)</th>
     <th>Assigned To</th>
     <th>Status (To-do / InProcess / ToReview / Done)</th>
   </tr>
   <tr>
     <th>US-01</th>
     <th>Visualizar la vista de inicio de la aplicacion</th>
     <th>W-01</th>
     <th>Vista inicial de la aplicación </th>
     <th>Como usuario nuevo que accede a la aplicación por primera vez,
        Quiero poder ver la vista de inicio de la aplicación,
        Para poder familiarizarme con la interfaz y las opciones disponibles.
     <th>2 hours</th>
     <th>Luis</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-02</th>
     <th>Visualizar la vista de inicio de sesion</th>
     <th>W-02</th>
     <th>Iniciar sesion</th>
     <th>Como usuario nuevo que desea utilizar el servicio,
       Quiero poder ver la opción de iniciar sesión en el sitio web o aplicación,
       Para acceder a todas las funcionalidades y personalizar mi experiencia según mis preferencias y necesidades.</th>
     <th>2 hours</th>
     <th>Godofredo</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-03</th>
     <th>Visualizar la vista registro /th>
     <th>W-03</th>
     <th>Registro de usuario</th>
     <th>Como usuario nuevo interesado en utilizar la aplicación,
        Quiero poder ver la vista de registro de usuario,
        Para poder crear una cuenta y comenzar a utilizar todas las funcionalidades disponibles.
     <th>2 hours</th>
     <th>Godofredo</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-04</th>
     <th>Visualizar el calendario de eventos futuros</th>
     <th>W-04</th>
     <th>Calendario de eventos</th>
     <th>Como usuario de la aplicación,
        Quiero poder acceder y visualizar el calendario de eventos futuros,
        Para poder planificar y organizarme con anticipación según las fechas y detalles de los eventos próximos.
     </th>
     <th>2 hours</th>
     <th>Luis</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-05</th>
     <th>Visualizacion de la sección para añadir evento</th>
     <th>W-05</th>
     <th>Registrar un evento</th>
     <th>Como usuario de la aplicación,
        Quiero poder acceder y visualizar la sección para añadir evento,
        Para poder crear nuevos eventos y agregarlos al calendario con los detalles necesarios.
        <th>2 hours</th>
     <th>Mario</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-06</th>
     <th>Visualización de la seccion del detalle del evento</th>
     <th>W-06</th>
     <th>Detalle de evento</th>
     <th>CComo usuario de la aplicación,
        Quiero poder acceder y visualizar la sección de detalle del evento,
        Para obtener información detallada sobre un evento específico, incluidos la fecha, la hora, la ubicación y cualquier otra información relevante.
    </th>
     <th>1 hours</th>
     <th>Jeremi</th>
     <th>Done</th>
   </tr>
 
   <tr>
     <th>US-07</th>
     <th>Visualización de la notificacion de transacción</th>
     <th>W-06</th>
     <th>Notificación de transacción</th>
     <th>Como usuario de la aplicación,
        Quiero poder recibir y visualizar notificaciones de transacciones,
        Para estar al tanto de las actualizaciones importantes relacionadas con mis actividades financieras, como pagos realizados, recibidos o cualquier otro tipo de transacción.
    </th>
     <th>1 hours</th>
     <th>Jeremi</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-08</th>
     <th>Visualización de la confirmación de la compra del boleto</th>
     <th>W-06</th>
     <th>Confirmación de la compra del boleto</th>
     <th>Como usuario que realiza la compra de un boleto,
        Quiero poder ver la confirmación de la compra del boleto,
        Para asegurarme de que la transacción se haya completado con éxito y tener un registro de mi compra.
        <th>1 hours</th>
     <th>Jeremi</th>
     <th>Done</th>
   </tr>
 </table>
 <h3>5.2.2.3 Development Evidence for Sprint Review</h3>
<table>
    <tr>
        <td>Repository</td>
        <td>Branch</td>
        <td>Commit Id</td>
        <td>Commit Message</td>
        <td>Commit Message Body</td>
        <td>Commited on (Date)</td>
    </tr>
    <tr>
        <td>WS52-Open-Source-Grupo-2-MyEvent-Informe</td>
        <td>feature/notifications</td>
        <td>841ef6dd1515f226a07bb977ee8892adad260c96</td>
        <td>feat: Agregar vistas de notificacion de compra de entradas a eventos</td>
        <td>Agregar la vistas de notificaciones de compra de entradas a los eventos</td>
        <td>Commits on Apr 30, 2024</td>
    </tr>
    <tr>
        <td>WS52-Open-Source-Grupo-2-MyEvent-Informe</td>
        <td>feature/notifcaciones</td>
        <td>676f1701e3b29cfe15c7e1806aa1b7f5b769f702</td>
        <td>feat: Agregar creacion de eventos</td>
        <td>Creacion del componente de creacion de eventos hacia el fake API</td>
        <td>Commits on May 2, 2024</td>
    </tr>
    <tr>
        <td>WS51-App-Web-Grupo-2-MyEvent-Informe</td>
        <td>feature/create-event</td>
        <td>df92b59f91fc971fd669716f5d0096b6bad2457c</td>
        <td>feat: Se agregó el componente home</td>
        <td>Creación de componente home </td>
        <td>Commits on Apr 28, 2024</td>
    </tr>
        <tr>
        <td>WS51-App-Web-Grupo-2-MyEvent-Informe</td>
        <td>feature/loginregistercomplete</td>
        <td>80dd7fde062e88f54d4c9f13b9f86c18b0dd2819</td>
        <td>feat: se agregó funcionalidad al botón login e inicialización en el apartado del catálogo</td>
        <td>Creacion del boton de login e inicialización del apartado del catalogo</td>
        <td>Commits on May 1, 2024</td>
    </tr>
        <tr>
        <td>WS51-App-Web-Grupo-2-MyEvent-Informe</td>
        <td>feature/notification</td>
        <td>841ef6dd1515f226a07bb977ee8892adad260c96</td>
        <td>feat: Agregar vistas de notificacion de compra de entradas a eventos</td>
        <td>Creación de componente de notificacion de la compra del boleto</td>
        <td>Commits on Apr 30, 2024</td>
    </tr>
        <tr>
        <td>WS51-App-Web-Grupo-2-MyEvent-Informe</td>
        <td>feature/notification</td>
        <td>676f1701e3b29cfe15c7e1806aa1b7f5b769f702</td>
        <td>feat: Agregar creacion de eventos</td>
        <td>Merge de la creacion de eventos en la rama</td>
        <td>Commits on May 2, 2024</td>
    </tr>
</table>
<h3>5.2.2.4 Testing Suite Evidence for Sprint Review</h3>
<p align="justify">
  Dado que estamos en la fase de diseño del prototipo de la aplicación web, aún no es posible llevar a cabo pruebas exhaustivas. Sin embargo, estamos evaluando diversas herramientas y metodologías para garantizar que, una vez implementada, nuestra aplicación web sea robusta y libre de errores.
</p>

<h3>5.2.2.5 Software Deployment Evidence for Sprint Review</h3>
<p>El proyecto se trabajo en un repositorio dentro de nuestra organización</p>
<img src="./imagenes/repoFront.png" >
<p>Enlace al repositorio del proyecto: https://github.com/EVENTEC/WS52-Open-Source-Grupo-2-MyEvent-FrontEnd</p>

<p>El deployment de nuestro Front-end se ha desarrollado en Netlify</p>
<img src="./imagenes/deployNetlify.png" >
<img src="./imagenes/deployNetlify2.png" >
<p>Enlace al proyecto desplegado: https://master--myevent-frontend-grupo2.netlify.app/ </p>

<h3>5.2.2.6 Services Documentation Evidence for Sprint Review</h3>
Debido a que estamos en la etapa de desarrollo del frontend de la aplicación web. No se está aplicando el servicio de Apis para la demostración de los datos, en su lugar se esta haciendo uso de una fake API.

<h3>5.2.2.7 Execution Evidence for Sprint Review</h3>
<img src="./imagenes/1.png">
<img src="./imagenes/2.png">
<img src="./imagenes/3.png">
<img src="./imagenes/4.png">
<img src="./imagenes/5.png">
<img src="./imagenes/6.png">

<h3>5.2.2.8 Team Collaboration Insights during Sprint</h3>
<p align="justify">
  Durante el Sprint actual, nos dispusimos a abordar las distintas mejoras para MyEvent. Empezamos con la creación de la plataforma principal en Angular. Para ello, dividimos las tareas para trabajar de manera eficiente y centrarnos en áreas específicas, con el fin de optimizar el tiempo y los recursos. Debido a esto, la participación de los miembros del equipo se ve reflejado en los commits realizados en el repositorio de trabajo:
</p>

<img src="./imagenes/Contributors1.png" width="600" height="350">
<img src="./imagenes/Contributors2.png" width="600" height="350">
<img src="./imagenes/Traffic.png" width="600" height="300">

<h3>5.2.3. Sprint 3</h3>

<h3>5.2.3.1 Sprint Planning 3</h3>
<table>
    <tr>
      <th>Sprint # </th>
      <th>Sprint 3 </th>
    </tr>
    <tr>
      <td><strong>Sprint Planning Background</strong></td>
      <td></td>
    </tr>
    <tr>
      <th>Date</th>
      <th>2024/05/20</th>
    </tr>
    <tr>
      <th>Time</th>
      <th>18:00 PM</th>
    </tr>
    <tr>
      <th>Location</th>
      <th>Discord</th>
    </tr>
    <tr>
      <th>Prepared by</th>
      <th>Luis Alejandro, Zárate Gamarra</th>
    </tr>
    <tr>
      <th>Attendess (to planning meeting)</th>
      <th>
        Luis Alejandro, Zárate Gamarra - U20181H198
        Gonzales Anaya, Luis Mario - U20201C585
        Jeremi Jose, Antonio Fretel - U202219022
   </th>
    </tr>
    <tr>
      <th>Sprint 2 Review Summary</th>
      <th>Correcciones y término del desarrollo de las tareas que corresponden al Sprint 2 </th>
    </tr>
    <tr>
      <th>Sprint 2 Retrospective Summary</th>
      <th>Cambios de user storys, épicas. Escasa cantidad de user storys realizadas.</th>
    </tr>
    <tr>
      <th>Sprint Goal & User Stories</th>
      <th>Corregir frontend e implementar las nuevas user storys, creación y realización del 50% del backend</th>
    </tr>
    <tr>
      <th>Sprint 3 Goal</th>
      <th>Se creó el repositorio del Backend de nuestra aplicación y se llegó a desplegar el proyecto </th>
    </tr>
    <tr>
      <th>Sprint 3 Velocity</th>
      <th>3 semanas </th>
    </tr>
    <tr>
      <th>Sum of Story Point</th>
      <th>5</th>
    </tr>
  </table>

<h3>5.2.3.2 Sprint Backlog 3</h3>
<table>
    <tr>
     <th>Sprint #</th>
     <th>Sprint 3</th>
   </tr>
    <tr>
     <th>User Story</th>
     <th></th>
     <th>Work-Item/Task</th>
   </tr>
   <tr>
     <th>Id</th>
     <th>Title</th>
     <th>Id</th>
     <th>Title </th>
     <th>Description</th>
     <th>Estimation(Hours)</th>
     <th>Assigned To</th>
     <th>Status (To-do / InProcess / ToReview / Done)</th>
   </tr>
   <tr>
     <th>US-01</th>
     <th>Creación de Cuenta</th>
     <th>W-01</th>
     <th>Crear una cuenta en la plataforma como usuario nuevo</th>
     <th>Como usuario nuevo, quiero poder crear una cuenta ingresando mis datos para acceder a MyEvent.
     <th>1 hour</th>
     <th>Mario</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-02</th>
     <th>Opción de Rol al Registrarse y Confirmación</th>
     <th>W-02</th>
     <th>Selecciona tu rol usuario nuevo</th>
     <th>Como usuario nuevo, quiero poder seleccionar mi rol (organizador o comprador) al registrarme en MyEvent.</th>
     <th>1 hour</th>
     <th>Luis</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-03</th>
     <th>Iniciar Sesión con Correo y Contraseña</th>
     <th>W-03</th>
     <th>Iniciar sesion una vez creada tu cuenta</th>
     <th>Como usuario registrado, quiero poder iniciar sesión utilizando mi correo electrónico y contraseña en MyEvent.
     <th>1 hour</th>
     <th>Jeremy</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-04</th>
     <th>Visualización de Opciones para Usuarios no Premium</th>
     <th>W-04</th>
     <th>Ventana de información acerca del servicio premium</th>
     <th>Como usuario estándar, quiero poder ver las ventajas y costos de la membresía premium en MyEvent.</th>
     <th>2 hours</th>
     <th>Mario</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-05</th>
     <th>Visualización de Perfil de Usuario</th>
     <th>W-05</th>
     <th>Vista para que los usuarios vean su informacion de pefil y puedan gestionarlos</th>
     <th>Como usuario registrado, quiero poder ver mi perfil en MyEvent para gestionar mis datos personales.
     <th>1 hour</th>
     <th>Luis</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-06</th>
     <th>Gestión de Sesión y Contraseña</th>
     <th>W-06</th>
     <th>Cerrar Sesion y cambio de contraseña</th>
     <th>Como usuario registrado, quiero poder cerrar sesión y cambiar mi contraseña en MyEvent para mantener la seguridad de mi cuenta.</th>
     <th>1 hour</th>
     <th>Mario</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-07</th>
     <th>Detalles del evento</th>
     <th>W-07</th>
     <th>Información relevante de los eventos existentes</th>
     <th>Como usuario interesado en un evento, quiero poder ver todos los detalles relevantes del mismo, incluyendo la fecha, hora, lugar, artistas o participantes, descripción del evento y opciones de boletos disponibles, para tomar una decisión informada sobre mi asistencia</th>
     <th>2 hours</th>
     <th>Jeremy</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-08</th>
     <th>Compra de boletos</th>
     <th>W-08</th>
     <th>Adquirir boletos de un evento favorito</th>
     <th>Como usuario que desea asistir a un evento, quiero poder seleccionar la cantidad y el tipo de boletos que deseo comprar, ingresar mis datos personales, seleccionar el método de pago y completar la transacción de compra de manera segura y sin problemas.
     <th>2 hours</th>
     <th>Mario</th>
     <th>Done</th>
   </tr>

   <tr>
     <th>US-09</th>
     <th>Compra exitosa</th>
     <th>W-09</th>
     <th>Confirmación de compra de boletos</th>
     <th>Como usuario que ha realizado una compra de boletos, quiero recibir una confirmación clara y visualmente atractiva de que mi pago ha sido exitoso, incluyendo detalles como el número de orden, la cantidad de boletos comprados y cualquier información adicional relevante, para tener la tranquilidad de que mi compra ha sido procesada correctamente.
        <th>1 hours</th>
     <th>Luis</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-10</th>
     <th>Rechazo de transacción</th>
     <th>W-10</th>
     <th>Información relevante en caso de rechazo de transacción</th>
     <th>Como usuario que ha intentado realizar una compra de boletos, quiero ser notificado de manera clara y comprensible en caso de que mi pago haya sido rechazado, incluyendo información sobre el motivo del rechazo y posibles acciones que pueda tomar para resolver el problema, para poder intentar nuevamente realizar la compra de manera exitosa o buscar alternativas de pago.
        <th>1 hour</th>
     <th>Jeremy</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-11</th>
     <th>Validaciones de información</th>
     <th>W-11</th>
     <th>validación de información al momento de la compra</th>
     <th>Como usuario que está completando el proceso de compra de boletos, quiero que se realicen validaciones en tiempo real de los datos que ingreso, incluyendo la detección de errores en campos como el correo electrónico, número de tarjeta de crédito, fecha de vencimiento, etc., para poder corregir cualquier error de manera rápida y precisa antes de finalizar la transacción.
        <th>2 hours</th>
     <th>Mario</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-12</th>
     <th>Publicar una Entrada para Reventa</th>
     <th>W-12</th>
     <th>Publicación de entrada en caso de reventa</th>
     <th>Como un cliente que ya no puede asistir a un evento quiero poder publicar mis entradas en modo reventa en la plataforma, para que pueda recuperar parte o todo el dinero que gasté en la entrada.
        <th>1 hour</th>
     <th>Luis</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-13</th>
     <th>Retirar Entrada de la Reventa</th>
     <th>W-13</th>
     <th>Retirar la entrada de reventa en caso ya no desee revender</th>
     <th>Como un cliente que ha publicado una entrada para reventa quiero poder retirar la entrada del mercado de reventa en cualquier momento, para poder utilizarla si cambio de opinión.
        <th>1 hour</th>
     <th>Jeremy</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-14</th>
     <th>Buscar Entradas Disponibles para Reventa</th>
     <th>W-14</th>
     <th>Busqueda de entradas en modo de reventa</th>
     <th>Como un cliente que busca entradas para un evento, quiero poder buscar entradas disponibles para reventa en la plataforma, para tener la oportunidad de asistir al evento aunque las entradas oficiales estén agotadas.
        <th>1 hour</th>
     <th>Mario</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-15</th>
     <th>Ver Información Detallada de la Entrada</th>
     <th>W-15</th>
     <th>Informacion relevante de la entrada en reventa</th>
     <th>Como un cliente interesado en comprar una entrada revendida, quiero ver información detallada de la entrada (como la ubicación del asiento y el precio), para tomar una decisión informada antes de comprar.
        <th>1 hour</th>
     <th>Luis</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-16</th>
     <th>Comprar una Entrada Revendida</th>
     <th>W-16</th>
     <th>Comprar una entrada en modo reventa</th>
     <th>Como un cliente que ha encontrado una entrada adecuada quiero poder comprar la entrada revendida de forma segura a través de la plataforma, para asegurar mi lugar en el evento.
        <th>2 hours</th>
     <th>Jeremy</th>
     <th>Done</th>
   </tr>

   <tr>
     <th>US-17</th>
     <th>Recibir Confirmación y Entradas Digitales</th>
     <th>W-17</th>
     <th>Confirmación de la entrada revendida adquirida</th>
     <th>Como un cliente que ha comprado una entrada revendida, quiero recibir una confirmación inmediata y las entradas digitales para tener la tranquilidad de que mi compra fue exitosa y poder asistir al evento.
        <th>1 hour</th>
     <th>Mario</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-18</th>
     <th>Crear evento</th>
     <th>W-18</th>
     <th>Crear un evento como organizador</th>
     <th>Como organizador de eventos quiero poder crear un nuevo evento ingresando información básica como título, descripción, fecha y hora, para que los usuarios puedan conocer los detalles principales del evento.
        <th>2 hours</th>
     <th>Luis</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-19</th>
     <th>Definir ubicación del evento</th>
     <th>W-19</th>
     <th>Especificar el lugar del evento creado</th>
     <th>Como organizador de eventos quiero poder establecer la ubicación del evento mediante una dirección física o un enlace a un evento virtual, para que los asistentes sepan dónde se llevará a cabo.
        <th>1 hours</th>
     <th>Jeremy</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-20</th>
     <th>Gestionar entradas</th>
     <th>W-20</th>
     <th>Definir especificaciones relevantes para el evento creado</th>
     <th>Como organizador de eventos quiero poder definir diferentes tipos de entradas con precios, cantidades y descripciones, para ofrecer opciones de compra adaptadas a las necesidades de los asistentes.
        <th>2 hours</th>
     <th>Mario</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-21</th>
     <th>Añadir imágenes y multimedia</th>
     <th>W-21</th>
     <th>Complementar la creacion de evento con imagenes y multimedia</th>
     <th>Como organizador de eventos quiero poder subir imágenes y videos promocionales para el evento, para atraer más asistentes y proporcionar una visión clara de lo que pueden esperar.
        <th>1 hour</th>
     <th>Luis</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-22</th>
     <th>Configurar opciones de privacidad</th>
     <th>W-22</th>
     <th>definir la privacidad del evento creado</th>
     <th>Como organizador de eventos quiero poder establecer si el evento es público o privado y definir las restricciones de acceso, para controlar quién puede ver y unirse al evento.
        <th>1 hour</th>
     <th>Jeremy</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-23</th>
     <th>Enviar invitaciones</th>
     <th>W-23</th>
     <th>Ivitar a personas al evento creado mediante diferentes medios</th>
     <th>Como organizador de eventos quiero poder enviar invitaciones a contactos específicos por correo electrónico o mediante un enlace directo, para asegurarme de que las personas clave estén informadas y puedan asistir.
        <th>2 hours</th>
     <th>Mario</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-24</th>
     <th>Publicar y compartir el evento</th>
     <th>W-24</th>
     <th>Publicar el evento en la plataforma y compartirlo por redes sociales</th>
     <th>Como organizador de eventos quiero poder publicar el evento y compartirlo en redes sociales, para aumentar la visibilidad del evento y atraer a más asistentes.
        <th>2 hours</th>
     <th>Luis</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-25</th>
     <th>Detalle de subscripción</th>
     <th>W-25</th>
     <th>Información relevante para comprar membresía</th>
     <th>Como comprador de boletos de la plataforma quisiera poder vizualizar los detalles de la compra de subscripcion premium para aprovechar los beneficios que ofrece este y saber si me beneficia su adquisicion
        <th>1 hour</th>
     <th>Jeremy</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-26</th>
     <th>Compra de subscripción</th>
     <th>W-26</th>
     <th>Compra de la membresia premium</th>
     <th>Como comprador de boletos quisiera comprar la subscripcion premium, ingresando mis datos de manera segura, para acceder a beneficios unicos de la plataforma
        <th>2 hours</th>
     <th>Mario</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-27</th>
     <th>Notificación de renovación</th>
     <th>W-27</th>
     <th>Aviso para la renovacion de mmebresía</th>
     <th>Como comprador de boletos quisiera recibir notificaciones de renovacion de membresia 7 dias antes de que caduque, para estar al tanto de ella y poder renovarla a tiempo.
        <th>1 hour</th>
     <th>Luis</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-28</th>
     <th>Renovar subscripción</th>
     <th>W-28</th>
     <th>Comprar nuevamente la membresía premium</th>
     <th>Como comprador de boletos quisiera renovar la subcripcion premium mediante la ventana de mi perfil o ventana de notificaciones para seguir disfrutando de los beneficios de la plataforma
        <th>1 hour</th>
     <th>Jeremy</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US-29</th>
     <th>Cancelar subscripción</th>
     <th>W-29</th>
     <th>cancelar la membresía premium</th>
     <th>Como comprador de boletos quisiera cancelar la subscripcion premium mediante la ventana de mi perfil y dejar de tener beneficios unicos en la plataforma
        <th>1 hour</th>
     <th>Mario</th>
     <th>Done</th>
   </tr>
 </table>

<h3>5.2.3.3 Development Evidence for Sprint Review</h3>
<table>
    <tr>
        <td>Repository</td>
        <td>Branch</td>
        <td>Commit Id</td>
        <td>Commit Message</td>
        <td>Commit Message Body</td>
        <td>Commited on (Date)</td>
    </tr>
    <tr>
        <td>EVENTEC-Aplicaciones-Web-WS51/Frontend</td>
        <td>feature/login-register</td>
        <td>46760adb5ef4d58bfcab2063ca176af521718000</td>
        <td>feat: Implementación para que funcione con el backend</td>
        <td>Arreglo en el manejo de datos</td>
        <td>Commits on Jun 8, 2024</td>
    </tr>
    <tr>
        <td>EVENTEC-Aplicaciones-Web-WS51/Frontend</td>
        <td>feature/contact</td>
        <td>e76d5a2bda57ede8c6555ab5b7ead15c1a8b85ca</td>
        <td>feat: Cambios en la estructura de la vista - Usuario</td>
        <td>Reorganizacion de carpetas</td>
        <td>Commits on May 30, 2024</td>
    </tr>
</table>

<h3>5.2.3.5 Execution Evidence for Sprint Review</h3>
<img src="./imagenes/sprint3/1.png">
<img src="./imagenes/sprint3/2.png">
<img src="./imagenes/sprint3/3.png">
<img src="./imagenes/sprint3/4.png">
<img src="./imagenes/sprint3/5.png">
<img src="./imagenes/sprint3/6.png">
<img src="./imagenes/sprint3/7.png">
<img src="./imagenes/sprint3/8.png">
<img src="./imagenes/sprint3/9.png">
<img src="./imagenes/sprint3/10.png">
<img src="./imagenes/sprint3/11.png">
<img src="./imagenes/sprint3/12.png">
<img src="./imagenes/sprint3/13.png">
<img src="./imagenes/sprint3/14.png">
<img src="./imagenes/sprint3/15.png">
<img src="./imagenes/sprint3/16.png">

<h3>5.2.3.6 Services Documentation Evidence for Sprint Review</h3>
<table>
  <thead>
    <tr>
      <th>Endpoint</th>
      <th>Verbo HTTP</th>
      <th>Enlace</th>
      <th>Parámetros</th>
      <th>Response</th>
      <th>Explicación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>/api/v1/users/1</td>
      <td>GET</td>
      <td><a href="http://localhost:8080/api/v1/users/1">http://localhost:8080/api/v1/users/1</a></td>
      <td>N/A</td>
      <td>{"id": 1, "name": "John Doe", "email": "john.doe@example.com"}</td>
      <td>Obtiene el usuario por ID</td>
    </tr>
    <tr>
      <td>/api/v1/users/correo/ianpe@example.com</td>
      <td>GET</td>
      <td><a href="http://localhost:8080/api/v1/users/correo/ianpe@example.com">http://localhost:8080/api/v1/users/correo/ianpe@example.com</a></td>
      <td>N/A</td>
      <td>{"id": 2, "name": "Ian Perez", "email": "ianpe@example.com"}</td>
      <td>Obtiene el usuario por correo</td>
    </tr>
    <tr>
      <td>/api/v1/users/name/Emily/surname/Davis</td>
      <td>GET</td>
      <td><a href="http://localhost:8080/api/v1/users/name/Emily/surname/Davis">http://localhost:8080/api/v1/users/name/Emily/surname/Davis</a></td>
      <td>N/A</td>
      <td>{"id": 3, "name": "Emily Davis", "email": "emily.davis@example.com"}</td>
      <td>Obtiene el usuario por nombre y apellido</td>
    </tr>
    <tr>
      <td>/api/v1/users</td>
      <td>GET</td>
      <td><a href="http://localhost:8080/api/v1/users">http://localhost:8080/api/v1/users</a></td>
      <td>N/A</td>
      <td>[{"id": 1, "name": "John Doe", "email": "john.doe@example.com"}, {"id": 2, "name": "Ian Perez", "email": "ianpe@example.com"}]</td>
      <td>Obtiene todos los usuarios</td>
    </tr>
    <tr>
      <td>/correo/ianpe@example.2</td>
      <td>DELETE</td>
      <td><a href="http://localhost:8080/correo/ianpe@example.2">http://localhost:8080/correo/ianpe@example.2</a></td>
      <td>{"name": "Ian Perez", "password": "examplePassword"}</td>
      <td>{"message": "Usuario eliminado exitosamente"}</td>
      <td>Elimina el usuario por nombre y contraseña</td>
    </tr>
    <tr>
      <td>/api/v1/users/change-password/3/emilyfddfdavis@example.com</td>
      <td>PUT</td>
      <td><a href="http://localhost:8080/api/v1/users/change-password/3/emilyfddfdavis@example.com">http://localhost:8080/api/v1/users/change-password/3/emilyfddfdavis@example.com</a></td>
      <td>{"password": "nuevaContra2"}</td>
      <td>{"message": "Contraseña actualizada exitosamente"}</td>
      <td>Actualiza la contraseña por ID y correo</td>
    </tr>
    <tr>
      <td>/api/v1/users/change-name/9/jesus@gmail.com</td>
      <td>PUT</td>
      <td><a href="http://localhost:8080/api/v1/users/change-name/9/jesus@gmail.com">http://localhost:8080/api/v1/users/change-name/9/jesus@gmail.com</a></td>
      <td>{"password": "huawei", "name": "Enrique"}</td>
      <td>{"message": "Nombre actualizado exitosamente"}</td>
      <td>Cambia el nombre del usuario</td>
    </tr>
    <tr>
      <td>/api/v1/events/create</td>
      <td>POST</td>
      <td><a href="http://localhost:8080/api/v1/events/create">http://localhost:8080/api/v1/events/create</a></td>
      <td>
        {"name": "Concierto de Rock", "date": "2024-06-15", "organizer": "Rock Productions", "location": "Estadio Central", "resale": true, "description": "¡Ven y disfruta de una noche llena de música rockera!", "price": 25.99, "capacity": 1000, "image": "https://ejemplo.com/imagen.jpg", "category": "Conciertos", "eventApiKey": "tu_clave_de_API"}
      </td>
      <td>{"message": "Evento creado exitosamente"}</td>
      <td>Inserta un nuevo evento</td>
    </tr>
    <tr>
      <td>/api/v1/events</td>
      <td>GET</td>
      <td><a href="http://localhost:8080/api/v1/events">http://localhost:8080/api/v1/events</a></td>
      <td>N/A</td>
      <td>
        [
          {"id": 1, "name": "Concierto de Rock", "date": "2024-06-15", "organizer": "Rock Productions", "location": "Estadio Central"},
          {"id": 2, "name": "Festival de Jazz", "date": "2024-07-10", "organizer": "Jazz Fest", "location": "Parque Central"}
        ]
      </td>
      <td>Obtiene todos los eventos</td>
    </tr>
    <tr>
      <td>/api/v1/events/name/Concierto de Rock</td>
      <td>GET</td>
      <td><a href="http://localhost:8080/api/v1/events/name/Concierto%20de%20Rock">http://localhost:8080/api/v1/events/name/Concierto%20de%20Rock</a></td>
      <td>N/A</td>
      <td>{"id": 1, "name": "Concierto de Rock", "date": "2024-06-15", "organizer": "Rock Productions", "location": "Estadio Central"}</td>
      <td>Obtiene evento por nombre</td>
    </tr>
    <tr>
      <td>/api/v1/events/name/Concierto de Rock/organizer/Rock Productions</td>
      <td>GET</td>
      <td><a href="http://localhost:8080/api/v1/events/name/Concierto%20de%20Rock/organizer/Rock%20Productions">http://localhost:8080/api/v1/events/name/Concierto%20de%20Rock/organizer/Rock%20Productions</a></td>
      <td>N/A</td>
      <td>{"id": 1, "name": "Concierto de Rock", "date": "2024-06-15", "organizer": "Rock Productions", "location": "Estadio Central"}</td>
      <td>Obtiene evento por nombre y organizador</td>
    </tr>
    <tr>
      <td>/api/v1/events/3</td>
      <td>DELETE</td>
      <td><a href="http://localhost:8080/api/v1/events/3">http://localhost:8080/api/v1/events/3</a></td>
      <td>N/A</td>
      <td>{"message": "Evento eliminado exitosamente"}</td>
      <td>Elimina el evento por ID</td>
    </tr>
    <tr>
      <td>/api/v1/events/6</td>
      <td>PUT</td>
      <td><a href="http://localhost:8080/api/v1/events/6">http://localhost:8080/api/v1/events/6</a></td>
      <td>
        {"name": "Concierto de Rock Actualizado", "date": "2024-06-20", "organizer": "Rock Productions Actualizado", "location": "Estadio Central Actualizado", "resale": false, "description": "¡Ven y disfruta de una noche llena de música rockera actualizada!", "price": 35.99, "capacity": 1500, "image": "https://ejemplo.com/imagen_actualizada.jpg", "category": "Conciertos Actualizados", "eventApiKey": "tu_clave_de_API_actualizada"}
      </td>
      <td>{"message": "Evento actualizado exitosamente"}</td>
      <td>Actualiza un evento</td>
    </tr>
    <tr>
      <td>/new-request</td>
      <td>GET</td>
      <td>N/A</td>
      <td>N/A</td>
      <td>{"message": "Nueva solicitud realizada exitosamente"}</td>
      <td>Nueva solicitud</td>
    </tr>
  </tbody>
</table>

<h3>5.2.3.7 Software Deployment Evidence for Sprint Review</h3>
<p>Hemos deployeado nuestra base de datos y logramos hacer un post dentro de la base de datos deployeada.</p>
<img src="./imagenes/sprint3/SoftwareDeploymentEvidence.png">

<h3>5.2.3.8 Team Collaboration Insights during Sprint</h3>
<p>Para el trabajo colaborativo nos ayudamos de la herramienta Github y de las ramas y commits que se podían hacer. Además de los merge que unen toda nuestra parte del trabajo.</p>
<img src="./imagenes/sprint3/insights-sprint3.png">

<h2>5.3 Validation Interviews</h2>
    <h3>5.3.1. Diseño de Entrevistas.</h3>
    <p><strong>Segmento Cliente:</strong></p>
    <ol>
        <li>¿Qué tan llamativa te resulta nuestra página web?</li>
        <li>¿Qué tan fácil te resulta registrarte e iniciar sesión?</li>
        <li>¿Qué te parece que te muestre al iniciar sesión una oferta para acceder a la versión premium de nuestra aplicación web?</li>
        <li>¿Puedes encontrar toda la información necesaria sobre un evento al hacer clic en él?</li>
        <li>¿Qué tan intuitivo te parece el proceso de selección y compra de entradas?</li>
        <li>¿Has tenido alguna dificultad al intentar transferir entradas a otro usuario?</li>
        <li>¿Encuentras algunas imperfecciones en nuestra plataforma?</li>
    </ol>
    <p><strong>Segmento Organizador:</strong></p>
    <ol>
        <li>
            <p>¿Qué tan intuitivo y sencillo te resultó el proceso de creación de cuenta y gestión de tu perfil? ¿Hay alguna característica o funcionalidad que crees que falta o podría mejorarse?</p>
        </li>
        <li>
            <p>¿Cómo fue tu experiencia al crear y personalizar un evento en la plataforma? ¿Encontraste todas las opciones que necesitabas para ofrecer una experiencia única a los asistentes?</p>
        </li>
        <li>
            <p>¿Qué tan fácil te resultó acceder a la información detallada de los eventos y realizar la compra de entradas? ¿Hubo algún aspecto de la experiencia de compra que te gustaría que fuera diferente o mejorado?</p>
        </li>
        <li>
            <p>¿Qué tipo de estadísticas y análisis te gustaría ver sobre la participación en tus eventos? ¿Cómo crees que esta información te ayudaría a evaluar el éxito de tus eventos y a mejorar la planificación futura?</p>
        </li>
        <li>
            <p>¿Qué te parece la opción de que los clientes puedan revender sus entradas a eventos directamente en la plataforma? ¿Cómo crees que esta funcionalidad impactaría en la asistencia y el manejo de las entradas para los eventos que organizas?</p>
        </li>
    </ol>
    
  <h3>5.3.2 Registro de entrevistas</h3>

<h3>Segmento Organizador de Eventos</h3>
<h4>Nombre: Fernando André Cipriano</h4>
<h4>Entrevistador: Piero Jhoynner Muñoz Salcedo</h4>
<details>
  <summary>Detalles:</summary>
    <ul>
    <li>Género: Masculino</li>
    <li>Edad: 25 años</li>
    <li>Ubicación: Cercado de Lima</li>
  </ul>
</details><br>

  <table style="border: 1px solid gray;">
    <tr>
        <td><img src="./imagenes/sprint3/foto entrevista A.PNG" alt="Descripción de la imagen"></td>
    </tr>
    <tr><td class="justificado">El entrevistado, quien es organizador de eventos, navegó en nuestra plataforma web y de momento nos comenta que le parecio util e intuitivo el inicio de sesion, y facil al momento de registrarse, afirma que podria mejorar añadiendo informacion en su perfil con relacion al historial de eventos pasados. Nos cuenta que tuvo una buena experiencia al momento de crear un evento y considera fundamental las invitaciones por medio de redes sociales. Ademas, considera que la compra de entradas son faciles y estan bien implementadas y lo unico que le gustaria añadir es el guardado de informacion de pago para mayor facilidad al momento de comprar entradas. Por otro lado, le gustaria que hubieran estadisticas detallas de la participacion e interaccion de las personas que asisten a los eventos para que así pueda tomar deciciones mas estrategicas para futuras fechas. Nos indica que la opcion de revender entradas lo considera muy bueno y no cree que el impacto que tiene fuese negativo, ya que esto aseguraria que el evento tenga mas asistentes, sin desperdiciar alguna entrada.
</td></tr>
    <tr><td>Link de la entrevista: <a href="https://www.youtube.com/watch?v=zWS4qhYYFmY">https://www.youtube.com/watch?v=zWS4qhYYFmY</a></td></tr>
  </table>  
    <h4>Segmento Organizador de eventos</h4>
    <h4>Nombre: Joaquin Paredes</h4>
    <img src="./imagenes/sprint3/VI1.png" width="400" height="200">
    <p><strong>Link del video: </strong> https://upcedupe-my.sharepoint.com/:v:/g/personal/u202113640_upc_edu_pe/EYxoxcwfW-xGstj_LsHO4OAB-mEsaPiV-p0wKHfwKRk-8w?e=ofvHp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D</p>
    <p>Joaquin como organizador de eventos esta satisfecho con MyEvent, encontrando la plataforma fácil de usar y efectiva. Las sugerencias para mejoras incluyen más opciones de personalización, plantillas prediseñadas para eventos y una opción de 'wishlist' para la compra de entradas. La reventa de entradas es vista como una funcionalidad positiva que puede mejorar la asistencia y la gestión de eventos.</p>


   <h3>Segmento Comprador de Entradas</h3>
<h4>Nombre: Nickol Ariana Sandoval</h4>
<h4>Entrevistador: Piero Jhoynner Muñoz Salcedo</h4>
<details>
  <summary>Detalles:</summary>
    <ul>
    <li>Género: Femenino</li>
    <li>Edad: 22 años</li>
    <li>Ubicación: Cercado de Lima</li>
  </ul>
</details><br>

  <table style="border: 1px solid gray;">
    <tr>
        <td><img src="./imagenes/sprint3/entrevista B.PNG" alt="Descripción de la imagen"></td>
    </tr>
    <tr><td class="justificado">La entrevistada indica que la plataforma le parecio fabulosa e intuitiva, ademas detallo que el modo de registrarse le parece muy seguro ya que le piden el DNI como medio de registro, ademas le parecio exelente la vista de adquirir membresia premium, ya que los descuentos hacen llamativo a la plataforma web. Indica que al hacer click en un evento le permite ver toda la informacion de esta para convenserse de su compra, ademas nos comenta que le parece facil la adquisicion entradas, ya que los datos que piden son muy pertinentes. Comenta que nunca tuvo la oportunidad de revender una entrada, pero a partir de la experiencia en la plataforma le transmite mas seguridad que hacerlo por sus redes u otros medios. Lo unico que detalla como una imperfeccion es que se coloquen lo precios generales directamente en cada imagen de evento en la pagina de inicio, ya que esto hace que como comprador de entradas se animen por comprar al ver el precio de la entrada pensando que es una vip pero al ingresar a los detalles del evento solo sea para general.
        
</td></tr>
    <tr><td>Link de la entrevista: <a href="https://youtu.be/pt136hPLp-A">https://youtu.be/pt136hPLp-A</a></td></tr>
  </table>


<h3>5.3.3 Evaluaciones según heurísticas</h3>
</head>
<body>
<h4 align="center"><b>UX Heuristics & Principles Evaluation</b></h4>
<h4 align="center"><b>Usability – Inclusive Design – Information Architecture</b></h4>
<h5><b>CARRERA:</b> Ingeniería de Software</h5>
<h5><b>CURSO:</b> Desarrollo de Aplicaciones Open Source</h5>
<h5><b>SECCIÓN:</b> WS52</h5>
<h5><b>PROFESORES:</b> Todos</h5>
<h5><b>AUDITOR:</b> Grupo 2</h5>
<h5><b>CLIENTE(S):</b> Gonzales Anaya, Luis Mario</h5>
<h4>SITE o APP A EVALUAR:</b></h4>
    <p>MyEvent</p>
<h4>TAREAS A EVALUAR:</h5>
<ol>
  <li>Creación de una cuenta</li>
  <li>Inicio de sesión</li>
  <li>Visualización de opciones para usuarios no premium</li>
  <li>Visualización de perfil de usuario</li>
  <li>Gestión de sesión y contraseña</li>
  <li>Renovación de la suscripción</li>
  <li>Notificación de cambio de horarios de eventos</li>
  <li>Atención prioritaria en el servicio al cliente</li>
  <li>Recomendación personalizada sobre eventos</li>
</ol>
<h5>No están incluidas en esta versión de la evaluación las siguientes tareas:</h3>
<ol>
  <li>Detalles de los eventos</li>
  <li>Compra de entradas</li>
  <li>Reventa de las entradas</li>
  <li>Compra de entradas revendidas</li>
  <li>Creación de eventos</li>
  <li>Gestión de entradas</li>
  <li>Mandado de invitaciones</li>
  <li>Publicación de eventos</li>
</ol>
<h4>ESCALA DE SEVERIDAD:</h4>
<p>Los errores serán puntuados tomando en cuenta la siguiente escala de severidad:</p>
<table>
  <tr>
    <th>Nivel</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Problema superficial: puede ser fácilmente superador por el usuario u ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente reléase.</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta.</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.</td>
  </tr>
</table>
<h4>TABLA RESUMEN:</h4>
<table>
  <tr>
    <th>#</th>
    <th>Problema</th>
    <th>Escala de severidad</th>
    <th>Heurística/Principio violada(o)</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Opción de “recordarme” en la zona de registro</td>
    <td>1</td>
    <td>Usability: Consistencia y estándares</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Las opciones Register y Login permanecen luego de iniciar sesión</td>
    <td>1</td>
    <td>Usability: Feedback y estado del sistema</td>
  </tr>
  <tr>
    <td>3</td>
    <td>No hay zona para actualizar contraseña</td>
    <td>1</td>
    <td>Usability: Control y libertad del usuario</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Las opciones de Cancelar y Renovar suscripción aparecen incluso cuando no tienes ninguna.</td>
    <td>1</td>
    <td>Usability: Consistencia y estándares</td>
  </tr>
  <tr>
    <td>5</td>
    <td>La zona de compra de suscripción no acepta números de tarjeta de débito/crédito</td>
    <td>4</td>
    <td>Usability: Flexibilidad y eficiencia de uso</td>
  </tr>
  <tr>
    <td>6</td>
    <td>La zona de renovación de suscripción no acepta números de tarjeta de débito/crédito</td>
    <td>4</td>
    <td>Usability: Flexibilidad y eficiencia de uso</td>
  </tr>
</table>
    
<h4>DESCRIPCIÓN DE PROBLEMAS:</h4>
<h5>PROBLEMA #1: Opción de “recordarme” en la zona de registro</h5>
<p>Severidad: 1</p>
<p>Heurística violada: Usabilidad - Consistencia y estándares</p>
<p>Problema:<br>
La opción de “recordarme” no sigue los estándares comunes de usabilidad en la zona de registro, lo que puede causar confusión en los usuarios que están acostumbrados a ver esta opción en la zona de inicio de sesión. Esto afecta la consistencia del diseño de la interfaz y puede reducir la confianza del usuario en el sistema.</p>
<img src="./imagenes/sprint3/Registro.PNG">
<p>Recomendación:<br>
Mover la opción de “recordarme” a la zona de inicio de sesión, donde los usuarios esperan encontrarla, asegurando así una experiencia más coherente y alineada con las prácticas estándar de diseño de interfaces de usuario.</p>

<h5>PROBLEMA #2: Las opciones register y login permanecen luego de iniciar sesión</h5>
<p>Severidad: 1</p>
<p>Heurística violada: Usabilidad - Feedback y estado del sistema</p>
<p>Problema:<br>
Una vez que el usuario ha iniciado sesión, las opciones para "register" y "login" siguen apareciendo en la interfaz. Esto puede causar confusión, ya que el sistema no proporciona un feedback claro del estado actual del usuario. Los usuarios pueden no estar seguros si han iniciado sesión correctamente.</p>
<img src="./imagenes/sprint3/RegisterLogin.PNG">
<p>Recomendación:<br>
Ocultar las opciones de "register" y "login" después de que el usuario haya iniciado sesión y, en su lugar, mostrar opciones relevantes como "perfil" o "cerrar sesión" para reflejar correctamente el estado del sistema.</p>

<h5>PROBLEMA #3: No hay zona para actualizar contraseña</h5>
<p>Severidad: 1</p>
<p>Heurística violada: Usabilidad - Control y libertad del usuario</p>
<p>Problema:<br>
No se proporciona una opción para que los usuarios actualicen su contraseña, lo que limita su capacidad para gestionar su información de seguridad. Esto es crucial para la administración de la cuenta y la seguridad personal.</p>
<img src="./imagenes/sprint3/Contraseña.PNG">
<p>Recomendación:<br>
Agregar una sección en la configuración de la cuenta donde los usuarios puedan actualizar su contraseña de manera fácil y segura, proporcionando instrucciones claras y feedback durante el proceso.</p>

<h5>PROBLEMA #4: La opción de cancelar y renovar suscripción aparece incluso cuando no tienes ninguna</h5>
<p>Severidad: 1</p>
<p>Heurística violada: Usabilidad - Consistencia y estándares</p>
<p>Problema:<br>
La opción para cancelar y renovar suscripción está visible incluso para usuarios que no tienen una suscripción activa. Esto puede causar confusión y lleva a una experiencia inconsistente.</p>
<img src="./imagenes/sprint3/Contraseña.PNG">
<p>Recomendación:<br>
Modificar la interfaz para que la opción de cancelar y renovar suscripción solo sea visible para usuarios con suscripciones activas, mejorando así la claridad y relevancia de las opciones presentadas.</p>

<h5>PROBLEMA #5: La zona de compra de suscripción no acepta números de tarjeta de débito/crédito</h5>
<p>Severidad: 4</p>
<p>Heurística violada: Usabilidad - Flexibilidad y eficiencia de uso</p>
<p>Problema:<br>
Aunque existe una zona para ingresar números de tarjeta de débito/crédito, al intentar completar la compra, se muestra un cuadro de diálogo indicando que el número de tarjeta es incorrecto. Esto frustra a los usuarios y les impide finalizar la compra, afectando la experiencia de usuario y las conversiones.</p>
<img src="./imagenes/sprint3/Compra.PNG">
<p>Recomendación:<br>
Revisar y corregir el proceso de validación de números de tarjeta para asegurarse de que acepta correctamente tarjetas de débito y crédito válidas. Realizar pruebas exhaustivas para garantizar que el sistema reconozca una variedad de tarjetas y proporcionar mensajes de error claros y específicos si hay problemas con los datos ingresados.</p>

<h5>PROBLEMA #6: La zona de renovación de suscripción no acepta números de tarjeta de débito/crédito</h5>
<p>Severidad: 4</p>
<p>Heurística violada: Usabilidad - Flexibilidad y eficiencia de uso</p>
<p>Problema:<br>
Similar al problema de compra de suscripción, en la zona de renovación de suscripción, aunque hay una opción para ingresar números de tarjeta de débito/crédito, el sistema muestra un cuadro de diálogo indicando que el número de tarjeta es incorrecto al intentar renovar. Esto dificulta la renovación de suscripciones y puede resultar en la pérdida de suscriptores.</p>
<img src="./imagenes/sprint3/Compra.PNG">
<p>Recomendación:<br>
Corregir el proceso de validación de números de tarjeta en la zona de renovación de suscripción, asegurándose de que se acepten correctamente tarjetas de débito y crédito válidas. Realizar pruebas para asegurar la funcionalidad y proporcionar mensajes de error claros y útiles para guiar a los usuarios en caso de problemas.</p>

<h1>CONCLUSIONES</h1>
<p>Durante el desarrollo del front end para la aplicación de venta de entradas de eventos "MyEvent", se demostró un compromiso sólido con la implementación eficiente y efectiva de soluciones utilizando tecnología Angular. La elección de utilizar fake APIs a través de db.json para simular el comportamiento de las APIs reales fue una estrategia inteligente que permitió un desarrollo ágil y centrado en los requisitos del cliente. Esta decisión también facilitó la colaboración entre los desarrolladores al proporcionar un entorno controlado y predecible para probar y validar el front end.

El uso de Angular como framework de desarrollo web permitió la creación de una interfaz de usuario dinámica y receptiva, brindando a los usuarios una experiencia fluida al navegar por la aplicación y comprar entradas para eventos. Además, la implementación de fake APIs garantizó que el equipo de desarrollo pudiera trabajar de manera independiente en el front end sin depender de servicios externos, lo que aceleró el proceso de desarrollo y facilitó la iteración y mejora continua del producto.

En resumen, el proyecto de desarrollo del front end para la aplicación de venta de entradas de eventos "MyEvent" fue un éxito gracias a la combinación de tecnología Angular y la implementación inteligente de fake APIs. Esta experiencia no solo demostró la capacidad del equipo para adaptarse y aprovechar las herramientas disponibles de manera efectiva, sino que también sentó las bases para futuros proyectos de desarrollo web con un enfoque similar.</p>
<h1>ANEXOS</h1>
<ul>
    <li>Marches Parra, J., & Granados Romero, A. (2022). Plataforma de compra y venta de entradas para eventos integrada en la tecnología blockchain. [Trabajo final de grado, Grau en Enginyeria Informàtica (Pla 2018), Escola Politècnica Superior d'Enginyeria de Vilanova i la Geltrú]. Universitat Politècnica de Catalunya. http://hdl.handle.net/2117/378090</li>
    <li>
        Lazcano Quintana, I., & Madariaga Ortuzar, A. (2016). El ocio nocturno de la juventud en España. En M.-A. Berthet, I. Lazcano Quintana, L. Lombi, A. Madariaga Ortuzar, A. Ramos Pérez, E. Rodríguez San Julián, A. Sanmartín Ortí, & S. J. Zoltán (Eds.), La marcha nocturna: ¿Un rito exclusivamente español? (pp. 34-95). ISBN 978-84-92454-33-4. https://dialnet.unirioja.es/descarga/articulo/6149003.pdf</li>
</ul>
<h3>5.2.4 Sprint 4</h3>

<h3>5.2.3.1 Sprint Planning 4</h3>
<table>
    <tr>
      <th>Sprint # </th>
      <th>Sprint 4 </th>
    </tr>
    <tr>
      <td><strong>Sprint Planning Background</strong></td>
      <td></td>
    </tr>
    <tr>
      <th>Date</th>
      <th>2024/06/20</th>
    </tr>
    <tr>
      <th>Time</th>
      <th>18:00 PM</th>
    </tr>
    <tr>
      <th>Location</th>
      <th>Discord</th>
    </tr>
    <tr>
      <th>Prepared by</th>
      <th>Luis Alejandro, Zárate Gamarra</th>
    </tr>
    <tr>
      <th>Attendess (to planning meeting)</th>
      <th>Alessandro Joaquin Bernardo Eusebio - u202113640
        Luis Alejandro, Zárate Gamarra	 - U20181H198
        Carmelino Dueñas, Michael Stefano	 - U202212760 
        Gonzales Anaya, Luis Mario	 - u20201C585
        Piero Jhoynner, Muñoz Salcedo	 - u202224446
   </th>
    </tr>
    <tr>
      <th>Sprint 3 Review Summary</th>
      <th>Correcciones realizadas y término del desarrollo de las tareas que corresponden al Sprint 3 </th>
    </tr>
    <tr>
      <th>Sprint 3 Retrospective Summary</th>
      <th>Nueva delimitacion de User Storys. Escaso tiempo para el desarrollo del backend de todos los US planteados.</th>
    </tr>
    <tr>
      <th>Sprint Goal & User Stories</th>
      <th></th>
    </tr>
    <tr>
      <th>Sprint 3 Goal</th>
      <th>Se definieron las Historias de Usuario a considerar, se completó el desarrollo del backend al 100%, se realizó una integración correcta entre el backend y el frontend, y se desplegó el producto final.</th>
    </tr>
    <tr>
      <th>Sprint 3 Velocity</th>
      <th>2 semanas </th>
    </tr>
    <tr>
      <th>Sum of Story Point</th>
      <th>5</th>
    </tr>
  </table>
  <h3>5.2.4.2 Sprint Backlog 4</h3>
<p>El principal objetivo de este Sprint es completar al 100% el backend de las US delimitadas para el correcto funcionamiento del producto.</p>
<table>
    <tr>
     <th>Sprint #</th>
     <th>Sprint 2</th>
   </tr>
    <tr>
     <th>User Story</th>
     <th></th>
     <th>Work-Item/Task</th>
   </tr>
   <tr>
     <th>Id</th>
     <th>Title</th>
     <th>Id</th>
     <th>Title </th>
     <th>Description</th>
     <th>Estimation(Hours)</th>
     <th>Assigned To</th>
     <th>Status (To-do / InProcess / ToReview / Done)</th>
   </tr>
   <tr>
     <th>US03</th>
     <th>Iniciar sesión con una cuenta</th>
     <th>W-01</th>
     <th>Validar datos de usuarios en el backend </th>
     <th>Validación del usuario sea tanto administrador o comprador para el ingreso a la plataforma.
     <th>2 hours</th>
     <th>Michael</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US08</th>
     <th>Compra de boletos</th>
     <th>W-02</th>
     <th>Validar datos de pago en el backend</th>
     <th>Validación de datos y pago en el backend para la compra de boletos</th>
     <th>2 hours</th>
     <th>Alessandro</th>
     <th>Done</th>
   </tr>
   <tr>
     <th>US18</th>
     <th>Crear evento </th>
     <th>W-03</th>
     <th>Validar los datos de creación de eventos en el backend</th>
     <th>Validación de datos en el backend para la creación de eventos
     <th>2 hours</th>
     <th>Luis</th>
     <th>Done</th>
   </tr>
   <tr>
     <th></th>
     <th></th>
     <th>W-04</th>
     <th>Implementar IAM</th>
     <th>Implementación de IAM para garantizar la seguridad y el control de acceso adecuado a los recursos
     </th>
     <th>2 hours</th>
     <th>Michael</th>
     <th>Done</th>
   </tr>
   <tr>
     <th></th>
     <th></th>
     <th>W-05</th>
     <th>Integrar y desplegar el Backend y Frontend</th>
     <th>Desarrollo y Despliegue de Función Integrada (Backend y Frontend)
     <th>2 hours</th>
     <th>Luis</th>
     <th>Done</th>
   </tr>
   <tr>
     <th></th>
     <th></th>
     <th>W-06</th>
     <th>Elaborar la presentación final</th>
     <th>Elaboración de presentación para la expocición final
    </th>
     <th>1 hours</th>
     <th>Piero</th>
     <th>Done</th>
   </tr>
 </table>
 
<h3>5.2.4.3 Development Evidence for Sprint Review</h3>
<p>Los principales avances fueron la elaboración del backend en su totalidad, junto a los endpoints respectivos.</p>
<table>
    <tr>
        <td>Repository</td>
        <td>Branch</td>
        <td>Commit Id</td>
        <td>Commit Message</td>
        <td>Commit Message Body</td>
        <td>Commited on (Date)</td>
    </tr>
    <tr>
        <td>WS52-Open-Source-Grupo-2-MyEvent-Frontend-Final</td>
        <td>main</td>
        <td>988836a83e60f0373c74a16d4e65b8f7764944f3</td>
        <td>feat: Creación de la entidad user y sus archivos de configuración, junto a la integración del IAM</td>
        <td>Creacion del backend de validacion de usuarios</td>
        <td>Commits on Jun 25, 2024</td>
    </tr>
    <tr>
        <td>WS52-Open-Source-Grupo-2-MyEvent-Frontend-Final</td>
        <td>main</td>
        <td>30e9d005088ed29841f60e3c9a68746360db39c5</td>
        <td>feat: Creación de la entidad compra</td>
        <td>Creacion del backend de validación de compra</td>
        <td>Commits on Jun 25, 2024</td>
    </tr>
    <tr>
        <td>WS52-Open-Source-Grupo-2-MyEvent-Backend</td>
        <td>main</td>
        <td>c33472470b7c2531d0b261984bac7ec876268814</td>
        <td>feat: Creacion de la entidad event y sus archivos de configuracion</td>
        <td>Creacion del backend de validación de eventos</td>
        <td>Commits on Jun 25, 2024</td>
    </tr>
     <tr>
        <td>WS52-Open-Source-Grupo-2-MyEvent-Frontend-Final</td>
        <td>feat/security</td>
        <td>c56452470b7c2531d0b207382bac7ec876254267</td>
        <td>feat: register form working with backend endpoints</td>
        <td>Creacion de la rama security para el authorized</td>
        <td>Commits on Jun 26, 2024</td>
    </tr>
    <tr>
        <td>WS52-Open-Source-Grupo-2-MyEvent-Frontend-Final</td>
        <td>feature/backupmain</td>
        <td>t6375920b7c2531d0b207382bac7ec746361937</td>
        <td>feat:implementacion de backup</td>
        <td>implementacion de backup</td>
        <td>Commits on Jun 26, 2024</td>
    </tr>
</table>
<h3>5.2.4.5 Execution Evidence for Sprint Review</h3>
<h4>Prueba de Sign-Up y Sign-In</h4>
<img src="./imagenes/evidence 1.jfif">
<img src="./imagenes/evidence 2.jfif">
<img src="./imagenes/evidence 2.jfif">
<img src="./imagenes/evidence 4.jfif">
<h4>Prueba de la proteccion de un endpoint por un authorized</h4>
<img src="./imagenes/Evidence 5.jfif">
<h3>5.2.4.6 Services Documentation Evidence for Sprint Review</h3>

<table>
  <thead>
    <tr>
      <th>Endpoint</th>
      <th>Verbo HTTP</th>
      <th>Enlace</th>
      <th>Parámetros</th>
      <th>Response</th>
      <th>Explicación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>/api/v1/authentication/sign-up</td>
      <td>POST</td>
      <td><a href="http://localhost:8080/api/v1/authentication/sign-up">http://localhost:8080/api/v1/authentication/sign-up</a></td>
      <td>N/A</td>
      <td>{"id": 4, "name": "user5name", "correo": "user5@gmail.com", "phone": "963693893", "dni": "04014004", "tipoDeCuenta": "user", "premium": "false", "roles": "ROLE_USER"}</td>
      <td>Envia datos del usuario registrado</td>
    </tr>
    <tr>
      <td>/api/v1/authentication/sign-in</td>
      <td>POST</td>
      <td><a href="http://localhost:8080/api/v1/authentication/sign-in">http://localhost:8080/api/v1/authentication/sign-in</a></td>
      <td>N/A</td>
      <td>{"id": 4, "correo": "user5@gmail.com", "token": "eyJhbGciOiJIUzM4NCJ9.eyJzdWIioiJ1c2VyNW5hbWUiLCJpYXQiOjE3MTk0Njc0NDIsImV4cCI6MTcyMDA3MjI0Mn0.4ZA1jmU1ZGw1k0-2hBBHPaLK9X5BWT8b29A89zkZaCVGPpdidZCPwWLL1GTp9Ig"}</td>
      <td>Envia datos del usuario</td>
    </tr>
    <tr>
      <td>/ap/v1/roles</td>
      <td>GET</td>
      <td><a href="http://localhost:8080/api/v1/roles">http://localhost:8080/api/v1/roles</a></td>
      <td>N/A</td>
      <td>N/A</td>
      <td>Prueba de proteccion por un authorized</td>
    </tr>
  </tbody>
</table>
<h3>5.2.4.7 Software Deployment Evidence for Sprint Review</h3>
<p>Logramos deployar con exito nuestra version final del backend integrado al frontend. Para Ello usamos phpMyAdmin.</p>
<img src="./imagenes/deploy1.jpeg">
<img src="./imagenes/deploy2.jpeg">
<img src="./imagenes/deploy3.jpeg">
<img src="./imagenes/deploy5.PNG">

<h3>5.2.4.8 Team Collaboration Insights during Sprint</h3>
<p>Para el trabajo colaborativo nos ayudamos de la herramienta Github y de las ramas y commits que se podían hacer. Además de los merge que unen toda nuestra parte del trabajo, tanto en el backend como en el frontend.</p>
<img src="./imagenes/git 1.PNG">
<img src="./imagenes/git 2.PNG">


<h2>5.3 Validation Interviews</h2>
    <h3>5.3.1. Diseño de Entrevistas.</h3>
    <p><strong>Segmento Cliente:</strong></p>
    <ol>
        <li>¿Qué tan llamativa te resulta nuestra página web?</li>
        <li>¿Qué tan fácil te resulta registrarte e iniciar sesión?</li>
        <li>¿Qué te parece que te muestre al iniciar sesión una oferta para acceder a la versión premium de nuestra aplicación web?</li>
        <li>¿Puedes encontrar toda la información necesaria sobre un evento al hacer clic en él?</li>
        <li>¿Qué tan intuitivo te parece el proceso de selección y compra de entradas?</li>
        <li>¿Has tenido alguna dificultad al intentar transferir entradas a otro usuario?</li>
        <li>¿Encuentras algunas imperfecciones en nuestra plataforma?</li>
    </ol>
    <p><strong>Segmento Organizador:</strong></p>
    <ol>
        <li>
            <p>¿Qué tan intuitivo y sencillo te resultó el proceso de creación de cuenta y gestión de tu perfil? ¿Hay alguna característica o funcionalidad que crees que falta o podría mejorarse?</p>
        </li>
        <li>
            <p>¿Cómo fue tu experiencia al crear y personalizar un evento en la plataforma? ¿Encontraste todas las opciones que necesitabas para ofrecer una experiencia única a los asistentes?</p>
        </li>
        <li>
            <p>¿Qué tan fácil te resultó acceder a la información detallada de los eventos y realizar la compra de entradas? ¿Hubo algún aspecto de la experiencia de compra que te gustaría que fuera diferente o mejorado?</p>
        </li>
        <li>
            <p>¿Qué tipo de estadísticas y análisis te gustaría ver sobre la participación en tus eventos? ¿Cómo crees que esta información te ayudaría a evaluar el éxito de tus eventos y a mejorar la planificación futura?</p>
        </li>
        <li>
            <p>¿Qué te parece la opción de que los clientes puedan revender sus entradas a eventos directamente en la plataforma? ¿Cómo crees que esta funcionalidad impactaría en la asistencia y el manejo de las entradas para los eventos que organizas?</p>
        </li>
    </ol>
    
  <h3>5.3.2 Registro de entrevistas</h3>

<h3>Segmento Organizador de Eventos</h3>
<h4>Nombre: Fernando André Cipriano</h4>
<h4>Entrevistador: Piero Jhoynner Muñoz Salcedo</h4>
<details>
  <summary>Detalles:</summary>
    <ul>
    <li>Género: Masculino</li>
    <li>Edad: 25 años</li>
    <li>Ubicación: Cercado de Lima</li>
  </ul>
</details><br>

  <table style="border: 1px solid gray;">
    <tr>
        <td><img src="./imagenes/foto entrevista A.PNG" alt="Descripción de la imagen"></td>
    </tr>
    <tr><td class="justificado">El entrevistado, quien es organizador de eventos, navegó en nuestra plataforma web y de momento nos comenta que le parecio util e intuitivo el inicio de sesion, y facil al momento de registrarse, afirma que podria mejorar añadiendo informacion en su perfil con relacion al historial de eventos pasados. Nos cuenta que tuvo una buena experiencia al momento de crear un evento y considera fundamental las invitaciones por medio de redes sociales. Ademas, considera que la compra de entradas son faciles y estan bien implementadas y lo unico que le gustaria añadir es el guardado de informacion de pago para mayor facilidad al momento de comprar entradas. Por otro lado, le gustaria que hubieran estadisticas detallas de la participacion e interaccion de las personas que asisten a los eventos para que así pueda tomar deciciones mas estrategicas para futuras fechas. Nos indica que la opcion de revender entradas lo considera muy bueno y no cree que el impacto que tiene fuese negativo, ya que esto aseguraria que el evento tenga mas asistentes, sin desperdiciar alguna entrada.
</td></tr>
    <tr><td>Link de la entrevista: <a href="https://www.youtube.com/watch?v=zWS4qhYYFmY">https://www.youtube.com/watch?v=zWS4qhYYFmY</a></td></tr>
  </table>  

<h4>Nombre: Rodrigo Quispe</h4>
<h4>Entrevistador: Michael Stefano Carmelino Dueñas</h4>
<details>
  <summary>Detalles:</summary>
    <ul>
    <li>Género: Masculino</li>
    <li>Edad: 20 años</li>
    <li>Ubicación: Cercado de Lima</li>
  </ul>
</details><br>

  <table style="border: 1px solid gray;">
    <tr>
        <td><img src="./imagenes/rodrigo.png" alt="Descripción de la imagen"></td>
    </tr>
    <tr><td class="justificado"> Rodrigo ha expresado una opinión favorable sobre la plataforma, destacando su intuición y facilidad de uso, así como la variedad de opciones disponibles para crear eventos únicos. Sin embargo, también ha señalado áreas de mejora, como la visualización de estadísticas relacionadas con la participación en los eventos. Considera que contar con datos más detallados y análisis en tiempo real podría ofrecer a los organizadores una mejor perspectiva sobre el rendimiento de sus eventos y la satisfacción de los asistentes.

Además, Rodrigo ha mencionado la importancia de incorporar una función de reventa de entradas en la plataforma. Esta característica podría impactar positivamente en la gestión de entradas para los eventos organizados, al permitir a los usuarios revender o transferir sus entradas de manera segura y conveniente. Rodrigo sugiere que esta opción podría incrementar la asistencia a los eventos al facilitar a los asistentes la posibilidad de compartir sus entradas con amigos o revenderlas en caso de imprevistos. En resumen, Rodrigo valora la plataforma pero considera que mejoras en estos aspectos podrían potenciar su utilidad para los organizadores.
</td></tr>
    <tr><td>Link de la entrevista: <a href="https://www.youtube.com/watch?v=fdC4Wm_SxVw">https://www.youtube.com/watch?v=fdC4Wm_SxVw</a></td></tr>
  </table>  

  
<h4>Segmento Organizador de eventos</h4>
    <h4>Nombre: Joaquin Paredes</h4>
    <img src="./imagenes/VI1.png" width="400" height="200">
    <p><strong>Link del video: </strong> https://upcedupe-my.sharepoint.com/:v:/g/personal/u202113640_upc_edu_pe/EYxoxcwfW-xGstj_LsHO4OAB-mEsaPiV-p0wKHfwKRk-8w?e=ofvHp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D</p>
    <p>Joaquin como organizador de eventos esta satisfecho con MyEvent, encontrando la plataforma fácil de usar y efectiva. Las sugerencias para mejoras incluyen más opciones de personalización, plantillas prediseñadas para eventos y una opción de 'wishlist' para la compra de entradas. La reventa de entradas es vista como una funcionalidad positiva que puede mejorar la asistencia y la gestión de eventos.</p>


   <h3>Segmento Comprador de Entradas</h3>
<h4>Nombre: Nickol Ariana Sandoval</h4>
<h4>Entrevistador: Piero Jhoynner Muñoz Salcedo</h4>
<details>
  <summary>Detalles:</summary>
    <ul>
    <li>Género: Femenino</li>
    <li>Edad: 22 años</li>
    <li>Ubicación: Cercado de Lima</li>
  </ul>
</details><br>

  <table style="border: 1px solid gray;">
    <tr>
        <td><img src="./imagenes/entrevista B.PNG" alt="Descripción de la imagen"></td>
    </tr>
    <tr><td class="justificado">La entrevistada indica que la plataforma le parecio fabulosa e intuitiva, ademas detallo que el modo de registrarse le parece muy seguro ya que le piden el DNI como medio de registro, ademas le parecio exelente la vista de adquirir membresia premium, ya que los descuentos hacen llamativo a la plataforma web. Indica que al hacer click en un evento le permite ver toda la informacion de esta para convenserse de su compra, ademas nos comenta que le parece facil la adquisicion entradas, ya que los datos que piden son muy pertinentes. Comenta que nunca tuvo la oportunidad de revender una entrada, pero a partir de la experiencia en la plataforma le transmite mas seguridad que hacerlo por sus redes u otros medios. Lo unico que detalla como una imperfeccion es que se coloquen lo precios generales directamente en cada imagen de evento en la pagina de inicio, ya que esto hace que como comprador de entradas se animen por comprar al ver el precio de la entrada pensando que es una vip pero al ingresar a los detalles del evento solo sea para general.
        
</td></tr>
    <tr><td>Link de la entrevista: <a href="https://youtu.be/pt136hPLp-A">https://youtu.be/pt136hPLp-A</a></td></tr>
  </table>
  <h4>Nombre: Jordy Muñoz Salcedo</h4>
<h4>Entrevistador: Piero Jhoynner Muñoz Salcedo</h4>
<details>
  <summary>Detalles:</summary>
    <ul>
    <li>Género: Masculino</li>
    <li>Edad: 24 años</li>
    <li>Ubicación: Cercado de Lima</li>
  </ul>
</details><br>

  <table style="border: 1px solid gray;">
    <tr>
        <td><img src="./imagenes/entrevista 6.PNG" alt="Descripción de la imagen"></td>
    </tr>
    <tr><td class="justificado">El entrevistado comenta que la plataforma le parece algo innovador y con exelente diseño, tambien comenta que le resulta facil iniciar sesion como cualquier otra pagina. Ademas, indica que le parece bien que le informen sobre los beneficios adicionales por subscripcion. Comenta que puede acceder intuitivamente a la informacion y a la compra relacionado al evento que desea asistir. Nos cuenta que no ha pasado por la necesidad de transferir alguna de sus entradas pero en caso suceda quisiera que fuese de la manera mas segura. Por ultimo, comentó que si bien no encuentra fallas en la plataforma, le gustaría que tenga un modo nocturno u otro color de fondo.
        
</td></tr>
    <tr><td>Link de la entrevista: <a href="https://youtu.be/HSkimzoH1ag">https://youtu.be/HSkimzoH1ag</a></td></tr>
  </table>


  <h4>Nombre: Ian Maqcavilca</h4>
<h4>Entrevistador: Michael Stefano Carmelino Dueñas</h4>
<details>
  <summary>Detalles:</summary>
    <ul>
    <li>Género: Masculino</li>
    <li>Edad: 20 años</li>
    <li>Ubicación: San Juan de Miraflores</li>
  </ul>
</details><br>

  <table style="border: 1px solid gray;">
    <tr>
        <td><img src="./imagenes/ianentre.png" alt="Descripción de la imagen"></td>
    </tr>
    <tr><td class="justificado">En la entrevista sale que le gusta nuestra plataforma, que le gusta la paleta de colores, la facilidad y claridad en el proceso de registro, inicio de sesión y compra de entradas para mejorar la experiencia del usuario. Nos sugiere implementar una opción de modo oscuro en la plataforma como mejora adicional para adaptarse a las preferencias de los usuarios.
        
</td></tr>
    <tr><td>Link de la entrevista: <a href="https://www.youtube.com/watch?v=waWT8DyTAdw">https://www.youtube.com/watch?v=waWT8DyTAdw</a></td></tr>
  </table>


<h3>5.3.3 Evaluaciones según heurísticas</h3>
</head>
<body>
<h4 align="center"><b>UX Heuristics & Principles Evaluation</b></h4>
<h4 align="center"><b>Usability – Inclusive Design – Information Architecture</b></h4>
<h5><b>CARRERA:</b> Ingeniería de Software</h5>
<h5><b>CURSO:</b> Desarrollo de Aplicaciones Open Source</h5>
<h5><b>SECCIÓN:</b> WS52</h5>
<h5><b>PROFESORES:</b> Todos</h5>
<h5><b>AUDITOR:</b> Grupo 2</h5>
<h5><b>CLIENTE(S):</b> Gonzales Anaya, Luis Mario</h5>
<h4>SITE o APP A EVALUAR:</b></h4>
    <p>MyEvent</p>
<h4>TAREAS A EVALUAR:</h5>
<ol>
  <li>Creación de una cuenta</li>
  <li>Inicio de sesión</li>
  <li>Visualización de opciones para usuarios no premium</li>
  <li>Visualización de perfil de usuario</li>
  <li>Gestión de sesión y contraseña</li>
  <li>Renovación de la suscripción</li>
  <li>Notificación de cambio de horarios de eventos</li>
  <li>Atención prioritaria en el servicio al cliente</li>
  <li>Recomendación personalizada sobre eventos</li>
</ol>
<h5>No están incluidas en esta versión de la evaluación las siguientes tareas:</h3>
<ol>
  <li>Detalles de los eventos</li>
  <li>Compra de entradas</li>
  <li>Reventa de las entradas</li>
  <li>Compra de entradas revendidas</li>
  <li>Creación de eventos</li>
  <li>Gestión de entradas</li>
  <li>Mandado de invitaciones</li>
  <li>Publicación de eventos</li>
</ol>
<h4>ESCALA DE SEVERIDAD:</h4>
<p>Los errores serán puntuados tomando en cuenta la siguiente escala de severidad:</p>
<table>
  <tr>
    <th>Nivel</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Problema superficial: puede ser fácilmente superador por el usuario u ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente reléase.</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta.</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.</td>
  </tr>
</table>
<h4>TABLA RESUMEN:</h4>
<table>
  <tr>
    <th>#</th>
    <th>Problema</th>
    <th>Escala de severidad</th>
    <th>Heurística/Principio violada(o)</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Opción de “recordarme” en la zona de registro</td>
    <td>1</td>
    <td>Usability: Consistencia y estándares</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Las opciones Register y Login permanecen luego de iniciar sesión</td>
    <td>1</td>
    <td>Usability: Feedback y estado del sistema</td>
  </tr>
  <tr>
    <td>3</td>
    <td>No hay zona para actualizar contraseña</td>
    <td>1</td>
    <td>Usability: Control y libertad del usuario</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Las opciones de Cancelar y Renovar suscripción aparecen incluso cuando no tienes ninguna.</td>
    <td>1</td>
    <td>Usability: Consistencia y estándares</td>
  </tr>
  <tr>
    <td>5</td>
    <td>La zona de compra de suscripción no acepta números de tarjeta de débito/crédito</td>
    <td>4</td>
    <td>Usability: Flexibilidad y eficiencia de uso</td>
  </tr>
  <tr>
    <td>6</td>
    <td>La zona de renovación de suscripción no acepta números de tarjeta de débito/crédito</td>
    <td>4</td>
    <td>Usability: Flexibilidad y eficiencia de uso</td>
  </tr>
</table>
    
<h4>DESCRIPCIÓN DE PROBLEMAS:</h4>
<h5>PROBLEMA #1: Opción de “recordarme” en la zona de registro</h5>
<p>Severidad: 1</p>
<p>Heurística violada: Usabilidad - Consistencia y estándares</p>
<p>Problema:<br>
La opción de “recordarme” no sigue los estándares comunes de usabilidad en la zona de registro, lo que puede causar confusión en los usuarios que están acostumbrados a ver esta opción en la zona de inicio de sesión. Esto afecta la consistencia del diseño de la interfaz y puede reducir la confianza del usuario en el sistema.</p>
<img src="./imagenes/sprint3/Registro.PNG">
<p>Recomendación:<br>
Mover la opción de “recordarme” a la zona de inicio de sesión, donde los usuarios esperan encontrarla, asegurando así una experiencia más coherente y alineada con las prácticas estándar de diseño de interfaces de usuario.</p>

<h5>PROBLEMA #2: Las opciones register y login permanecen luego de iniciar sesión</h5>
<p>Severidad: 1</p>
<p>Heurística violada: Usabilidad - Feedback y estado del sistema</p>
<p>Problema:<br>
Una vez que el usuario ha iniciado sesión, las opciones para "register" y "login" siguen apareciendo en la interfaz. Esto puede causar confusión, ya que el sistema no proporciona un feedback claro del estado actual del usuario. Los usuarios pueden no estar seguros si han iniciado sesión correctamente.</p>
<img src="./imagenes/sprint3/RegisterLogin.PNG">
<p>Recomendación:<br>
Ocultar las opciones de "register" y "login" después de que el usuario haya iniciado sesión y, en su lugar, mostrar opciones relevantes como "perfil" o "cerrar sesión" para reflejar correctamente el estado del sistema.</p>

<h5>PROBLEMA #3: No hay zona para actualizar contraseña</h5>
<p>Severidad: 1</p>
<p>Heurística violada: Usabilidad - Control y libertad del usuario</p>
<p>Problema:<br>
No se proporciona una opción para que los usuarios actualicen su contraseña, lo que limita su capacidad para gestionar su información de seguridad. Esto es crucial para la administración de la cuenta y la seguridad personal.</p>
<img src="./imagenes/sprint3/Contraseña.PNG">
<p>Recomendación:<br>
Agregar una sección en la configuración de la cuenta donde los usuarios puedan actualizar su contraseña de manera fácil y segura, proporcionando instrucciones claras y feedback durante el proceso.</p>

<h5>PROBLEMA #4: La opción de cancelar y renovar suscripción aparece incluso cuando no tienes ninguna</h5>
<p>Severidad: 1</p>
<p>Heurística violada: Usabilidad - Consistencia y estándares</p>
<p>Problema:<br>
La opción para cancelar y renovar suscripción está visible incluso para usuarios que no tienen una suscripción activa. Esto puede causar confusión y lleva a una experiencia inconsistente.</p>
<img src="./imagenes/sprint3/Contraseña.PNG">
<p>Recomendación:<br>
Modificar la interfaz para que la opción de cancelar y renovar suscripción solo sea visible para usuarios con suscripciones activas, mejorando así la claridad y relevancia de las opciones presentadas.</p>

<h5>PROBLEMA #5: La zona de compra de suscripción no acepta números de tarjeta de débito/crédito</h5>
<p>Severidad: 4</p>
<p>Heurística violada: Usabilidad - Flexibilidad y eficiencia de uso</p>
<p>Problema:<br>
Aunque existe una zona para ingresar números de tarjeta de débito/crédito, al intentar completar la compra, se muestra un cuadro de diálogo indicando que el número de tarjeta es incorrecto. Esto frustra a los usuarios y les impide finalizar la compra, afectando la experiencia de usuario y las conversiones.</p>
<img src="./imagenes/sprint3/Compra.PNG">
<p>Recomendación:<br>
Revisar y corregir el proceso de validación de números de tarjeta para asegurarse de que acepta correctamente tarjetas de débito y crédito válidas. Realizar pruebas exhaustivas para garantizar que el sistema reconozca una variedad de tarjetas y proporcionar mensajes de error claros y específicos si hay problemas con los datos ingresados.</p>

<h5>PROBLEMA #6: La zona de renovación de suscripción no acepta números de tarjeta de débito/crédito</h5>
<p>Severidad: 4</p>
<p>Heurística violada: Usabilidad - Flexibilidad y eficiencia de uso</p>
<p>Problema:<br>
Similar al problema de compra de suscripción, en la zona de renovación de suscripción, aunque hay una opción para ingresar números de tarjeta de débito/crédito, el sistema muestra un cuadro de diálogo indicando que el número de tarjeta es incorrecto al intentar renovar. Esto dificulta la renovación de suscripciones y puede resultar en la pérdida de suscriptores.</p>
<img src="./imagenes/sprint3/Compra.PNG">
<p>Recomendación:<br>
Corregir el proceso de validación de números de tarjeta en la zona de renovación de suscripción, asegurándose de que se acepten correctamente tarjetas de débito y crédito válidas. Realizar pruebas para asegurar la funcionalidad y proporcionar mensajes de error claros y útiles para guiar a los usuarios en caso de problemas.</p>
<h3>5.4 Video About-the-Product</h3>
        <td><img src="./imagenes/about the product.PNG" alt="Descripción de la imagen"></td>
    <td>Link del video: <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20181h198_upc_edu_pe/EfGWqHFjsiZHuqV94bJdDZgB1WyCLRTdDVQchXc2HKRuLA?e=wOvQ13&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">https://upcedupe-my.sharepoint.com/:v:/g/personal/u20181h198_upc_edu_pe/EfGWqHFjsiZHuqV94bJdDZgB1WyCLRTdDVQchXc2HKRuLA?e=wOvQ13&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D</a></td>
<h1>CONCLUSIONES</h1>
<p>Durante el desarrollo del front end para la aplicación de venta de entradas de eventos "MyEvent", se demostró un compromiso sólido con la implementación eficiente y efectiva de soluciones utilizando tecnología Angular. La elección de utilizar fake APIs a través de db.json para simular el comportamiento de las APIs reales fue una estrategia inteligente que permitió un desarrollo ágil y centrado en los requisitos del cliente. Esta decisión también facilitó la colaboración entre los desarrolladores al proporcionar un entorno controlado y predecible para probar y validar el front end.

El uso de Angular como framework de desarrollo web permitió la creación de una interfaz de usuario dinámica y receptiva, brindando a los usuarios una experiencia fluida al navegar por la aplicación y comprar entradas para eventos. Además, la implementación de fake APIs garantizó que el equipo de desarrollo pudiera trabajar de manera independiente en el front end sin depender de servicios externos, lo que aceleró el proceso de desarrollo y facilitó la iteración y mejora continua del producto.

En resumen, el proyecto de desarrollo del front end para la aplicación de venta de entradas de eventos "MyEvent" fue un éxito gracias a la combinación de tecnología Angular y la implementación inteligente de fake APIs. Esta experiencia no solo demostró la capacidad del equipo para adaptarse y aprovechar las herramientas disponibles de manera efectiva, sino que también sentó las bases para futuros proyectos de desarrollo web con un enfoque similar.

En el mismo tenor de éxito que se logró en el desarrollo del front end, la creación e implementación del backend para la aplicación "MyEvent" fue igualmente notable. Utilizando JPA (Java Persistence API), se estableció una base de datos robusta y eficiente que gestionó de manera efectiva la persistencia de datos y las operaciones CRUD (Crear, Leer, Actualizar, Borrar). El uso de JPA no solo facilitó la implementación de características críticas, como la gestión de usuarios y el seguimiento de eventos, sino que también aseguró que la aplicación fuera escalable y preparada para futuras expansiones.

En conclusion, el equipo demostró una exelente comunicación y coordialidad durante lo largo del proyecto, en la documentación se vió reflejado la objetividad y claridad, tanto como en el despliegue del sistema de gestion de identidades y accesos(IAM) para las funcionalidades de login y sign up, como en la implementación del backend y su integración con el frontend. </p>
<h1>Video About-the-Team</h1>
<p>En resumen, el grupo evidenció una adecuada coordialidad y comunicación conjunta, lo cual permitió llegar exitosamente a la etapa final del proyecto a pesar de contar con inconvenientes por incumplimientos por parte de algunos integrantes. Ademas, un aspecto a tomar en cuenta es la falta de consulta por parte de los integrantes del equipo en cuanto a los frameworks y diversas herramientas que se usaron durante el desarrollo del proyecto, el cual llevo al replanteo del proyecto de cara a la entrega final. Sin embargo, esto sin duda nos sirvirá como aprendizaje para entregas futuras. </p>
 <td><img src="./imagenes/about-the-team.PNG" alt="Descripción de la imagen"></td>
    <td>Link del video: <a href="https://www.youtube.com/watch?v=k4VuP4pdqqo">https://www.youtube.com/watch?v=k4VuP4pdqqo</a></td>
<h1>ANEXOS</h1>
<ul>
    <li>Marches Parra, J., & Granados Romero, A. (2022). Plataforma de compra y venta de entradas para eventos integrada en la tecnología blockchain. [Trabajo final de grado, Grau en Enginyeria Informàtica (Pla 2018), Escola Politècnica Superior d'Enginyeria de Vilanova i la Geltrú]. Universitat Politècnica de Catalunya. http://hdl.handle.net/2117/378090</li>
    <li>
        Lazcano Quintana, I., & Madariaga Ortuzar, A. (2016). El ocio nocturno de la juventud en España. En M.-A. Berthet, I. Lazcano Quintana, L. Lombi, A. Madariaga Ortuzar, A. Ramos Pérez, E. Rodríguez San Julián, A. Sanmartín Ortí, & S. J. Zoltán (Eds.), La marcha nocturna: ¿Un rito exclusivamente español? (pp. 34-95). ISBN 978-84-92454-33-4. https://dialnet.unirioja.es/descarga/articulo/6149003.pdf</li>
</ul>






