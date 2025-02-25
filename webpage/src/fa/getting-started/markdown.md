# مارک داون

برگه تقلب مارک داون به صورت یک مرجع سریع و ویترینی از چیدمان مارک داون در QOwnNotes در نظر گرفته شده است.

## سربرگ ها

برای سر و شکل دادن به متن خود از سرفصل ها استفاده کنید.

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

::: tip
**پنل جهت یابی** ساختار سرفصل های شما را نشان می دهد.
:::

از سوی دیگر، برای H1 و H2، یک سبک زیرخط دار:

```markdown
Alt-H1
======

Alt-H2
------
```

::: tip
به صورت پیش فرض QOwnNotes ** نام پرونده یادداشت** را از **سرفصل 1** ایجاد می کند (h1).
:::

## تکیه

```markdown
تکیه (که با نام ایتالیک نیز شناخته می شود) با علامت *ستاره*.

تکیه مؤکد (که به صورت پررنگ نیز شناخته می شود) با علامت **ستاره**.
```

::: tip
می‌توانید از [میانبر](./shortcuts.md) <kbd>Ctrl + B</kbd> برای پررنگ کردن متن و از <kbd>Ctrl + I</kbd> برای ایتالیک کردن آن استفاده کنید.
:::

## خط زیرین

علاوه بر این، یک گزینه اختیاری در تنظیمات برای فعال کردن خط زیرین وجود دارد که در * تنظیمات پیش نمایش* قابل اجرا می باشد.

```markdown
_خط زیرین_
```

::: tip
می توانید از [میانبر](./shortcuts.md) <kbd>Ctrl + U</kbd> برای زیر خط دار کردن یک متن استفاده کنید.
:::

## ابطال

```markdown
~~ابطال~~
```

::: tip
می توانید از [میانبر](./shortcuts.md) <kbd>Alt + Shift + S</kbd> برای ابطال یک متن استفاده کنید.
:::

## لیست ها

روش های زیادی برای ایجاد لیست وجود دارد.

```markdown
1. نخستین مورد لیست مرتب شده
2. مورد بعدی
  *زیر فهرست مرتب نشده.
1. اعداد حقیقی اهمیتی ندارند بلکه فقط عدد هستند
  1. زیرفهرست مرتب شده (تنها در ویرایشگر کار می کند نه در پیش نمایش)
4. و موردی دیگر.

* برای لیست مرتب نشده می توان از ستاره
- یا منها
+ یا بعلاوه استفاده کرد
```

::: tip
با فشار دادن دکمه <kbd>ورود</kbd> در انتهای هر لیست، یک مورد لیست جدید ایجاد می شود.
:::

## پیوندها

روش های متعددی برای ایجاد پیوند وجود دارد.

```markdown
[من یک پیوند سبک توکار هستم](https://www.google.com)

[من یک پیوند سبک توکار به همراه عنوان هستم]((https://www.google.com "Google's Homepage")

[می توانید از اعداد برای تعریف های پیوند سبک مرجع استفاده کنید][1]

URLها و URLهای موجود در براکت های زاویه دار به طور خودکار به پیوندهای واقع در پیش نمایش تبدیل می شوند. 
http://www.example.com or <http://www.example.com>

[1]: https://www.qownnotes.org
```

::: tip
می توانید از [میانبر](./shortcuts.md) <kbd>Ctrl + L</kbd> برای **ایجاد پیوند به صفحات وب یا سایر یادداشت ها** استفاده کنید.

استفاده از <kbd>Ctrl + Shift + X</kbd> یک کادر گفتگو را ظاهر می کند که به شما کمک می کند تا ** پیوست ها** را در یادداشت خود درج کنید.

می توانید با فشار دادن <kbd>Ctrl + Space</kbd> و در حالی که مکان نما را بر روی پیوند در ویرایش یادداشت نگه داشته اید، پیوند را دنبال کنید.
:::

### نشانک ها

نشانک های بکار رفته توسط [ افزونه مرورگر همراه وب QOwnNotes ](./browser-extension.md) از پیوندهای موجود در لیست ها استفاده می کنند.

