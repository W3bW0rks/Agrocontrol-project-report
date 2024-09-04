# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
Descripcion del porque estos elementos seran importantes

### Colores
La paleta de colores de **AgroControl** se compone de cuatro colores principales:

| Color Name      | Hex Code | RGB             | Uso Principal                        |
|-----------------|----------|-----------------|--------------------------------------|
| White           | #FFFFFF  | rgb(255, 255, 255) | Texto en fondos oscuros, fondos secundarios |
| Midnight Green  | #043A3A  | rgb(4, 58, 58)    | Fondos primarios, encabezados         |
| Emerald         | #2FB95D  | rgb(47, 185, 93)  | Botones, elementos destacados         |
| Davy's Gray     | #525252  | rgb(82, 82, 82)   | Texto en fondos claros, bordes       |

<p align="center">
  <img src="https://github.com/W3bW0rks/project-report/blob/e58070de24f0f16b5b579c75224f5d9461bd8bef/assets/chapter-4-images/colors.png" alt="colors-style-guidelines">
</p>

### Tipografía
Se emplean dos fuentes principales en toda la identidad visual de AgroControl:

- **Raleway**: Usada para títulos, subtítulos y elementos destacados.
  - Tamaños utilizados: 
    - 64px para títulos principales.
    - 38px para subtítulos.
    - 21px para encabezados menores.

- **Mulish**: Utilizada para el cuerpo de texto y subtítulos menores.
  - Tamaños utilizados:
    - 16px para el cuerpo del texto y descripciones.



