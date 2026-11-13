# Cron Meta Lead Manager website

The public landing page for Cron Meta Lead Manager, the WhatsApp lead manager for Meta ads.
A plain static site: `index.html` and the `img` folder. No build step.

Before going live, edit the two settings near the bottom of `index.html`:

- `CRON_WHATSAPP`: the company WhatsApp number (digits only, with country code). The demo form sends to it.
- `APP_URL`: where the system runs. Sign in opens `APP_URL/login`, Create account opens `APP_URL/signup`.

The product tour screenshots in `img/tour` use a sample business and invented data. No real customer chats.
