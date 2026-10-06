# WhatsMail

WhatsMail is a Windows desktop companion that connects an authorized WhatsApp account as a linked device and turns incoming messages/media into formatted email notifications.

Important:
- Use only with an account you are authorized to connect.
- The linked-device implementation uses the Baileys library. It is not an official WhatsApp SDK and may stop working if WhatsApp changes its protocol or policies.
- Never publish your WhatsApp auth folder or SMTP credentials.
- For Gmail SMTP, use an App Password where applicable; do not put your normal Google password in the app.
- Production deployment should move secrets to secure OS storage and add a subscription/admin backend.

Build:
npm install
npm start
npm run dist

GitHub Actions automatically builds a Windows installer on every push to main and publishes it as a workflow artifact.


Build pipeline initialized.
