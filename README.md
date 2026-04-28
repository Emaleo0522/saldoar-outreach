# Saldoar — Outreach Forms

Página interna de Saldoar para agilizar el contacto con proveedores de pagos LATAM. Generada en cowork session, deployada como sitio estático.

## Qué es

Una sola página HTML con los formularios de outreach de la **1era ola** de providers. Para cada uno incluye:

- Botón directo al formulario / canal de contacto del provider
- Campos pre-completados (nombre, email, empresa, cargo, website)
- Mensaje personalizado con el pitch de Saldoar, listo para copiar con un clic
- Notas contextuales sobre particularidades del form (captcha, canal alternativo, etc.)

## Providers — 1era ola

| # | Provider | Canal | Idioma |
|---|----------|-------|--------|
| 1 | LocalPayment (Aleph) | Form web — dropdown "Sales" + hCaptcha | ES |
| 2 | Bamboo Payments | Form web contact-sales | EN |
| 3 | Koywe | Book a demo (Calendly) | ES |
| 4 | Wise Business | Form web contact | EN |
| 5 | MercadoPago | Centro de Partners / Discord oficial | ES |
| 6 | Stripe Connect | Stripe Sales form — elegir "Connect" | EN |

## Flujo de uso

1. Abrir la página deployada
2. Clic en **"Abrir formulario"** del provider
3. Copiar cada campo con el botón **"Copiar"**
4. Pegar en el campo correspondiente del form externo
5. Enviar
6. Marcar el provider como `contacted` en Notion con la fecha

## Stack

HTML estático puro — sin dependencias, sin build step. Deploy directo en Vercel.
