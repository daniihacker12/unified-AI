Unibox AI

Demo chats

Tone Language

## Paste any chat, get the point

Export a WhatsApp chat (open the chat, tap the menu, More, Export chat, Without media) or copy messages from Telegram, Instagram or email. Paste them here.

What do you need

The answer shows up here.

Your pasted text goes to Claude on your own account. Nothing is saved by this page.

## Connect your real apps

Right now this page shows demo chats so you can try the AI. To read and answer real messages, each app needs a small server that receives its messages and sends this page the replies. Every app below offers an official way in.

WhatsAppneeds server

- WhatsApp Business Platform (Cloud API) from Meta
- A business phone number and a verified Meta business account
- A webhook URL on your server for incoming messages

Telegrameasiest

- Create a bot with @BotFather and copy its token
- Set a webhook or poll getUpdates
- Free, works in minutes

Instagramneeds server

- Instagram Messaging API through a Meta app
- A professional Instagram account linked to a Facebook Page
- Meta app review before going live

Emailneeds server

- Gmail API or any IMAP and SMTP mailbox
- OAuth sign-in for Gmail
- A job that checks for new mail

### How the real version fits together

1. Each app sends new messages to your server through a webhook.
2. The server saves them in one database and calls Claude to summarize and draft replies, using your price list and rules.
3. You approve replies here, or turn on Autopilot for the rules you trust. The server sends them back through the same app.

Copy this brief and paste it into a new Claude chat or Claude Code session to have the server built for you.