# 💜 Mis 30 Añitos · Andreita

Invitación web animada: se toca el sobre, se abre, sale la carta con confeti y aparece la invitación con foto, cuenta regresiva y botones para confirmar por WhatsApp, ver cómo llegar y agendar la fecha.

## Personalizar
En `index.html`, busca el bloque `CONFIG` al inicio del `<script>`:
- `whatsapp`: número para confirmar asistencia, con código de país y sin `+` (ej. `51987654321`).
- `fechaISO` y `direccion`: fecha y lugar del evento.

## Publicar en Netlify
1. En Netlify: **Add new site → Import an existing project → GitHub** y elige este repositorio.
2. Build command: *(vacío)* · Publish directory: `.`
3. Deploy. Cada `git push` vuelve a publicar automáticamente.

Sitio 100 % estático (HTML + CSS + JS), sin dependencias.
