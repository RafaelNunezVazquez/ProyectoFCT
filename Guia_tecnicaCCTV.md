# Esta guía nos orientará en la materia de circuito cerrado de televison o CCTV.

![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/22212e16-d10b-4740-87e7-2f0cdcad309c)

Generalmente la finalidad de un CCTV se relaciona con mejorar la seguridad de distintos sectores, pueden ir desde aplicaciones sencillas, de tipo residencial, hasta aplicaciones complejas de vigilancia ciudadana.

![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/3deed16b-625e-4e87-8dae-60bcde7fee65)

También tiene otras aplicaciones que no están necesariamente orientadas a la seguridad, se puede usar para el control de procesos industriales o logísticos, control del tráfico, en el sector salud y así como en estudios académicos.

![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/ccbe801f-3dc8-4620-b940-9597b13feaa1)

## Tipos de CCTV.

### 1. CCTV analogico:

            * Generalmente tiene resoluciones más bajas comparadas con los sistemas digitales (SD a HD).
      
            * Se graba en un DVR (Digital Video Recorder), que convierte la señal analógica a digital para almacenamiento.

            * Utiliza cámaras analógicas que transmiten señales de video a través de cables coaxiales.

            * Los formatos de video analógico son varios: HDCVI, HDTVI, AHD.

            * Usos comunes:
                        
                        Instalaciones pequeñas y medianas con requisitos básicos de videovigilancia.
                        Instalaciones antiguas donde la infraestructura de cables coaxiales ya está instalada.

![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/a8fe9b7c-77a4-4261-b9a1-0758b0417089)

 
### 2. CCTV Digital o IP:

            * Utiliza cámaras IP (Internet Protocol) que transmiten datos de video digitalmente a través de una red (LAN/WAN).

            * La calidad de video puede ser muy alta, con soporte para resoluciones como 1080p, 4K y más, dependiendo de las cámaras IP utilizadas.   
            * Se graba en un NVR (Network Video Recorder) o servidores de red

            * Usos comunes:
           
            * Instalaciones grandes y sofisticadas con necesidades avanzadas de videovigilancia.
            * Cuando las localizaciones de las cámaras estén dispersas y lejos del centro de control a distancias habitualmente mayores  de 100 metros.

   ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/d9525723-f181-4d90-abd1-e23131bee3e4)

   
### 3. CCTV híbridos:

            * Es posible considerar un sistema hibrido al realizar la migración de un sistema CCTV análogo a un sistema de seguridad IP

            * Utilizando la misma infraestructura en cableado coaxial existente para transmitir video digital desde cámaras IP.
            
            * La migracion se hace más facil usando conectores como LR1002 de PoE a BNC. 

            * Utiliza un XVR (eXtended Video Recorder) o un NVR híbrido que puede manejar ambas señales analógicas y digitales.

            * Combina cámaras analógicas y cámaras IP en un mismo sistema.

            * Usos comunes:
               
               Instalaciones que están migrando de sistemas analógicos a digitales.
               Lugares donde se quiere aprovechar la infraestructura existente mientras se agregan cámaras IP.

   ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/859a5b2c-c81e-4341-961e-a4afa28fc496)

   ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/710c62c5-4c13-4675-9040-32617dbb6649)

## Componentes necesarios para un CCTV.

### 1. Grabador DVR,XVR o NVR:

- DVR: (Digital Video Recorder) se utiliza principalmente con cámaras analógicas.

      Las cámaras analógicas envían señales de video a la DVR, que convierte estas señales analógicas a formato digital y luego las  almacena en un disco duro.

      Requiere cables coaxiales o UTP para la transmisión de video y cables de alimentación para cada cámara.

  ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/ca076526-fe18-436a-bb47-c956474737a2)


- NVR: (Network Video Recorder) se utiliza con cámaras IP (cámaras de red).

            Graba video desde cámaras IP que envían datos de video a través de una red (LAN/WAN).
            Utiliza cables Ethernet para la transmisión de datos y, si es compatible con PoE (Power over Ethernet), también puede alimentar las cámaras a través del mismo cable.            
            Las cámaras IP digitalizan el video y lo transmiten a través de una red Ethernet. La NVR recibe estos flujos de datos digitales y los almacena en un disco duro.            

  ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/0b620de7-aae3-49ea-9b01-c48351b553ca)
      

- XVR: (eXtended Video Recorder) es una grabadora híbrida que admite tanto cámaras analógicas como cámaras IP.

              Combina las funcionalidades de DVR y NVR, permitiendo la conexión de cámaras analógicas y cámaras IP.
              Puede recibir señales analógicas y convertirlas a digital, así como recibir flujos de datos digitales de cámaras IP a través de una red.
              Ofrece flexibilidad en la configuración de sistemas de videovigilancia híbridos, utilizando cables coaxiales para cámaras analógicas y cables Ethernet para cámaras IP.

    ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/ae0c25a4-a02d-4b90-8c55-22e1fda03b54)

### 2.  Disco Duro: Su tamaño determina la cantidad de tiempo que la grabadora podrá grabar dependiendo de varios factores, formato de imagen, cantidad de camaras, etc..

            Por ello cuando elegimos el disco duro debeos tener en cuenta los siguientes factores:
                 * Numero de canales en grabador (camaras).
                 * Resolucion de las camaras.
                 * Tasa de bits (bitrate).
                 * Dias de retencion deseados.
                 * Compresion de video ej: H264,H265...

            Pasos para calcular el almacenamiento existe un procedimiento pero las distribuidoras tienen su propia calculadora diseñada para facilitar los calculos. 

