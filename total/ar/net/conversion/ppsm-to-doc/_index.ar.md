---
title: تحويل PPSM إلى DOC عبر C# .NET 
url: /ar/net/conversion/ppsm-to-doc/ 
description: تحويل مستندات PowerPoint ppsm إلى ملفات مستندات Word باستخدام C#. تحويل ملفات متعددة داخل ASP.NET أو تطبيقات .NET الأخرى.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="تحويل PPSM إلى DOC باستخدام C#" h2="أنشئ Microsoft PowerPoint PPSM Presentation إلى تطبيقات تحويل مستندات Word DOC على .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSM" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" apiHomeLink="https://products.aspose.com/total/family/" codeSamplesLink="https://github.com/aspose-total" liveDemosLink="" docsLink="https://docs.aspose.com/total/net" installationsDocsLink="https://docs.aspose.com/total/net" nugetLink="https://www.nuget.org/packages/aspose.total" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/total/net" learnAsLink="https://docs.aspose.com/total/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحويل PPSM إلى DOC باستخدام C#" %}}

من أجل أتمتة العملية لأي عرض تقديمي لـ PowerPoint ppsm إلى تحويل دفعي لملفات مستندات Word ، سنستخدم [Aspose.Slides for .NET](https://products.aspose.com/slides/net) و [Aspose.Words لـ .NET](https://products.aspose.com/words/net) واجهات برمجة التطبيقات. الأول هو واجهة برمجة تطبيقات معالجة العروض التقديمية في PowerPoint والتي تتيح لك إنشاء شرائح Microsoft PowerPoint أو تعديلها. حيث أن الأخير عبارة عن واجهة برمجة تطبيقات لمعالجة النصوص لمعالجة مستندات Microsoft Word أو معالجتها. تعد كل من واجهات برمجة التطبيقات جزءًا من حزمة [Aspose.Total for .NET](https://products.aspose.com/total/net). يمكنك [تنزيل] مباشرة  من Nuget أو يمكنك استخدام الأوامر التالية من وحدة تحكم مدير الحزمة.

{{% blocks/products/pf/agp/code-block title="أمر وحدة تحكم مدير الحزم" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحويل PPSM إلى DOC عبر C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. أضف مرجع Aspose.Slides لـ .NET و Aspose.Words لـ .NET
1. قم بتحميل عرض PowerPoint PPSM باستخدام فئة [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. احفظ المستند في كائن [MemoryStream](https://docs.microsoft.com/en-us/dotnet/api/system.io.memorystream؟view=net-5.0)
1. قم بإنشاء [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) وقم بتهيئته باستخدام كائن MemoryStream
1. احفظ المستند باستخدام [Aspose.Words.Document.Save("output.doc"، SaveFormat.Doc)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية.
- بيئة التطوير مثل Microsoft Visual Studio.
- Aspose.Slides for .NET و Aspose.Words لـ .NET DLL المشار إليها في مشروعك.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="يوضح نموذج التعليمات البرمجية هذا كيفية تحويل PPSM إلى DOC باستخدام C#" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint PPSM file
Aspose.Slides.Presentation ppsm = new Aspose.Slides.Presentation("source.ppsm");

var stream = new MemoryStream();

ppsm.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var doc = new Aspose.Words.Document(stream);
      
// Save the Word DOC document
doc.Save("output.doc", Aspose.Words.SaveFormat.Doc);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="تطبيق مجاني لتحويل PPSM إلى DOC" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPSM file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ppsm-to-doc" name="PPSM إلى DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ppsm-to-docx" name="PPSM إلى DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ppsm-to-rtf" name="PPSM إلى RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ppsm-to-dot" name="PPSM إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ppsm-to-dotx" name="PPSM إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ppsm-to-dotm" name="PPSM إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ppsm-to-docm" name="PPSM إلى DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ppsm-to-flatopc" name="PPSM إلى FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ppsm-to-odt" name="PPSM إلى ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ppsm-to-ott" name="PPSM إلى OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ppsm-to-wordml" name="PPSM إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ppsm-to-txt" name="PPSM إلى TXT" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}