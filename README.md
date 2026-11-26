# Bienaventurados — Agencia de viajes

Sitio web para **Bienaventurados**, una agencia de viajes para familias y grupos de amigos de Paysandú. Tiene landing, catálogo de salidas con precios, página de reserva con cálculo por persona y un chatbot que responde dudas frecuentes.

🔗 **Demo en vivo:** https://bienaventurados.netlify.app/

## Qué hace

### Landing (`index.html`)
- Hero con la propuesta ("los mejores viajes se miden en momentos juntos") y contadores animados.
- Carrusel de destinos y sección "Por qué nosotros" con los diferenciales: itinerarios a medida, turismo responsable, asistencia humana 24/7, pago en cuotas, guías locales.
- **Próximas salidas:** tarjetas con duración, transporte y precio por persona (Iguazú, Bariloche, Florianópolis, Punta Cana, Europa, Japón). Cada una lleva a su página de pago.
- Testimonios y formulario de contacto que envía la consulta por email con FormSubmit.
- **Chatbot "Bea":** asistente que responde sobre destinos, precios, pagos y cómo trabaja la agencia. Funciona por palabras clave en el navegador (sin IA ni servidor) y tiene botones de preguntas rápidas.

### Reserva y pago (`pago.html?viaje=...`)
- Detalle del viaje elegido: qué incluye, fechas de salida y transporte.
- Selector de cantidad de personas (de 1 a 30) que recalcula **total, seña del 20 % y saldo**.
- Formulario de reserva que se envía por email.
- Cuatro formas de pago en pestañas: transferencia bancaria, Mercado Pago, tarjeta y pago en persona, con botones para copiar datos.
- Acceso directo a WhatsApp.

## Tecnología

- HTML, CSS y JavaScript vanilla, sin frameworks.
- [FormSubmit](https://formsubmit.co/) para recibir consultas y reservas por email sin backend.
- Deploy en Netlify.

## Correrlo localmente

Abrí `index.html` en el navegador. Para probar una reserva: `pago.html?viaje=bariloche` (también `iguazu`, `florianopolis`, `caribe`, `europa`, `japon`).

> Los datos bancarios del sitio son de ejemplo.

---

Proyecto de **Sebastián Soba**.
