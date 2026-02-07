# ERP – Accounting, Manufacturing & Cost Centers (Frontend Only)

نظام ERP ويب (واجهة فقط) يعمل بدون سيرفر وبدون قاعدة بيانات خارجية.

## التشغيل

- افتح `index.html` مباشرة على المتصفح.
- للنشر على GitHub Pages:
  1) أنشئ Repository جديد.
  2) ارفع ملفي `index.html` و `README.md`.
  3) من Settings → Pages اختر Branch (عادة `main`) و Folder (Root) ثم Save.

## حسابات الدخول الافتراضية

| الدور | المستخدم | كلمة المرور |
|---|---|---|
| Admin | admin | admin123 |
| Accountant | accountant | acc123 |
| Viewer | viewer | view123 |

## ملاحظات مهمة

- التخزين محليًا داخل المتصفح (LocalStorage).
- يدعم: Backup/Restore JSON، وتصدير/استيراد Excel **عبر SheetJS**، وطباعة PDF **عبر jsPDF**.
- تم ربط المكتبات عبر CDN:
  - في حال تريد تشغيل النظام *بدون إنترنت* بشكل دائم: حمّل ملفات المكتبات محليًا وضعها داخل المشروع وعدّل روابط `<script>` في `index.html`.

## الهيكل

- `index.html` : كل النظام (Self-Contained)
- `README.md` : تعليمات

