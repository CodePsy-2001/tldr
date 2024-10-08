# apt-get

> أداة إدارة الحزم لديبيان وأوبونتو.
> ابحث عن الحزم باستخدام `apt-cache`.
> لمزيد من التفاصيل: <https://manned.org/apt-get.8>.

- تحديث قائمة الحزم الموجودة وإصداراتها (يوصى بتشغيله قبل أي أمر `apt-get` آخر):

`apt-get update`

- تثبيت حزمة معينة، أو تحديثها إلى آخر إصدار متوفر:

`apt-get install {{package}}`

- إزالة حزمة معينة:

`apt-get remove {{package}}`

- إزالة حزمة معينة وملفات الإعدادات الخاصة بها:

`apt-get purge {{package}}`

- تطوير جميع الحزم المثبتة إلى أجدد الإصدارات المتوفرة:

`apt-get upgrade`

- تنظيف المستودع المحلي - إزالة ملفات الحزم (.deb) من التنزيلات المعطلة التي لم يعد من الممكن تنزيلها:

`apt-get autoclean`

- إزالة جميع الحزم التي لم تعد مطلوبة:

`apt-get autoremove`

- تطوير الحزم المثبتة (مثل `upgrade`)، ولكن تقوم بإزالة الحزم القديمة وتثبيت حزم إضافية لتلبية التوابع الجديدة:

`apt-get dist-upgrade`
