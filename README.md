# Professional Portfolio | الموقع الشخصي

موقع Portfolio عربي/إنجليزي باتجاهي RTL/LTR، مبني باستخدام **HTML5 وCSS3 وBootstrap 5 وJavaScript**. يحتوي على أقسام النبذة الشخصية، التعليم، المهارات، المشاريع، الشهادات، والتواصل.

> **مهم قبل التسليم:** راجع بيانات الاسم والتعليم والمعدل والشهادات وأرقام المشاريع وروابط GitHub/LinkedIn والبريد والهاتف. بعض البيانات الموجودة في النسخة الحالية تجريبية أو أمثلة، ولا ينبغي تسليمها على أنها معلومات حقيقية. ملف `assets/cv.pdf` ملف تجريبي ويجب استبداله بسيرتك الذاتية الحقيقية.

## تشغيل المشروع

1. فك ضغط المشروع.
2. افتح مجلد المشروع في Visual Studio Code.
3. افتح `index.html` في المتصفح، أو استخدم إضافة Live Server.
4. يلزم اتصال بالإنترنت لتحميل Bootstrap والأيقونات والخطوط من CDN.

## بنية المشروع

```text
portfolio/
├── index.html
├── style.css
├── README.md
├── .gitignore
└── assets/
    ├── cv.pdf
    └── images/
        ├── profile.jpg
        ├── banner.jpg
        ├── project1.jpg
        ├── project2.jpg
        └── project3.jpg
```

## قبل الرفع على GitHub

- [ ] استبدال ملف `assets/cv.pdf` بسيرة ذاتية صحيحة.
- [ ] تحديث البريد ورقم الهاتف ورابط WhatsApp.
- [ ] تحديث روابط GitHub وLinkedIn وKaggle وروابط مستودعات المشاريع لتشير إلى حسابات ومشاريع موجودة فعلًا.
- [ ] مراجعة المعدل الدراسي والشهادات والأرقام والنتائج المذكورة في المشاريع، وحذف أي معلومة غير دقيقة.
- [ ] اختبار الموقع على الهاتف والكمبيوتر وتجربة زر اللغة والوضع الليلي وفلاتر المشاريع.
- [ ] التأكد من أن الصور مسموح باستخدامها وأنها لا تحتوي بيانات خاصة.

## رفع المشروع باستخدام Git من VS Code

بعد تثبيت Git وفتح مجلد المشروع في VS Code، افتح Terminal ونفّذ الأوامر التالية (استبدل `YOUR-USERNAME` باسم حسابك، وأنشئ Repository فارغًا على GitHub باسم `professional-portfolio` أولًا):

```bash
git init
git add .
git commit -m "Add personal portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/professional-portfolio.git
git push -u origin main
```

إذا كان `origin` موجودًا بالفعل، لا تكرر أمر `git remote add origin`؛ تحقق منه باستخدام `git remote -v`.

## نشر الموقع عبر GitHub Pages

1. افتح المستودع على GitHub ثم **Settings → Pages**.
2. في **Build and deployment** اختر **Deploy from a branch**.
3. اختر الفرع `main` والمجلد `/ (root)` ثم اضغط **Save**.
4. انتظر اكتمال النشر. سيكون الرابط عادةً `https://YOUR-USERNAME.github.io/professional-portfolio/`.

## ملاحظة حول نموذج التواصل

نموذج التواصل الحالي واجهة أمامية تعليمية تحاكي الإرسال فقط، ولا ترسل البيانات إلى بريد أو خادم. لا تدخل فيه بيانات حساسة، ولا تقدمه على أنه نموذج إرسال فعلي.
