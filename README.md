# iran_proviences

-- SUMMARY --

This module simply adds a vocabulary called "Iran Proviencies and Counties" which holds data about Iran proviences and their counties.
Although there is "Address Field" which can store information about Provience, Local Area , address and etc, in some cases we only need to mention information about Provience or Adminstrative Area (County) of Iran, where this module may become usefull
ماژول استانها و شهرستانهای ایران برای دروپال 8

-- REQUIREMENTS --

Only Core Drupal Taxonomy
 -taxonomy

-- INSTALLATION --

* Install as usual, see http://drupal.org/node/1897420 for further information.


-- CONFIGURATION --

*No Configuration needed

-- HOW IT WORKS --

This module consist of a json file which holds data about Iran Provinces and each provience Countis. When installing the module an script in hook_install will be executed which first creates a taxonomy vocabulary and then adds proviencies and their Counties as their child terms.

you easily can modify vocabulary if you need.

این ماژول دارای یک فایل نصبی ، یک فایل معرفی و یک فایل اطلاعات استانها و شهرستانهای مربوط به آن با فرمت جیسون است.
 با نصب ماژول هوک اینستال موجود در فایل با فرمت اینستال اجرا شده ، یک کتابخانه برای ذخیره ترمهای مربوط به استان و شهرستانها ایجاد میکند و پس از آن با خواندن اطلاعات موجود در فایل جیسون هر استان به عنوان یک ترم ذخیره میشود و پس از آن شهرستانهای مربوط به آن استان در قالب ترمهای فرزند آن استان به کتابخانه اضافه میشوند.
 -----------------------------------
 با وجود اینکه در دروپال ماژول آدرس فیلد وجود دارد و امکان اضافه کردن لیست استانها و شهرستانها به آن وجود داشت با این وجود ممکن است در برخی موارد صرفا بخواهیم یک استان یا شهرستان را از کاربر بگیریم و سایر اطلاعات را نیاز نداشته باشیم ، در این حالت این ماژول مناسب خواهد بود.
 -----------------------------------
 لیست استانها و شهرستانها بر اساس دادههای مرکز آمار و با بروزرسانی مربوط به سال 1397 میباشد.
 -----------------------------------
این ماژول پیشنیاز خاصی ندارد و صرفا بایستی ماژول تکسونومی فعال باشد.
------------------------------------
تمامی دستورالعملهای این ماژول در فایل با پسوند دات اینستال رخ میدهد و از این جهت به فایل با پسوند ماژول نیازی نبود.
