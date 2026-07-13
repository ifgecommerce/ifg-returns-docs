# Privacidad y gestión de datos — IFG Returns & Withdrawals

<div class="lang-switcher">
  <a class="lang-item" href="../"><img src="../assets/flags/gb.svg" alt="" class="flag-icon">English</a>
  <a class="lang-item" href="../it/"><img src="../assets/flags/it.svg" alt="" class="flag-icon">Italiano</a>
  <a class="lang-item" href="../de/"><img src="../assets/flags/de.svg" alt="" class="flag-icon">Deutsch</a>
  <a class="lang-item" href="../fr/"><img src="../assets/flags/fr.svg" alt="" class="flag-icon">Français</a>
  <span class="lang-item lang-current"><img src="../assets/flags/es.svg" alt="" class="flag-icon">Español</span>
</div>

Esta página describe cómo la propia aplicación recopila, utiliza y conserva los datos. Documenta el comportamiento técnico de la aplicación — no sustituye a la política de privacidad general de la empresa IFG eCommerce, ni constituye asesoramiento legal.

## Qué se recopila

Cuando un cliente envía una devolución a través del formulario de la tienda online: nombre, apellidos, dirección de envío, correo electrónico, número de pedido y, opcionalmente, número de teléfono y notas. La aplicación también lee datos del pedido desde Shopify (número de pedido, correo electrónico, fecha del pedido, estado de tramitación) para verificar que la solicitud es auténtica.

Además, los comerciantes proporcionan los datos legales de su propia empresa y su dirección de devolución durante la incorporación, que se utilizan para generar notificaciones de desistimiento y recibos conformes con la normativa.

## Por qué se recopila

- Para verificar que una solicitud de devolución corresponde a un pedido real (prevención del fraude).
- Para procesar la devolución/el reembolso y generar correos electrónicos de confirmación y recibos en PDF.
- Para cumplir con las obligaciones en materia de derechos del consumidor de la UE (Directiva 2011/83/UE y su modificación 2023/2673), que exigen identificar al cliente y el contrato.

## Con quién se comparte

- **Shopify** — para verificar pedidos y, en los planes correspondientes, para emitir reembolsos directamente (API de administración de Shopify).
- **Envío de correo electrónico** (Nodemailer / Resend) — para enviar al cliente los correos de confirmación, recibo y actualización de estado.
- **Proveedores de IA (Anthropic – Claude; alternativamente Google – Gemini)** — impulsan el chat de soporte dentro de la aplicación que utilizan los comerciantes para hacer preguntas sobre la aplicación. Procesan el texto de la pregunta de soporte del comerciante (no los datos del pedido del cliente) para generar las respuestas. Esto puede implicar el tratamiento de datos fuera de la UE (Estados Unidos) bajo las garantías contractuales adecuadas (Cláusulas Contractuales Tipo).

Los datos no se venden ni se utilizan con fines publicitarios.

## Conservación de datos

Si un comerciante desinstala la aplicación, o solicita la eliminación de datos, los datos personales del cliente (nombre, correo electrónico, teléfono, notas) se anonimizan. Los campos contables a nivel de pedido (número de pedido, resolución, importes) se conservan, anonimizados, ya que su conservación es un requisito contable fiscal estándar (hasta 10 años) — los registros anonimizados ya no se pueden vincular a una persona identificada.

## Seguridad

- El acceso a Shopify utiliza tokens de acceso offline con caducidad, renovados automáticamente — sin credenciales de larga duración.
- La base de datos (Firestore) solo es accesible a través de la identidad del propio servicio backend de la aplicación; no existe acceso público de lectura ni escritura.

## Preguntas o solicitudes

Para ejercer una solicitud de acceso o eliminación de datos, ponte en contacto con el comerciante de la tienda en la que realizaste el pedido, o escribe a [info@ifgecommerce.com](mailto:info@ifgecommerce.com).
