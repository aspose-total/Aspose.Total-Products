---
title: تحويل ODT إلى PPTX عبر C# .NET أو مع محول مجاني على الإنترنت
description: تحويل مستندات Word odt إلى ملفات PowerPoint pptx باستخدام C#. تحويل ملفات متعددة داخل ASP.NET أو تطبيقات .NET الأخرى.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="تحويل ODT إلى PPTX باستخدام C# أو عبر الإنترنت" h2="أنشئ Microsoft Word ODT إلى تطبيقات تحويل PowerPoint PPTX على .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="كيفية تحويل ODT إلى PPTX باستخدام C# أو عبر الإنترنت" %}}

من أجل أتمتة العملية لأي ملفات Word odt لتحويل دفعة العرض التقديمي لـ PowerPoint pptx ، سنستخدم [Aspose.Words for .NET](https://products.aspose.com/words/net) و [Aspose.Slides لـ .NET](https://products.aspose.com/slides/net) واجهات برمجة التطبيقات. الأول هو واجهة برمجة تطبيقات معالجة النصوص لمعالجة مستندات Microsoft Word أو معالجتها. حيث أن الأخير عبارة عن واجهة برمجة تطبيقات لمعالجة العروض التقديمية تتيح لك إنشاء شرائح Microsoft PowerPoint أو تعديلها. تعد كل من واجهات برمجة التطبيقات جزءًا من حزمة [Aspose.Total for .NET](https://products.aspose.com/total/net). يمكنك [تنزيل] مباشرة  من Nuget أو يمكنك استخدام الأوامر التالية من وحدة تحكم مدير الحزمة.

{{% blocks/products/pf/agp/code-block title="أمر وحدة تحكم مدير الحزم" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحويل ODT إلى PPTX عبر C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. أضف مرجع Aspose.Total لـ .NET
1. قم بتحميل ملف ODT باستخدام فئة [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. احفظ مستند ODT في تنسيق HTML
1. قم بإنشاء كائن [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. استيراد محتوى HTML في إطار نصي لأي شكل شريحة داخل العرض التقديمي
1. احفظ المستند باستخدام [Aspose.Slides.Presentation.Save("output.pptx"، SaveFormat.Pptx)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية.
- بيئة التطوير مثل Microsoft Visual Studio.
- Aspose.Words for .NET & amp؛ Aspose.Slides لـ .NET DLLs أو Aspose.Total لـ .NET DLL المشار إليها في مشروعك.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="يوضح نموذج التعليمات البرمجية هذا كيفية تحويل ODT إلى PPTX باستخدام C# أو عبر الإنترنت" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word ODT file
Aspose.Words.Document odt = new Aspose.Words.Document("sourceWordFile.odt");

// Save ODT file to HTML 
odt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages ODT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPTX.

using (Presentation pptx = new Presentation()){

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

	// Save the PPTX Presentation
	pptx.Save("filepath\\pres.pptx", Aspose.Slides.Export.SaveFormat.Pptx);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>محول عبر الإنترنت لـ ODT إلى PPTX</h3>

<iframe title="pptx to odt" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pptx&from=odt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="تطبيق مجاني لتحويل ODT إلى PPTX" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPTX file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{% blocks/products/pf/feature-page-section  h2="تحويل ملف ODT إلى PPTX برمجيًا: حالات الاستخدام" %}}
الملفات ODT (OpenDocument Text) تستخدم بانتظام لإنشاء، تحرير، و分享 الوثائق النصية، مما يجعلها خياراً مثالياً للكتابات، الطلاب، وال επαγγελيسين على حد سوء. ومع ذلك، عندما يتعلق الأمر بمقدمة المعلومات المعقدة في شكل فيизيالي جذاب، فإن العروض المبنية على PowerPoint تصبح 必须.

تحويل ملفات ODT إلى صيغ PowerPoint هو عملية هامة لتمكين القدرات الكاملة في إنشاء العروض. هذه التحول يتيح لك:

**الاستخدامات:**

*   **العروض الbusiness**: تحويل الملفات ODT لإنشاء عروض business محترفة، مثل عرض تحديث الشركة، إطلاق المنتجات، وแคmpaign التسويق.
*   **العروض الأكاديمية**: استخدام PowerPoint لمقدمة النتائج البحثية، الرسائل الأكاديمية، واقتراحات الماجستير، في شكل جذابVisually، مما يساعد على التفاعل مع الجمهور وتنقل المعلومات المعقدة بفعالية.
*   **المواد التسويقية وال市场**: تحويل الملفات ODT لإنشاء عروض تسويق تفاعلية، demos المنتجات، والمواد التسويقية، مما يساعدك على التميز عن竞争اء.
*   **العروض التعليمية**: استخدام PowerPoint لإنشاء خطط دراسية جذابة، تutorials، وورشات، مما يجعل الموضوعات المعقدة أكثر إ易اسة ومتعة للطلاب.
*   **المشاريع الشخصية والblogs**: تحويل الملفات ODT لإنشاء مقالات محترفة، قصص شخصية، ومشاريع كتابة، مما يساعدك على مشاركة أفكارك وقصصك مع جمهور أوسع.
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
                          <span itemprop="name"><b>كيف يمكنني تحويل ODT إلى PPTX Online؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">تم دمج التطبيق عبر الإنترنت لتحويل ODT أعلاه. لاستخدام هذا التطبيق ، يمكنك إضافة ملف ODT الخاص بك عن طريق سحبه وإفلاته في المنطقة البيضاء المحددة أو بالنقر داخل المنطقة لاستيراد المستند. بعد ذلك ، اضغط على زر التحويل لبدء عملية التحويل. بعد اكتمال تحويل ODT إلى PPTX ، يمكنك تنزيل ملفك المحول حديثًا بنقرة واحدة فقط ، وسيكون متاحًا لك في شكل ملف PPTX.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>كم من الوقت يستغرق تحويل ODT؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">يعمل هذا المحول عبر الإنترنت بسرعة ولكنه يعتمد بشكل أساسي على حجم ملف ODT الذي يتم تحويله. بالنسبة لملفات ODT الصغيرة ، يمكن إتمام التحويل إلى PPTX في غضون ثوانٍ. ومع ذلك ، إذا قمت بدمج كود التحويل في تطبيق .NET ، فستعتمد سرعة التحويل على مدى تحسين تطبيقك لعملية التحويل.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>هل من الآمن تحويل ODT إلى PPTX باستخدام محول Aspose.Total المجاني؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">بالطبع! بمجرد اكتمال تحويل ODT إلى PPTX ، سيكون رابط التنزيل لملف PPTX المحول حديثًا متاحًا على الفور. كما يضمن سلامة عملية التحويل ، حيث أن جميع الملفات المرفوعة ، بما في ذلك ملفات ODT ، آمنة تمامًا وسيتم حذفها من النظام بعد 24 ساعة. علاوة على ذلك ، ستتوقف روابط التنزيل عن العمل بعد هذه الفترة ، مما يضمن خصوصية ملفاتك وحمايتها. التطبيق المتكامل مجاني للاستخدام ومصمم لأغراض الاختبار بحيث يمكن للمستخدمين تقييم النتائج قبل دمج الكود في مشاريعهم.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ما المتصفح الذي يجب أن أستخدمه لتحويل ODT؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">يمكنك استخدام أي متصفح ويب حديث ، مثل Google Chrome أو Firefox أو Opera أو Safari ، لتحويل ODT إلى PPTX عبر الإنترنت. ومع ذلك ، إذا كنت تقوم بتطوير تطبيق سطح مكتب ، فمن المستحسن استخدام Aspose.Total ODT Conversion API للحصول على معالجة سلسة وفعالة.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}