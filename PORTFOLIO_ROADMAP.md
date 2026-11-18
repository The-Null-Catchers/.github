# .github — خطة البورتفيليو

مرجع التقييم الأساسي: 17 نوفمبر 2026. تحديث نشر الخطة داخل المستودع: 18 نوفمبر 2026.

الخطة خاصة بهذا المستودع، ومستخلصة من خطة Null Catchers المشتركة. وصف «الموجود الموثق» يعكس المراجعة بتاريخها؛ تحقّق من الكود ووثائق الحالة الحالية قبل إنشاء مهمة جديدة. لا تعِد تنفيذ ميزة موجودة، ولا تعتبر وجود تعريف CI دليلًا على نجاح تشغيله.

**تقدير شريحة العرض الأولى:** 5–8 ساعات. التقدير تخطيطي لمطور يعرف المشروع، ويستثني انتظار حسابات المتاجر والمراجعات الخارجية وتجهيز بيئة الهدف. لا يغطي جميع بنود P2.

## الأولويات الخاصة بالمشروع

**الموجود المتحقق:** `profile/README.md` يعرض المؤسسة والمشاريع والتقنيات. المستودع مساند للبورتفيليو، وليس تطبيقًا يحتاج database أو API.

**P0 — واجهة المؤسسة** جهّز بطاقات عرض لثلاثة مشاريع بعد تثبيت روابط أدلتها ومسارات إعادة التجربة.

**P1 — عملية قابلة للتكرار:** أضف قالب issue للمشكلة/الدليل/معيار الإنجاز وقالب PR للتغيير/التحقق/الأثر، بعد مراجعة القوالب الموجودة إن أضيفت لاحقًا. أضف index لخريطة الخطط، وفحص روابط يمنع بقاء روابط demo أو artifacts منتهية.

**P2 — لاحقًا:** reusable workflows مشتركة بحذر؛ استخرج فقط خطوات متكررة متطابقة فعلًا. لا تجبر Laravel وGo وPython وFlutter على pipeline واحد، ولا تضف PAT واسع الصلاحية لتسهيل auto-merge.

**معيار الإنجاز:** الزائر يصل خلال نقرتين إلى تجربة ودليل لواحد من المشاريع الرئيسية، الروابط صالحة، والإنجاز منسوب إلى أصحابه دون اختراع فريق أو مستخدمين أو نتائج.