### Marca
El logotipo principal de **AgroControl** está compuesto por las palabras "Agro" y "Control". La palabra "Agro" se muestra en color blanco (#FFFFFF) y la palabra "Control" en color esmeralda (#2FB95D). El logotipo se presenta en dos variaciones principales:

1. **Color completo:** Utilizado en fondos claros.
2. **Versión invertida:** Utilizado en fondos oscuros, con la palabra "Agro" en blanco y "Control" en esmeralda.



<p align="center">
  <img src="https://github.com/W3bW0rks/project-report/blob/36ceb2415864a6b2c2a7f84f538e6d2743f9f3f3/assets/chapter-4-images/logo-agro.png" alt="logo-agrocontrol">
</p>

## Background

**Fondos Primarios, Secundarios y Terciarios**  
Utilizamos una combinación de colores para los fondos según el propósito de la sección:

- **Fondo Primario:** Midnight Green (#043A3A)
- **Fondo Secundario:** Blanco (#FFFFFF)
- **Fondo Terciario:** Davy's Gray (#525252)

## Text Styles

**Estilos de Texto**  
Los estilos de texto siguen la jerarquía visual y la tipografía especificada en las pautas generales:

- **H1:** 64px, Raleway, Midnight Green (#043A3A)
- **H2:** 38px, Raleway, Midnight Green (#043A3A)
- **H3:** 24px, Raleway, Midnight Green (#043A3A)
- **Párrafo (p):** 16px, Mulish, Davy's Gray (#525252)
- **Enlaces (a):** 16px, Mulish, Emerald (#2FB95D) 


![Text-styles](https://github.com/W3bW0rks/project-report/blob/36ceb2415864a6b2c2a7f84f538e6d2743f9f3f3/assets/chapter-4-images/font-sizes.png)



## Button Styles

**Estilos de Botón y Controles**  
Los botones y otros controles interactivos tienen una apariencia clara y coherente:

- **Botón Principal:** Fondo esmeralda (#2FB95D), texto blanco (#FFFFFF)
- **Botón Secundario:** Fondo blanco (#FFFFFF), borde esmeralda (#2FB95D), texto esmeralda (#2FB95D)
- **Dropdowns y Switches:** Combina Davy's Gray (#525252) para fondo y esmeralda (#2FB95D) para acentos



![Buttons-1](https://github.com/W3bW0rks/project-report/blob/36ceb2415864a6b2c2a7f84f538e6d2743f9f3f3/assets/chapter-4-images/button-style1.png)
![Buttons-2](https://github.com/W3bW0rks/project-report/blob/36ceb2415864a6b2c2a7f84f538e6d2743f9f3f3/assets/chapter-4-images/button-style2.png)


## Icons

**Iconos**  
Los iconos utilizados están diseñados para un fondo blanco (#FFFFFF) con acentos en Midnight Green (#043A3A) y esmeralda (#2FB95D).

## Misc

**Componentes Misceláneos**  
Esta categoría incluye elementos como la barra de navegación, carruseles y otros componentes interactivos.

- **Nav Bar:** Fondo Midnight Green (#043A3A) con enlaces en blanco (#FFFFFF)
- **Slideshow:** Transiciones suaves con botones de navegación en esmeralda (#2FB95D)


![Miscellaneos preview web](https://github.com/W3bW0rks/project-report/blob/36ceb2415864a6b2c2a7f84f538e6d2743f9f3f3/assets/chapter-4-images/nav-bar-1.png)

### 4.1.2. Web Style Guidelines.

## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
## 4.2.1 Sistemas de Organización

#### Descripción General
Para garantizar una experiencia de usuario óptima, hemos implementado diferentes sistemas de organización dentro de la interfaz de **AgroControl**. Estos sistemas están diseñados para mejorar la navegabilidad y asegurar que los usuarios encuentren fácilmente la información y las herramientas que necesitan.

#### Tipos de Sistemas de Organización

##### 1. Jerárquico
El sistema de organización jerárquico se utiliza en la mayoría de las páginas clave de AgroControl. Este sistema estructura el contenido de manera que se distinga el nivel de importancia mediante diferencias físicas como tamaño, color, contraste y alineación. Por ejemplo, los títulos y subtítulos más importantes se presentan en tamaños y colores más destacados.

##### 2. Secuencial
En las secciones donde los usuarios necesitan seguir un proceso paso a paso, como el registro o la configuración de su cuenta, se emplea un sistema de organización secuencial. Este enfoque guía a los usuarios a través de un camino específico hacia su objetivo, proporcionando el contenido necesario en cada paso del proceso.

##### 3. Matricial
Para los usuarios que prefieren una navegación más personalizada, se implementa un sistema matricial en áreas específicas, como la búsqueda de artículos en el blog. Este sistema permite a los usuarios elegir cómo desean navegar por el contenido, ya sea de manera alfabética, cronológica o por tema.

#### Aplicación en la Interfaz de AgroControl
Estos sistemas de organización se combinan de manera efectiva para proporcionar una interfaz intuitiva y accesible. Los usuarios pueden moverse fluidamente por la plataforma, ya sea que estén siguiendo un proceso guiado o explorando el contenido a su manera.
#### 4.2.2. Labeling Systems.
The labeling system aims at uniting the data effectively and represent them in simple way and avoid confusing great amount of information. A widely adopted way to achieve this is by creating the labels which represent loads of data in few words.
![Labeling Systems](https://github.com/W3bW0rks/project-report/blob/36ceb2415864a6b2c2a7f84f538e6d2743f9f3f3/assets/chapter-4-images/labeling-systems-1.png)
![Icons-Searching Systems](https://github.com/W3bW0rks/project-report/blob/36ceb2415864a6b2c2a7f84f538e6d2743f9f3f3/assets/chapter-4-images/labeling-systems-2.png)

### 4.2.3. SEO Tags and Meta Tags

**Meta & SEO (Search Engine Optimization) Tags:**  sirven para que la pagina web sea encontrada facilmente es lo que sale al encontrar la pagina en el buscador (se ponen en el <"head">)
* **Titulo**: ```<title>AgroControl - Gestiona Todo Tu Ciclo Agrícola con Eficiencia</title> ```
* **Descripcion**: ```<meta name="description" content="AgroControl te ayuda a gestionar cada etapa del proceso agrícola, desde el sembrío hasta la distribución, de manera simple y efectiva."> ```
* **Palabras Clave:** ``` <meta name="keywords" content="agricultura, gestión agrícola, software agrícola, eficiencia agrícola, AgroControl">```



### 4.2.4. Searching Systems.

**¿Qué se busca?:**  
El sistema de búsqueda de **AgroControl** permite a los usuarios buscar información clave relacionada con la gestión agrícola, como guías, artículos de blog, servicios específicos, o detalles sobre cómo usar la aplicación.

**¿Qué resultados se mostrarán?:**  
Los resultados de la búsqueda incluirán una lista de artículos relevantes, páginas de servicio, secciones de ayuda, y cualquier contenido relacionado con las palabras clave ingresadas por el usuario. Los resultados se mostrarán en orden de relevancia, destacando los más cercanos a los términos de búsqueda.

**Interfaz de búsqueda:**  
La interfaz de búsqueda de **AgroControl** está diseñada para ser intuitiva y fácil de usar. Un campo de búsqueda prominente se encuentra en la parte superior de la página, permitiendo a los usuarios ingresar términos rápidamente. Mientras el usuario escribe, se despliegan sugerencias automáticas para ayudar a refinar la búsqueda. Los filtros adicionales permiten a los usuarios ordenar los resultados por categoría, fecha o relevancia, asegurando que encuentren exactamente lo que necesitan con el mínimo esfuerzo.


### 4.2.5. Navigation Systems.

### Hierarchical Navigation System
El sistema de navegación jerárquico en **AgroControl** organiza la navegación desde la página principal hasta las páginas de destino específicas. Los usuarios pueden comenzar en la página de inicio y desde allí acceder a secciones clave como "Servicios", "Blog", o "Contacto", permitiendo un flujo de navegación claro y estructurado.

### Global Navigation System
Como complemento del sistema jerárquico, **AgroControl** utiliza un sistema de navegación global que facilita el movimiento vertical dentro de una misma página. A través de un menú de navegación fijo, los usuarios pueden desplazarse por las diferentes secciones de la página, manteniendo siempre la opción de regresar a la página principal desde cualquier punto.

### Local Navigation System
El sistema de navegación local se utiliza para permitir a los usuarios moverse entre sub-sitios o páginas secundarias dentro de **AgroControl**. Este sistema complementa la navegación global, proporcionando enlaces directos a otras páginas relevantes, como la página de detalles de un servicio específico o un artículo del blog, asegurando una experiencia de navegación fluida y coherente.
## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
la pagina donde te registras y ves info del web app (te manda al web app)

## 1. Hero
El Hero es la sección principal y destacada de la landing page, captando la atención del usuario con un llamado a la acción o una introducción a la aplicación.

![Hero](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Wireframes/desktop/Hero.png)

---

## 2. Agricultores - Wireframe
Este wireframe muestra la estructura de la página destinada a los agricultores, incluyendo las secciones y funcionalidades específicas para este grupo de usuarios.

![Agricultores Wireframe](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Wireframes/desktop/Agricultores%20-%20Wireframe.png)

---

## 3. Distribuidores - Wireframe
En este wireframe se presenta la página dedicada a los distribuidores, destacando las funcionalidades y el diseño pensado para ellos.

![Distribuidores Wireframe](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Wireframes/desktop/Distribuidores-wireframe.png)

---

## 4. Gallery
Aquí se encuentra la sección de galería, donde se mostrarán imágenes relacionadas con la aplicación o los servicios ofrecidos.

![Gallery](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Wireframes/desktop/Gallery.png)

---

## 5. Plan Agricultor
Este wireframe ilustra el plan diseñado para los agricultores, detallando precios y características específicas del plan.

![Plan Agricultor](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Wireframes/desktop/Plan%20Agricultor.png)

---

## 6. Plan Distribuidor
Similar al plan de agricultores, este wireframe muestra los detalles del plan pensado para los distribuidores, con su propia estructura y características.

![Plan Distribuidor](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Wireframes/desktop/Plan%20Distribuidor.png)

---

## 7. Testimonial
La sección de testimoniales muestra opiniones y comentarios de usuarios satisfechos, proporcionando credibilidad y confianza en la aplicación.

![Testimonial](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Wireframes/desktop/Testimonial.png)

---


## 8. Contact Us
Este wireframe detalla la página de contacto, donde los usuarios pueden encontrar información para comunicarse con la empresa.

![Contact Us](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Wireframes/desktop/Contact%20Us.png)

---

## 9. Footer
El footer incluye enlaces rápidos, información de contacto y otras secciones relevantes para la navegación del usuario en toda la aplicación.

![Footer](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Wireframes/desktop/Footer.png)

---

### 4.3.2. Landing Page Mock-up.
Mockup es todo lo relacionado al diseño de la pagina

## 1. Hero
El Hero es la sección principal y destacada de la landing page, captando la atención del usuario con un llamado a la acción o una introducción a la aplicación.

![Hero](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Mockup/desktop/Mockup_Hero.png)

---

## 2. Agricultores - Wireframe
Este wireframe muestra la estructura de la página destinada a los agricultores, incluyendo las secciones y funcionalidades específicas para este grupo de usuarios.

![Agricultores Wireframe](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Mockup/desktop/Mockup_Agricultores.png)

---

## 3. Distribuidores - Wireframe
En este wireframe se presenta la página dedicada a los distribuidores, destacando las funcionalidades y el diseño pensado para ellos.

![Distribuidores Wireframe](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Mockup/desktop/Mockup_Distribuidores.png)

---

## 4. Gallery
Aquí se encuentra la sección de galería, donde se mostrarán imágenes relacionadas con la aplicación o los servicios ofrecidos.

![Gallery](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Mockup/desktop/Mockup_Gallery.png)

---

## 5. Plan Agricultor
Este wireframe ilustra el plan diseñado para los agricultores, detallando precios y características específicas del plan.

![Plan Agricultor](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Mockup/desktop/Mockup_Plan-Agricultor.png)

---

## 6. Plan Distribuidor
Similar al plan de agricultores, este wireframe muestra los detalles del plan pensado para los distribuidores, con su propia estructura y características.

![Plan Distribuidor](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Mockup/desktop/Mockup_Plan%20Distribuidor.png)

---

## 7. Testimonial
La sección de testimoniales muestra opiniones y comentarios de usuarios satisfechos, proporcionando credibilidad y confianza en la aplicación.

![Testimonial](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Mockup/desktop/Mockup_testimonial.png)

---


## 8. Contact Us
Este wireframe detalla la página de contacto, donde los usuarios pueden encontrar información para comunicarse con la empresa.

![Contact Us](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Mockup/desktop/Mockup_form.png)

---

## 9. Footer
El footer incluye enlaces rápidos, información de contacto y otras secciones relevantes para la navegación del usuario en toda la aplicación.

![Footer](https://github.com/W3bW0rks/project-report/blob/090ca558fab006a3bd0c749657b7f9ebc1d4dd68/assets/chapter-4-images/Mockup/desktop/Mockup_footer.png)


## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
lo funcional de cada aspecto del wireframe 
![Web Aplication Wireframe](image.jpg)
### 4.4.2. Web Applications Wireflow Diagrams.
Wireflow es como se va a navegar por la pagina (boton me lleva a esta pagina y este me regresa)
![Web Aplication Wireflow](image.jpg)
### 4.4.2. Web Applications Mock-ups.
Diseño en todo aspecto
![Web Aplication Mockup](image.jpg)
### 4.4.3. Web Applications User Flow Diagrams.
un flow diagram de como el usuario utilizara la pagina **[PARA CADA USER GOAL]** 
![Web Aplication User Flow Diagram](image.jpg)
## 4.5. Web Applications Prototyping.
[URL del Prototipo (Hecho en figma)](https://www.example.com)
## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.

<img src="https://github.com/W3bW0rks/project-report/blob/86565a482a768881d3025ce9ee6de32b9003f71c/assets/chapter%204-C4%20model/Context%20Diagram.png">
   
### 4.6.2. Software Architecture Container Diagrams.

<img src="https://github.com/W3bW0rks/project-report/blob/86565a482a768881d3025ce9ee6de32b9003f71c/assets/chapter%204-C4%20model/Container%20Diagram.png">

### 4.6.3. Software Architecture Components Diagrams.

#### Login and Registration Bounded Context

<img src="https://github.com/W3bW0rks/project-report/blob/86565a482a768881d3025ce9ee6de32b9003f71c/assets/chapter%204-C4%20model/Component%20Diagram%20-%20UserContext.png">

#### Payment Bounded Context

<img src="https://github.com/W3bW0rks/project-report/blob/86565a482a768881d3025ce9ee6de32b9003f71c/assets/chapter%204-C4%20model/Component%20Diagram%20-%20PaymentContext.png">

#### Calendar Bounded Context

<img src="https://github.com/W3bW0rks/project-report/blob/86565a482a768881d3025ce9ee6de32b9003f71c/assets/chapter%204-C4%20model/Component%20Diagram%20-%20CalendarContext.png">

#### Product Bounded Context

<img src="https://github.com/W3bW0rks/project-report/blob/86565a482a768881d3025ce9ee6de32b9003f71c/assets/chapter%204-C4%20model/Component%20Diagram%20-%20ProductContext.png">

#### Offer Bounded Context

<img src="https://github.com/W3bW0rks/project-report/blob/86565a482a768881d3025ce9ee6de32b9003f71c/assets/chapter%204-C4%20model/Component%20Diagram%20-%20OfferContext.png">

#### Financial Bounded Context

<img src="https://github.com/W3bW0rks/project-report/blob/86565a482a768881d3025ce9ee6de32b9003f71c/assets/chapter%204-C4%20model/Component%20Diagram%20-%20FinancialContext.png">

## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
Esta yaselasaben (diagrama de clases)
Clases(name), objetos(nombre-objeto [como objeto]), metodos("Accion") y atributos(Correo, edad,nombre como valor, ID)
### 4.7.2. Class Dictionary.
Inherit (ave(superclase) -> (subclase)canario )
Polymorphism (Ej. funcion de persona hablar() -> Peruano hablar() , Gringo hablar() todos tienen una funcion que contiene persona y van cambiando sus formas)
Abstraction (Ej. Solo muestra el usuario, pero esta su edad, correo y veces usada que uso app en la base de datos (fuera de vista))
Encapsulation (cuando tienes tus variables y metodos en la misma clase las estas encapsulando, aun mas se encapsulan en Private y Public )
## 4.8. Database Design.
### 4.8.1. Database Diagram.
Diagrama de base de datos (la relacion entre clases PK FK el Normalizar tmbn, isiyisi 🕸)







