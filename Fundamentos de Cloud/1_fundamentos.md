# Fundamentos del cloud Computing
La presentación respectiva trae por nombre _Fundamentos del cloud computing_ como PDF o como pptx.

El cloud se basa en la arquiectura cliente-servidor, se depende de internet totalmente. Se puede trabajar de manera offline gracias a algunas herramientas, pero siempre viene después la sincronización a través de internet con el servidor o cloud.

En la página 6 encontramos una definición del _cloud_. Con cloud se permite acceder a muchisimas cosas que se encuentran montadas o almacenadas en otro lado que no es localmente y que es provisto por un individuo u organización com olo puede ser Microsoft con su servicio cloud _Azure_.

Antes del Cloud existía algo como un _data center_ que tal cual son servidores que debe montar la empresa y esto trae muchas limitantes por el costo, tamaño físico y de almacenamiento virtual y tiempo de montar más data center.

Con cloud uno de subscribe por recursos en alguna parte del mundo. Ahí dentro podemos montar maquinas virtuales por poner un ejemplo. Con esto se paga menos, la insfraestructura no se la lleva la empresa, solo para por lo que usa en la nube.

## Características:
En cloud, se puede extender de manera casi infinita, mientras pagues claro, a este concepto se le denomina _elasticidad_, se puede crecer hasta donde la billetera alcance.

La _inmediatez_ es otro de sus puntos fuertes, los recursos del cloud se pueden usar inmediatamente. Crear una máquina virtual se hace en minutos.

Otro punto a destacar es la _concurrencia_ que tiene que ver con la capacidad de manejar peticiones o solicitudes de muchos clientes, o que se quiera mover una cantidad grande de datos en la bbd. Siendo _escalable_ hasta que la cartera lo permita.

Todos los provedores de cloud ofrecen un _autoservicio y bajo demanda_ que practicamente no esperar a que te lleven lo que necesitas, sino que tu solo puedes tomar lo que necesites y cuando lo necesites.

Los recursos a usar van por _ubicación_ o regiones, es como en los videojuegos online, se puede seleccionar a qué servidor te quieres conectar, que van por regiones, puede ser norteamérica, asia, subamérica, ... estas son las regiones que van por ubicación geográfica. Cada región tiene costos diferentes, no es lo mismo montar una máquina virtual en áfrica que en EU además que hay que considerar la _latencia_. 

## Métodos de entrega
En la nube, hay responsabilidades compartidas, algunas cosas quedan del lado del provedor y otras son nuestras. Cuando la responsabilidad es _on premise_ ya responsabilidad total es nuestra, es como trabajar en local o con un servidor privado.

Cuando el servicio que necesitamos es una infraestructura se conoce como _IaaS_ donde alquilamos el amacenamiento, los servidores, redes, máquinas virtuales.

La plataforma como serivicio _PaaS_ te deja solo en tus manos las aplicaciones y la data, todo lo demás es problema del provedor.

Y por último, encontramos el sofwtare as a Service _SaaS_, donde es un servicio a consumir, donde el cliente no mete las manos para nada, como un netflix o algo como ese tipo de servicios.

## Billing
Los costos varian de qué nube se use, lo que vayas a necesitar de esa nube, es decir los recursos a necesitar, llamado usualmente como el modelo _on demand_. Cada nube tiene su _calculadora de precios_, en donde podemos simular lo que necesitaremos como una máquina virtual y sus especificaciones y su tiempo de uso. Hay personas que se dedican a solo este punto, minimizar costos pendendiendo de su uso. 

_Reserved:_ Si se requiere constantemente del servicio (mes con mes), entonces se puede optar por una subscripción o modelo de reserva, para esto se debe contactar con la empresa directamente, esto optimiza el billing.  

Y el último modelo es _spot_. Donde se paga minuto a minuto para servicios en tiempo real.

Los _CapEx_ son costos que tiene que ver con la infraestrestructura, como el costo de red, servidores, personal técnico, ... Pero estos se omiten o se incluyen en la subscripción al servicio cloud. Pero los _OpEx_ son los gastos de operación, que sí que los tienes que pagar, como lo es la renta de algún servicio en la nube o el escalado de estos servicios.

# Azure
Servicio cloud de Microsoft que permite construir, testear, desplegar y gestionar aplicaciones y servicios. Se integra con otros servicios de microsoft como el 365. Algunos de sus servicios son: data, análisis, desarrollo, computo, seguridad, almacenamiento, redes, ...