Aqui dejo el enlace a la calculadora de almacenamiento de la pagina web de Dahua un gran distribuidor.

https://us.dahuasecurity.com/support/software-downloads-and-tools/capacity-calculator/

   ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/c0be8cd4-3c68-48e6-9292-53753d606a05)

### 3. Camaras. Generalmente se utilizan estos.

   - bullet:

            Caracteristicas:

                * Forma: Tienen una carcasa cilíndrica, lo que facilita el apuntamiento preciso hacia áreas específicas.
                * Montaje: Normalmente se montan en paredes o postes
                * Visibilidad: Son más visibles y disuasorias, en su  contra, se ve haca donde apunta facilitando a vandalos o ladrones.
                * Alcance: Generalmente tienen lentes de largo alcance, ideales para distancias mayores.

            Usos comunes:
                             
                 Interiores:
                             
                 Exteriores:
                            * Son ideales para monitorear áreas exteriores como estacionamientos, entradas y perímetros 
                            * Enfoque en Áreas Específicas: Perfectas para vigilar entradas, portones y áreas específicas donde se necesita un enfoque dirigido y claro. 

     ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/47799f03-d609-4fa7-88f7-609d3a010ffb)
     
   - Domo:
     
            Muchas son resistentes a vandalismo (vandal-proof) y condiciones climáticas (weatherproof).       
            Compactas y de forma semiesférica, se instalan generalmente en techos o paredes.
            Menos visibles y más estéticas, se mezclan fácilmente con el entorno.

            Usos comunes:
                 Interiores:
                             Tiendas y comercios: Para monitorear áreas de venta y prevenir robos, sacar grabaciones en caso de robo.
                             Bancos y cajeros automáticos: Para seguridad adicional y monitoreo de actividades sospechosas.
                             Oficinas: Para vigilancia de pasillos, entradas y áreas comunes.

                 Exteriores:

                             Entradas y salidas: Para monitorear puntos de acceso, con versiones resistentes a la intemperie.
                             Garajes y estacionamientos: Para supervisar vehículos y actividades.
                             Edificios públicos: Por su resistencia a vandalismo y su diseño discreto.
                                       

     ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/a8317b7a-e5cc-44f0-80b6-f905961e6474)
     
   - IP:

           * Ofrecen resoluciones desde 720p (HD) hasta 4K y superiores, proporcionando imágenes claras y detalladas.
           * Se conectan a una red IP a través de cables Ethernet o de forma inalámbrica mediante Wi-Fi.
           * Ofrecen imágenes de alta resolución y calidad superior en comparación con las cámaras analógicas.
           * Facilitan la adición de nuevas cámaras sin necesidad de cambiar la infraestructura de cableado existente.
           * Incorporan análisis de video y funciones inteligentes que mejoran la eficacia de la vigilancia y la seguridad.
           * Almacenamiento en tarjetas SD integradas, en dispositivos de almacenamiento en red (NAS), o en servidores en la nube.
           * Autenticación y autorización para acceso seguro a la cámara.
           
     ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/5566fdb2-29e3-4931-82fc-0c2ea582ac72)

     
### 4. Fuentes de alimentación para las cámaras CCTV:

         - Una fuente de alimentación por cámara: esto requiere empalmar corriente que sea activa 24 horas.
       
   ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/b2b4543f-4b72-4893-8b6b-cbb23dda0767)

        - Una gran fuente de alimentación junto al grabador: centraliza el suministro de energía en un solo lugar.
       
   ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/3d97b00c-5c67-4342-9e1a-b1f065c3c18e)

### 5. Cables. Es importante que sea el adecuado dependiendo de la situación.

   - Para conectar el sistema de video de las cámaras usamos dos tipos de cables:
     
   -       Cable coaxial de dos hilos: el clásico. Válido si no se necesitan cámaras IP.
   -       Cable UTP: cada vez más usado, válido en cualquier situación.
     
   - Para conectar la corriente usamos:
  
   -       Cable de corriente: sacamos corriente de un punto cercano a la camara, empalmamos fuente alimentacion.

      ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/ce834da8-08d6-4737-a157-c9c527e5cdb3)

   -       Cable UTP: con un par de hilos del cable UTP llevamos la corriente desde la fuente de rejilla hasta la cámara.

      ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/6288cab6-07f4-4b15-bb81-4151d05bea26)

### 6. Cartel de zona video vigilada:
   
   - Para cumplir con la Ley Orgánica de Protección de Datos (LOPD) se debe instalar un cartel que muestra que la zona está siendo           grabada. Es preferible incluir varios carteles en las zonas donde el sistema de CCTV tenga alcance.

      ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/b1922069-993d-48e9-9282-7e1ccf01e4ea)

### 7. Conectores: Usamos dos tipos de conectores.

   -  Video :

   -       Cable BNC o video balum: ()

      ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/017c7828-7f7b-4f2f-8154-05057eb06429)

   -  Corriente :
   
   -     Conector DC de tornillo. Estos los usamos cuando la corriente viene de fuente de rejilla y cable UTP

     ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/79deb5f6-3dc6-4a59-accb-d676aabe454f)
   
                 Ficha empalme: Estas las usamos cuando la corriente viene tirada por cable desde AC corriente alterna 220 y fuente
                 alimentacion cargador

      ![image](https://github.com/RafaelNunezVazquez/ProyectoFCT/assets/91255999/73c4bccf-63f6-4195-9a40-0fca262ee892)
