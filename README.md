# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.

A continuación, daremos a conocer los productos de software que hemos utilizado para el desarrollo de nuestro proyecto.

**Project Management**				

- **Whatsapp:** [https://web.whatsapp.com/](https://web.whatsapp.com/)

    La plataforma de Whatsapp se empleó para realizar la organización de tareas para el equipo, así como también para poder ayudarnos entre nosotros ante cualquier duda que se tuviera en el trabajo.
- **Discord:** [https://discord.com/](https://discord.com/)

    La plataforma Discord se empleó para poder realizar las reuniones de forma virtual, en dichas reuniones dábamos un reporte sobre el avance de las tareas que se nos habían asignado, así como también se usó para la elaboración de idea de negocio.

**Product UX/UI Design**

- **Miro:** [https://www.miro.com](https://www.miro.com)
    
    La plataforma Miro se empleó para el desarrollo del Lean ux canvas, Análisis de competidores,  As-is Scenario mapping, To-be Scenery mapping.

- **Uxpresia:** [https://uxpressia.com/**](https://uxpressia.com/)

    La plataforma Uxpresia se empleó para la elaboración del User Persona, Empathy maps, Journey Maps e Impact maps.

- **Figma:** [https://www.figma.com/](https://www.figma.com/)

    La plataforma figma se empleó para el desarrollo wireframes y mock up del landing page, y para los wireframes, mock up y prototyping del web applications. 

**Software Development**

- **Landing Page**

  Para el desarrollo de nuestro landing page se usará HTML5, CSS y Javascript.

- **Frontend Web Application**

  Se ha utilizado a Angular como framework de Javascript. En adición, para la implementación de componentes reutilizables y accesibles se usó Angular Material como biblioteca de componentes UI. 

**Software Testing**

Para la realización de pruebas de testeo de software  que se ha utilizado para el landing page y  la aplicación web hemos empleado las herramientas de desarrollador de los siguientes navegadores web: Google Chrome (<https://www.google.com/chrome/>), Microsoft Edge (<https://www.microsoft.com/en-us/edge>) y Mozilla Firefox (<https://www.mozilla.org/en-US/firefox/browsers/>). Asimismo, dichos navegadores cuentan con aplicaciones desktop y móviles las cuales son totalmente gratuitas y por consiguientes accesible para todas las personas.

**IDE's de desarrollo**

- **Webstorm:** [https://www.jetbrains.com/webstorm/](https://www.jetbrains.com/webstorm/)

    Webstorm es un IDE enfocado al desarrollo de frontend y posee una gran cantidad de herramientas que pueden agilizar el proceso de desarrollo. Para poder usar Webstorm es necesario tener una licencia

**Software Deployment**

- **Github Pages:** [https://pages.github.com/?(null)](https://pages.github.com/?\(null\))

    La plataforma Github pages se empleó para el deployment del landing page, para ello fue necesario vincular el repositorio de github con github pages. De esta manera, Github Pages se encargará automáticamente del deploy de la página.

**Software Documentation**

- **Github:** [https://github.com/](https://github.com/)

    La plataforma Github se empleó para la creación de documentación de nuestro proyecto, así como del landing page. Se optó por esta plataforma porque permite el desarrollo colaborativo entre desarrolladores. La evidencia de commits demuestra la participación que ha tenido cada uno de los integrantes en el desarrollo del proyecto.

- **Structurizr:** [https://structurizr.com/](https://structurizr.com/)

    La plataforma Structurizr se empleó para la creación de los diagramas C4 de nuestro proyecto, para la elaboración de los diagramas se necesita emplear una sintaxis similar a un lenguaje de programación.

- **Vertabelo:** [https://vertabelo.com/](https://vertabelo.com/)

    La plataforma Vertabelo es una aplicación web colaborativa la cual ha sido empleada para la elaboración del diseño de base de datos.

### 5.1.2. Source Code Management.
El gitjab donde tengamos el proyecto

### 5.1.3. Source Code Style Guide & Conventions.

**HTML:** [https://www.w3schools.com/html/html5_syntax.asp](https://www.w3schools.com/html/html5_syntax.asp)

**Index.html:**
Es la página por defecto dentro de los directorios de los servidores de cualquier sitio web que se carga siempre que se solicita un dominio y no se especifica el nombre de un archivo en específico. Y en la mayoría de los casos el propio servidor web es el que se encarga de buscar el archivo index.
**Convenciones de HTML:**

- Se debe declarar el tipo de documento en la primera línea: < !DOCTYPE html >
- Se recomienda usar minúsculas en las etiquetas y estructuras: < body > < p >
- Se recomienda cerrar todas las etiquetas y estructuras: < p >This is a paragraph. < /p >
- Se recomienda usar minúsculas en los atributos: < a href="https://www.google.com/html/" >
- Se recomienda usar comillas en los valores de atributo: < table class="striped" >
- Se debe especificar el alt, ancho y alto de las imágenes: < img src="html5.gif" alt="HTML5" style="width:128px; height:128px" >
- Se recomienda no usar espacios a la hora de usar el signo “=”: < link rel="stylesheet" href="styles.css" >
- Solo se debe usar líneas en blaco para facilitar la lectura de bloques de códigos grandes o lógicos
- No se debe omitir el elemento < title > ya que es vital para el motor de búsqueda, así como también se recomienda que el contenido de los < title > sea preciso y significativo: < title >HTML Style Guide and Coding Conventions< /title >
- No se recomienda omitir las etiquetas < html > y < body > ya que puede producir errores en navegadores antiguos y puede bloquear el software DOM y XML.
- Se debe usar el atributo lang para declarar el idioma de la página web: < html lang="en-us" >
- Se debe utilizar el atributo meta para una interpretación adecuada e indexación correcta en los motores de búsqueda: < meta charset="UTF-8" >

**CSS:** [https://google.github.io/styleguide/htmlcssguide.html](https://google.github.io/styleguide/htmlcssguide.html)

**Style.css:**
El estilo de cascada (CSS) se puede usar para estilos de texto, por ejemplo, cambiar de color y el tamaño de los encabezados, enlaces, entre otras cosas.

**Convenciones de CSS**

- Utilizar el protocolo HTTPS para imágenes y otros archivos multimedia: @import 'https://fonts.googleapis.com/css?family=Open+Sans’; Todo el código debe estar en minúsculas como nombres de elementos HTML, atributos, valores de atributo, entre otros: color: #e5e5e5;
- El nombre de una clase debe transmitir lo que hace de la forma más breve posible ya que de esta manera se apoya la comprensibilidad y eficiencia del código: navegación {}. autor {} Se debe separar los nombres de las clases con un guion (“-”): navegación {}. autor {}
- Se recomienda usar propiedades abreviadas cuando sea posible: border - top: 0;
- Se recomienda usar la notación hexadecimal de 3 caracteres en colores que lo permitan: color: #ebc;
- Se recomienda ordenar las declaraciones de propiedades y características en orden alfabético
- Se debe usar un “;” después de cada declaración: pantalla: bloque;
- Se debe usar un espacio después de los “:” de cada nombre de la propiedad: font – weight-bold;
- Se debe usar un espacio entre el último sector y la llave “ { “que comienza el bloque de declaración: vídeo {…}
- Se debe usar las comillas simples (‘ ‘) para los atributos y valores de propiedad: familia de fuentes : ' open sans', arial, sans - serif ;

**Gherkin:** [https://cucumber.io/docs/gherkin/reference/](https://cucumber.io/docs/gherkin/reference/)

**< usertStoryID >.featrue:**

En este archivo de formato feature estarán las historias de usuario como características de la aplicación. Asimismo, se pueden encontrar los criterios de aceptación para las diversas situaciones. 
**Convenciones de Gherkin:**

- Se utiliza la palabra Feature para introducir una descripción de alto nivel de una función de software y agruparlos en escenarios relacionados
- Example o Scenario sirven para plantear una situación
- Se utiliza Given para describir el contexto inicial, When para describir un evento y Then para describir un resultado esperado y And para adicionar información. Given,When,Then y And se usan para describir un escenario
- El carácter “|” sirve para formar una tabla datos, las cuales son útiles para pasar una lista de valores a una definición de paso.

**Java:** [https://google.github.io/styleguide/javaguide.html](https://google.github.io/styleguide/javaguide.html)

**Convenciones de Java:**

- Los nombres de clases y tipos deben ser sustantivos en mayúscula inicial.
- Los nombres de los métodos deben ser minúsculas.
- El nombre de las variables debe ser en minúsculas y usar camel case.
- Para las sentencias if,else,for,do y while se deben usar “ { } “.
- Los nombres de variables que son Constantes deben ir en mayúsculas

**JavaScript:** [https://google.github.io/styleguide/jsguide.html](https://google.github.io/styleguide/jsguide.html)

**Convenciones de JavaScript:**

- Se debe usar Camelcase para los nombres de variables y funciones.
- Se debe usar Pascalcase para los nombres de constructores o clases.
- Se debe usar mayúsculas y guiones bajos para los nombres de las constantes, por ejemplo, UPPER\_CASE\_WITH\_UNDERSCORES.
- Se debe usar let y const para definir las variables, var debe evitarse.
- Para los comentarios de una sola línea debe usar “ // ” y para bloques de comentario se debe usar  “ /* */ ”.
- Se debe incluir un punto y coma al final de cada instrucción.

**TypeScript:** [https://google.github.io/styleguide/tsguide.html](https://google.github.io/styleguide/tsguide.html)

**Convenciones de TypeScript:**

- Se debe usar Camelcase para los nombres de variables y funciones.
- Se debe usar Pascalcase para los nombres de interfaces o clases.
- Se debe usar number para valores numéricos, string para cadenas de texto y boolean para los valores booleanos.
- Se debe usar const para las constantes.
- Se debe usar extends para la herencia 
- Se debe usar implements para la implementación de interfaces
- Se debe usar por imports y exports para modularizar el código
- Se debe usar “ | ” para la unión y “ & ” para las intersecciones

**Spring Boot:** [https://docs.spring.io/spring-boot/docs/current/reference/html/features.html](https://docs.spring.io/spring-boot/docs/current/reference/html/features.html)

**Convenciones de Spring Boot:**

- Se debe emplear @Controller, @Service, @Repository, @Component, @Autowired, entre otros más, para poder definir y gestionar los componentes de Spring.
- Para el manejo de excepciones se debe hacer uso de @ControllerAdvice y @ExceptionHandler para poder gestionar los errores de manera consistente.
- Se debe usar @Transactional para gestionar las transacciones.
- En el caso que se quiera gestionar la autenticación y autorización de una aplicación, se debe usar Spring Security.
- Se debe usar nombre de paquetes y clases descriptivas que reflejan la funcionalidad de los componentes.

**Angular:** [https://angular.io/guide/styleguide](https://angular.io/guide/styleguide)

**Convenciones de Angular:**

- Se debe usar kebab-case para los nombres de archivos y carpetas, por ejemplo: my-component.component.ts.
- Se debe usar UpperCamelCase para nombrar clases y componentes, por ejemplo: MyComponent
- Se debe usar camelCase para nombrar propiedades y métodos, por ejemplo:myProperty, myMethod().
- Se debe evitar las dependencias circulares entre módulos y componentes.
- Se recomienda usar Typescript en vez de Javascript para poder aprovechar la verificación de tipos estáticos.
- Es recomendable habilitar el modo estricto de Typescript: strict: true en tsconfig.json.

### 5.1.4. Software Deployment Configuration.
Configuraciones de donde y como deployeamos el proyecto
## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1.


<table>
     <tr> 
        <th>  Sprint #  </th>
        <th> Sprint 1 </th>
     </tr>
     <tr> 
        <td style="font-weight: bold;" colspan="7"> Sprint Planing Background</td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Date </td>
       <td> 26/08/2024 </td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Time </td>
       <td> 11:00 horas (GMT-5) </td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Location </td>
       <td> Modalidad remota a través de la plataforma Whatsapp <td>
     </tr>
      <tr>
        <td style="font-weight: bold;"> Prepared By </td>
        <td> Webworks <td>
     </tr>
        <tr>
        <td style="font-weight: bold;"> Attendees (to planning meeting) </td>
        <td> Zavala Quedena, Gonzalo Andre
        <br>
          Arroyo Ormeño, André Alonso
           <br>
          Principe Godoy, Johan
          <br>
          Espino Flores, Alejandro
          <br>
	        Aiquipa Poma, Sebastian Andres
         <td>
     </tr>
     <tr>
        <td style="font-weight: bold;"> Sprint 0 Review Summary </td>
        <td> Dado que se trata del primer sprint, no hay un review summary de un sprint anterior.<td>
     </tr>
     <tr>
        <td style="font-weight: bold;"> Sprint 1 Retrospective Summary </td>
        <td> Dado a que nos encontramos en nuestro primer sprint, aun no identifcamos planes de mejora.<td>
     </tr>
     <tr> 
        <td style="font-weight: bold;" colspan="7"> Sprint Goal & User Stories</td>
     </tr>
       <tr>
          <td style="font-weight: bold;"> Sprint 1 Goal</td>
          <td> En este sprint se espera implementar la landing page de la aplicación web y la startup. Al finalizar este sprint, la landing page debe estar desplegada en Netlifly y cualquier usuario debería poder acceder y visualizar la página a través de un link. <td>
      </tr>
       <tr>
          <td style="font-weight: bold;"> Sprint 1 Velocity </td>
          <td> 11 <td>
      </tr>
      <tr>
          <td style="font-weight: bold;"> Sum of Story Points </td>
          <td> 11 <td>
      </tr>

  </table>

#### 5.2.1.2. Sprint Backlog 1.

<table><tr><th colspan="2" valign="top"><a name="_6cxtvwxzjfs6"></a><b>SPRINT</b></th><th colspan="6" valign="top"><b>SPRINT 1</b></th></tr>
<tr><td colspan="2" valign="top"></td><td colspan="6" valign="top"><b>Work-Item / Task</b></td></tr>
<tr><td valign="top"><b>User Story ID</b></td><td valign="top"><b>Title</b></td><td valign="top"><b>id</b></td><td valign="top"><b>Title</b></td><td valign="top"><b>Description</b></td><td valign="top"><b>Tiempo (horas)</b></td><td valign="top"><b>Assigned to</b> </td><td valign="top"><b>Status (to-do/ in process/ To review/ done)</b></td></tr>
<tr><td rowspan="2" valign="top">E1-US101</td><td rowspan="2" valign="top">Barra de navegación del Landing Page</td><td valign="top">T1</td><td valign="top">Navbar section</td><td valign="top">Implementación del navbar con botón de ingreso a la aplicación AgroControl.</td><td valign="top">2</td><td valign="top">Alejandro Espino</td><td valign="top">Done</td></tr>
<tr><td valign="top">T2</td><td valign="top">Responsive design navbar section</td><td valign="top">Añadir el diseño responsive para la barra de navegación</td><td valign="top">3</td><td valign="top">Alejandro Espino</td><td valign="top">Done</td></tr>
<tr><td rowspan="2" valign="top">E1-US102</td><td rowspan="2" valign="top">Sección hero de landing page</td><td valign="top">T3</td><td valign="top">Hero section</td><td valign="top">Implementación del apartado hero section</td><td valign="top">2</td><td valign="top">Alejandro Espino</td><td valign="top">Done</td></tr>
<tr><td valign="top">T4</td><td valign="top">Responsive design hero section</td><td valign="top">Añadir el diseño responsive para la hero section</td><td valign="top">2</td><td valign="top">Alejandro Espino</td><td valign="top">Done</td></tr>
<tr><td rowspan="2" valign="top">E1-US103</td><td rowspan="2" valign="top">Sección Caracteristicas del producto de landing page</td><td valign="top">T5</td><td valign="top">Features section</td><td valign="top">Implementar sección de características de la aplicación.</td><td valign="top">1</td><td valign="top">Johan Principe</td><td valign="top">Done</td></tr>
<tr><td valign="top">T6</td><td valign="top">Responsive design features section</td><td valign="top">Añadir el diseño responsive para la features section</td><td valign="top">2</td><td valign="top">Johan Principe</td><td valign="top">Done</td></tr>
<tr><td rowspan="2" valign="top">E1-US104</td><td rowspan="2" valign="top">Sección de testimonios en landing page</td><td valign="top">T7</td><td valign="top">Testimonials section</td><td valign="top">Implementar las tarjetas con los testimonios de los usuarios.</td><td valign="top">1</td><td valign="top">Gonzalo Zavala</td><td valign="top">Done</td></tr>
<tr><td valign="top">T8</td><td valign="top">Responsive design  testimonials section</td><td valign="top">Añadir el diseño responsive para la sección de testimonios</td><td valign="top">1.5</td><td valign="top">Gonzalo Zavala</td><td valign="top">Done</td></tr>
<tr><td rowspan="2" valign="top">E1-US105</td><td rowspan="2" valign="top">Sección de planes en landing page</td><td valign="top">T19</td><td valign="top">Pricing section</td><td valign="top">Implementar sección de membresía de acuerdo al segmento.</td><td valign="top">3</td><td valign="top">Andre Arroyo</td><td valign="top">Done</td></tr>
<tr><td valign="top">T10</td><td valign="top">Responsive design  pricing section</td><td valign="top">Añadir el diseño responsive para la sección</td><td valign="top">2</td><td valign="top">Andre Arroyo</td><td valign="top">Done</td></tr>
<tr><td rowspan="2" valign="top">E1-US106</td><td rowspan="2" valign="top">Sección de footer a la aplicación en landing page</td><td valign="top">T11</td><td valign="top">Footer section</td><td valign="top">Implementación del footer</td><td valign="top">2</td><td valign="top">Alejandro Espino</td><td valign="top">Done</td></tr>
<tr><td valign="top">T12</td><td valign="top">Responsive design  footer section</td><td valign="top">Añadir el diseño responsive para la sección</td><td valign="top">2</td><td valign="top">Alejandro Espino</td><td valign="top">Done</td></tr>
<tr><td rowspan="2" valign="top">E1-US107</td><td rowspan="2" valign="top">Sección para conocer al equipo de trabajo</td><td valign="top">T1</td><td valign="top">Team presentation section</td><td valign="top">Implementar sección con contactos del equipo de trabajo</td><td valign="top">3</td><td valign="top">Se hizo xd?</td><td valign="top">Done</td></tr>
<tr><td valign="top">T2</td><td valign="top">Responsive design  team presentation section</td><td valign="top">Añadir el diseño responsive para la sección</td><td valign="top">2</td><td valign="top">Se hizo xd?</td><td valign="top">Done</td></tr>
</table>

#### 5.2.1.3. Development Evidence for Sprint Review.

| Repository                | Branch                    | Commit ID | Commit Message                              | Commit Message Body | Commited On(Date) |
|---------------------------|---------------------------|-----------|---------------------------------------------|---------------------|-------------------|
| agrocontrol-landing-page  | feature/about-the-product | 1f5b64e   | refactor: improve styles for responsiveness | -                   | 05/09/2024        |
| agrocontrol-landing-page  | feature/app-features      | 7fea01d   | refactor: improve css styles.               | -                   | 05/09/2024        |
| agrocontrol-landing-page  | feature/contact           | 7fea01d   | refactor: improve css styles.               | -                   | 05/09/2024        |
| agrocontrol-landing-page  | feature/footer            | 7fea01d   | refactor: improve css styles.               | -                   | 05/09/2024        |
| agrocontrol-landing-page  | feature/hero              | 1f5b64e   | refactor: improve styles for responsiveness | -                   | 05/09/2024        |
| agrocontrol-landing-page  | feature/nav-bar           | 84ed335   | feat: add styles                            | -                   | 05/09/2024        |
| agrocontrol-landing-page  | feature/plans             | 7fea01d   | refactor: improve css styles.               | -                   | 05/09/2024        |
| agrocontrol-landing-page  | feature/user-testimonials | 01d4b8c   | feat(hero): added hero section              | -                   | 03/09/2024        |

#### 5.2.1.4. Testing Suite Evidence for Sprint Review.

Se llevaron a cabo pruebas preliminares para verificar la correcta visualización y funcionamiento de la landing page en diferentes dispositivos y navegadores.

#### 5.2.1.5. Execution Evidence for Sprint Review.

<img src="https://github.com/W3bW0rks/project-report/blob/d64dbc887ef135023a4ee13adeff39df2de6859f/assets/chapter-5-images/AgroControlLanding.png" alt="AgroControl LandingPage image">

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

En este primer Sprint nos enfocamos únicamente en crear el landing page, sin necesidad de utilizar servicios extra.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Para el sprint presentado de la landing page se optó por varias herramientas para su desarrollo y despliegue en la web de manera pública.

* Git: Se utilizó para el control de versiones del código fuente.
* GitFlow: Se utilizó para ver el avance de los integrantes del equipo.
* GitHub: Se utilizó para crear el repositorio de la landing page, donde se subió el código fuente.
* Vercel: Se utilizó esta herramienta ya que nos ofrece un despliegue sin costo de manera rápida y fácil, además que se puede vincular directamente con el repositorio de GitHub.



#### 5.2.X.8. Team Collaboration Insights during Sprint.
![Sprint review Team Collaboration Insights](image.jpg) imagenes de colaboraciones github

## 5.3. Validation Interviews.
### 5.3.1. Diseño de Entrevistas.
**Preguntas generales:**

1. ¿Cuál es su nombre?
2. ¿Qué edad tiene?
3. ¿A qué se dedica?
4. ¿[Opinion de idea de propuesta]?

**Entrevistas usuario segmento 2**
1. ¿Lorem?
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem?

**Entrevistas usuario segmento 2**
1. ¿Lorem?
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem?
### 5.3.2. Registro de Entrevistas.
**Segmento 1**  
Nombre: _____
Edad: _ años
Ocupación: _____  
![Imagen de entrevista](image.jpg)  
{texto mucho}

**Segmento 2**  
Nombre: _____
Edad: _ años
Ocupación: _____  
![Imagen de entrevista](image.jpg)
{texto}
### 5.3.3. Evaluaciones según heurísticas.
| HEURÍSTICA   | EVALUACIÓN ✅❌ | NOTA      |
| --------------------------------------------- | ---------- | --------- |
| Visibilidad del estado del sistema            |            | {texto}   |
| Coincidencia entre el sistema y el mundo real |            | {texto}   |
| Control y libertad del usuario                |            | {texto}   |
| Consistencia y estándares                     |            | {texto}   |
| Prevención de errores                         |            | {texto}   |
| Mostrar antes que recordar                    |            | {texto}   |
| Flexibilidad y eficiencia de uso              |            | {texto}   |
| Diseño estético y minimalista                 |            | {texto}   |
| Comunicar errores con facilidad               |            | {texto}   |
| Ayuda y documentación                         |            | {texto}   |
## 5.4. Video About-the-Product.
[URL del video about the product](https://www.example.com)
