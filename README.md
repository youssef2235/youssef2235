# 🌱 BlueGreenEG - بلو جرين للتمية الزراعية

<div align="center">
  <img src="https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Core">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</div>

## 📝 نظرة عامة

BlueGreenEG هي منصة متكاملة للزراعة المستدامة في مصر، تهدف إلى توفير حلول مبتكرة للمزارعين والمهتمين بالزراعة المستدامة. المنصة تقدم مجموعة واسعة من المنتجات الزراعية والمقالات التعليمية لمساعدة المستخدمين في تحقيق أهدافهم الزراعية.

## ✨ المميزات الرئيسية

### 🛍️ إدارة المنتجات
- عرض المنتجات الزراعية المتنوعة
- تصنيف المنتجات حسب الفئات
- وصف تفصيلي للمنتجات
- إدارة المخزون والأسعار
- صور عالية الجودة للمنتجات

### 📚 إدارة المقالات
- مقالات تعليمية متخصصة
- تصنيف المقالات حسب المواضيع
- محتوى غني ومفيد
- دعم الصور والفيديوهات
- تحسين محركات البحث (SEO)

### 👥 إدارة المستخدمين
- نظام تسجيل دخول آمن
- إدارة الصلاحيات
- الملفات الشخصية
- تتبع النشاطات

### 🎨 واجهة مستخدم
- تصميم عصري وجذاب
- تجربة مستخدم سلسة
- توافق مع جميع الأجهزة
- دعم اللغة العربية
- سهولة التنقل والاستخدام

## 🚀 التقنيات المستخدمة

- **Backend**: ASP.NET Core MVC
- **Frontend**: HTML5, CSS3, JavaScript
- **Framework**: Bootstrap 5
- **Database**: SQL Server
- **Editor**: TinyMCE
- **Icons**: Font Awesome
- **Fonts**: Tajawal

## 🛠️ متطلبات التشغيل

- .NET 6.0 SDK أو أحدث
- SQL Server 2019 أو أحدث
- Visual Studio 2022 أو أحدث
- Git

## 📦 تثبيت وتشغيل المشروع

1. **نسخ المشروع**
   ```bash
   git clone https://github.com/yourusername/BlueGreenEG.git
   ```

2. **تثبيت الحزم**
   ```bash
   cd BlueGreenEG
   dotnet restore
   ```

3. **تطبيق الترحيلات**
   ```bash
   dotnet ef database update
   ```

4. **تشغيل المشروع**
   ```bash
   dotnet run
   ```

## 📁 هيكل المشروع

```
BlueGreenEG/
├── Controllers/         # وحدات التحكم
├── Models/             # نماذج البيانات
├── Views/              # صفحات العرض
├── wwwroot/           # الملفات الثابتة
│   ├── css/           # ملفات التنسيق
│   ├── js/            # ملفات JavaScript
│   └── images/        # الصور
├── Migrations/        # ملفات الترحيل
└── Program.cs         # نقطة البداية
```

## 🔒 الأمان

- تشفير كلمات المرور
- حماية من هجمات CSRF
- التحقق من صحة المدخلات
- حماية نقاط النهاية API
- تسجيل الأحداث الأمنية

## 📈 تحسين الأداء

- تخزين مؤقت للبيانات
- ضغط الصور
- تحسين استعلامات قاعدة البيانات
- تحميل الكسول للموارد
- تقليل حجم الملفات

## 🤝 المساهمة

نرحب بمساهماتكم في تطوير المشروع! يرجى اتباع الخطوات التالية:

1. Fork المشروع
2. إنشاء فرع جديد (`git checkout -b feature/AmazingFeature`)
3. Commit التغييرات (`git commit -m 'Add some AmazingFeature'`)
4. Push إلى الفرع (`git push origin feature/AmazingFeature`)
5. فتح طلب Pull Request

## 📄 الترخيص

هذا المشروع مرخص تحت رخصة MIT - انظر ملف [LICENSE](LICENSE) للتفاصيل.

## 📞 التواصل والدعم

- 📧 البريد الإلكتروني: support@bluegreeneg.com
- 🌐 الموقع الإلكتروني: www.bluegreeneg.com
- 📱 الهاتف: +201022356064

---

<div align="center">
  <p>Made with ❤️ by BlueGreenEG Team</p>
  <p>© 2024 BlueGreenEG. All rights reserved.</p>
</div>