```markdown
- [نام صفحه وب](https://www.example.com) #برچسب1 #برچسب2 برخی از توضیحات و برچسب ها
```

## تصاویر

امکان تعبیه تصاویر در QOwnNotes وجود دارد. آنها در پیش نمایش نشان داده می شوند.

```markdown
![متن جایگزین تصویر](media/my-image.jpg)
```

::: tip
می توانید از [میانبر](./shortcuts.md) <kbd>Ctrl + Shift + I</kbd> برای درج تصویر در یادداشت استفاده کنید. همچنین تصاویر می‌توانند در کلیپ بورد قرار بگیرند؛ به طوری که کادر گفتگو آن را شناسایی کرده و یک پیش نمایش نشان می دهد.

علاوه بر این، می‌توانید با <kbd>Ctrl + Shift + V</kbd> یک تصویر را مستقیماً از کلیپ بورد به یادداشت خود بچسبانید.
:::


## کد توکار و کد بلاک ها

```markdown
"کد" توکار دارای "بک تیک هایی" در اطرافش است.
```

::: tip
می توانید برای ایجاد یک کد بلاک توکار از [میانبر](./shortcuts.md) <kbd>Ctrl + Shift + C</kbd> در متن توکار منتخب یا درست در داخل متن استفاده کنید.
:::

بلوک های کد یا با خطوط دارای سه بک تیک محصور شده یا با چهار فاصله دچار فرورفتگی می شوند.

### 4 حصار فاصله

چهار فاصله در جلوی کدتان برای نشان دار کردن آن به عنوان کد بلاک اضافه کنید.

```markdown
    s = " کد با فرورفتگی فاصله"
    print s
```

### حصار بک تیک

علاوه بر این می توانید از سه بک تیک برای ایجاد یک کد پلاک استفاده کنید.
~~~مارک داون
```
کد اینجا وارد می شود
کد اینجا وارد می شود
```
~~~

::: tip
شما می توانید از [shortcut] (./shortcuts.md) <0
<kbd>Ctrl + Shift + C</kbd>
برای ایجاد یک کد بلاک در چندین خط منتخب از متن یا در یک خط خالی استفاده کنید. 
:::

### حصار بک تیک با برجسته سازی کد

مقداری برجسته سازی چیدمان با کد پلاک ها در QOwnNotes نیز وجود دارد.

~~~مارک داون
```بش
# یک توضیح هستم
cd Notes
~~~
~~~
زبان های پشتیبانی شده (و شناسه های کد بلاک) فعلی عبارتند از:
* BASh scripting, `bash`
* C, `c`
* C++, `cpp`
* C++, `cxx`
* C++, `c++`
* C#, `c#`
* CMake, `cmake`
* C#, `csharp`
* CSS, `css`
* Go, `go`
* HTML, `html`
* INI, `ini`
* Java, `java`
* JavaScript, `javascript`
* JavaScript, `js`
* JSON, `json`
* Makefile, `make`
* PHP, `php`
* Python, `py`
* Python, `python`
* QML, `qml`
* Rust, `rust`
* Shell scripting, `sh`
* SQL, `sql`
* TypeScript, `ts`
* TypeScript, `typescript`
* V, `v`
* Vex, `vex`
* XML, `xml`
* YAML, `yml`
* YAML, `yaml`


## جداول

جداول بخشی از مشخصات مارک داون اصلی نیستند اما پیش نمایش QOwnNotes آنها را پشتیبانی می کند. 

```مارک داون
علامت دو نقطه می تواند برای تراز کردن ستون ها بکار رود.

| جداول        | جالب           | هستند  |
| ------------- |:-------------:| -----:|
| ستون 3      | راست چین است | $1600 |
| ستون 2      | وسط چین است      |   $12 |
| خطوط گورخری | منظم هستند      |    $1 |

باید حداقل سه خط تیره که هر سلول سربرگ را جدا می کند، وجود داشته باشد.

همچنین می توانید از مارک داون توکار استفاده کنید.

| مارک داون| کمتر| جذاب |
| --- | --- | --- |
| *همچنان* | `به خوبی` | **نمایان سازی می کند** |
| 1 | 2 | 3 |
~~~

::: tip
<kbd>Alt + Shift + T</kbd> را فشار دهید تا یک کادر گفتگو فعال شود که می تواند به شما در ایجاد جداول کمک کند. حتی می توانید پرونده های CSV را در آن کادر گفتگو وارد کنید.

به منظور قالب بندی خودکار یک جدول مارک داون از <kbd>Ctrl + Space</kbd> در داخل آن استفاده کنید.
:::

## نقل قول های بلند

```markdown
> نقل قول های بلند در پست الکترونیکی برای شبیه سازی متن پاسخ بسیار سودمند هستند.
> این خط بخشی از همان نقل قول است.

