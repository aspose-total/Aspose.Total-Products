---
title: قم بإزالة التعليقات التوضيحية ODT عبر الإنترنت أو قم بإدارة التعليقات التوضيحية عبر C++
description: حذف التعليقات من ملف ODT من خلال التطبيق عبر الإنترنت مجانًا. كود C++ API لإدارة تعليقات ملفات ODT.

family: total
platformtag: cpp
feature: Annotate
informat: ODT
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="امسح التعليقات من مستند ODT عبر الإنترنت أو قم بإدارتها عبر C++" h2="تطوير تطبيق أداة مساعدة للتعليقات التوضيحية للمستندات ODT قوي يعتمد على C++. الكود المدرج لإدارة تعليقات ملف ODT من خلال C++." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="إزالة التعليقات التوضيحية لـ ODT عبر الإنترنت" %}}

1. قم باستيراد ملف ODT لحذف التعليقات عن طريق تحميله
1. قم بذلك عن طريق النقر داخل منطقة الإفلات عبر السحب والإسقاط لتطبيق التعليقات التوضيحية
1. اعتمادًا على حجم ملف ODT وسرعة الإنترنت، انتظر لبضع ثوانٍ
1. انقر فوق الزر "إزالة" لمسح التعليقات
1. قم بتنزيل الملف على الفور

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="حذف تعليقات مستند ODT عبر C++" %}}

1. إضافة مرجع مكتبة إلى مشروع C++
1. تحميل ملف ODT
1. احصل على جميع العقد باستخدام GetChildNodes الذي يحتوي على NodeType::Comment كمعلمة
1. اتصل بـ NodeCollection.Clear عند جمع التعليقات

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="كود C++: حذف التعليقات من ملف ODT" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "remove-word-document-comments.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="أضف تعليقات عبر C++" %}}

1. إنشاء كائن فئة Document وDocumentBuilder
1. أو قم بتحميل المستند
1. استخدم فئة التعليق لإضافة التعليق
1. استخدم الأسلوب AppendChild مع التعليق obj كمعلمة
1. استخدم الطريقة ذات الصلة مثل get_Paragraphs()->Add
1. أو الطريقة الأخرى هي استخدام فئتي CommentRangeStart وCommentRangeEnd
1. اتصل بطريقة الحفظ لحفظ الملف مع التعليقات المضافة

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="استخراج كافة التعليقات" %}}

1. قم بتحميل المستند عبر كائن فئة المستند
1. احصل على جميع GetChildNodes في NodeCollection
1. قم بالتكرار خلال كل مجموعة وجمع المعلومات عنها

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="كود C++: إضافة تعليق إلى ملف ODT" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "word-document-annotations.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ Code: استخراج كافة التعليقات" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>تطوير تطبيق التعليقات التوضيحية للمستند ODT عبر C++</h2>

هل تحتاج إلى تطوير تطبيق أو أداة مساعدة للتعليقات التوضيحية ODT لتقديم الملاحظات أو تقديم الاقتراحات أو التعاون مع الآخرين في المستند؟باستخدام [Aspose.Words for C++](https://products.aspose.com/words/cpp/)، وهي واجهة برمجة تطبيقات فرعية لـ [Aspose.Total for C++](https://products.aspose.com/total/ar/cpp/)، يمكن لأي مطور C++ دمج كود API أعلاه داخل تطبيق التعليقات التوضيحية للمستند الخاص به.تتيح مكتبة C++ القوية برمجة أي حل للتعليقات التوضيحية للمستند.علاوة على ذلك، يمكنه دعم العديد من التنسيقات الشائعة بما في ذلك تنسيق ODT.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="مكتبة C++ للتعليق على ملفات ODT" %}}

هناك ثلاثة خيارات لتثبيت Aspose.Words for C++ على بيئة المطور لديك.يرجى اختيار ما يناسب احتياجاتك واتباع التعليمات خطوة بخطوة:<br /><br />

- Install a [حزمة نوجيت](https://www.nuget.org/packages/Aspose.Words.Cpp/). See [توثيق](https://docs.aspose.com/words/cpp/installation/#install-or-update-aspose-words-for-cpp-using-nuget)
- قم بتثبيت المكتبة باستخدام [وحدة تحكم إدارة الحزم](https://docs.aspose.com/words/cpp/installation/#install-or-update-asposewords-using-package-manager-console) داخل Visual Studio IDE
- قم بتثبيت المكتبة يدويًا باستخدام [مثبت الويندوز](https://docs.aspose.com/words/cpp/installation/#install-asposewords-for-c-by%20hand)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}
يمكنك استخدام مكتبة C++ هذه لتطوير البرامج على أنظمة التشغيل Microsoft Windows وLinux وmacOS:<br /><br />

- دول مجلس التعاون الخليجي >= 6.3.0 وClang >= 3.9.1 مطلوبة لنظام التشغيل Linux
- Xcode >= 12.5.1 وClang وlibc++ مطلوبة لنظام التشغيل macOS

<br /><br />
إذا كنت تقوم بتطوير برنامج لنظام التشغيل Linux أو macOS، فيرجى التحقق من المعلومات المتعلقة بتبعيات المكتبة الإضافية (الحزم مفتوحة المصدر لـfontconfig وmesa-glu) في [توثيق المنتج](https://docs.aspose.com/words/cpp/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="الأسئلة الشائعة" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>الأسئلة الشائعة</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>هل يمكنني استخدام كود C++ أعلاه في تطبيقي؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">نعم، نرحب بتنزيل هذا الرمز واستخدامه لغرض تطوير تطبيق التعليقات التوضيحية للمستندات المستند إلى C++.يمكن أن يكون هذا الرمز بمثابة مورد قيم لتعزيز وظائف وقدرات مشاريعك في مجال معالجة المستندات الخلفية ومعالجتها.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>هل يعمل تطبيق التعليقات التوضيحية للمستندات عبر الإنترنت على نظام التشغيل Windows فقط؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">لديك المرونة اللازمة لبدء التعليقات التوضيحية للمستند لإزالة التعليقات على أي جهاز، بغض النظر عن نظام التشغيل الذي يعمل عليه، سواء كان Windows أو Linux أو Mac OS أو Android. كل ما هو مطلوب هو متصفح ويب معاصر واتصال إنترنت نشط.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>هل من الآمن استخدام التطبيق عبر الإنترنت لإضافة تعليقات توضيحية إلى مستند ODT؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">بالطبع! ستتم إزالة ملفات الإخراج التي تم إنشاؤها من خلال خدمتنا بشكل آمن وتلقائي من خوادمنا خلال إطار زمني مدته 24 ساعة.ونتيجة لذلك، ستتوقف روابط العرض المرتبطة بهذه الملفات عن العمل بعد هذه الفترة.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ما المتصفح الذي يجب أن يستخدم التطبيق؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">يمكنك استخدام أي متصفح ويب حديث مثل Google Chrome أو Firefox أو Opera أو Safari لإضافة تعليقات توضيحية إلى مستند ODT عبر الإنترنت.ومع ذلك، إذا كنت تقوم بتطوير تطبيق سطح مكتب، فإننا نوصي باستخدام واجهة برمجة التطبيقات Aspose.Total لمعالجة المستندات من أجل الإدارة الفعالة.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}