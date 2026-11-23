## Contexto: IT y OT

* **IT (tecnologias de la informacion):** sistemas informaticos de una empresa, como servidores, redes, bases de datos y aplicaciones.
* **OT (tecnologías de operación):** sistemas que controlan maquinas y procesos fasicos, como robots, sensores o lineas de produccion.

Hoy las fabricas conectan sus maquinas (OT) a las redes de la empresa (IT). Las THD ayudan a que esa union funcione y sea segura. Parte de los ejemplos vienen de **Telefonica**, la unidad del grupo Telefonica que reune sus servicios de ciberseguridad, cloud, IoT y big data.

| THD | Donnde la usa Telefonica | Mejora IT-OT |
|---|---|---|
| Big data | Servicios de anAlisis de datos para empresas | Los datos de la planta se convierten en decisiones |
| IA | Computer Vision, análisis de vídeo con IA | Lo que ven las cámaras de la planta se analiza al instante |
| IoT | Lineas IoT, balizas V16, contadores de agua | Los objetos físicos envían datos a los sistemas IT |
| Cloud | Nube VDC y servicio multicloud TROS | La infraestructura IT crece según se necesita |
| Ciberseguridad | Servicio gestionado de seguridad OT e IoT | Se protegen a la vez los entornos IT y OT |


## 1. Big data

**Definicion.** Conjunto de tecnologias que permiten recopilar, analizar y tratar grandes cantidades de datos de distintas fuentes para sacar conclusiones útiles.

**Características principales:**

* **Volumen:** procesa cantidades enormes de datos.
* **Velocidad:** puede analizar los datos casi en tiempo real.
* **Variedad:** trata datos de distintos tipos y orígenes (texto, audio, video, etc).

**Aplicación en Telefónica.** Telefónica ofrece a sus clientes servicios de Big Data divididos en arquitectura del dato, ciencia de datos, visualización (paneles interactivos) e ingeniería de datos. En 2024, Telefónica Tech e IBM firmaron un acuerdo para desarrollar una plataforma abierta, híbrida y multicloud de analítica, gestión del dato e IA, con una oficina de casos de uso para hacer pilotos con clientes.

**Mejora IT-OT.** El IoT conecta los sensores de las máquinas (OT) y esos datos llegan a las herramientas de Big Data (IT), que los analizan. Telefónica indica, por ejemplo, que sirve para vigilar la cadena de valor y detectar qué fases de un proceso son ineficientes.


## 2. Inteligencia artificial (IA)

**Definición.** Tecnología que permite a las máquinas analizar información y sacar conclusiones o tomar decisiones. En Telefónica se ve sobre todo en la visión artificial, que permite a una máquina entender qué hay en una imagen o vídeo.

**Características principales:**

* Analiza vídeo e imágenes en tiempo real a partir de cámaras.
* Se ofrece en una plataforma propia en la nube, con pago por uso.
* Incluye casos de uso ya preparados, como control logístico, conteo de personas u optimización de procesos manuales.

**Aplicación en Telefónica.** Con Computer Vision, la empresa de transporte DB Schenker mide el 100% de la carga en 30 segundos y en tiempo real, sin que un operario tenga que intervenir. En el MWC 2024, Telefónica y Würth enseñaron casos de uso para centros logísticos sobre 5G, como la detección de atascos de cajas en cintas transportadoras o la auditoría del contenido de las cajas ante reclamaciones.

**Mejora IT-OT.** Las cámaras y las máquinas de la planta (OT) generan vídeo, y la IA, que es parte de IT, lo analiza al momento para automatizar tareas que antes hacía una persona.


## 3. Internet de las cosas (IoT)

**Definición.** Conexión a Internet de objetos y dispositivos con sensores (máquinas, contadores, vehículos...) para que envíen datos sin intervención humana.

**Características principales:**

* Usa redes pensadas para dispositivos, como NB-IoT.
* Es la fuente de datos de las otras tecnologías: genera la información que luego analizan el Big Data y la IA.
* Se aplica en sectores como la industria, la salud y las utilities (agua y gas).

**Aplicacion en Telefónica.** Telefónica Tech mantiene el liderazgo del mercado IoT en España con 17 millones de líneas. Un ejemplo son las balizas V16: su conectividad IoT envía la geolocalización del vehículo parado a la plataforma de la DGT, que avisa al resto de conductores. Otro caso es el de Global Omnium, que tiene cientos de miles de contadores de agua que se leen a distancia con NB-IoT.

**Mejora IT-OT.** Los dispositivos físicos (OT) pasan a estar conectados y envían sus datos a las plataformas de gestión (IT), de modo que se pueden vigilar y mantener a distancia.

## 4. Cloud

**Definición.** Uso de servidores y servicios informáticos a través de Internet, en vez de tenerlos instalados en la propia empresa.

**Características principales:**

* Permite añadir recursos a medida que se necesitan y pagar por uso.
* Puede ser pública, privada o híbrida (una mezcla de ambas).
* Cada empresa puede elegir dónde guardar sus datos según sus requisitos de seguridad o normativa.

**Aplicación en Telefónica.** La ONCE ha migrado sus servicios a la nube VDC (Virtual Data Center) de Telefónica Tech, que incluye también comunicaciones y ciberseguridad con un modelo de pago por uso. Además, Telefónica Tech ofrece TROS, un servicio multicloud basado en Red Hat OpenShift para modernizar aplicaciones mediante contenedores.

