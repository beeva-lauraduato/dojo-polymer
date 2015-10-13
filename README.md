# dojo-polymer
Dojo para el curso de polymer


## ReWine
###Review de vinos

####Introducción:

Este ejercicio pretende que se apliquen los conocimientos obtenidos en la anterior charla de Polymer de este mismo curso, junto con los que desde entonces hayáis adquirido trasteando.

Se proporcionan enlaces de interés, así como requerimientos orientados a que se usen determinadas herramientas.
Cualquier duda, por favor, no duden en escribirnos.

####La aplicación:
Se propone crear una aplicación basada en componentes que permita hacer reviews de vinos. Debe constar de las siguientes secciones:
  - Home: Poner lo que querais aquí! :)
  - Vinos: Listado de vinos y formulario para añadir nuevos vinos. Los vinos pueden ser borrados y modificados     también.
  - Vino = {name: String, Type: String, Desc: String}
  - Vino: Página detalle del vino, con una lista de reviews y un formulario para añadir nuevas reviews.
  - Reviews = {date:Date, mark: Number(0-10), text: String}
  - Reviews: Últimas reviews y buscador de reviews aplicando filtros sobre sus campos

El resto de detalles se dejan al libre albedrío de los desarrolladores ;P

####Requisitos:
Se deben cumplir los siguientes requisitos:
  - Debe hacerse uso de Firebase para la persistencia de los datos.
  - No es necesario implementar autenticación ni registro de usuarios en la aplicación.
  - Debe hacer uso del Polymer Starter kit.
  - Usar el Iron Component Page en alguno de los componentes propios para mostrar su documentación y su demo.
  - Realizar tests de WCT para alguno de los componentes propios desarrollados.
  - Usar al menos un Behavior

####Enlaces de interés:

Polymer starter kit: https://developers.google.com/web/tools/polymer-starter-kit/
Generador: https://github.com/yeoman/generator-polymer
Firebase component: https://elements.polymer-project.org/elements/firebase-element?active=firebase-collection
WCT: https://github.com/Polymer/web-component-tester
Iron Component Page: https://elements.polymer-project.org/elements/iron-component-page
Polymer guides: https://www.polymer-project.org/1.0/docs/devguide/feature-overview.html
