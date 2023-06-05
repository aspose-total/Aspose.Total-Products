---
title: تحويل صفحات الويب HTML إلى صور باستخدام C #
description: كشط صفحات الويب الخاصة بالموقع وتصدير HTML إلى الصور. تطوير تطبيقات .NET لكشط بيانات موقع الويب إلى JPEG و PNG و GIF و BMP وما إلى ذلك. 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل صفحات الويب إلى صور عبر C #" h2="استخراج بيانات موقع الويب من صفحات الويب بتنسيق HTML. قم بتحويل صور HTML إلى صور JPG و GIF و PNG و BMP ضمن تطبيقات .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">لماذا يتم تحويل صفحات الويب إلى صور؟</h2>
<p>يمكن أن يكون تحويل صفحات الويب إلى صور مفيدًا في مجموعة متنوعة من المواقف. إنه مطلب شائع للعديد من التطبيقات. في بعض السيناريوهات ، من الضروري التقاط صفحة الويب بالكامل كصورة ، بما في ذلك الأجزاء غير المرئية على الشاشة. يمكن أن يكون هذا مفيدًا لإنشاء معاينات موقع الويب ، أو التقاط الإيصالات والفواتير ، أو أرشفة صفحات الويب لأغراض قانونية. يمكن استخدامه لإنشاء لقطات شاشة لصفحات الويب لأغراض التوثيق أو الاختبار. يمكن استخدامه أيضًا لإنشاء صور مصغرة أو معاينات لصفحات الويب لاستخدامها في نتائج البحث أو معارض الصور. سواء كنت تقوم ببناء تطبيق سطح مكتب أو تطبيق ويب ، فهناك العديد من الخيارات المتاحة لتحويل صفحات الويب إلى صور باستخدام C #.</p><br />

<p>يمكن أن يوفر تحويل صفحات الويب إلى صور باستخدام C # العديد من الفوائد ، بما في ذلك:</p><br />
<ul>
<li>تحسين إمكانية الوصول: يمكن أن تكون الصور أسهل في القراءة والفهم للأشخاص الذين يعانون من إعاقات بصرية أو إعاقات أخرى.</li>
<li>زيادة قابلية: يمكن مشاركة الصور بسهولة أو تضمينها في مستندات أو تطبيقات أخرى.</li>
</ul>
<p>يمكن أن يمثل تحويل صفحات الويب إلى صور باستخدام C # أيضًا بعض التحديات ، بما في ذلك:</p><br />
<ul>
<li>دعم تنسيق محدود: قد لا تدعم بعض واجهات برمجة التطبيقات أو الأدوات جميع تنسيقات الصور أو قد يكون لها قيود على حجم أو دقة الصور الناتجة.</li>
<li>قضايا التوافق: قد لا يتم عرض بعض صفحات الويب بشكل صحيح في جميع المستعرضات أو قد تتطلب إعدادات أو مكونات إضافية معينة لعرضها بشكل صحيح.</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="كيفية تحويل صفحات الويب إلى صور باستخدام C #؟" %}}
لتحويل صفحات الويب إلى صور باستخدام C # ، يمكنك استخدام Aspose.HTML لـ .NET API الذي يوفر هذه الوظيفة لتحويل صفحات HTML إلى تنسيقات صور ، بما في ذلك JPEG و PNG و TIFF.</p>

1. قم بتحميل مستند HTML باستخدام أحد المُنشئين المتاحين في [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). يمكنك تحميل HTML من ملف أو كود HTML أو دفق أو عنوان URL.
2. قم بإنشاء مثيل جديد من [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) وقم بتعيين الخاصية ImageFormat إلى JPEG. بشكل افتراضي ، يتم تعيين الخاصية Format على PNG.
3. استخدم ملف [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) طريقة من فئة المحول لحفظ مستند HTML كملف JPEG. ستحتاج إلى توفير HTMLDocument و ImageSaveOptions ومسار ملف الإخراج كمعلمات إلى أسلوب ConvertHTML ().
4. سيتم حفظ ملف JPEG الناتج في مسار الملف المحدد.
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات تخريد الويب وتحويل الصور" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total ''` أو قم بالتثبيت مباشرة من Package Manager Console في Visual Studio.

اثنين [Aspose.Total for .NET](https://products.aspose.com/total/net/) الطفل API ، [Aspose.HTML for .NET](https://products.aspose.com/html/net/) سيتم دمجها.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}