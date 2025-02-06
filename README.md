# مشروع ModernBinder

ModernBinder هو تطبيق سطح مكتب مبني باستخدام Python وPyQt5 لربط وتشفير الملفات بطريقة آمنة وسهلة الاستخدام.

## ⚠️ تحذير أمني
```
يُحظر استخدام هذا المشروع لأي أغراض غير مشروعة أو ضارة. يجب الالتزام التام بقوانين البلدان المعنية فيما يتعلق باختبار الاختراق والأمن السيبراني.
```

## المميزات

- واجهة مستخدم رسومية سهلة الاستخدام
- تشفير الملفات باستخدام خوارزميات تشفير قوية
- دعم تغيير امتدادات الملفات
- إمكانية تجميع عدة ملفات في ملف تنفيذي واحد
- دعم السحب والإفلات للملفات

## المتطلبات

- Python 3.12 أو أحدث
- المكتبات المطلوبة موجودة في ملف `requirements.txt`

## التثبيت

1. قم بنسخ المستودع:
```bash
git clone https://github.com/yourusername/ModernBinder.git
cd ModernBinder
```

2. قم بإنشاء بيئة افتراضية وتفعيلها:
```bash
python -m venv venv
# في Windows
venv\Scripts\activate
```

3. قم بتثبيت المتطلبات:
```bash
pip install -r requirements.txt
```

## التشغيل

لتشغيل التطبيق مباشرة:
```bash
python main.py
```

## بناء ملف تنفيذي

لإنشاء ملف تنفيذي (.exe):
```bash
python setup.py build
```
سيتم إنشاء الملف التنفيذي في مجلد `build`.

## الهيكل

```
ModernBinder/
├── main.py              # نقطة البداية للتطبيق
├── setup.py            # ملف إعداد cx_Freeze
├── requirements.txt    # متطلبات المشروع
├── core/              # المكونات الأساسية
│   ├── binder.py      # منطق الربط والتشفير
│   └── ext_spoof.py   # التعامل مع امتدادات الملفات
├── ui/                # واجهة المستخدم
│   ├── main_window.py
│   ├── file_dialog.py
│   └── assembly_dialog.py
└── resources/         # الموارد (الأيقونات، الستايل)
    └── icons/
```

## المساهمة

نرحب بمساهماتكم! يرجى اتباع الخطوات التالية:
1. قم بعمل Fork للمشروع
2. قم بإنشاء فرع جديد (`git checkout -b feature/amazing_feature`)
3. قم بإجراء تغييراتك وتوثيقها
4. قم برفع التغييرات (`git push origin feature/amazing_feature`)
5. قم بإنشاء طلب دمج (Pull Request)

## الترخيص

هذا المشروع مرخص تحت رخصة MIT - انظر ملف [LICENSE](LICENSE) للتفاصيل.

## الاتصال

- اسم المطور - [@yourusername](https://github.com/yourusername)
- رابط المشروع: [https://github.com/yourusername/ModernBinder](https://github.com/yourusername/ModernBinder)

## ملاحظات إضافية
- مشروع مخصص للأغراض التعليمية والأمنية فقط، يdemonstrate تقنيات الدمج الآمن.
- الميزات الرئيسية:
  - دمج الملفات الثنائية في حاوية واحدة
  - آلية تشفير متقدمة لإخفاء المحتوى
  - دعم توقيعات رقمية مخصصة
  - توافق مع أنظمة Windows الحديثة
- متطلبات التشغيل:
  - نظام Windows 10/11
  - .NET Framework 4.8+
  - مساحة قرص صافية 50MB
- ترخيص الاستخدام:
  - هذا المشروع مرخص تحت [الترخيص الأخلاقي للبحوث الأمنية v1.0](https://ethical-research.org/license)