**الديمو:** صفحة المؤسسة → مشروع رئيسي → walkthrough → architecture → CI/release. **الأدلة:** [Profile](https://github.com/The-Null-Catchers/.github/blob/main/profile/README.md).

## الدفعة التالية

| ترتيب التنفيذ | المستودعات | المطلوب قبل العرض |
|---|---|---|
| تثبيت أدلة المشاريع الأقرب إلى العرض | [DocMind](https://github.com/The-Null-Catchers/DocMind/blob/main/PORTFOLIO_ROADMAP.md)، [ChessCoach-AI](https://github.com/The-Null-Catchers/ChessCoach-AI/blob/main/PORTFOLIO_ROADMAP.md)، [GeoPulse](https://github.com/The-Null-Catchers/GeoPulse/blob/main/PORTFOLIO_ROADMAP.md) | تسجيل موثق من إصدار معروف، وتعليمات تجربة، وذكر حدود السيناريو المعروض. |
| إغلاق فجوات التحقق على الأجهزة والأدلة العربية | [FitTrack](https://github.com/The-Null-Catchers/FitTrack/blob/main/PORTFOLIO_ROADMAP.md)، [TaskPilot](https://github.com/The-Null-Catchers/TaskPilot/blob/main/PORTFOLIO_ROADMAP.md)، [Masroof](https://github.com/The-Null-Catchers/Masroof/blob/main/PORTFOLIO_ROADMAP.md) | دليل الجهاز أو OCR الفعلي، وسجل نتائج مرتبط بـSHA. |
| اعتماد نطاق مشروع جديد | [StockFlow](https://github.com/The-Null-Catchers/StockFlow/blob/main/PORTFOLIO_ROADMAP.md) | مراجعة المسودة واعتماد الأدوار وسياسة الرصيد قبل بدء الكود. |

تُنشر بطاقة المشروع عند وجود رابط خطة ورابط إصدار أو تشغيل يمكن التحقق منه، وطريقة لإعادة التجربة. تفحص الروابط من جلسة زائر. تظل الخطط الأصلية للمشاريع الأخرى متاحة في الفهرس أدناه.

## بوابة قبول نسخة البورتفيليو

- [ ] يستطيع شخص آخر تشغيل المسار الرئيسي من checkout نظيف، باتباع README، دون أسرار شخصية.
- [ ] توجد قصة واحدة مكتملة: مستخدم محدد، مشكلة محددة، ومسار بداية إلى نتيجة محفوظة.
- [ ] ينجح اختبار للمسار الرئيسي وحالة فشل مهمة، وتُختبر حدود الصلاحيات حيث توجد حسابات متعددة.
- [ ] توجد بيانات عرض اصطناعية معلنة، قابلة لإعادة الإنشاء؛ ولا توجد بيانات عملاء أو أسرار في اللقطات.
- [ ] توجد 4–6 لقطات حقيقية أو العدد الملائم للأداة، وفيديو 60–120 ثانية، وروابط تعمل. تُلتقط الأدلة من إصدار معروف.
- [ ] README يوضح المزايا الفعلية، طريقة التشغيل، الرسم المعماري، القيود، وروابط الاختبارات والديمو.
- [ ] Case study قصيرة تشرح قرارين هندسيين، بديلًا جرى استبعاده ولماذا، وفشلًا حقيقيًا وكيف يعالجه النظام.
- [ ] صفحة Release تسجل SHA وCI والمتطلبات والقيود. لا تُنشر أرقام أداء دون workload وعتاد وطريقة قياس.
- [ ] حُسمت سياسة الترخيص ونسب المساهمات قبل التوزيع؛ لا نختار ترخيصًا تلقائيًا لجميع المستودعات.

الديمو المستضاف مفيد وليس شرطًا لكل أداة. أدوات تنفيذ الكود وإدارة الخوادم والأسرار يمكن عرضها بفيديو وبيئة معزولة وتجربة محلية قابلة للإعادة. لا تفتح تنفيذًا عامًا غير محدود لمجرد وجود رابط بورتفيليو.

## التنفيذ والمتابعة

- حوّل P0 إلى مهام صغيرة، لكل منها سلوك متوقع ومعيار قبول واختبار مناسب.
- ابدأ بتأكيد الموجود؛ عدّل هذه الخطة عندما يغلق بند بدليل مرتبط بcommit أو PR.
- سجّل مصدر بيانات الديمو، والـSHA الذي التُقطت منه الأدلة، وحدود التجربة الفعلية.
- راجع الفرق النهائي وانتظر نجاح الفحوص المطلوبة لنفس SHA قبل الدمج، مع احترام حماية الفرع.
- إذا كان التعديل وثائق فقط ولا يوجد فحص ينطبق عليه، سجّل التحقق من محتواها وروابطها؛ لا تسجل اختبارات تشغيل لم تُنفّذ.
- لا تُنشر أرقام أداء أو ادعاءات أمان أو جاهزية إنتاج بلا دليل مناسب.

## خطط المستودعات الأخرى

| المستودع | الخطة |
|---|---|
| brand-assets | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/brand-assets/blob/main/PORTFOLIO_ROADMAP.md) |
| DocMind | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/DocMind/blob/main/PORTFOLIO_ROADMAP.md) |
| ChessCoach-AI | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/ChessCoach-AI/blob/main/PORTFOLIO_ROADMAP.md) |
| VaultPass | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/VaultPass/blob/main/PORTFOLIO_ROADMAP.md) |
| FitTrack | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/FitTrack/blob/main/PORTFOLIO_ROADMAP.md) |
| Masroof | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/Masroof/blob/main/PORTFOLIO_ROADMAP.md) |
| DeployForge | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/DeployForge/blob/claude/deployforge-platform-hppvk5/PORTFOLIO_ROADMAP.md) |
| BrowserGrid | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/BrowserGrid/blob/main/PORTFOLIO_ROADMAP.md) |
| StreamForge | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/StreamForge/blob/main/PORTFOLIO_ROADMAP.md) |
| .github | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/.github/blob/main/PORTFOLIO_ROADMAP.md) |
| TaskPilot | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/TaskPilot/blob/main/PORTFOLIO_ROADMAP.md) |
| CloudDeck | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/CloudDeck/blob/main/PORTFOLIO_ROADMAP.md) |
| StockFlow | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/StockFlow/blob/main/PORTFOLIO_ROADMAP.md) |
| GeoPulse | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/GeoPulse/blob/main/PORTFOLIO_ROADMAP.md) |
| PulseMesh | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/PulseMesh/blob/main/PORTFOLIO_ROADMAP.md) |
| EventCore | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/EventCore/blob/main/PORTFOLIO_ROADMAP.md) |
| CodeArena | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/CodeArena/blob/main/PORTFOLIO_ROADMAP.md) |
| SearchForge | [PORTFOLIO_ROADMAP.md](https://github.com/The-Null-Catchers/SearchForge/blob/main/PORTFOLIO_ROADMAP.md) |
