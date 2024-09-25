# P1_Jim-nezCerpaIgnacio_DWEC


# Idea de la aplicación
    Idea de la aplicación: Describir de manera clara y concisa la idea de la aplicación web y su propósito.

La aplicación será una herramienta diseñada para facilitar la organización y gestión de colecciones de cartas TCG (Trading Card Game). Su propósito es proporcionar a los usuarios una forma sencilla y cómoda de llevar un inventario detallado de las cartas que poseen, incluyendo el número de copias de cada carta. Además de permitir a los usuarios crear y gestionar sus propias barajas de cartas, organizar sus colecciones y mantener una lista de deseos de cartas que están buscando. 

# Audiencia objetivo
    Audiencia objetivo: Definir el público para el que está destinada la aplicación, explicando su relevancia y cómo se beneficiarán de la aplicación.
Esta aplicación está destinada tanto a coleccionistas de cartas como a jugadores ocasionales del juego. 

Se beneficiarán por tener una gran organización y control de su inventario de cartas, sabrán que cartas necesitan en cualquier momento, podrán hacerse sus propias barajas con facilidad y cómodidez desde cualquier parte del mundo.
Tendrán acceso en todo momento a su colección, lo cual puede ser de mucha utilidad cuando estás en una tienda física y quieres comprarte alguna carta.
También, para el interés de los coleccionistas, podrán ver el valor ecónomico que tiene cada carta en el mercado.

# Ánalisis de mercado 
    Análisis de mercado: Investigar y analizar aplicaciones similares en el mercado. Identificar características comunes y oportunidades de diferenciación para la nueva aplicación, destacando qué valor añadido ofrecerá.
Collectr es una aplicación que comparte la idea de ser una aplicación donde puedes organizar tus colecciones de cartas TCG.
La diferencia principal de su idea con la mia, es que su aplicación está bastante más orientada a la compraventa de cartas, teniendo un servicio de ventas de cartas dentro de la propia aplicación.
Tenemos en común mayormente el poder organizar colecciones de cartas según el TGC que tengas. Pero una diferencia sustancial es que yo tengo en mente poder organizar tus propias barajas competitivas y no incitar a la especulación del material coleccionable.

Deckstats es una aplicación que también comparte la misma idea que mi aplicación, y de una manera maś cercana que Collectr. Mi principal ventaja respecto esta aplicación es que mi app no se limita únicamente a las Magic, yo también abarco otros TGC famosos como Yu-Gi-oH o Pokémon TGC.
Reconozco que la idea de tener un foro o red social para poder comunicarte con otros jugadores es algo que no había pensado y que es una característica muy buena para mejorar la comunidad.
# Funcionalidades claves
    Funcionalidades clave: Identificar y listar las funcionalidades principales que ofrecerá la aplicación (ej: sistema de autenticación, gestión de usuarios, etc.).
* Sistema de autenticación
  * Es necesario tener un sistema en de autenticación por el mero hecho de que para la asociación de una colección de cartas, barajas,etc tendré que saber de quien es. De otra manera no podría saber de quien es y no tendría mucho sentido tener una app como esta.
* Gestión de usuarios
    * Al tener la capacidad de tener cuentas de usuario, tener una manera de gestionar las cuentas de los usuarios es algo también necesario por el bienestar de la organización de la aplicación web     
* Buscador de cartas
    * El poder buscar las cartas es una función esencial porque el querer un acceso a la carta que quieras en concreto es algo super básico y esencial. 
* Creador de barajas
    * Crear una baraja en la que tengas las cartas con las que juegas es algo importante en los TGC, pues ayuda a saber con que cartas puedes contar o saber que cartas te faltan en tu baraja.
* Organizador de barajas
    * Tener la capacidad de organizar las barajas que has creado es importante, pues mantener un control sobre ellas es necesario. Si quierer borrarla, nombrarla, modificarla,etc.  
* Organizador de colección
    * Organizar tu colección de cartas, que no es lo mismo que una baraja, es importante para saber que tipo de cartas tienes por ejemplo.  


# Modelos de ejecución
    Modelos de ejecución (c.e. 1a): Investigar y comparar los modelos de ejecución en cliente y servidor, explicando sus diferencias y ejemplos de uso.
| Cliente | Servidor |
|---------|----------|
| bla bla | bla bla  |
| bla     | bla      |
| bla     | bla      |
# Lenguajes de programación web
    Lenguajes de programación web (c.e. 1c, 1d): Analizar los lenguajes de programación más utilizados para el desarrollo web en cliente, como JavaScript y TypeScript, explicando sus ventajas y desventajas.
