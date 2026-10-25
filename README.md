# Baby Care Tracker — v1.0 Beta

متابعة رعاية الطفل · تطبيق أندرويد يعمل دون إنترنت

[العربية](#العربية) · [English](#english)

## العربية

تطبيق لتسجيل رعاية الطفل على جهاز واحد. يعمل التطبيق بالكامل دون إنترنت،
ويحفظ الملفات والسجلات في SQLite والصور في مساحة التطبيق الخاصة على الجهاز.
لا يوجد حساب أو Firebase أو مزامنة سحابية أو إرسال بيانات إلى المطوّر.

**تنزيل:** من قسم [Releases](https://github.com/ahmedayman-cs/baby-care-tracker-download/releases)،
اختر **Baby Care Tracker v1.0 Beta** ثم الملف **Baby-Care-Tracker-v1.0-Beta.apk**.
قارن بصمة SHA-256 بملف `SHA256SUMS` قبل التثبيت.

### التثبيت والبيانات

1. نزّل ملف APK وافتحه من تطبيق الملفات. اسم التطبيق الظاهر هو **Baby Care Tracker**.
2. اسم حزمة النسخة التجريبية هو **`com.babycare.tracker.beta`**.
   هذه نسخة مستقلة تُثبت بجانب النسخة الأصلية وGUI Test، وتبدأ بسجلات فارغة.
   لا تستورد بيانات تلك التطبيقات أو تستبدلها؛ تبقى سجلاتك في التطبيق القديم.
3. اسمح لتطبيق الملفات أو المتصفح بالتثبيت من هذا المصدر فقط إذا طلب أندرويد ذلك.
   إذا حظر أندرويد التثبيت، توقف وتحقق من الملف؛ لا تحذف تطبيقك القديم لفرض التثبيت.
4. عند الحاجة، اسمح بالإشعارات واضبط تذكيرات الدواء وأذونات المنبهات من داخل التطبيق.
5. تتطلب تحديثات **هذه النسخة التجريبية** نفس الحزمة وشهادة التوقيع. اختر تحديثًا،
   ولا تحذف التطبيق أو تمسح بياناته للاحتفاظ بسجلاته.

**لا توجد حاليًا ميزة نسخ احتياطي أو استعادة يدوية، بما فيها الصور.**
حذف التطبيق أو مسح بياناته أو فقدان الجهاز قد يؤدي إلى فقدان السجلات المحلية.
لا توجد آلية ترحيل تلقائي لبيانات النسخة الأصلية أو GUI Test.

### الميزات

- ملفات متعددة للأطفال، صور، وعرض العمر حسب تاريخ الميلاد.
- نوم ليلي وقيلولات، حساب المدة عبر منتصف الليل، وعدد الاستيقاظات ومؤقتات محفوظة.
- رضاعة طبيعية بالمدة، حليب صناعي بالمل، وطعام صلب بالغرام أو الملعقة دون جمع الوحدات.
- سجل الحفاضات والبول والبراز، مع حساب الأحداث المشتركة بدقة.
- أدوية وجرعات **يدخلها المستخدم**، مواعيد ثابتة أو دورية، وتذكيرات محلية اختيارية.
  لا يقترح التطبيق جرعة دواء أو جدول علاج، ولا يعيد جدولة الجرعات تلقائيًا عند التأخير.
- لوحة صحة برسوم ٧ و٣٠ يومًا، وسجل الوزن والطول ومحيط الرأس.
- رحلة نمو حسب العمر، مكتبة إرشادية، وتسجيل المعالم الملحوظة وتواريخها.
- العربية من اليمين لليسار والإنجليزية، وتوقيت ١٢ ساعة، وتصميم بيج وبني.
- إشعارات مستمرة لمؤقتات النوم والرضاعة، مع إيقاف وفتح التطبيق، عندما يسمح أندرويد.

### المتطلبات والحدود

- يتطلب أندرويد **7.0 / API 24** أو أحدث. التحقق الآلي لهذه النسخة على أندرويد 15؛
  لا يعني ذلك اختبار كل إصدار أو هاتف. النسخة تجريبية وتحتاج تجربة على جهازك.
- الإشعارات والمنبهات والعمل في الخلفية تعتمد على أذونات أندرويد وسياسة البطارية.
- السجلات الناقصة لا تعني غياب الرعاية. الإرشادات والمعالم والمراجع عامة وليست تشخيصًا
  أو مواعيد نهائية جامدة للنمو. الرسوم لا تستنتج حالات طبية.
- رسوم النمو تعرض القياسات المسجلة؛ لا توجد منحنيات مئوية من WHO دون بيانات مرجعية موثقة.
- لا يوجد نسخ احتياطي/استعادة يدوية أو حساب أو مزامنة بين الأجهزة.
- قد يظهر اسم **Baby Care Tracker** لأكثر من تطبيق إذا احتفظت بالنسخة الأصلية؛
  تحقق من حزمة `.beta` وإصدار Beta في صفحة «حول التطبيق».

هذا المستودع للتنزيل والتوثيق فقط؛ مصدر Flutter ليس منشورًا هنا.
راجع [الخصوصية](PRIVACY.md) و[ملاحظات الإصدار](RELEASE_NOTES.md) وتراخيص المكونات
المرفقة `THIRD-PARTY-NOTICES.txt`. تنزيل APK من GitHub يحتاج اتصالًا؛ استخدام التطبيق لا يحتاجه.

## English

A single-device baby-care journal. The installed app works fully offline: records
live in local SQLite and photos in private app storage. There is no account,
Firebase, cloud sync, telemetry, or upload to the developer.

**Download:** open [Releases](https://github.com/ahmedayman-cs/baby-care-tracker-download/releases),
choose **Baby Care Tracker v1.0 Beta**, then **Baby-Care-Tracker-v1.0-Beta.apk**.
Compare its SHA-256 with `SHA256SUMS` before installing.

### Installation and existing data

1. Download and open the APK in Files. The visible application name is **Baby Care Tracker**.
2. This beta uses **`com.babycare.tracker.beta`**. It installs alongside production and
   GUI Test, starts with its own empty records, and does not import or replace their data.
   Keep those installations to access their existing records.
3. If Android asks, allow your Files app/browser to install from that source.
   If installation is blocked, stop and verify the file. Do not uninstall an existing app to force it.
4. Enable notifications and medicine/alarm permissions in the app when needed.
5. Future updates to **this beta** must use the same package and signing certificate.
   Choose Update; keep the installation and storage to retain its records.

**Manual backup and restore, including photos, are not currently available.**
Uninstalling, clearing storage, or losing the device can lose local records.
Automatic migration from production or GUI Test is not implemented.

### Features

- Multiple child profiles, photos, and natural age display from date of birth.
- Night sleep, naps, overnight duration calculations, wake-up counts, and persistent timers.
- Breastfeeding duration, formula in mL, and solids in grams or spoons, kept separate.
- Urine, stool, and combined diaper events with accurate counts.
- User-entered medicines/doses, fixed or repeating schedules, and optional local reminders.
  The app does not recommend doses or treatment schedules, or shift future doses when one is late.
- Health analytics with 7/30-day charts, plus weight, length/height, and head measurements.
- Age-based Growth Journey, guidance library, and dated observed-milestone records.
- Arabic RTL, English, 12-hour time, and a beige-and-brown interface.
- Persistent sleep/breastfeeding timer notifications with Stop and Open actions when Android permits.

### Requirements and limitations

- Requires **Android 7.0 / API 24 or later**. Automated verification uses Android 15;
  every Android version/device has not been tested. This is a beta requiring device testing.
- Notifications, alarms, and background behavior depend on Android permissions and battery policy.
- Missing records do not establish missed care. Guidance, milestones, and ranges are informational,
  not diagnoses or rigid deadlines. Charts do not infer medical conditions.
- Growth charts show recorded measurements; no WHO percentiles are claimed without validated references.
- No manual backup/restore, accounts, or multi-device sync.
- If another installed app has the same visible name, check the `.beta` package and Beta version in About.

This repository distributes binaries and documentation only. Flutter project source is not published here.
See [Privacy](PRIVACY.md), [release notes](RELEASE_NOTES.md), and `THIRD-PARTY-NOTICES.txt`
for third-party licenses. GitHub downloading uses the network; the installed app does not require it.

Please do not post children's records, photos, medication details, database files, or unredacted logs publicly.