قطع نقل قول.

> این خط بسیار طولانی است که هنگامی که از یک سطر یا ستون به سطر یا ستون بعدی حرکت می کند، همچنان به درستی نقل می شود. وای پسر اجازه دهید به نوشتن ادامه دهیم تا مطمئن شویم که این خط به اندازه کافی طولانی است تا به درستی برای هر کسی بین سطرها و ستون ها حرکت کند. اوه، می توانید **مارک داون** را در یک نقل قول بلند *جای دهید*. 
```

::: tip
می توانید به QOwnNotes بگویید که نقل قول های بلند یا فقط نویسه نقل قول را به طور کامل در * تنظیمات ویرایشگر* برجسته کند

می توانید از [میانبر](./shortcuts.md) <kbd>Ctrl + Shift + B</kbd> برای علامت گذاری متن به صورت نقل قول بلند استفاده کنید.
:::

## خط افقی جدا کننده

سه راه برای رسم یک خط افقی جدا کننده وجود دارد: خط ربط، ستاره یا زیرین خط.

```markdown
سه یا بیشتر...

خط ربط

---

ستاره

***

زیرین خط

___
```

## شکست خط

- ** دو خط نو** دسترسی شما را به یک **پاراگراف جدید** میسر می سازد.
- **یک خط نو** دسترسی شما را به یک **خط جدید در همان پاراگراف** میسر می سازد.
- برای برخورداری از **شکست خط بدون پاراگراف**، باید از **دو فاصله مؤخر** استفاده نمایید.

```markdown
در اینجا برای شروع خطی در اختیار ما گذاشته شده است.

این خط به وسیله دو خط نو از مورد فوق جدا می شود و یک *پاراگراف مجزا* خواهد بود.

این خط یک پاراگراف مجزا را نیز شروع می کند اما...  
این خط تنها با دو فاصله مؤخر و یک خط نوی منفرد جدا می شود و یک خط مجزا در *همان پاراگراف* است.
```

::: tip
فاصله های مؤخر به صورت پیش فرض در ویرایشگر برجسته هستند.
:::

## توضیحات

توضیحات در پیش نمایش نشان داده نمی شود.

```markdown
[comment]: # (این توضیح در پیش نمایش ظاهر نخواهد شد)

<!-- توضیحات HTML نیز پنهان هستند -->
```

::: tip
هنگام ایجاد خودکار نام پرونده یادداشت، بلاک کامنت html اصلی در یادداشت هم نادیده گرفته می شود.
:::

## لیست های صندوق بررسی

شما می توانید لیست های ساده انجام دادنی را با لیست های صندوق بررسی ایجاد کنید.

```markdown
- [x] انجام شده
- [ ] انجام دادنی
```

::: tip
شما قادر خواهید بود صندوق های بررسی را در پیش نمایش علامت بزنید یا علامت آنها را بردارید.
:::

## پیش‌ گفتار

در QOwnNotes می توانید از یک پیش گفتار (مانند YAML) برای افزودن مقداری ابر اطلاعات اضافی استفاده کنید. **در پیش نمایش نشان داده نمی شود** و **برای تشکیل خودکار نام پرونده یادداشت اختلال ایجاد نمی کند**.

```markdown
---
عنوان: یک نام
توضیح: مقداری توضیح
---

# سرخط یادداشت از اینجا آغاز می شود

مقداری متن
```

نام پرونده این یادداشت نمونه `Note headline starts here.md`خواهد بود.
