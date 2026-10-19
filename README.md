# غِراس - اغرس ذاتك ليثمر وطنك

## هيكلة المشروع
ghiras/
├── index.html
├── css/style.css
├── js/data.js (البيانات)
├── js/app.js (المنطق + ربط Google Sheet)
├── google-apps-script/Code.gs
└── README.md

## الرفع على GitHub Pages
1. سوي repo جديد اسمه ghiras
2. ارفع كل الملفات
3. Settings > Pages > Branch main / root > Save
4. رابطك: https://USERNAME.github.io/ghiras/

## الربط بجوجل شيت
1. sheets.google.com > شيت جديد
2. Extensions > Apps Script > الصق كود Code.gs
3. Deploy > Web app > Anyone > انسخ الرابط
4. افتح js/app.js وضع الرابط في GOOGLE_SHEET_API_URL

الآن كل ناجح ينحفظ تلقائيا في الشيت.
