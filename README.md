# Tutorial System Requirements
Para hacer los diagramas de requisitos:

0. Seguid el modelo del diagrama "User Requirements", que est� completamente terminado

1. El diagrama "System Requirements" s�lo tiene "packages" que organizan cada uno de los requisitos.
	Para acceder a vuestros diagramas (los que ten�is que rellenar), en la vista de Papyrus deb�is ir al "Model Explorer". Ah�, abr�s RootElement->System Requirements->Vuestro paquete (e.g. "1. Functional Requirements")->Diagrama. Es AH� donde ten�is que construir el diagrama.
	
2. El paquete "Usability Requirements" est� empezado, para que teng�is una idea de c�mo seguir. Le pod�is echar un vistazo.

3. Cada diagrama tiene un RATIONALE explicando el contenido del diagrama, y un COMMENT donde viene:
Nombre del diagrama
Versi�n (ponedle el d�a en que lo acab�is donde pone xx)
Autor: xd

4. Cada requisito debe tener una IDENTIFICACI�N (id) y un contenido (TEXT).

5. La identificaci�n tiene que seguir unas reglas. Empieza siempre con las iniciales de vuestro diagrama (e.g. "UR" para el diagrama de Usability Requirements). El primer requisito es el 1 (e.g. "UR1), el siguiente el 2 (e.g. "UR2"), etc. Si hay requisitos anidados, seguid la serie "UR1.1", "UR1.2", "UR1.2.1.57", etc. Ten�is un ejemplo en el diagrama "Usability Requirements"

6. El texto lo dejo a vuestra brillantez y creatividad. S�lo hay una norma: los requisitos se escriben con "shall" (e.g. "Requirements specifications shall be stated using 'shal'"). Si hay cosas "deseables" pero que no son exigibles, se puede usar "should" (e.g. "Requirementes should be written in perfect English xD")

7. Idealmente pod�is incluir la trazabilidad del requisito. Pon�is al final del texto "Traced to:" y pon�is los identificadores del requerimiento del "User Requirements" del que proviene. Ten�is un ejemplo en "Usability Requirements". En realidad es lo que hay que hacer pero es mucho trabajo. Sed honrados y dedicadle el tiempo que pod�is. Si no lo haceis ahora, habr� que hacerlo en Navidades igualmente.

8. Vamos a intentar hacer bien los branch, los commits y los merge para que no se pierda el trabajo de nadie.

9. Tened en cuenta que tengo que hacer captura de pantalla de los diagramas y meterlos en un documento pdf. Intentad que os quepan en lo que ser�a un A4. Si es imposible, tenemos que crear subdiagramas. En ese caso avisadme y os explico c�mo se hace

10. Eso es todo. Disfrutad :)

************************************************************************************************************
EXTRA: C�mo hacer que el cuadrito de Requirements muestre la id y el texto (requested by Fran):

En SysML rellen�is el nombre, la id y el texto
En Appearance os vais abajo del todo. En la tabla marc�is el tick de "In Compartment" en la fila de "Requirement". Acto seguido quit�is el tick de todos los items que no sean "text" e "id"
Por �ltimo, quit�is y pon�is el tick de "text" para que "id" salga arriba y "text" salga abajo

C'est tout