---
title: تحويل PPS إلى DOCX عبر C# .NET أو مع محول مجاني على الإنترنت
description: تحويل مستندات PowerPoint pps إلى ملفات مستندات Word باستخدام C#. تحويل ملفات متعددة داخل ASP.NET أو تطبيقات .NET الأخرى.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="تحويل PPS إلى DOCX باستخدام C# أو عبر الإنترنت" h2="أنشئ Microsoft PowerPoint PPS Presentation إلى تطبيقات تحويل مستندات Word DOCX على .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPS" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="كيفية تحويل PPS إلى DOCX باستخدام C# أو عبر الإنترنت" %}}

من أجل أتمتة العملية لأي عرض تقديمي لـ PowerPoint pps إلى تحويل دفعي لملفات مستندات Word ، سنستخدم [Aspose.Slides for .NET](https://products.aspose.com/slides/net) و [Aspose.Words لـ .NET](https://products.aspose.com/words/net) واجهات برمجة التطبيقات. الأول هو واجهة برمجة تطبيقات معالجة العروض التقديمية في PowerPoint والتي تتيح لك إنشاء شرائح Microsoft PowerPoint أو تعديلها. حيث أن الأخير عبارة عن واجهة برمجة تطبيقات لمعالجة النصوص لمعالجة مستندات Microsoft Word أو معالجتها. تعد كل من واجهات برمجة التطبيقات جزءًا من حزمة [Aspose.Total for .NET](https://products.aspose.com/total/net). يمكنك [تنزيل] مباشرة  من Nuget أو يمكنك استخدام الأوامر التالية من وحدة تحكم مدير الحزمة.

{{% blocks/products/pf/agp/code-block title="أمر وحدة تحكم مدير الحزم" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحويل PPS إلى DOCX عبر C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. أضف مرجع Aspose.Slides لـ .NET و Aspose.Words لـ .NET
1. قم بتحميل عرض PowerPoint PPS باستخدام فئة [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. احفظ المستند في كائن [MemoryStream](https://docxs.microsoft.com/en-us/dotnet/api/system.io.memorystream؟view=net-5.0)
1. قم بإنشاء [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) وقم بتهيئته باستخدام كائن MemoryStream
1. احفظ المستند باستخدام [Aspose.Words.Document.Save ("output.docx"، SaveFormat.Docx)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية.
- بيئة التطوير مثل Microsoft Visual Studio.
- Aspose.Slides for .NET و Aspose.Words لـ .NET DLL المشار إليها في مشروعك.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="يوضح نموذج التعليمات البرمجية هذا كيفية تحويل PPS إلى DOCX باستخدام C# أو عبر الإنترنت" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint PPS file
Aspose.Slides.Presentation pps = new Aspose.Slides.Presentation("source.pps");

var stream = new MemoryStream();

pps.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var docx = new Aspose.Words.Document(stream);
      
// Save the Word DOCX document
docx.Save("output.docx", Aspose.Words.SaveFormat.Docx);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>محول عبر الإنترنت لـ PPS إلى DOCX</h3>

<iframe title="docx to pps" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=docx&from=pps" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="تطبيق مجاني لتحويل PPS إلى DOCX" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPS file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>أسئلة مكررة</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>كيف يمكنني تحويل PPS إلى DOCX Online؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">تم دمج التطبيق عبر الإنترنت لتحويل PPS أعلاه. لاستخدام التطبيق ، يمكنك إضافة ملف PPS الخاص بك إما عن طريق سحبه وإفلاته في المنطقة المخصصة أو النقر داخل المنطقة لاستيراد الملف. بمجرد إضافة الملف ، انقر فوق الزر "تحويل" لبدء عملية التحويل. بعد اكتمال تحويل PPS إلى DOCX ، يمكنك تنزيل ملفك المحول حديثًا بنقرة واحدة فقط ، وسيكون متاحًا بتنسيق DOCX.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>كم من الوقت يستغرق تحويل PPS؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">هذا المحول عبر الإنترنت سريع ، لكن سرعة تحويل PPS إلى DOCX تعتمد بشكل أساسي على حجم ملف PPS الذي يتم تحويله. يمكن تحويل ملفات PPS الأصغر إلى تنسيق DOCX في غضون ثوانٍ. بالإضافة إلى ذلك ، إذا قمت بدمج رمز تحويل PPS إلى DOCX في تطبيق .NET ، فستعتمد سرعة التحويل على مدى جودة تطبيقك لعملية التحويل.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>هل من الآمن تحويل PPS إلى DOCX باستخدام محول Aspose.Total المجاني؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">بالطبع! بمجرد اكتمال عملية تحويل PPS إلى DOCX ، سيكون رابط التنزيل لملف DOCX المحول متاحًا على الفور. يتم حذف جميع الملفات المرفوعة ، بما في ذلك ملفات PPS ، من النظام بعد 24 ساعة ، وتتوقف روابط التنزيل عن العمل بعد هذه الفترة الزمنية. يضمن المحول عبر الإنترنت أمان ملفاتك وخصوصيتها ، ويتوفر التطبيق المتكامل مجانًا لأغراض الاختبار. يتيح ذلك للمستخدمين التحقق من النتيجة قبل دمج الكود في مشاريعهم.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ما المتصفح الذي يجب أن أستخدمه لتحويل PPS؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">يمكنك استخدام أي متصفح ويب معاصر مثل Google Chrome أو Firefox أو Opera أو Safari لتحويل ملفات PPS إلى DOCX عبر الإنترنت. ومع ذلك ، إذا كنت تقوم بإنشاء تطبيق سطح مكتب ، فمن المستحسن استخدام Aspose.Total PPS Conversion API للحصول على عملية تحويل سلسة وسلسة.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}