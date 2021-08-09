Windows Server 2019 Github مع وصول RDP (ngrok US) رابط الريبو: https://github.com/jrrodriguez81/Windows2019RDP-US

قم بإنشاء خادم VPS مجاني مع 2cpu-7gb Ram مجانًا مع Github:

بالنسبة إلى آسيا ، انتقل إلى https://github.com/jrrodriguez81/Windows2019RDP-AP

انقر فوق Fork في الزاوية اليمنى من الشاشة لحفظه في Github الخاص بك.

قم بزيارة https://dashboard.ngrok.com للحصول على NGROK_AUTH_TOKEN

في Github ، انتقل إلى الإعدادات> الأسرار> سر المستودع الجديد

في الاسم: أدخل NGROK_AUTH_TOKEN

في القيمة: قم بزيارة https://dashboard.ngrok.com/auth/your-authtoken انسخ والصق Authtoken الخاص بك في

اضغط على إضافة سر

انتقل إلى الإجراء> CI> تشغيل سير العمل

أعد تحميل الصفحة واضغط على CI> build

اضغط على السهم لأسفل في Connect To Your RPD للحصول على IP ، User ، Password.

إذا تم حذف إعادة الشراء الخاصة بي ، فانتقل على GITHUB إلى .github / workflows> RDP-US.yml وقم بتحرير رابط جديد إلى الريبو الخاص بك. ALL. بات في مجلد الملفات
