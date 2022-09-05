# Resumen-Video

### Tendencias en el desarrollo del software.

En el desarrollo del software existen dos mundos diferentes que son el Backend que se encarga acceder a la información que el cliente necesita y el Frontend que es la capa que el cliente puede ver donde se pueden aplicar diferentes frameworks como angular y react.

La evolución del desarrollo del software se ha medido según la complejidad de las aplicaciones que se han ido desarrollando a través del tiempo

Empezando por la era monolítica en donde los sistemas eran muy complejos, la computación estaba basada en mainframes haciendo el uso de terminales brutas.

En el año 84 llega el uso del computador personal , empiezan a aparecer las aplicaciones de escritorio en donde se usaban interfaces basadas en texto como aplicaciones contables.

+ En los años 90 aparecen los primeros sistemas de información empresarial,CRM , ERP 
+ En el 2001 aparecen los sitios web transaccionales
+ En el 2008 aparecen los rich internet application en donde en un ambiente web se pudiera aplicar una misma funcionalidad que las aplicaciones de escritorio.

### Evolución del desarrollo de software.


 Antes el ciclo del desarrollo de las aplicaciones de 12 a 18 meses evolucionó a un ciclo de desarrollo del tiempo cero (días o horas utilizando metodologías ágiles.

+ Se pasa de un equipos centralizados trabajando en un mismo módulo a equipos distribuidos , diferentes preferencias ( Políglota) 

+ Se empieza el uso de componentes pequeños en arquitecturas basadas en microservicios en vez de los monolíticos. 

+ Las interfaces de usuario pasan de ser básicas a crear mejores interfaces tambien en aplicaciones híbridas aplicadas a los móviles.

+ Se pasa de desarrollar primeros las funcionalidades a diseñar primero las APIS

### Características de las app web modernas

+ Usa HTML5 / CSS3
+ Exponen servicios REST en formato JSON o usan GraphQL.
+ Tendencias a aplicar Arquitecturas con microservicios y Serveless.
+ Emplean servicios de aplicaciones de redes sociales.
+ Usan diseño web adaptable. Responsive Web Design.
+ Aplicación web de una sola página (SPA

### Infraestructura para el desarrollo de apps modernas

En sistemas grandes se hace el uso de DevOps para automatizar el despliegue , las pruebas , la entrada en operación del sistema , el monitoreo para asi poder agilizar el desarrollo

Hacer uso de contenedores como Docker , orquestación para portabilidad.

### Aspectos importantes de la arquitectura.


+ Seleccionar la vista arquitectónica. use por ejemplo 4+1 vistas o modelo C4 ( contexto,contenedores,componentes y código) , es importante hacer un buen modelamiento del sistema y tener una arquitectura robusta.
+ Seleccionar un estilo arquitectónico  ( Monolítico,SOA, Microservicios, Arquitectura en capas).
+ Seleccionar entre una solución Cloud o servidores on-premise.
+ Considere Autenticación / Autorización y Privacidad.
+ Defina reglas de seguridad y protocolos de comunicación.
+ Defina si se necesita balanceo de carga  ( Ngingx), messaging
+ Hacer una revisión general de cualquier algoritmo critico que controle el servicio.
+ Considere cuellos de botella y determine soluciones 
+ Seleccione tipos de almacenamiento SQL o noSQl
+ Comprender que datos deben almacenarse en caché y cómo mejorar el rendimiento,la seguridad y la disponibilidad con el almacenamiento en caché.
+ Seleccionar un sistema de monitoreo y logging. como gestionar excepciones y fallos 
+ Defina la separación entre áreas públicas y restringidas.


### Importancia de las WebAPIs

+ Es muy común que las aplicaciones Cloud presenten Web APIs para comunicarse entre ellas
+ El desarrollo móvil se alimenta de APIs 
+ Las necesidades de la industria requieren opciones dinámicas como Microservicios, DevOps 

Swagger / Open API  : descripción de servicios API , documenta las APIs facilita su uso por desarrolladores. integración con herramientas de APIs management

SPA : una aplicación web que se ejecuta en una única página, logrando así una experiencia de usuario más cercana a una aplicación de escritorio.

### Implicaciones de una arquitectura basada en HTML5

+ El browser es la plataforma.
+ HTML genera nuevas UI hacia distintos dispositivos.
+ Aplicaciones = HTML5 + JS + CSS3 + Recursos del servidor
+ Requiere diferentes aproximaciones de programación

### Arquitectura de servidores ligeros.

+ Mejora el desempeño gracias a la función de Caching
Escabilidad , menor transferencia de datos , el estado de la sesión en el cliente
+ Reduce la complejidad
+ Mejora la experiencia de usuario.

### PWA Aplicaciones web progresivas

Fueron creadas por google en 2015, una PWA utiliza las últimas tecnologías disponibles en los navegadores para ofrecer una experiencia en móviles lo más parecida a la de una aplicación nativa.

### Características 

+ Que tenga el mayor rendimiento posible en móviles y que cargue de manera casi instantánea.
+ Una buena interfaz que se parezca lo máximo posible a una nativa.
+ La posibilidad de trabajar sin conexión.
+ poder enviar notificaciones a los usuarios, como una app nativa.

### Microservicios

Los microservicios son usados por una cantidad de empresas como netflix,uber , facebook, Paypal , Soundcloud. evolucionado de sistemas monolíticos a sistemas basados en microservicios

+ Tienen un estilo arquitectónico.
+ Desarrollar una simple aplicación como:

+ una suite de pequeños servicios 
+ servicios altamente desacoplados 
+ Enfocado en pequeñas tareas
+ Cada uno corriendo su propio proceso / sus propios datos.
+ Comunicando con mecanismos ligeros.
+ Independiente del lenguaje


### Arquitectura Serverless

Paradigma de programación en la nube donde la lógica se divide en funciones y se ejecuta en respuesta a eventos también Permite reducir los costos operacionales (Paga por llamadas y no por todo el servicio  y la complejidad, está basado en microservicios













