---
layout: post
title: "Evitar resultados de IA en buscadores web usando Opera"
date: 2026-01-17 15:49:26 -0300
categories: 
description: Cómo configurar uBlock en Opera para bloquear resultados de IA en buscadores y mejorar tu privacidad. Tutorial paso a paso. Con Alma Tech.
image: /assets/images/ublockenopera.png
---

Los bloqueadores de anuncios son herramientas fundamentales para proteger nuestra seguridad digital. Más allá de mejorar la experiencia de navegación al eliminar publicidades molestas, estos complementos actúan como una primera línea de defensa contra rastreadores, scripts maliciosos y sitios web que intentan recopilar información personal sin nuestro consentimiento. En esta ocasión te muestro cómo además se pueden configurar para evitar los resultados de Inteligencia Artificial en los buscadores online.

## Instalación y configuración en Opera

### Paso 1: Acceder a la tienda de addons
Podés hacerlo ingresando a [https://addons.opera.com](https://addons.opera.com)

### Paso 2: Instalar la extensión
Usás el buscador para encontrar la extensión "uBlock" y la agregás al navegador. Para que no queden dudas, el logo de la extensión es ésta:

![image](/assets/images/ublockresultsearch.png)

### Paso 3: Abrir la configuración
Una vez que instalaste la extensión, desde los tres puntos en la esquina inferior izquierda del navegador seleccionando "Extensiones" vas a encontrar el listado de todas las extensiones que tenés instaladas. Buscás uBlock y seleccionás "Detalles" o "Configuración" (según la versión que tengas) y vas a ver un listado de configuraciones extenso como éste:

![image](/assets/images/ublocksettings.png)

Vas a seleccionar "Opciones de la extensión" donde se muestran todas las adaptaciones que podés hacer en uBlock.

### Paso 4: Realizar las modificaciones necesarias
Una vez dentro del menú de opciones de la extensión vas a seleccionar la pestaña "Mis filtros" y vas a escribir lo siguiente en la primera línea del casillero de texto:

google.com##.GcKpu

Te va a quedar algo más o menos así:

![image](/assets/images/ublockmyfilters.png)

Guardas todos los cambios y la próxima vez que utilices Google los resultados se van a mostrar como en la versión web tradicional sin IA ni sugerencias, etc.


## #datazo
Esta misma configuración se puede utilizar en todos los navegadores que permiten uBlock como extensión, no lo probé en otros porque estoy utilizando los que sugerí en este reel de Instagram pero leí por allí que sirve para todos ;)

_Nota: este post se escribió y se testeó en enero de 2026, las cosas cambian muy rápidamente así que tené en cuenta que depende cuándo lo estés leyendo puede que las interfaces y funcionalidades hayan cambiado._
---

Si te resultó útil este tutorial y querés seguir aprendiendo sobre seguridad digital, privacidad online y herramientas para proteger tu navegación, te invito a seguirme en mis redes sociales. También ofrecemos [asesoría y capacitación](/asesoria-capacitacion/) para equipos que quieran profundizar en estos temas.
