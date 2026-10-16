# Quality Standard Team Website

موقع ثابت جاهز للنشر على GitHub Pages لإدارة معيار تصميم البرنامج والمعيار السابع المؤسسي.

## الوظائف
- Dashboard وMaster Tracker لعدد 30 مهمة.
- صفحة مخصصة لـTask 1 وإغلاقها.
- تحليل ملاءمة NARS/ARS وحساب النتيجة.
- فهرس الأدلة، سجل الفجوات، الاجتماعات، والأعضاء الخمسة.
- حفظ تلقائي داخل المتصفح باستخدام LocalStorage.
- تصدير واستيراد JSON لتبادل آخر نسخة بين أعضاء الفريق.

## النشر على GitHub Pages
1. أنشئ مستودعًا جديدًا، مثل `quality-standard-team`.
2. ارفع الملفات الموجودة في هذا المجلد إلى الجذر.
3. من Settings > Pages اختر Deploy from a branch.
4. اختر branch: `main` والمجلد `/root` ثم Save.
5. افتح الرابط الذي ينشئه GitHub Pages.

## طريقة العمل الجماعي في النسخة الحالية
GitHub Pages موقع ثابت، لذلك لا توجد قاعدة بيانات مشتركة تلقائيًا. كل عضو يحفظ على جهازه. لتبادل التحديثات:
1. العضو المسؤول يضغط "تصدير JSON".
2. يرفع ملف JSON إلى مجلد team-data أو يرسله للمنسق.
3. بقية الفريق تستخدم "استيراد JSON".

## تعاون لحظي متعدد المستخدمين
للحفظ المشترك في نفس اللحظة، اربط الموقع لاحقًا بـSupabase أو Firebase. لا تضع مفاتيح إدارية سرية داخل ملفات GitHub العامة.


## Excel Master Tracker المضمّن
تمت إضافة المصنف المستضاف على SharePoint داخل صفحة مستقلة. العرض داخل iframe للمتابعة، بينما التحرير والحفظ يتمان من خلال زر "فتح وتحرير في Excel" وبصلاحيات SharePoint الممنوحة للأعضاء.


## NARS ↔ ARS Consistency Matrix
أضيفت صفحة مستقلة للمصفوفة المنشورة على SharePoint، وتشمل عرضًا مضمّنًا، زر تحرير في Excel، وملخص تغطية المسودة. تستخدم الصفحة النصوص والترقيم الرسميين لـNARS لقطاع الحاسبات والمعلومات، إصدار أكتوبر 2010. ويجب مراجعة أحكام الربط واعتمادها مؤسسيًا قبل النسخة النهائية.


## ARS–PLO Alignment Matrix
Includes 34 Software Engineering ARS statements, 12 proposed PLOs, a binary coverage map, summary indicators, and review instructions. The PLO wording remains draft until matched to the approved Program Specification.

The ARS–PLO workbook is embedded from SharePoint. Editing is performed through Excel for the web using institutional permissions.