### JavaScript
Es un lenguaje de programación scripting para la parte de cliente en aplicaciones webs. Se ejecuta en los navegadores y es el más conocido de todos. Aunque sea para clientes, se ha conseguido que también sirva para desarrollar aplicaciones backend.

Nació para darle dinanismo a las páginas y es el lenguaje principal al momento de hacer aplicaciones para clientes.

De JavaScript han nacido otros lenguajes y varias librerías y framework debido a su gran popularidad y comodidez al ser usado

**Ventajas**
 * Es uno de los lenguajes de programación más famosos, ocupando el puesto 6 en el index de TIOBE, lo que implica que tiene un gran apoyo por parte de las compañías y tiene una gran comunidad, por lo que hay muchas soluciones a muchos problemas y muchos recursos para aprender a dominarlo.
 * Ayuda a disminuir la carga del servidor, pues al ser un lenguaje bastante capaz, puede hacer que el navegador gestione algunas tareas y el servidor de las esenciales. 
 * Es bastante versátil pues cuenta con muy buena compatibilidad con otros lenguajes de programación
 * Es genial para proyectos pequeños por su simplicidad
 * Tiene buena comptabilidad con navegadores viejos pues todo es retrocompatible en javascript.

**Desventajas**
 * Tiene varias vulnerabilidades explotables, lo que hace que no sea una opción del todo segura al momento de desarrollar y tengas que hacer un trabajo extra para cubrir esas vulnerabilidades
 * Tiene un tipado dinámico, que no es algo tan malo y depende de a quien le preguntes pues te dirá que es una ventaja, en lo personal prefiero el tipado estático para tener más control sobre el tipo de datos con el que trabajo.
 * Si te pasas poniendo funciones es posible que realintices la página por tener que cargar varias cosas.
 * Es algo dificil de depurar pues tienes que recurrir al depurador del navegador.

### TypeScript
Este lenguaje nace de javascript con la principal diferencia de incluir algunas mejoras, siendo la principal la inclusión de un tipado estático.
Por todo lo que comentaré en las ventajas,digo que TypeScript es un lenguaje adecuado para proyectos medianos y grandes en diferencia con javascript, que es mejor para proyectos pequeños.

**Ventajas**
 * Es más fácil de hacer un código seguro y que se pueda mantener gracias al tipado
 * Es más legible que javascript gracias al tipado estático
 * Al igual que javascript, tiene un buen soporte por parte de la comunidad, pues también es un lenguaje famoso.
 * Es compatible con todos los framework y librerías de javascript pues tiene de núcleo el propio javascript, esto permite poder trasladar más cómodamente tus proyectos de javascript.
**Desventajas**
 * Es más aparatoso en proyectos pequeños debido a que tienes que estar, precisamente, tipando todas las variables.
 * Tiene problemas de compatibilidad en navegadores viejos.
### Dart
Es un lenguaje orientado a objetos que creó Google para el desarrollo de aplicaciones web y cuyo código se puede pasar a JavaScript. 

**Ventajas**
* 

**Desventajas**

### Elm

**Ventajas**


**Desventajas**

# Tecnologías a utilizar
    Tecnologías a utilizar: Seleccionar las tecnologías (lenguajes de programación, frameworks, herramientas de desarrollo) que se utilizarán para el desarrollo de la aplicación. Justificar la elección en base a la investigación realizada. Asegurarse de incluir:

        Evaluación de los mecanismos de integración de lenguajes de marcas con lenguajes de programación de clientes web (c.e. 1e): Describir cómo los lenguajes de marcas (como HTML) se integran con los lenguajes de programación (como JavaScript) en la aplicación.

        Evaluación de herramientas de programación para clientes web (c.e. 1f): Seleccionar herramientas de desarrollo (editores de código, frameworks, bibliotecas) y justificar su elección. Explicar las funciones y ventajas de cada herramienta en el contexto del desarrollo web.
# Comptabilidad en navegadores
    Compatibilidad en navegadores (c.e. 1b): Realizar un estudio sobre cómo los diferentes navegadores manejan JavaScript y otros lenguajes utilizados en el desarrollo web, identificando problemas de compatibilidad y soluciones. Incluye un análisis sobre cómo la integración de lenguajes de marcas y lenguajes de programación afecta la compatibilidad y el rendimiento de la aplicación en diferentes navegadores.
