# [AnkiApp ليست جزءًا من نظام Anki](#ankiapp-is-not-part-of-the-anki-ecosystem)

=======================================================================================

تم تطوير برنامج يسمى AnkiApp من قبل مجموعة من الأشخاص المنفصلين، ولا يرتبط ببقية نظام Anki. تم إصداره سنوات بعد تأسيس Anki في السوق، ونحن نشتبه في أن الاسم تم اختياره عمدًا للاستفادة من التعرف على العلامة التجارية التي بنيناها. استخدام Anki في الاسم يعني أنه سيعمل مع العملاء الأخريين لـ Anki، والذي لا يحدث ذلك.

إذا كنت قد قمت بتنزيل AnkiApp عن طريق الخطأ، يرجى النظر في ترك مراجعة في متجر التطبيقات لتنبيه الناس إلى حقيقة عدم ارتباط AnkiApp بـ Anki.

تتكون نظام Anki من Anki و AnkiMobile و AnkiDroid و AnkiWeb، والتي يتم ربطها جميعًا من موقعنا الرسمي:  [https://apps.ankiweb.net](https://apps.ankiweb.net)

**استيراد من AnkiApp - مقاربة جديدة**

قام عبدو بنشر [إضافة برمجية](https://ankiweb.net/shared/info/2072125761) للمساعدة في استيراد أوراق AnkiApp الخاصة بك إلى Anki. هذه هي الطريقة الموصى بها، حيث لا يتطلب منك دفع مال لمطوري AnkiApp للوصول إلى بياناتك. كمكافأة إضافية، فإنها أسهل من الطريقة القديمة.

**استيراد من AnkiApp - مقاربة قديمة**

تعتمد الطريقة التالية على ميزة التصدير في AnkiApp. قام مطورو AnkiApp مؤخرًا بإزالة تلك الميزة من المستخدمين المجانيين، مما يتطلب من المستخدمين الدفع مقابل اشتراك قبل أن يتمكنوا من تصدير بياناتهم. لهذا السبب، يوصى بالطريقة الموصى بها أعلاه. ولكن للذاكرة، يمكن الاطلاع على التعليمات القديمة أدناه:

إذا كنت قد أضفت محتوى بطريقة غير مقصودة إلى AnkiApp ، فيمكنك نقله إلى Anki. لا يمكن استيراد تقدم الدراسة ، ولكن يمكن استيراد النص الأساسي والصور:

1. تصدير من AnkiApp ، مما يمنحك ملفًا .zip
2. فك ضغط الملف في مكان ما - ستحصل على ملف fields.csv وملفات الوسائط الأخرى.
3. استخدم File> Import في Anki لاستيراد ملف fields.csv. في نافذة الاستيراد ، تأكد من تمكين خانة الاختيار "السماح بـ HTML في الحقول".

إذا كان الملف يحتوي على صور ، فيجب تغيير مراجع الصور تلك إلى تنسيق يفهمه Anki. حدد جميع البطاقات التي تم استيرادها في نافذة التصفح في Anki ، واستخدم عنصر القائمة Edit> Find&Replace. ثم استبدل:
{{
ب

<img src="
ثم قم بعملية Find&Replace أخرى ، واستبدل

}}
ب

">
أخيرًا ، ستحتاج إلى نقل ملفات الصور التي استخرجتها من ملف الضغط إلى مجلد User 1/collection.media:

<https://docs.ankiweb.net/files.html#file-locations>
[https://docs.ankiweb.net/files.html#file-locations]
