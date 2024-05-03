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
                    <td>00:00 am</td>
                </tr>
                <tr>
                    <td>Location</td>
                    <td>Google Meet</td>
                </tr>
                <tr>
                    <td>Prepared By</td>
                    <td>Godofredo Quispe Tipo</td>
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
    <th>Michael</th>
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
    <th>Piero</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US-04</th>
    <th>Visualizar una sección de contacto</th>
    <th>W-04</th>
    <th>Sección de contacto</th>
    <th>Como usuario, quiero una seccion donde pueda observar tarjetas de presentacion de personas con las cuales pueda comunicarme relacionadas con la empresa.</th>
    <th>3 hours</th>
    <th>Mario</th>
    <th>Done</th>
  </tr>
  <tr>
    <th>US-05</th>
    <th>Visualización de elementos Call to Action</th>
    <th>W-05</th>
    <th>Elementos call to action</th>
    <th>Como visitante, quiero poder observar dentro de la landing page algun elemento que pueda dirijirme directamente a la descarga o uso de la aplicacion que promueve esta landing page</th>
    <th>30 minutes</th>
    <th>Alessandro</th>
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
Registro de usuario:
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/9a4fbf95-c832-4e19-a6df-9a0c013722e8>
Ingreso de usuario:
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/da88db46-8844-4c7c-b92b-4e7dcda6371e>
Ingreso de fecha de publicacion del evento:
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/0ccf3c98-e90d-4dbc-9167-7f0ec1626e00>
Añadiendo evento:
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/8185c700-0e34-43ec-9905-9f0765532e80>
Descripcion del Evento:
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/ad5b917f-4805-4f87-a254-c9088fe44ee8>
Registro de Evento Confirmado:
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
