# RetoDeSemana1
La nube y Azure 

# La nube 

La nube permite a los usuarios acceder a los mismos archivos y aplicaciones casi desde cualquier dispositivo, ya que los procesos informáticos y de almacenamiento tienen lugar en servidores y de almacenamiento tiene lugar en servidores en un centro de datos, y no de forma local en el dispositivo del usuario.

otra deficiones pueden ser: 
  - la nube esta formada de servidores en centros de datos en todo el mundo. Transladarse a la nube puede ahorrar dinero a las empresas y ser un factor de comodidad para los usuarios.
  - "La nube" hace referencia a los servidores a los que se accede a través de internet, y al software y bases de datos que se ejecutan en esos servidores.

# ¿Cuáles son los principales modelos de servicio de la computación en nube?

  * Software como servicio (SaaS): en lugar de que los usuarios instalen una aplicación en su dispositivo, las aplicaciones de SaaS se alojan en servidores en la nube y los usuarios pueden acceder a ellas a través de Internet. El SaaS es como alquilar una casa: el arrendador sigue siendo el propietario de la casa, pero el arrendatario tiene derecho a usarla como si fuera suya. Ejemplos de aplicaciones de SaaS incluyen Salesforce, MailChimp y Slack.

  * Plataforma como servicio (PaaS): en este modelo, las empresas no pagan por las aplicaciones alojadas, sino que pagan por lo que necesitan para desarrollar sus propias aplicaciones. Los proveedores de PaaS proporcionan todo lo necesario para crear una aplicación, incluyendo herramientas de desarrollo, infraestructura y sistemas operativos, todo a través de Internet. El PaaS se puede comparar con alquilar todas las herramientas y equipamiento necesarios para construir una casa, en lugar de alquilar la casa en sí. Algunos ejemplos de PaaS incluyen Heroku y Microsoft Azure.

  * Infraestructura como servicio (IaaS): en este modelo, una empresa alquila los servidores y el almacenamiento que necesita de un proveedor de nube. Luego, utilizan esa infraestructura en la nube para desarrollar sus aplicaciones. IaaS es como una empresa que alquila un terreno en el que se puede construir lo que se quiera, pero tienen que proporcionar su propio equipamiento y materiales de construcción. Los proveedores de IaaS incluyen DigitalOcean, Google Compute Engine y OpenStack.

Con anterioridad, SaaS, PaaS e IaaS eran los tres modelos principales de computación en nube, y, en esencia, todos los servicios en la nube encajan en alguna de estas tres categorías. Sin embargo, en los últimos años ha aparecido un cuarto modelo:

  * Función como servicio (FaaS): FaaS, también conocida como computación sin servidor, divide las aplicaciones en la nube en componentes todavía más pequeños que solo se ejecutan cuando son necesarios. Imagínate que fuera posible alquilar una casa por partes: por ejemplo, el arrendatario solo paga por el comedor a la hora de la cena, el dormitorio a la hora de dormir, el comedor cuando ve la TV, y cuando no esté usando ninguna de ellas, no tendrán que pagar el alquiler de las mismas.

Las aplicaciones sin servidor o FaaS se siguen ejecutando en servidores, como todos estos modelos de computación en nube. Pero se las conoce como "sin servidor" porque no se ejecutan en máquinas designadas, y porque las empresas que desarrollan las aplicaciones no tienen que gestionar ningún servidor.

Además, las funciones sin servidor aumentan o se duplican, según más usuarios usen la aplicación. ¡Imagínate que el comedor del arrendatario se pudiera expandir a la carta cuando hubiera visita! Más información sobre cómo funciona la computación sin servidor (FaaS).

# ¿Cuáles son los diferentes tipos de implementación en nube?

  - Nube privada: una nube privada es un servidor, centro de datos o red distribuida que está al servicio de una única organización.
  - Nube pública: una nube pública es un servicio gestionado por un proveedor externo que puede incluir servidores en uno o varios centros de datos. A diferencia de una nube privada, las nubes públicas las comparten muchas organizaciones. Con el uso de máquinas virtuales, diferentes empresas pueden compartir los servidores individuales, una situación que se conoce como "tenencia múltiple", ya que varios arrendatarios alquilan espacio en el servidor dentro del mismo servidor.
  - Nube híbrida: las implementaciones de nube híbrida combinan nubes públicas y privadas, e incluso pueden incluir servidores heredados en las instalaciones. Una organización puede utilizar su nube privada para algunos servicios y la nube pública para otros, o puede usar la nube pública como copia de seguridad de su nube privada.
  - Multinube: la multinube es un tipo de implementación en la nube que implica el uso de varias nubes públicas. En otras palabras, una organización con una implementación de multinube alquila servidores y servicios virtuales de varios proveedores externos; para continuar con la anterior analogía, esto sería como alquilar varias parcelas adyacentes de diferentes propietarios. Las implementaciones de multinube también pueden ser una nube híbrida y viceversa.

# Azure
  ¿Qué es Azure?
  
es un conjunto integral de servidores en la nube que los desarrolladores y los profesionales de TI utilizan para crear, implementar y administrar aplicaciones a través de nuestra red global de centros de datos.

otra definición es: Azure es una nube pública de pago por uso que te permite compilar, implementar y administrar rápidamente aplicaciones en una red global de datacenters (centros de datos) de Microsoft.

  ## ¿cómo funciona? 
  
En el portal Microsoft Azure existen diferentes servicios de infraestructura y de plataforma para que puedas “montar” los servicios que necesites de manera sencilla, con unos cuántos clics. En tu portal dispones de un botón [New +] y a partir de ahí, sólo tienes que elegir la región de los datacenter donde estará tu servicio y, a continuación, el tipo de servicio con sus características.

Entre los servicios, dispones de infraestructuras (IaaS: almacenamiento, redes, máquinas virtuales…) y plataformas (PaaS: bases de datos de alta disponibilidad SQL, CMS para desarrollo de web, backend para aplicaciones móviles…). Son compatibles con todo tipo de tecnología: bases de datos Oracle, Linux, php, iOs, My SQL, Android, php…

Estos servicios están garantizados con una disponibilidad del 99.99%, y en caso de fallo en disponibilidad superior, Microsoft se compromete a indemnizar por los daños. Además, cuenta con todas las certificaciones en materia seguridad y protección de datos. ¿Sabías que es la primera plataforma cloud que cumple en categoría alta las características de la certificación de conformidad del Esquema Nacional de Seguridad?

Esta potente solución empresarial para la gestión de tus infraestructuras y aplicaciones presenta grandes ventajas: destacamos la flexibilidad y el pago por uso. Con Azure ya no es necesaria la inversión en máquinas físicas y el mantenimiento que conllevan. De esta manera, se simplifica el despliegue ya que no hay que comprometerse con largos periodos de amortización, se agiliza el proceso de configuración y nos permite adaptar nuestros sistemas a nuestras necesidades en pocos minutos, con total flexibilidad. Además, dispone de herramientas para poder monitorizar el rendimiento y así predecir si es necesario escalar o no nuestras máquinas, y en consecuencia, pagar por lo que realmente necesitas. Por este motivo, distinguimos tres situaciones en las que, sin duda, recomendamos utilizar los servicios de Azure:

  * En el despliegue de una solución en la que el incremento de uso va a ser exponencial (o desconocido) y no podemos definir con garantías el pico de demanda máximo.
  * Cuando sabes que la demanda del servicio va a fluctuar en el tiempo.
  * En entornos de desarrollo o pruebas que posteriormente podrían seguirse utilizando o no, o que pueden “apagarse” puntualmente y después volverse a activar.
