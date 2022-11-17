---
title: 通过 C++ 将 WORDML 转换为 POT
description: 在您的 C++ 应用程序中将 WORDML 导出为 POT，而无需使用 Microsoft Word of PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: WORDML
outformat: POT
otherformats: PPT PPS PPTX ODP PPSX PPSM POWERPOINT POTM POTX PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="将 WORDML 转换为 POT 的 C++ API" h2="在您的 C++ 应用程序中将 WORDML 导出为 POT，而无需使用 Microsoft Word&reg;或 PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包含强大的文件自动化 API，允许在使用其中两个 API 时自动进行 WORDML 到 POT 的转换。使用 [Aspose.Words for C++](https://products.aspose.com/words/cpp/) 加载您的 WORDML 并将其转换为 HTML，然后通过 PowerPoint 操作 C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) 加载 HTML 创建一个新的演示文稿，并将其保存为 POT。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ 上的 WORDML 到 POT 转换" %}}
1.使用[Wordmlument](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument)类参考打开WORDML文件
2. 使用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_stdbasicostream_saveoptions) 成员函数将 WORDML 转换为 HTML
3.初始化一个新的[Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)对象
4. 在你的幻灯片中添加一个自选图形，并在其中添加 AddTextFrame
5. 加载 HTML 内容并将其写入您的 Presentation 文件中
6. 使用 [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 方法将文档保存为 POT 格式，并将 Pot 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total.Cpp``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，从 [下载](https://downloads.aspose.com/total/cpp) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load WORDML file with an instance of Wordmlument
Wordmlument wordmlument = new Wordmlument("template.wordml");
System::SharedPtr<Wordmlument> wordml = System::MakeObject<Wordmlument>(u"sourceFile.wordml");
// save the wordmlument in HTML file format
wordml->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Pot
pres->Save(output.pot, Aspose::Slides::Export::SaveFormat::Pot);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 加载受密码保护的 WORDML 文档" %}}
除了文档转换，[Aspose.Words for C++](https://products.aspose.com/words/cpp/) API 为 C++ 开发人员提供了大量的文档操作功能。如果您的 Microsoft Word WORDML 文件格式受密码保护，您仍然可以使用 API 打开它。为了加载加密文档，您可以使用特殊的构造函数重载，它接受 [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) 对象。此对象包含 Password 属性，该属性指定密码字符串。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected wordmlument, the password is passed to the wordmlument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"wordmlPassword");
// load the wordmlument from the local file system by filename:
SharedPtr<Wordmlument> wordml = MakeObject<Wordmlument>(u"Encrypted.wordml", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 在 POT 文档中添加注释" %}}
在将 WORDML 保存为 POT 的同时，您还可以使用 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) 在您的 POT 文档中添加更多功能。例如，您可以在演示文稿中添加评论。演示幻灯片注释与特定作者相关联。 Presentation 类在 ICommentAuthorCollection 中保存负责添加幻灯片注释的作者集合。对于每个作者，ICommentCollection 中都有一组评论。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Pot
pres->Save(output.pot, Aspose::Slides::Export::SaveFormat::Pot);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/wordml-to-ppt/" name="WORDML 至 PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/wordml-to-pps/" name="WORDML 至 PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/wordml-to-pptx/" name="WORDML 至 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/wordml-to-pot/" name="WORDML 至 POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/wordml-to-ppsx/" name="WORDML 至 PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/wordml-to-ppsm/" name="WORDML 至 PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/wordml-to-powerpoint/" name="WORDML 至 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/wordml-to-potm/" name="WORDML 至 POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/wordml-to-potx/" name="WORDML 至 POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/wordml-to-pptm/" name="WORDML 至 PPTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}