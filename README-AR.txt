PiSLA 1.7.0 — حزمة التحديث

المحتويات:
- PiSLA-Desktop-v1.7.0.zip: مشروع Windows Electron.
- PiSLA-Android-Project-v1.7.0.zip: مشروع Android مع ملف الواجهة المحدّث.
- .github/workflows/build-windows.yml: سير عمل بناء نسخة Windows.

طريقة البناء من الهاتف عبر GitHub:
1. ارفع PiSLA-Desktop-v1.7.0.zip إلى جذر المستودع.
2. استبدل ملف .github/workflows/build-windows.yml بالملف المرفق داخل مجلد .github/workflows.
3. افتح Actions وشغّل Build PiSLA Windows v1.7.0. بعد نجاحه نزّل Artifact باسم PiSLA-Windows-v1.7.0.
4. ارفع PiSLA-Android-Project-v1.7.0.zip وفق آلية بناء Android الموجودة في مستودعك، ثم شغّل workflow الخاص بـ APK.
5. لا تخلط بين Artifact البناء وملف المشروع المصدر.

النسخة 1.7.0 تتضمن تحسينات الواجهة المكتبية، أدوات تنسيق جدول الجذاذة، أنماط تحليل إضافية، تحسين ترتيب أدوات محرر الخريطة على سطح المكتب والهاتف، إعدادات نوع الروابط والإطار والطباعة.

ملاحظة اختبار: تم التحقق من سلامة صياغة JavaScript داخل HTML، لكن لم يُنفّذ بناء Windows أو APK في هذه البيئة. يجب التحقق من البناء والوظائف على GitHub وعلى جهاز Android قبل اعتماد النسخة النهائية.
