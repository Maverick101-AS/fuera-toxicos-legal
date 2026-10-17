# Política de privacidad — Fuera Tóxicos

_Última actualización: 17 de octubre de 2026_

**Responsable del tratamiento:** Leora Digital, Murcia (España). Contacto: leora.agencia.ia@gmail.com

**Fuera Tóxicos** no te pide registro ni cuenta de usuario, no recopila tu nombre ni ningún dato que te identifique —la única excepción es el correo que puedes dejar, si quieres, al enviar una propuesta (punto 3)— y no incluye anuncios ni herramientas de seguimiento o analítica de terceros. Todo el contenido informativo (fichas de químicos, sustituciones, evidencia científica) está incluido en la app y se puede consultar sin conexión a internet.

Hay cinco funciones que se conectan a internet:

**1. El escáner de productos.** Tiene dos formas de usarse, y se comportan de manera distinta:

- **Por código de barras:** la app envía únicamente ese código —ningún dato personal— primero a nuestra propia base de datos, por si ese producto ya lo consultó alguien antes, y si no está, a Open Beauty Facts, Open Food Facts y Open Products Facts (tres bases de datos colaborativas hermanas, de la misma organización sin ánimo de lucro, independientes y externas a esta app), hasta encontrarlo. De lo que se encuentra guardamos una copia en nuestra base de datos —nombre, marca, imagen e ingredientes del producto— para que el siguiente que lo escanee no tenga que volver a preguntar fuera. Esa copia es información pública de productos: **no lleva asociado ningún identificador tuyo ni de tu dispositivo**, así que no queda registro de quién ha escaneado qué. Los servicios externos no están controlados por Fuera Tóxicos y tienen su propia política de privacidad.
- **Leyendo la etiqueta con la cámara:** la foto **no sale de tu móvil en ningún momento**. El reconocimiento del texto se hace en el propio dispositivo (ML Kit de Google en Android, a través de los servicios de Google Play ya instalados en el teléfono; Apple Vision en iOS, que forma parte del sistema operativo). No se envía la imagen a ningún servidor, ni al nuestro ni a terceros. La foto se te muestra en la pantalla del resultado, para que puedas comprobar qué se ha leído y descartar lo que no sea la lista de ingredientes, y **no se guarda en ningún sitio**: la copia temporal que hace el móvil se borra en cuanto deja de mostrarse, al escanear otra cosa o cambiar de modo. Si cierras la app antes, queda en la memoria temporal del propio móvil hasta que el sistema la vacía. Esta función no necesita conexión a internet.

No se guarda ninguna foto ni ningún dato del escaneo en ningún servidor nuestro.

**2. La sección Propuestas.** Solo si pulsas "Apoyar esta propuesta", la app guarda en nuestra base de datos qué propuesta has apoyado, la fecha y un identificador aleatorio generado en tu propio dispositivo la primera vez que apoyas una propuesta o das un "me gusta" a una receta.

- Ese identificador es un número al azar. No se deriva de tu teléfono, de tu cuenta ni de ningún identificador publicitario, y su único fin es evitar que un mismo dispositivo cuente dos veces.
- No va asociado a tu nombre, tu email ni a ningún otro dato tuyo, y no se usa para elaborar perfiles ni para publicidad.
- Los datos se alojan en **Supabase**, en servidores situados en la **Unión Europea**, que actúa como encargado del tratamiento.
- Si desinstalas la app, el identificador desaparece de tu dispositivo. Si quieres que borremos un apoyo ya registrado, escríbenos y lo eliminamos.
- Limitarte a leer las propuestas no envía nada tuyo: solo se descarga el contador de apoyos, sin ningún identificador. Si ya has apoyado una propuesta, eso lo recuerda tu propio móvil, no nuestro servidor.

**3. El buzón de propuestas.** Solo si escribes y envías una propuesta desde la sección Propuestas, se guarda en nuestra base de datos el texto que has escrito, la fecha y un identificador aleatorio de dispositivo **distinto** del de los apoyos (que sirve para limitar cuántas se pueden enviar al día y, si tienes Premium, para revisar antes tus propuestas: ver el apartado 5). Al ser distinto, tu correo, si lo dejas, no queda enlazado con lo que hayas apoyado o te haya gustado. El correo electrónico es **opcional**: puedes enviarla sin dejarlo, y si lo dejas se usa solo para contestarte sobre esa propuesta, nunca para publicidad ni para ninguna otra cosa. Lo que escribas **no se publica ni lo ve ningún otro usuario**: lo leemos, comprobamos los datos y, si se sostiene, redactamos nosotros la propuesta. Para revisarla, una copia del texto —**nunca tu correo**, y con los correos, teléfonos, DNI o cuentas bancarias que hayas escrito dentro ya tapados— se guarda en un espacio de trabajo privado de **GitHub**, donde la revisamos. Además, ese mismo texto puede analizarse con un sistema automático de **Anthropic**, que lo contrasta con la normativa oficial publicada y nos prepara un resumen de lo que ha encontrado. **Ese sistema no decide nada**: publicar o descartar una propuesta es siempre una decisión de una persona, y ninguna propuesta llega a la app sin esa revisión. Anthropic no usa ese texto para entrenar sus modelos. GitHub y Anthropic son empresas de Estados Unidos, así que esa copia sale de la Unión Europea: GitHub la protege con el Marco de Privacidad de Datos UE-EE. UU. y con las cláusulas contractuales tipo aprobadas por la Comisión Europea, y Anthropic con esas mismas cláusulas. Puedes pedirnos que borremos lo que enviaste escribiéndonos.