**Mejora IT-OT.** La nube da a IT la capacidad para almacenar y procesar los datos que generan las máquinas. Con la nube híbrida, los datos sensibles pueden quedarse en las instalaciones de la empresa y el resto ir a la nube.

## 5. Ciberseguridad

**Definición.** Conjunto de tecnologías y servicios que protegen sistemas, redes y datos frente a ataques. En la industria incluye proteger también las máquinas y dispositivos conectados.

**Características principales:**

* Vigila el tráfico de la red para ver qué dispositivos hay conectados y detectar anomalías.
* Se ofrece como servicio gestionado desde centros de operaciones de seguridad (SOC).
* Cubre a la vez IT, OT e IoT.

**Aplicación en Telefónica.** Telefónica Tech ofrece un servicio gestionado de seguridad OT e IoT basado en la tecnología de Nozomi Networks, atendido desde su red de 11 SOC. Analiza el tráfico de la red del cliente de forma pasiva, mediante sondas, y avisa si detecta incidencias graves. Además, ha desarrollado Aristeo, una red de señuelos con hardware industrial real que se despliega en Internet para atraer y estudiar ataques. Avasant la ha reconocido como líder en servicios de ciberseguridad por tercer año consecutivo.

**Mejora IT-OT.** Al conectar las fábricas a las redes IT, las máquinas OT antiguas quedan expuestas a ataques. Un servicio que vigila IT y OT a la vez da una visión común de los riesgos de los dos entornos.

## Conclusiones

La THD mas determinante para el modelo de negocio de Telefonica es la ciberseguridad.

El motivo es que todo lo demás depende de ella. El IoT, el Big Data, la IA y el cloud consiguen que IT y OT trabajen juntos, pero esa unión aumenta el riesgo de ataques. Sin seguridad, los clientes industriales no se atreverían a conectar sus fábricas. Además, es el área donde Telefónica tiene más reconocimientos externos y servicios propios, como el servicio gestionado OT/IoT o Aristeo.

Hay una tecnología que no está en nuestra lista pero es muy importante para Telefónica: el 5G, que es la base de su conectividad y aparece en varios casos (por ejemplo, el de Würth).


## Fuentes

* [Telefónica que és](https://www.telefonica.com/es/nosotros/)
* [Telefónica Empresas, Big Data. ](https://www.telefonicaempresas.es/grandes-empresas/tecnologias/big-data/)
* [Telefónica Empresas, Servicios Big Data.](https://www.telefonicaempresas.es/grandes-empresas/servicios/para-tus-procesos/soluciones-ia-y-big-data/servicios-big-data/)
* [Telefonica Empresas, Computer Vision.](https://www.telefonicaempresas.es/grandes-empresas/servicios/para-tus-procesos/soluciones-ia-y-big-data/computer-vision-analisis-ia-mediante-video/)
* [Telefónica transforma la gestión logística en su propuesta de Industria Inteligente en el MWC.](https://www.telefonica.com/es/sala-comunicacion/telefonica-transforma-la-gestion-logistica-en-su-propuesta-de-industria-inteligente-en-el-mwc)
* [AI logistics: la revolucion de la inteligencia artificial en los centros logísticos.](https://www.telefonica.com/es/mwc/agora-2024/ai-logistics-la-revolucion-de-la-inteligencia-artificial-en-los-centros-logisticos/)
* [Telefónica Empresas, Soluciones IoT para empresas.]( https://www.telefonicaempresas.es/grandes-empresas/servicios/para-tus-procesos/soluciones-iot-para-empresas/)
* [Telefónica Tech mantiene el liderazgo en el mercado español de IoT con 17 millones de líneas.]( https://www.telefonica.com/es/sala-comunicacion/prensa/telefonica-tech-mantiene-liderazgo-mercado-espanol-iot-17-millones-lineas/)
* [NB-IoT para la transformación digital del agua. ](https://www.telefonica.com/es/sala-comunicacion/blog/nb-iot-agua/)
* [ Telefónica Empresas, Nube pública y privada.]( https://www.telefonicaempresas.es/grandes-empresas/servicios/para-tu-nube/nube-publica-y-privada/)
* [La ONCE elige a Telefónica Tech para migrar sus servicios a Cloud.]( https://www.telefonica.com/es/sala-comunicacion/prensa/la-once-elige-a-telefonica-tech-para-migrar-sus-servicios-a-cloud/)
* [Telefónica Empresas, Ciberseguridad.]( https://www.telefonicaempresas.es/grandes-empresas/servicios/para-tu-ciberseguridad-y-seguridad-tecnologica/ciberseguridad/)
* [Telefónica Tech monitorizará la seguridad en entornos industriales y de IoT.]( https://www.telefonica.com/es/sala-comunicacion/prensa/telefonica-tech-monitorizara-la-seguridad-en-entornos-industriales-y-de-iot/)
[Telefónica Tech, compañía líder en servicios de ciberseguridad por Avasant.]( https://www.telefonica.com/es/sala-comunicacion/prensa/telefonica-tech-compania-lider-servicios-ciberseguridad-avasant/)