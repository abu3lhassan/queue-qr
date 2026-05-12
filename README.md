# Queue QR Production Auth V1

## الصفحات
- ticket.html: صفحة العميل / QR
- display.html: شاشة العرض
- admin.html: اختيار الكاونتر
- counter1.html إلى counter4.html: صفحات الموظفين
- owner.html: صفحة المالك

## Firebase Auth
فعّل Email/Password من:
Authentication -> Sign-in method -> Email/Password

أنشئ حساب المالك بهذا البريد:
ali.h.alhenabi@gmail.com

أنشئ حسابات الموظفين من Firebase Console.

## Security Rules
انسخ محتوى:
database-rules.json

إلى:
Realtime Database -> Rules

ثم Publish.

## ملاحظات
- العميل لا يحتاج تسجيل دخول.
- الموظف يحتاج تسجيل دخول لاستدعاء التالي.
- المالك فقط يستطيع التصفير وتغيير عدد الكاونترات.
- لا تضف owner.html للصفحة الرئيسية.
