---
title: تحويل DOCM إلى XLS في C++ أو مع محول مجاني على الإنترنت
description: C++ API لتحويل DOCM إلى XLS أو التطبيق عبر الإنترنت دون استخدام Microsoft Word أو Microsoft Excel أو عبر الإنترنت. اختبر محول POT إلى CSV على الإنترنت مجانًا بسرعة قبل دمج الكود.

family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: XLS
otherformats: ODS CSV DIF EXCEL XLT SXC XLSM XLTM TSV XLAM FODS XLSX XLSB XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتحويل DOCM إلى XLS أو التطبيق عبر الإنترنت" h2="تصدير DOCM إلى XLS عبر C++ بدون استخدام Microsoft <sup>&reg;</sup> Word أو Microsoft <sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
يمكنك تضمين ميزة تحويل DOCM إلى XLS داخل تطبيقات C++ بسهولة. باستخدام واجهة برمجة تطبيقات معالجة وتحويل غنية بالميزات وقوية وسهلة الاستخدام [Aspose.Words for C++](https://products.aspose.com/words/cpp/) ، يمكنك تصدير DOCM إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) ، يمكنك تحويل HTML إلى XLS. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل DOCM إلى XLS أو التطبيق عبر الإنترنت" %}}
1. افتح ملف DOCM باستخدام [Document](https://reference.aspose.com/words/cpp/class/aspose.words.docmument) مرجع فئة
2. تحويل DOCM إلى HTML باستخدام وظيفة العضو [Save](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_string_saveformat)
3. قم بتحميل مستند HTML باستخدام مرجع فئة [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. احفظ المستند بتنسيق XLS باستخدام وظيفة العضو [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="الوصول إلى خصائص مستند DOCM عبر C++" %}}
يسمح لك [Aspose.Words for C++](https://products.aspose.com/words/cpp/) أيضًا بالوصول إلى خصائص مستند ملف DOCM ويتيح لك اتخاذ قرار مستنير قبل عملية التحويل. للوصول إلى خصائص المستند ، يمكنك استخدام [BuiltInDocumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_docmument_properties) للحصول على خصائص مضمنة و [CustomDocumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.custom_docmument_properties) للحصول على خصائص مخصصة. يوضح مثال التعليمات البرمجية التالي كيفية تعداد كل الخصائص المضمنة والمخصصة في مستند.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-docmument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="احفظ ملف XLS للتدفق عبر C++" %}}
بعد تحويل DOCM إلى XLS ، يمكّنك [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) من حفظ مستندك للدفق. لحفظ الملفات في تدفق ، أنشئ كائن MemoryStream أو FileStream واحفظ الملف في كائن الدفق هذا عن طريق استدعاء [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) أسلوب الكائن [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349). حدد تنسيق الملف المطلوب باستخدام تعداد [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) عند استدعاء [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
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
                          <span itemprop="name"><b>كيف يمكنني تحويل DOCM إلى XLS Online؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">لاستخدام محول DOCM إلى XLS أعلاه ، ما عليك سوى اتباع هذه الخطوات السهلة. أولاً ، قم بإضافة ملف DOCM الخاص بك إلى المحول إما عن طريق سحب الملف وإفلاته في المنطقة البيضاء أو النقر داخل المنطقة لاستيراد المستند. بعد ذلك ، انقر فوق الزر "تحويل" لبدء عملية التحويل. <br />

بمجرد اكتمال تحويل DOCM إلى XLS ، ستتمكن من تنزيل الملف المحول على الفور بنقرة واحدة فقط. هذا يجعل من السهل للغاية تحويل ملفات DOCM إلى تنسيق XLS ، ويمكنك القيام بكل ذلك دون الحاجة إلى تثبيت أي برامج أو مكونات إضافية إضافية.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>كم من الوقت يستغرق تحويل DOCM؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">عندما يتعلق الأمر باستخدام محول DOCM إلى XLS ، فإن سرعة عملية التحويل تعتمد بشكل كبير على حجم ملف DOCM الخاص بك. بالنسبة للملفات الأصغر ، يمكن إكمال التحويل في بضع ثوانٍ فقط ، مما يجعلها سريعة وفعالة بشكل لا يصدق. ومع ذلك ، قد يستغرق تحويل الملفات الأكبر حجمًا وقتًا أطول قليلاً. <br />

إذا كنت تخطط لدمج رمز تحويل DOCM إلى XLS في تطبيق .NET الخاص بك ، فستعتمد سرعة وكفاءة عملية التحويل أيضًا على مدى جودة تطبيقك. من خلال التأكد من تحسين تطبيقك لعملية التحويل ، يمكنك المساعدة في ضمان تحويل ملفات DOCM إلى تنسيق XLS بسرعة ودقة.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>هل من الآمن تحويل DOCM إلى XLS باستخدام محول Aspose.Total المجاني؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">بالطبع! عند استخدام محول DOCM إلى XLS ، يمكنك أن تطمئن إلى أن ملفاتك آمنة ومأمونة. بعد اكتمال التحويل ، سيتم تزويدك برابط تنزيل لملف XLS الجديد الخاص بك. سيكون هذا الرابط متاحًا على الفور ويمكن استخدامه لتنزيل الملف على جهازك. <br />

لضمان أمان وخصوصية ملفاتك ، نقوم تلقائيًا بحذف أي ملفات تم تحميلها بعد 24 ساعة. هذا يعني أنه لن يتمكن أي شخص آخر من الوصول إلى ملفاتك بمجرد اكتمال عملية التحويل. بالإضافة إلى ذلك ، تم تصميم محول DOCM إلى XLS ليكون آمنًا وآمنًا ، لذا يمكنك الوثوق في أن ملفاتك يتم التعامل معها بعناية فائقة.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ما المتصفح الذي يجب أن أستخدمه لتحويل DOCM؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">محول DOCM إلى XLS هو أداة عبر الإنترنت يمكن الوصول إليها من خلال أي متصفح ويب حديث ، بما في ذلك Google Chrome و Firefox و Opera و Safari. هذا يجعله سهل الاستخدام بشكل لا يصدق ، حيث يمكنك ببساطة فتح المحول في متصفحك والبدء في تحويل ملفات DOCM إلى تنسيق XLS على الفور. <br />

ومع ذلك ، إذا كنت تقوم بتطوير تطبيق سطح مكتب وتحتاج إلى حل أكثر قوة لتحويل DOCM ، فقد ترغب في التفكير في استخدام Aspose.Total DOCM تحويل API. تم تصميم واجهة برمجة التطبيقات القوية هذه خصيصًا للمطورين وتقدم مجموعة واسعة من الميزات والإمكانيات للعمل مع ملفات DOCM ، بما في ذلك التحويل إلى تنسيق XLS.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}