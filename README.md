# WhatsApp Rust Bot — Linux x86_64 (fixed build)

نسخة Linux x86_64 مبنية من WhatsApp Rust Bot، مع إصلاح تشغيل Deno المرفق حتى يستطيع yt-dlp حل تحديات YouTube JavaScript وإظهار الجودات المتاحة.

## الاستخدام

1. حمّل ملف `whatsapp-rust-bot-linux-x86_64-fixed.zip` وفك الضغط.
2. انسخ `.env.example` إلى `.env` وضع رقم WhatsApp الدولي.
3. ضع `cookies.txt` بصيغة Netscape بجانب الملف التنفيذي عند الحاجة.
4. شغّل `./run.sh` أو `./start.sh`، ولا تشغّل الملف التنفيذي مباشرة إذا لم يكن Deno مثبتًا على النظام.

ملف ZIP مرفوع كملف عادي داخل المستودع، وليس GitHub Release.

لا ترفع ملفات `.env` أو `cookies.txt` أو `whatsapp_bot.db` إلى GitHub.
