﻿<div style="direction: rtl;">

بسم الله الرحمن الرحیم
===================

## 1. مقدمه

این پروژه یک پروژه خالی است که شامل ``style`` ها و فایل ``layout`` ای می شود که 
به ما در نمایش یک داکیومت فارسی کمک می کند.

## 2. نوشتن صفحات فارسی

برای اینکه یک صفحه فارسی داشته باشیم فقط کافی است که در ابتدای فایل آن صفحه کد 
زیر را بنویسیم تا تمام مطالب آن صفحه به استثنای مطالبی که اساسا انگلیسی هستن مثل
کد ها.

```
.. rst-class:: persian
```

## 3. تنظیم مستندات

برای اینکه این پروژه را برای کار خودتان آماده کنید ابتدا فایل ``conf.py`` داخل 
پوشه ``source`` را باز کنید و سپس مقادیر زیر را تکمیل کنید.

```
# -- Project information -----------------------------------------------------

project = 'Guideline'
copyright = '2019, Mahdi Aslami Khavari'
author = 'Mahdi Aslami'

```

## 4. استفاده کردن

برای درست کردن مستندات به شکل یک سایت کافی است دستور زیر را اجرا کنید این دستور 
از فایل ``make.bat`` استفاده می کند.

```
$ make html
```

می توانید اطلاعات سایت خود را از پوشه ``build/html`` مشاهده کنید.

## 5. Lisences

در این پروژه از فونت «ایران شارپ» استفاده شده است که جهت استفاده در پروژه ها 
نیاز به خرید دارد جهت اطلاعات بیشتر به سایت زیر مراجعه کنید.

[www.fontiran.com][1]

مهدی اسلمی خاوری 28 مرداد 1398

</div>

[1]: www.fontiran.com