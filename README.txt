تطبيق PWA - مساعد نادي العلوم والتكنولوجيا (نسخة n8n)

1) افتح index.html وغيّر WEBHOOK_URL إلى رابط n8n (Production URL).
2) في n8n: فعّل الـ Workflow (Active) وفي Chat Trigger ضع Allowed Origins = * أو عنوان موقعك.
3) ارفع كل الملفات (بنفس المجلد) إلى استضافة تدعم HTTPS، مثل:
   Netlify Drop (app.netlify.com/drop) أو GitHub Pages أو Cloudflare Pages.
4) افتح الرابط من الهاتف:
   - Android (Chrome): قائمة ⋮ ← تثبيت التطبيق.
   - iPhone (Safari): زر المشاركة ← إضافة إلى الشاشة الرئيسية.
