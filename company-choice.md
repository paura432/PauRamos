# Elección de empresa: TrackFlow

## Empresa seleccionada

He elegido **TrackFlow**, una empresa de logística de última milla y gestión de almacenes que opera entre Estados Unidos y España, con almacenes en Los Ángeles y Zaragoza.

## Por qué he elegido TrackFlow

Lo que más me ha llamado la atención de TrackFlow es que no plantea un problema aislado. Todo está conectado.

Un pedido entra, afecta al inventario, pasa por el almacén, se asigna a un transportista, se envía, se hace seguimiento y, en algunos casos, termina en una devolución. Eso me permite trabajar durante el curso sobre distintas partes de un mismo sistema en lugar de construir ejercicios independientes que luego no tienen demasiado que ver entre sí.

También me interesa bastante el punto de partida tecnológico de la empresa. TrackFlow tiene sistemas diferentes entre sus dos almacenes, un ERP antiguo, integraciones poco documentadas y datos repartidos entre varias plataformas. Es un escenario bastante realista: no partes de cero ni puedes sustituirlo todo, sino que tienes que entender lo que existe, conectarlo y construir encima.

Ese tipo de problema es precisamente el que más me interesa trabajar.

## Problemas de negocio que más me interesan

Uno de los primeros es el **inventario**.

Los almacenes de Los Ángeles y Zaragoza utilizan sistemas distintos y no existe una visión común del stock en tiempo real. Además, parte de los pedidos llega por email en distintos formatos y se introduce manualmente.

Me parece interesante porque obliga a combinar varias piezas: backend, APIs, procesamiento de datos e integración de sistemas. No sería simplemente mostrar un inventario en una pantalla, sino conseguir primero que exista una fuente de información fiable que pueda utilizar el resto del sistema.

Otro problema que me interesa especialmente es la **gestión de transportistas**.

TrackFlow trabaja con varios transportistas y actualmente tanto la selección como buena parte del seguimiento requieren procesos manuales. Además, no tienen estructurados datos históricos importantes como entregas a tiempo, incidencias por ruta o coste por kilogramo.

Aquí veo un caso muy claro donde los datos pueden utilizarse para tomar mejores decisiones: unificar el tracking y, más adelante, construir un sistema que pueda recomendar de forma explicable qué transportista utilizar según el destino, el peso o la urgencia.

También me parece muy interesante la parte de **devoluciones**.

Según el briefing, representan entre el 18 % y el 25 % del volumen dependiendo del cliente y del país, y actualmente se revisan manualmente. La inspección del estado de los productos también es subjetiva.

Poder automatizar parte de ese flujo y utilizar visión por computador para ayudar a clasificar el estado de un producto devuelto me parece uno de los casos de IA más interesantes del proyecto porque la IA estaría participando en un proceso operativo real, no funcionando como una capa decorativa.

Por último está la **atención al cliente**.

Los agentes trabajan con email, WhatsApp y teléfono sin un sistema de tickets unificado, y gran parte de las consultas están relacionadas con seguimiento y devoluciones.

Aquí tiene mucho sentido construir un agente que pueda consultar información real del sistema y apoyarse en una base de conocimiento mediante RAG para responder preguntas de forma fundamentada.

## Retos de AI Engineering que quiero trabajar

Uno de los retos que más me interesa es combinar **RAG y agentes**.

No quiero limitarme a hacer un chatbot que responda preguntas. Me interesa que el agente pueda utilizar documentación real, políticas logísticas y datos del sistema para responder sobre tracking, devoluciones u otros procesos sin inventarse información.

El hecho de que TrackFlow opere entre Estados Unidos y España también permite trabajar con búsqueda semántica y soporte en distintos idiomas.

Otro reto que me parece especialmente atractivo es la **visión por computador aplicada a las devoluciones**. El briefing plantea que un operario pueda fotografiar un producto y utilizar IA para clasificar su estado. Me gusta porque conecta directamente un modelo de IA con una operación física del negocio.

También quiero trabajar la selección explicable de transportistas, la integración de distintas APIs de tracking, los pipelines de datos, el tiempo real y la observabilidad.

Para mí esta última parte es importante: no solo quiero conseguir que una funcionalidad funcione, sino entender cómo construir un sistema en el que también podamos saber qué está pasando cuando deja de funcionar.

## Valor para mi portfolio

Una de las razones principales por las que he elegido TrackFlow es que creo que puede convertirse en un proyecto de portfolio bastante completo.

Me permite trabajar con APIs, backend, integración de sistemas, pipelines de datos, tiempo real, RAG, agentes, visión por computador, automatización y observabilidad dentro de un mismo producto.

Pero lo que más me interesa es que todas esas tecnologías tienen un motivo para estar ahí.

No quiero terminar el curso con una colección de funcionalidades de IA añadidas porque sí. Quiero poder enseñar TrackFlow y explicar el recorrido completo:

qué problema tenía la empresa, qué información necesitábamos, cómo diseñé el sistema, por qué elegí determinadas soluciones y dónde aporta realmente valor la IA.

Mi objetivo es que el proyecto vaya creciendo durante el curso hasta convertirse en un sistema coherente, donde cada milestone añada una pieza nueva sobre lo que ya existe.

Al final quiero poder enseñar no solo que sé utilizar modelos de IA, sino que sé integrarlos dentro de un producto real junto con backend, datos, automatización, monitorización y decisiones de arquitectura.
