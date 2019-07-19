# M Ü E V E #

## Índice

- [Descripción](#resumen-del-proyecto)
- [Objetivos](#objetivos)
- [Problema](#problema)
- [Etapa de descubrimiento](#etapa-de-descubrimiento)
- [Benchmark](#benchmark)
- [User Personas](#user-personas)
- [Storyboard](#storyboard)
- [Etapa de ideación](#etapa-de-ideación)
- [Propuesta de valor](#propuesta)
- [Prototipado](#prototipado)
- [Testing](#testing)
- [Propuesta](#propuesta)

## Descripción

Müeve es una aplicación móvil con la cual los usuarios de automóviles electrónicos podrán encontrar las estaciones de carga más cercanas desocupadas, iniciar la carga por medio de un código QR, pagar el servicio y tener un historial de consumo. 

Esta aplicación fue desarrollada por Au haus y Engine Factory, quienes buscan crear la red de carga inteligente más grande y eficiente en México. 

El reto de nuestro equipo, comprendido por Viviana Navarro, Ariadna Gutiérrez, Elizabeth Ramírez y Karen Amicone, consiste en mejorar el diseño UX y UI de Müeve.

## Objetivos

El objetivo de este reto será el rediseño UX y UI de una aplicación móvil enfocada al usuario final, implementando las mejoras en su experiencia. Deberá ser visualmente atractiva y sencilla de utilizar.

Los objetivos particulares de la empresa son: 

1. Experiencia de la interfaz sencilla y agradable.
2. Plantear un ecosistema de carga para formar una app.
3. Conocer puntos de carga (Mapa).
4. Estándares de cargador.
5. Potencia. ¿Qué tan rápido puedes cargar tu carro?
6. Interacción de carga (Dashboard).
7. Apartar cargador. (Engagement) por cantidad.
8. Puedan añadir puntos de carga que no estén en el mapa.
9. Generar ruta y mapearla. 
10. Estimación de tiempo.
11. Saber si la estación es gratuita o de cobro.

## Benchmark

![benchmark](https://drive.google.com/file/d/1LQG3vu5wJkO3istja8r0AiALlRe59s95/)

### Ecocarga

 En la aplicación cualquier usuario puede visualizar en un mapa las estaciones disponibles en Chile. El usuario puede, si así lo desea, ingresar la marca y modelo de su vehículo eléctrico para filtrar las estaciones que son compatibles con su vehículo. Además puede hacer una estimación del tiempo de carga en las distintas estaciones que se despliegan en el plano.
 
**Pros:**
- Muestra sólo aquellas estaciones que son compatibles con el vehículo.
- Estima el tiempo de carga en las distintas estaciones que se despliegan en el plano.
- El usuario ingresa datos de su auto sólo si así lo desea.

**Contras:**
- Mal referenciada en el mapa.
- No hay instrucciones de cómo cargar.
- No permite calcular el tiempo de carga de motocicletas y monopatines.
- No incluye todas las marcas de híbridos.

### eCharge 

Muestra la estación de carga disponible más cercana. Usa una gran red de estaciones de carga pública en continua expansión. La carga es rápida y fácil. Además es posible pagar con diferentes métodos de pago como PayPal, tarjeta de crédito, el contrato de electricidad o un cupón.

**Pros:**
- Encuentra las estaciones de carga en el área o cerca de una dirección específica.
- Filtra el mapa general según la estación de carga correspondiente.
- Permite consultar la disponibilidad de puntos de recarga en tiempo real.
- Agrega el método de pago una vez lo utiliza siempre.
- Varios métodos de pago.
- Supervisa la sesión de carga activa y sigue el progreso de carga.
- Guarda las estaciones de carga de uso habitual como favoritos.
- Revisa las sesiones de carga anteriores y los costos en cualquier momento.
- Proporciona información sobre la contribución al medio ambiente por el uso de autos eléctricos.
- Informa sobre problemas con las estaciones de carga.

**Contras:**

- Recopila datos personales.
- Muchos pasos.

### Nextcharge

Muestra un mapa con más de 200,000 puntos de recarga para vehículos eléctricos en todo el mundo.

**Pros:** 
- El usuario puede actualizar los puntos de carga.

**Contras:**
- Información poco fiable.
- Faltan puntos de carga.


### Electromaps

Electromaps permite encontrar todos los puntos de recarga para vehículos eléctricos disponibles para el uso público. 
 
**Pros:**

- Muestra las estaciones de carga en funcionamiento e incluso la potencia del cargador.

- Activa la recarga y realiza el pago. 

- Consulta los detalles de cada punto de recarga.

- Consulta los comentarios que han dejado los usuarios.

- Muestra las fotos asociadas a cada punto de recarga.

- Abre directamente el mapa para guiar al usuario a un punto si así lo desea.

- Permite verificar telefónicamente la disponibilidad y el funcionamiento.


**Contras:**

- Hay puntos que no funcionan.
- No están actualizados todos los puntos.
- La aplicación es poco intuitiva.

### Google Maps

Es fácil de usar y rápida en la navegación. Hay mapas de más de 220 países y territorios con millones de empresas y lugares señalados.

**Pros:**
- Ahorra tiempo con la modificación automática de la ruta según la información del tráfico y otras variables.

- Mapas sin conexión para buscar y navegar cuando no hay conexión a internet.

**Contras:** 

- No es posible personalizar el volumen del audio o el tipo de aviso. 

- Algunos usuarios han reportado que se pierde la conexión. 

### Waze

Waze es una aplicación que proporciona datos sobre el tráfico, obras, accidentes, etc., y dibuja la mejor ruta de un punto a otro actualizándolas en tiempo real con base en el tráfico y otros inconvenientes. 

**Pros:**
 
- Avisos de tráfico, policía, peligros y mucho más en la ruta.

- Permite llegar más rápido. 

- Cambios de ruta instantáneos para evitar tráfico y ahorrar tiempo.

- Pagar menos por el combustible. 

- Encuentra la gasolinera más barata en la ruta.

- Eliger entre varias voces para guiar mientras el usuario conduce. 

**Contras:**

- Han desaparecido un radar que hasta hace poco aparecía, menos mal que conozco donde se encuentra.

- El navegador bien, le falta mejorar las rutas sugeridas, además es engorroso realizar una búsqueda de estacionamiento cuándo uno esta próximo a su destino, creo que debería sugerirlo automáticamente.

### Edrive
Esta aplicación es un nuevo paso hacia el desarrollo de una mejor relación entre los clientes y las tecnologías de edrive. El equipo de edrive technologies cree que la nueva era de la tecnología solo se puede cumplir al proporcionar y satisfacer las necesidades diarias del cliente proporcionándole nuevas tecnologías. 

**Pros:**

- Facilidad de uso y navegación.
- Seguimiento en tiempo real. 
- Diferentes tipos de MAP. 
- Dirección del vehículo. 
- Color sobre la base del estado del vehículo. 
- Notificaciones en vivo. 
- Informes. 
- Ubicación histórica. 

**Contras:**
- Lugar incorrecto?
- No puedes ingresar no hay lugar donde registrarse primero.

Las características más buscadas en las aplicaciones que ya están en funcionamiento son las siguientes:

- Buscador de estaciones de carga eléctrica en tiempo real
- Estaciones de recarga disponibles, Ocupados,etc.
- Detalles de  la estación como precio por minuto de carga, potencia y tipo de conector
- Filtrar por tipo de conector.
- Supervisar progreso y estatus de recargas.
- Informar en tiempo real problemas de los puntos de recarga.
- Imágenes, dirección, estatus, precio, del punto de recarga.
- Mapear la ruta a la estación de carga
- Método de pago guardado
- Activar la recarga
- Mostrar las operaciones e histórico de estas
- Personalización del vehículo



## Historias de usuario

Yo como usuario, quiero loguearme con mi correo y contraseña.
Yo como usuario, quiero tener acceso a puntos de recarga.
Yo como usuario, quiero iniciar mi carga
Yo como usuario, quiero poder configurar mi método de pago.
Yo como usuario, quiero tener acceso al histórico de mis consumos.

## Análisis de Heurísticas

**Checklist** 
- [ ] Visibilidad del Estado del Sistema: 
* Muestra barras de proceso de información, 
* Muestran mensajes de confirmación que indican que la tarea se ha finalizado con éxito.


- [x] Consistencia entre el sistema y el mundo real: 
*  Código lingüístico igual al del usuario, 
*  Presentación lógica de la interfaz

- [ ] El usuario es libre y tiene control:
* Facilidad para hacer y deshacer
* Facilidad para desplazarse dentro del prototipo

- [ ] Consistencia y estándares:
* Los objetos están organizados de forma coherente
* Utiliza íconos convencionales

- [ ] Prevención de errores:
* Presenta señales para prevenir errores

- [ ] Mejor reconocer que memorizar:
* Muestra una interfaz amigable e intuitiva
* Relación con los objetos y las funciones

- [ ] Flexibilidad y eficiencia de uso:
* Presenta dos interfaces(novato y experto)
* Muestra atajos para acciones frecuentes(exp.)

- [ ] Diseño estético y minimalista:
*El home presenta exceso de información
*No hay una segmentación clara de los eventos 
* Muestra información necesaria
* La presentación de la interfaz presenta armonía

- [ ] Ayuda al usuario a reconocer, diagnosticar y recuperarse de los errores:
* Indica errores a través de mensajes o sonidos
* Indica mensajes de avances y éxito.

- [ ] Ayuda y documentación:
* El botón de ayuda siempre está presente
* Presenta FAQ o videos tutoriales.



Observaciones en la app Müeve:
- No se logra un login correcto.
- No es intuitiva debido a que algunos botones no tienen consistencia dentro de la app.
- Tiene errores técnicos, ya que se cierra cuando se intenta regresar al menú o a la actividad anterior.
- No muestra el proceso de la información mientras se está cargando.
- Los íconos no tienen consistencia.
- La tipografía y los estándares establecidos no tienen consistencia.
- El logo no tiene el formato correcto puesto que se distorsiona al iniciar la app.
- El usuario no puede regresar por falta de íconos de error o el regreso no funciona.
- No hay facilidad para desplazarse.
- No tiene un punto de ayuda o chat de comunicación para  auxiliar al usuario.


## Etapa de descubrimiento ##



### Contexto ###


México cuenta con 900 estaciones de carga para vehículos eléctricos.
Datos de la Asociación Mexicana de la Industria Automotriz (AMIA) indica que en 2016 se vendieron 8 mil 260 unidades de vehículos híbridos y eléctricos, mientras de enero a noviembre de 2017 la cifra aumentó a 9 mil 177 vehículos. 
Los Estados con mayor venta de vehículos híbridos y eléctricos son Ciudad de México con el 44.6%, Estado de México con 13.4%, Jalisco con 7.2%, Nuevo León con 6.1% y Michoacán con 2.9%.

                                          Estadísticas a 18-07-2019




Datos a nivel país de México 2019.



Tipos de recarga
Hablamos de conectores y los diferentes métodos de recarga, que infieren directamente en la compatibilidad entre el punto de recarga y el vehículo
RECARGA CONVENCIONAL (16 Amperios)
El vehículo se enchufa durante aproximadamente 8 horas para obtener una carga completa.
La carga convencional monofásica emplea la intensidad y voltaje eléctricos del mismo nivel que la propia vivienda, es decir, 16 amperios y 230 voltios. Esto implica que la potencia eléctrica que puede entregar el punto para este tipo de cargas es de aproximadamente 3,7 kW.
Con este nivel de potencia, el proceso de carga de la batería tarda unas 8 horas. Esta solución es óptima, fundamentalmente, para recargar el vehículo eléctrico durante la noche en un garaje de una vivienda unifamiliar o garaje comunitario.
Para conseguir que el vehículo eléctrico sea una realidad y teniendo en cuenta el sistema eléctrico actual, la recarga óptima desde el punto de vista de eficiencia energética, es realizar este tipo de recarga durante el período nocturno, que es cuando menos demanda energéticaexiste.

RECARGA SEMI-RÁPIDA (32 Amperios)
El vehículo se enchufa durante aproximadamente 4 horas, la mitad de las horas que implica la recarga convencional, para obtener una carga completa.
La carga semi-rápida emplea 32 amperios de intensidad y 230 VAC de voltaje eléctrico. Esto implica que la potencia eléctrica que puede entregar el punto para este tipo de cargas es de aproximadamente 7,3kW.
Con este nivel de potencia, el proceso de carga de la batería tarda unas 4 horas. Esta solución es óptima, fundamentalmente, para recargar el vehículo eléctrico durante la noche en un garaje de una vivienda unifamiliar o garaje comunitario.
RECARGA RÁPIDA
El vehículo se enchufa durante aproximadamente 30 minutos para obtener una carga del 80% de la batería.
La carga rápida emplea una mayor intensidad eléctrica y, además, entrega la energía en corriente continua, obteniéndose una potencia de salida del orden de 50kW.
Esta solución es la que, desde el punto de vista del cliente, se asemeja a sus hábitos actuales de repostaje con un vehículo de combustión.
Esta cargas deben ser concebidas como extensión de autonomía o cargas de conveniencia.
Las exigencias a nivel eléctrico son mayores que en la recarga convencional. Lo que puede implicar la necesidad de adecuación de la red eléctrica existente. Por poner una referencia, la potencia requerida para este tipo de instalaciones es comparable a la de un edificio de 15 viviendas.

 
Una de las dudas más recurrentes acerca de los vehículos eléctricos es la referente al tema de su recarga: ¿cómo recargo mi vehículo?, ¿durante cuánto tiempo lo tengo que dejar cargando?

La recarga de los vehículos eléctricos depende fundamentalmente del tipo de carga, el modo de carga y el tipo de conector. Estos factores dependen de las características que presente tu vehículo y del lugar donde recargues tu vehículo.
Un aspecto importante es destacar que, a día de hoy, no todos los vehículos eléctricos disponen de las mismas características de carga. Es importante que te informes bien en el concesionario y preguntes acerca de este tema antes de comprar el vehículo.
Carga en casa. Por las noches.
Siempre que te sea posible, lo más cómodo y usual es que recargues tu vehículo en tu vivienda (o en su defecto en el trabajo) en caso de tener esta posibilidad. La solución más económica es recargar el vehículo por la noche, cuando las tarifas son de bajo coste (durante el periodo nocturno puede llegar a ser un tercio del coste durante el día). Con las autonomías actuales de los vehículos, éstos pueden quedar cargados sin problema al 100% como máximo en 8 horas siempre que para la recarga estés utilizando un punto de recarga específico de vehículo eléctrico.
Cuando se adquiere el vehículo en el concesionario, normalmente suele venir con un cable que llaman de “emergencia” y que es compatible con un enchufe doméstico (Schuko). Aun así, esto no suele ser lo más recomendable, ya que es probable que el enchufe del que dispongas en tu vivienda no esté dimensionado eléctricamente para un uso intensivo como es el de la carga de un vehículo eléctrico y además, cargarlo en un enchufe doméstico en lugar de utilizar un punto de recarga específico siempre conllevará más tiempo de recarga. Por ello, lo más recomendable sería la utilización de un punto de recarga específico instalado normalmente en alguna pared anexa a la plaza de garaje para conseguir una mayor seguridad y eficacia en la recarga de nuestro vehículo.

 
Por otro lado, tenemos que conocer qué conector tiene nuestro vehículo, es decir, qué conector está en la bocana del vehículo donde conectamos uno de los lados del cable de carga. Existen dos tipos: algunos vehículos vienen con un tipo de conector denominado técnicamente como SAE J1772 (conector tipo 1) o y otros con un conector Mennekes (conector tipo 2). Es importante conocer que no todos los vehículos tienen el mismo conector en la estructura del vehículo, sobre todo porque si nos encontramos en la calle con un punto de recarga con el cable incorporado que vaya directamente a la bocana del vehículo, debemos cerciorarnos de que es compatible.Físicamente es sencillo, porque físicamente no se puede conectar un cable con conector de un tipo en un vehículo que tenga otra tipología. Como todo producto que es nuevo y que evoluciona, seguramente en el futuro solo haya una tipología de conector, (como ha ocurrido con los USB) pero hasta que llegue ese momento debemos tener en cuenta esto cuando compremos nuestro vehículo.
Además de este tipo de recarga convencional, donde hemos dicho que con las baterías actuales se carga aproximadamente un vehículo eléctrico 100% entre 6 y 8 horas, hay vehículos que adicionalmente tienen otras tipologías de carga (Carga semirrápida o carga rápida) que permiten al vehículo poder cargar en una hora o en 30 minutos el 80% de la batería. Esta carga más rápida solo es posible si por un lado el vehículo dispone de esta funcionalidad y por otro se utiliza la infraestructura de recarga adecuada. A continuación se explica un poco más esta posibilidad.
En cualquier caso os recomendamos que os informéis bien de las opciones disponibles respecto a tipos de conectores, tipos de recarga y modos de recarga que más se adecuan a nuestras necesidades específicas.
Carga en vía pública.
La carga semirrápida y la carga rápida se encuentran principalmente en la infraestructura de acceso público ( vía pública, estaciones de servicios, centros comerciales, etc). La primera nos da la posibilidad de cargar nuestro vehículo en una hora aproximadamente y la segunda nos permite cargar hasta el 80% de la batería del vehículo en unos 30 minutos (dependiendo también del vehículo) siendo, a día de hoy, la que más se asemeja al repostaje en gasolineras convencionales.
Algunos vehículos traen de serie la carga rápida, otros como un opcional y otros no la contemplan. Es importante tener en cuenta antes de comprar el vehículo si tiene esta opción. En caso afirmativo, su coste (algunos fabricantes la ponen de serie y otros como un opcional con coste), porque para determinados usos, puede ser necesario utilizar una carga más rápida y si el vehículo no la contempla, luego no se puede incorporar.
Entre los tipos de conectores que permiten la carga rápida nos encontramos, los conectores CCS Combo, conector CHAdeMO y el conector Mennkes.
Para finalizar
Si vas a poder cargar tu vehículo en tu casa bajo el mismo contrato eléctrico de tu vivienda, debes valorar si pasarte o no a una tarifa con discriminación horaria, ya que puede suponerte un ahorro considerable si vas a poder cargar tu vehículo durante la noche. Tanto los vehículos como algunos puntos de recarga pueden programar la carga y cargarlo durante las horas más baratas, pudiendo dejar el cable conectado el vehículo se pondrá a cargar a la una de la mañana, cuando la energía es más barata (siempre que tengas una tarifa con discriminación horaria)
En el caso de carga rápida, lo más recomendable es proceder a la misma cuando la batería esté lo más descargada posible, para conseguir una mayor eficiencia en el proceso. Aun así se recomienda no utilizar esta tipología de carga como la carga habitual y única de la batería.
Es importante no olvidarse de llevar siempre en el maletero los tipos de cable que tu vehículo permite para poder hacer frente a cualquier eventualidad que pudiera surgir (cable de emergencia con un Schuko).
Antes de dejar el vehículo, siempre que no hayas programado la carga para más tarde, está bien que te asegures de que el proceso de recarga se ha iniciado correctamente, comprobándolo en el cuadro de mando del vehículo o dependiendo del modelo en las indicaciones del conector o en las señales luminosas del vehículo.
Desde Endesa recomendamos siempre la instalación de un punto de recarga en casa, en lugar de cargar tu vehículo directamente al enchufe de tu vivienda, por motivos de seguridad, comodidad y reducción del tiempo de carga.


## User Persona ##

Nuestra User persona utilizamos el método de shadowing en redes sociales, que nos permitió conocer en poco tiempo, a los dueños de autos eléctricos que fomentan el uso de ellos. Realizamos una encuesta que hicimos llegar a un club de Fans de Autos Eléctricos, sin embargo la falta de tiempo no permitió que ellos nos dieran alguna respuesta favorable. Por lo que optamos por encontrar un perfil con respecto a los distintos perfiles que localizamos de personas que tienen autos eléctricos buscando un patrón de ellos. Por lo regular son personas que tienen familia, y ven a futuro por el bienestar de ellos.



## Storyboard ##
Historia de nuestro usuario documentada en video:

Allan sale de su hogar y aborda junto con su esposa un Taxari vehículo Italiano 100% eléctrico, empieza a narrar cómo se utilizan este tipo de vehículos nos comenta que el precio del auto es de $669,000 MXN,narra el recorrido que tiene que efectuar en las mañanas  con su auto eléctrico , su esposa cometa de que un detalle con los autos eléctricos es que la cuestión de la carga es delicada debido a que puedes quedarte sin carga y es un problemática nuevamente por la falta de infraestructua, también menciona que la carga del vehículo se da con una corriente 220 y rinde hasta 150 Km con una carga de entre 9 y 10 horas. 

Video:
https://www.facebook.com/franciscomcabeza/videos/vb.713948332/10156341035933333/?type=2&video_source=user_video_tab

## Propuesta de Valor ##

Para este punto ya utilizando las herramientas del análisis de heurísticas de la aplicación Müeve, así como un benchmark de la competencia que nos permitió verificar que están ofreciendo en sus aplicaciones y que se podría implementar, este segmento de México, de enero a octubre del 2018 se han vendido en México 13,925 unidades híbridas o eléctricas, en el mismo periodo del año pasado las unidades comercializadas ascendían a 8,288 unidades, lo que representa un crecimiento de 68 por ciento. Por lo que es una gran oportunidad de negocio que pretende que desde la app se puedan realizar estos cobros, así como sincronizar toda la información que se tiene desde los puntos de recarga, a través de API’S.

Decidimos utilizar la herramienta de value proposition canvas para fijar qué es lo que se tenía que corregir de diseño en la aplicación.




