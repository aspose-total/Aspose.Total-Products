---
title: تحويل OTT إلى POT عبر C# .NET أو مع محول مجاني على الإنترنت
description: تحويل مستندات Word ott إلى ملفات PowerPoint pot باستخدام C#. تحويل ملفات متعددة داخل ASP.NET أو تطبيقات .NET الأخرى.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="تحويل OTT إلى POT باستخدام C# أو عبر الإنترنت" h2="أنشئ Microsoft Word OTT إلى تطبيقات تحويل PowerPoint POT على .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="كيفية تحويل OTT إلى POT باستخدام C# أو عبر الإنترنت" %}}

من أجل أتمتة العملية لأي ملفات Word ott لتحويل دفعة العرض التقديمي لـ PowerPoint pot ، سنستخدم [Aspose.Words for .NET](https://products.aspose.com/words/net) و [Aspose.Slides لـ .NET](https://products.aspose.com/slides/net) واجهات برمجة التطبيقات. الأول هو واجهة برمجة تطبيقات معالجة النصوص لمعالجة مستندات Microsoft Word أو معالجتها. حيث أن الأخير عبارة عن واجهة برمجة تطبيقات لمعالجة العروض التقديمية تتيح لك إنشاء شرائح Microsoft PowerPoint أو تعديلها. تعد كل من واجهات برمجة التطبيقات جزءًا من حزمة [Aspose.Total for .NET](https://products.aspose.com/total/net). يمكنك [تنزيل] مباشرة  من Nuget أو يمكنك استخدام الأوامر التالية من وحدة تحكم مدير الحزمة.

{{% blocks/products/pf/agp/code-block title="أمر وحدة تحكم مدير الحزم" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحويل OTT إلى POT عبر C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. أضف مرجع Aspose.Total لـ .NET
1. قم بتحميل ملف OTT باستخدام فئة [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. احفظ مستند OTT في تنسيق HTML
1. قم بإنشاء كائن [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. استيراد محتوى HTML في إطار نصي لأي شكل شريحة داخل العرض التقديمي
1. احفظ المستند باستخدام [Aspose.Slides.Presentation.Save("output.pot"، SaveFormat.Pot)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية.
- بيئة التطوير مثل Microsoft Visual Studio.
- Aspose.Words for .NET & amp؛ Aspose.Slides لـ .NET DLLs أو Aspose.Total لـ .NET DLL المشار إليها في مشروعك.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="يوضح نموذج التعليمات البرمجية هذا كيفية تحويل OTT إلى POT باستخدام C# أو عبر الإنترنت" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word OTT file
Aspose.Words.Document ott = new Aspose.Words.Document("sourceWordFile.ott");

// Save OTT file to HTML 
ott.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages OTT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to POT.

using (Presentation pot = new Presentation()){

	// Access the default first slide of presentation
	ISlide slide = pres.Slides[0];

	// Adding the AutoShape to accomodate the HTML content 
	// Adjust it as of your need
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// Adding text frame to the shape
	ashape.AddTextFrame("");

	// Clearing all paragraphs in added text frame
	ashape.TextFrame.Paragraphs.Clear();

	// Loading the HTML file using stream reader
	TextReader tr = new StreamReader("filepath\\test.html");

	// Adding text from HTML stream reader in text frame
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// Save the POT Presentation
	pot.Save("filepath\\pres.pot", Aspose.Slides.Export.SaveFormat.Pot);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>محول عبر الإنترنت لـ OTT إلى POT</h3>

<iframe title="pot to ott" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=pot&from=ott" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="تطبيق مجاني لتحويل OTT إلى POT" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POT file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{% blocks/products/pf/feature-page-section  h2="تحويل ملف OTT إلى POT برمجيًا: حالات الاستخدام" %}}
الملخص:

الملفات الالكترونية بناءً على النماذج (OTT - Object-oriented Template Technology) تستخدم لتخزين معلومات التنسيق، مما يجعلها مثالية لإنشاء interfaces المستخدمين و تطبيقات الويب动态. ومع ذلك، عندما نعمل مع محتوى وثيقة (static content)، يصبح formato Portable Document Format (PDF) أساسيًا في出版 الكتبات وال分发.

تحويل الملفات OTT إلى formats PDF هو 必要 للاستخدام الكامل لاستطاعاتك في مجال النشر وال 分发. هذا التحول يتيح لك:

** استخدامات:**

*   **出版 الوثائق**: تحويل الملفات OTT لإنشاء وثائق عالية الجودة وم专业ة مثل الدعايات والرصاص والتقارير.
*   **إنشاء الكتبات الإلكترونية**: استخدام PDF ل出版 الكتبات الإلكترونية، مما يضمن أن المحتوى مرفق و可قرأ على أجهزة مختلفة.
*   ** 分发 محتوى الويب**: تحويل الملفات OTT ل 分发 محتوى الويب مثل المقالات والمدونات والجريدات الإخبارية.
*   **منصة النشر الرقمي**: استخدام PDF لإنشاء منصات النشر الرقمية، مما يتيح للاستخدمين تنزيل واطلاع على المنشورات بوعي.

*   **ال_archival و الحفاظ على الوثائق**: تحويل الملفات OTT للحفاظ على الوثائق لفترة طويلة من الزمن، مما يضمن استمراريةaccess و استخدامها.
{{% /blocks/products/pf/feature-page-section %}}
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
                          <span itemprop="name"><b>كيف يمكنني تحويل OTT إلى POT Online؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">تم دمج التطبيق عبر الإنترنت لتحويل OTT أعلاه. لاستخدام هذا التطبيق ، يمكنك إضافة ملف OTT الخاص بك عن طريق سحبه وإفلاته في المنطقة البيضاء المحددة أو بالنقر داخل المنطقة لاستيراد المستند. بعد ذلك ، اضغط على زر التحويل لبدء عملية التحويل. بعد اكتمال تحويل OTT إلى POT ، يمكنك تنزيل ملفك المحول حديثًا بنقرة واحدة فقط ، وسيكون متاحًا لك في شكل ملف POT.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>كم من الوقت يستغرق تحويل OTT؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">يعمل هذا المحول عبر الإنترنت بسرعة ولكنه يعتمد بشكل أساسي على حجم ملف OTT الذي يتم تحويله. بالنسبة لملفات OTT الصغيرة ، يمكن إتمام التحويل إلى POT في غضون ثوانٍ. ومع ذلك ، إذا قمت بدمج كود التحويل في تطبيق .NET ، فستعتمد سرعة التحويل على مدى تحسين تطبيقك لعملية التحويل.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>هل من الآمن تحويل OTT إلى POT باستخدام محول Aspose.Total المجاني؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">بالطبع! بمجرد اكتمال تحويل OTT إلى POT ، سيكون رابط التنزيل لملف POT المحول حديثًا متاحًا على الفور. كما يضمن سلامة عملية التحويل ، حيث أن جميع الملفات المرفوعة ، بما في ذلك ملفات OTT ، آمنة تمامًا وسيتم حذفها من النظام بعد 24 ساعة. علاوة على ذلك ، ستتوقف روابط التنزيل عن العمل بعد هذه الفترة ، مما يضمن خصوصية ملفاتك وحمايتها. التطبيق المتكامل مجاني للاستخدام ومصمم لأغراض الاختبار بحيث يمكن للمستخدمين تقييم النتائج قبل دمج الكود في مشاريعهم.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ما المتصفح الذي يجب أن أستخدمه لتحويل OTT؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">يمكنك استخدام أي متصفح ويب حديث ، مثل Google Chrome أو Firefox أو Opera أو Safari ، لتحويل OTT إلى POT عبر الإنترنت. ومع ذلك ، إذا كنت تقوم بتطوير تطبيق سطح مكتب ، فمن المستحسن استخدام Aspose.Total OTT Conversion API للحصول على معالجة سلسة وفعالة.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}