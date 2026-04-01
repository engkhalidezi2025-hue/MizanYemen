# ⚖️ ميزان اليمن القضائي - تطبيق Android

منصة ذكاء قضائي يمنية متكاملة مبنية بتقنية WebView.

## 🚀 كيفية بناء الـ APK عبر GitHub

### الخطوة 1: رفع المشروع
```bash
git init
git add .
git commit -m "ميزان اليمن - الإصدار الأول"
git branch -M main
git remote add origin https://github.com/USERNAME/mizan-yemen.git
git push -u origin main
```

### الخطوة 2: تنزيل الـ APK
- اذهب إلى تبويب **Actions**
- انتظر انتهاء البناء (~5 دقائق) ✅
- اضغط على **ميزان-اليمن-APK** → تنزيل

## 📱 مميزات التطبيق
- ✅ يعمل بشكل كامل داخل الجهاز (HTML محلي)
- ✅ يدعم رفع الملفات (صور + PDF) للتحليل
- ✅ يدعم JavaScript و localStorage كاملاً
- ✅ يتصل بـ Gemini API مباشرة
- ✅ يدعم اللغة العربية واتجاه RTL

## 📁 هيكل المشروع
```
MizanYemen/
├── .github/workflows/build.yml     ← GitHub Actions
├── app/src/main/
│   ├── assets/index.html           ← التطبيق الكامل
│   ├── java/com/mizanyemen/
│   │   └── MainActivity.java
│   └── AndroidManifest.xml
├── build.gradle
└── settings.gradle
```

## 👥 الفريق
- **فكرة وإشراف:** القاضي خالد عبدالنور البركاني
- **إعداد وبرمجة:** م. أمير البريهي
- **إعداد وبرمجة:** م. خالد العزي