Base jurídica del tratamiento: tu consentimiento, que das al pulsar el botón de apoyo (art. 6.1.a del RGPD). Conservamos ese registro mientras la campaña siga activa. Puedes ejercer tus derechos de acceso, rectificación, supresión y oposición escribiendo a la dirección de contacto.

**4. Los "me gusta" de las recetas.** Al abrir la sección Recetas, la app descarga cuántos "me gusta" tiene cada receta; eso no envía nada tuyo, y qué recetas te gustan lo recuerda tu propio móvil. Solo si pulsas el corazón de una receta, se guarda en nuestra base de datos (Supabase, Unión Europea) qué receta te ha gustado, la fecha y el mismo identificador aleatorio de dispositivo descrito en el punto 2, únicamente para que un mismo dispositivo no cuente dos veces. Si vuelves a pulsar el corazón, ese registro se borra. Base jurídica: tu consentimiento, que das al pulsar el corazón (art. 6.1.a del RGPD).

**5. Premium (suscripción).** Si te suscribes, el pago lo gestiona **Apple o Google Play**, no nosotros: nunca vemos tu tarjeta ni tus datos de pago. Para saber si tienes Premium y qué precios mostrarte usamos **RevenueCat**, un servicio de suscripciones de una empresa de Estados Unidos que trata estos datos como encargado del tratamiento. La app lo consulta al abrirse, aunque no te suscribas, con un identificador aleatorio generado en tu móvil (no es tu nombre, tu correo ni un identificador publicitario) y, si compras, con el justificante de la compra. Ese identificador es el mismo que el del buzón de propuestas (apartado 3), no el de los apoyos ni el de los «me gusta»: si tienes Premium, RevenueCat nos comunica que está activo y hasta cuándo, y las propuestas que envíes se marcan como de Premium para revisarlas antes. No se cruza con lo que hayas apoyado ni con lo que te haya gustado. Base jurídica: la ejecución del contrato de suscripción (art. 6.1.b del RGPD).

Tu historial de escaneos, tus recetas favoritas, tus productos favoritos y tu preferencia de idioma se guardan únicamente en el almacenamiento local de tu dispositivo y nunca salen de él; puedes borrarlos desde la propia app o desinstalándola.

Como en cualquier conexión a internet, los servicios con los que habla la app (Supabase, Open Food Facts, RevenueCat y GitHub) ven la dirección IP de tu dispositivo para atender la petición, y puede quedar en sus registros técnicos; nosotros no la usamos para identificarte.

Fuera Tóxicos no está dirigida a menores de 14 años ni recoge datos suyos de forma consciente.

Puedes ejercer tus derechos de acceso, rectificación, supresión, oposición, limitación y portabilidad escribiendo a la dirección de contacto, y reclamar ante la Agencia Española de Protección de Datos (aepd.es).

Si en el futuro se añadiera cualquier función adicional que implique tratamiento de datos, esta política se actualizará antes de su activación y se notificará dentro de la app.

Para consultas sobre privacidad, escribe a **leora.agencia.ia@gmail.com**.

---

# Privacy Policy — Fuera Tóxicos

_Last updated: October 17, 2026_

**Data controller:** Leora Digital, Murcia (Spain). Contact: leora.agencia.ia@gmail.com

**Fuera Tóxicos** asks for no sign-up or user account and collects no name or data that identifies you — the only exception is the email you may optionally leave when sending a proposal (point 3) — and includes no ads or third-party tracking/analytics tools. All informational content (chemical entries, swaps, scientific evidence) ships with the app and can be read offline.

Five features connect to the internet:

**1. The product scanner.** It can be used in two ways, and they behave differently:

- **By barcode:** the app sends only that code — no personal data — first to our own database, in case someone has already looked that product up, and if it isn't there, to Open Beauty Facts, Open Food Facts, and Open Products Facts (three sibling collaborative databases from the same non-profit, independent and external to this app), until it is found. We keep a copy of what is found — the product's name, brand, image, and ingredients — in our database, so the next person to scan it doesn't have to ask again. That copy is public product information: **it carries no identifier of you or your device**, so no record exists of who scanned what. The external services aren't controlled by Fuera Tóxicos and have their own privacy policies.
- **Reading the label with the camera:** the photo **never leaves your phone**. Text recognition runs on the device itself (Google ML Kit on Android, through the Google Play services already installed on the phone; Apple Vision on iOS, part of the operating system). The image is not sent to any server, ours or a third party's. The photo is shown to you on the results screen, so you can check what was read and leave out anything that isn't the ingredient list, and it is **not saved anywhere**: the temporary copy the phone makes is deleted as soon as it is no longer shown, when you scan something else or switch mode. If you close the app before that, it stays in the phone's own temporary storage until the system clears it. This feature does not need an internet connection.

No photo or scan data is saved on any server of ours.

**2. The Proposals section.** Only if you tap "Support this proposal", the app stores in our database which proposal you supported, the date, and a random identifier generated on your own device the first time you support a proposal or like a recipe.

- That identifier is a random number. It is not derived from your phone, your account, or any advertising identifier, and its only purpose is to stop the same device counting twice.
- It is not linked to your name, your email, or any other data about you, and it is not used for profiling or advertising.
- The data is hosted on **Supabase**, on servers located in the **European Union**, acting as data processor.
- If you uninstall the app, the identifier disappears from your device. If you want a recorded support deleted, contact us and we will remove it.
- Simply reading the proposals sends nothing about you: only the supporter count is downloaded, with no identifier. If you have already supported a proposal, your own phone remembers it, not our server.

**3. The proposal inbox.** Only if you write and send a proposal from the Proposals section, we store in our database the text you wrote, the date, and a random device identifier **separate** from the one used for supports (used to limit how many can be sent per day and, if you have Premium, to review your proposals first: see section 5). Because it is separate, your email, if you leave it, is not linked to anything you have supported or liked. The email address is **optional**: you can send without it, and if you do leave it, it is used only to reply to you about that proposal, never for advertising or anything else. What you write is **not published and is not seen by any other user**: we read it, check the facts and, if it holds up, we write the proposal ourselves. To review it, a copy of the text — **never your email**, and with any emails, phone numbers, ID numbers or bank accounts you wrote in it already masked — is kept in a private **GitHub** workspace, where we review it. That same text may also be analysed by an automated system from **Anthropic** that compares it against published official regulation and prepares a summary of what it found for us. **That system decides nothing**: publishing or discarding a proposal is always a human decision, and no proposal reaches the app without that review. Anthropic does not use that text to train its models. GitHub and Anthropic are US companies, so that copy leaves the European Union: GitHub protects it under the EU-U.S. Data Privacy Framework and the standard contractual clauses approved by the European Commission, and Anthropic under those same clauses. You can ask us to delete what you sent by contacting us.

Legal basis for processing: your consent, given when you tap the support button (GDPR art. 6(1)(a)). We keep that record for as long as the campaign remains active. You can exercise your rights of access, rectification, erasure, and objection by writing to the contact address.

**4. Recipe likes.** When you open the Recipes section, the app downloads how many likes each recipe has; this sends nothing about you, and your own phone remembers which recipes you like. Only if you tap the heart on a recipe, we store in our database (Supabase, European Union) which recipe you liked, the date, and the same random device identifier described in point 2, solely so the same device is not counted twice. Tapping the heart again deletes that record. Legal basis: your consent, given by tapping the heart (Art. 6.1.a GDPR).

**5. Premium (subscription).** If you subscribe, payment is handled by **Apple or Google Play**, not by us: we never see your card or payment details. To know whether you have Premium and which prices to show, we use **RevenueCat**, a subscription service from a US company that processes this data as a data processor. The app queries it when it opens, even if you do not subscribe, with a random identifier generated on your phone (not your name, email or an advertising identifier) and, if you buy, with the purchase receipt. That identifier is the same one used for the proposal inbox (section 3), not the one for supports or likes: if you have Premium, RevenueCat tells us it is active and until when, and the proposals you send are marked as Premium so we review them first. It is not linked to anything you have supported or liked. Legal basis: performance of the subscription contract (GDPR art. 6(1)(b)).

Your scan history, favourite recipes, favorited products, and language preference are stored only in your device's local storage and never leave it; you can remove them from within the app or by uninstalling it.

As with any internet connection, the services the app talks to (Supabase, Open Food Facts, RevenueCat and GitHub) see your device's IP address to answer the request, and it may remain in their technical logs; we do not use it to identify you.

Fuera Tóxicos is not aimed at children under 14 and does not knowingly collect their data.

You can exercise your rights of access, rectification, erasure, objection, restriction and portability by writing to the contact address, and lodge a complaint with the Spanish Data Protection Agency (aepd.es).

If any future feature were to involve additional data processing, this policy will be updated before it is enabled, and this will be noted in the app.

For privacy questions, contact **leora.agencia.ia@gmail.com**.
