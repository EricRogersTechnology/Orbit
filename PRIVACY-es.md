# Orbit — Política de privacidad

PRIVACY-es.md → [English](https://ericrogerstechnology.com/Orbit/PRIVACY.html)

**Última actualización: 21 de julio de 2026**

Orbit (en la App Store aparece como **Orbit Dashboard**) es una app independiente de
panel personal. Esta política explica qué hace y qué no hace la app con tu información.
La versión corta: **Orbit no tiene cuenta, ni anuncios, ni analíticas. El desarrollador
no opera servidores y nunca recibe tus datos.**

Orbit accede a mucha de tu información personal —calendario, recordatorios, salud,
correo, contactos, fotos, ubicación—. Todo se lee en tu dispositivo, para mostrarlo en
tu panel. Nada se envía al desarrollador.

---

## Qué recopilamos

**El desarrollador no recopila nada.** Orbit no tiene cuentas de usuario, ni inicio de
sesión, ni publicidad, ni analíticas o SDK de seguimiento de terceros, ni un servidor
operado por el desarrollador. No hay ningún servidor del desarrollador en todo esto.

## Dónde viven tus datos

Lo que creas en Orbit —capturas, notas, tareas, proyectos, entradas de diario, rutinas,
ajustes y el diseño del panel— se guarda:

- **En tu dispositivo**, y
- **En tu propio iCloud privado** (base de datos privada de Apple CloudKit y
  almacenamiento de clave-valor de iCloud), para que se sincronice entre tu iPhone,
  iPad, Mac, Apple TV y Apple Watch.

La sincronización con iCloud usa **tu** cuenta de Apple y la infraestructura de Apple.
Se rige por la [Política de Privacidad de Apple](https://www.apple.com/legal/privacy/).
El desarrollador no tiene acceso a tus datos de iCloud.

## Información que Orbit lee de tu dispositivo

Cada una de estas es **opcional**: Orbit pregunta primero y funciona sin ninguna de
ellas:

- **Calendario y Recordatorios** — se leen, y se escriben cuando añades o completas algo.
  Provienen de las propias bases de datos de Calendario y Recordatorios de Apple en tu
  dispositivo.
- **Salud** — actividad, sueño, entrenamientos y otras métricas que actives
  individualmente, leídas de Apple Salud. Cada métrica está desactivada hasta que la
  enciendes. Orbit las lee para mostrarlas; no escribe tus datos de salud en ningún lugar
  fuera del dispositivo.
- **Contactos** — se leen en vivo de tu agenda para la sección Personas, los cumpleaños y
  los avisos para retomar contacto. Orbit no copia tu agenda en su propio almacenamiento.
- **Fotos** — se muestran en tu Cronología, y se guardan en tu fototeca solo cuando lo
  pides.
- **Ubicación** — solo "Mientras se usa la app", y solo para el tiempo. Ver más abajo.
- **Micrófono y reconocimiento de voz** — solo mientras dictas una captura. Ver más abajo.
- **HomeKit y Apple Music** — se leen solo si usas esos módulos.

Todo esto se queda en tu dispositivo. Orbit lo muestra; no lo transmite.

## Ubicación (solo para el tiempo)

Si usas el Tiempo, Orbit solicita acceso a la ubicación **"Mientras se usa la app"** para
mostrar las condiciones locales. Tus coordenadas se envían al proveedor meteorológico
para obtener un pronóstico, y **no se almacenan, no se vinculan a tu identidad y nunca se
usan para publicidad ni seguimiento**. El proveedor es **Open-Meteo**
(`open-meteo.com`); la solicitud contiene únicamente una latitud y una longitud. Si nunca
usas el Tiempo, la app no solicita tu ubicación.

## Dictado e inteligencia en el dispositivo

La Captura puede interpretar lo que escribes o dictas y convertirlo en una tarea, nota,
idea, cita o persona. Esa interpretación ocurre **en tu dispositivo** con los modelos en
el dispositivo de Apple.

**El dictado (voz a texto) es distinto y conviene aclararlo.** Orbit usa el framework
Speech de Apple para convertir tu dictado en texto. Según tu dispositivo, idioma y
versión de iOS, Apple podría realizar ese reconocimiento en sus servidores en lugar de en
el dispositivo. Ese paso es de Apple, regido por la
[Política de Privacidad de Apple](https://www.apple.com/legal/privacy/); el desarrollador
nunca recibe tu audio ni la transcripción. Si prefieres que nada salga del dispositivo,
escribe tus capturas en vez de dictarlas.

## Correo

Si conectas cuentas de correo, Orbit se comunica **directamente desde tu dispositivo con
tu proveedor de correo** mediante IMAP/SMTP. No hay ningún servidor de correo del
desarrollador de por medio, y tu correo nunca se copia a ningún otro sitio.

**Las contraseñas de tu correo se guardan en el Llavero de iOS** —no en un archivo de
ajustes, no en documentos de iCloud, ni en ningún lugar que el desarrollador pueda leer—.
Para proveedores que las requieren (como Gmail), usa una contraseña específica de la app.

Las entregas y los detalles de viaje se reconocen leyendo el correo **que ya tienes**, en
tu dispositivo, cotejando dominios de remitentes y números de seguimiento. Orbit **no**
contacta a transportistas, aerolíneas ni sitios de reservas para hacerlo.

## Otros servicios que puedes conectar

Todos opcionales, todos desactivados hasta que los conectas, y cada uno se comunica
directamente desde tu dispositivo:

- **Noticias / RSS** — las fuentes que añadas, y **Feedly** (`feedly.com`) si conectas una
  cuenta.
- **Bolsa** — datos de cotización de Yahoo Finance (`query1.finance.yahoo.com`) para los
  símbolos de tu lista de seguimiento.
- **Ventas de App Store Connect** — si publicas apps, Orbit lee tus propios informes de
  ventas desde `api.appstoreconnect.apple.com` con una clave de API que **tú** creas y
  pegas. La clave se guarda en tu Llavero.
- **Ring** — si conectas una cuenta de Ring para el módulo de Garaje/Casa.

Las credenciales de estos servicios viven en tu Llavero. El desarrollador no recibe nada
de ninguno de ellos.

## Conexiones de red que hace la app

En resumen, Orbit se conecta con:

1. **iCloud de Apple** — para sincronizar tus propios datos entre tus propios
   dispositivos.
2. **Tu proveedor de correo** — directamente, solo si conectas una cuenta.
3. **Open-Meteo** — para el tiempo, solo si lo usas.
4. **Yahoo Finance, Feedly, App Store Connect, Ring** — solo si los conectas o los usas.
5. **Las fuentes RSS que hayas añadido.**

No hay otras conexiones de red, y no se envía ningún dato al desarrollador ni a ningún
anunciante.

## Face ID

Si activas el Bloqueo de la app, Orbit usa Face ID (o el código de tu dispositivo) para
protegerla. La autenticación la gestiona por completo iOS: **la app nunca recibe tus
datos biométricos**, solo una respuesta de sí o no del sistema.

## Copia de seguridad y exportación

Orbit hace copias automáticas y puede exportar tus datos a un archivo que tú controlas.
Esos archivos se crean en tu dispositivo y van a donde tú decidas ponerlos; el
desarrollador nunca los recibe.

## Compras dentro de la app

Cualquier compra la procesa por completo la **App Store de Apple**; el desarrollador solo
recibe los informes de ventas estándar de Apple y **nunca** ve tus datos de pago.

## Menores

Orbit no está dirigido a menores y no recopila información personal de nadie.

## Cambios en esta política

Si esta política cambia, la versión actualizada se publicará aquí con una nueva fecha de
"Última actualización".

## Contacto

¿Preguntas sobre privacidad? Contacto: **Eric@EricRogersTechnology.com**
