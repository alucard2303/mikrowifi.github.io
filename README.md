=== JUANFI WIFI SYSTEM - DOCUMENTACIÓN DE PLANTILLA DE HOTSPOT MIKROTIK ===

Descripción:
JuanFi Hotspot Template es un tema Bootstrap mínimo creado y diseñado para el sistema JuanFi Wifi utilizando enrutadores mikrtotik. Cuenta con sus créditos wifi actuales, como el tiempo restante, extender el tiempo, insertar monedas e iniciar y cerrar sesión en la red wifi. La plantilla de punto de acceso Mikrotik del sistema Wifi de JuanFi es un tema receptivo integrado en el marco Bootstrap 5.

Colaboradores: smrtrnx
Etiquetas: Juanfi, HotspotTemplate, Mikrotik

Requiere routers mikrotik y Sistema Wifi Juanfi
Probado en: mikrotik haplite y mikrotik hex

Etiqueta estable: 1.1.0
Licencia: GNU General Public License v2 o posterior
URI de licencia: LICENCIA

Una plantilla de punto de acceso mikrotik creada para el sistema Juanfi Wifi

== Descripción ==

Descripción


== DERECHOS DE AUTOR Y LICENCIA ==

Plantilla de punto de acceso JuanFi Mikrotik, Copyright 2021 smrtrnx.

Juanfi Mikrotik Hotspot Template se distribuye bajo los términos de GNU GPL

Este programa es software libre: puedes redistribuirlo y/o modificar
bajo los términos de la Licencia Pública General GNU publicada por
la Free Software Foundation, ya sea la versión 3 de la Licencia, o
(a su elección) cualquier versión posterior.

Este programa se distribuye con la esperanza de que sea útil,
pero SIN NINGUNA GARANTIA; sin siquiera la garantía implícita de
COMERCIABILIDAD o IDONEIDAD PARA UN FIN DETERMINADO. Ver el
Licencia Pública General GNU para más detalles.

== INSTALACIÓN ==

Lea todo el proceso de instalación antes de hacerlo.

NOTA:

EL RIESGO ES TUYO, te sugiero que crees una copia de seguridad de tu configuración reciente.

REQUISITOS DEL SISTEMA:

Mikrotik Hex y Haplite o cualquier Mikrotik que admita MicroSD para alojar los archivos de temas.

1. Inicie sesión en el enrutador Mikrotik usando winbox
2. Ir a Archivos
3. Arrastre y suelte la carpeta dist
   (Si su enrutador es compatible con MicroSD, guarde los archivos dist en la tarjeta MicroSD)
   (Ejemplo: Disco1/)
4. Vaya a Mikrotik IP > Hotspot > Perfiles de servidor > hsprof1
5. Cambie el Directorio HTML a dist
   (Si guardó los archivos del tema en la tarjeta MicroSD Disk1, luego seleccione Disk1/dist)

6. Modifique el archivo bundle.min.js
   - Abra el paquete.min.js con su editor de texto especificado
   - Presiona CTRL+F y pega vendoIp:
   - Cambie el vendoIp: según corresponda, coincida con la dirección IP de su ESP8266
   - Puede verificar su DIRECCIÓN IP ESP8266 yendo a Mikrotik> IP> SERVIDOR DHCP> ARRENDAMIENTOS, usando winbox o webfig
   - Guarde y cargue el archivo bundle.min.js en el directorio dist/assets/js en sus archivos Mikrotik que cargó en el PASO 3.

== Preguntas Frecuentes ==

= ¿Este tema admite complementos? (No)

== Créditos ==

* JuanFi https://github.com/ivanalayan15/JuanFi, ivanalayan15/JuanFi tiene licencia Apache License 2.0 [https://github.com/ivanalayan15/JuanFi/blob/master/LICENSE]

* smrtrnx https://github.com/smrtrnx/JuanFiTemplate, Designer / Frontend Developer tiene licencia bajo GNU GENERAL PUBLIC LICENSE

* Bootstrap 5 de twitter está autorizado bajo la licencia MIT. https://github.com/twbs/bootstrap/blob/master/LICENSE.

* jquery.min.js Fundación OpenJS y JQuery https://openjsf.org/, Licencia JQuery https://jquery.org/license/
