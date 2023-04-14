---
title: 通过 C++ 将 DOTM 转换为 POT 或使用免费的在线转换器
description: 在您的 C++ 应用程序中将 DOTM 导出为 POT，而无需使用 Microsoft Word of PowerPoint 或在线。在集成代码之前快速测试免费的 POT 到 CSV 在线转换器。

family: total
platformtag: cpp
feature: conversion
informat: DOTM
outformat: POT
otherformats: PPTM POWERPOINT PPTX POTX PPSX ODP PPSM POTM PPS PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="将 DOTM 转换为 POT 的 C++ API 或在线应用程序" h2="在您的 C++ 应用程序中将 DOTM 导出为 POT，而无需使用 Microsoft Word&reg;或 PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包含强大的文件自动化 API，允许在使用其中两个 API 时自动进行 DOTM 到 POT 的转换。使用 [Aspose.Words for C++](https://products.aspose.com/words/cpp/) 加载您的 DOTM 并将其转换为 HTML，然后通过 PowerPoint 操作 C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) 加载 HTML 创建一个新的演示文稿，并将其保存为 POT。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ 上的 DOTM 到 POT 转换" %}}
1. 用[Dotmument](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument)类参考打开DOTM文件
2. 使用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_stdbasicostream_saveoptions) 成员函数将 DOTM 转换为 HTML
3. 始化一个新的[Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)对象
4. 在你的幻灯片中添加一个自选图形，并在其中添加 AddTextFrame
5. 加载 HTML 内容并将其写入您的 Presentation 文件中
6. 使用 [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 方法将文档保存为 POT 格式，并将 Pot 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total.Cpp``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，从 [下载](https://releases.aspose.com/total/cpp) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOTM file with an instance of Dotmument
Dotmument dotmument = new Dotmument("template.dotm");
System::SharedPtr<Dotmument> dotm = System::MakeObject<Dotmument>(u"sourceFile.dotm");
// save the dotmument in HTML file format
dotm->Save(u"HtmlOutput.HTML");
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

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>免费的 DOTM 到 POT 在线转换器</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pot&from=dotm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 加载受密码保护的 DOTM 文档" %}}
除了文档转换，[Aspose.Words for C++](https://products.aspose.com/words/cpp/) API 为 C++ 开发人员提供了大量的文档操作功能。如果您的 Microsoft Word DOTM 文件格式受密码保护，您仍然可以使用 API 打开它。为了加载加密文档，您可以使用特殊的构造函数重载，它接受 [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) 对象。此对象包含 Password 属性，该属性指定密码字符串。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected dotmument, the password is passed to the dotmument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"dotmPassword");
// load the dotmument from the local file system by filename:
SharedPtr<Dotmument> dotm = MakeObject<Dotmument>(u"Encrypted.dotm", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 在 POT 文档中添加注释" %}}
在将 DOTM 保存为 POT 的同时，您还可以使用 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) 在您的 POT 文档中添加更多功能。例如，您可以在演示文稿中添加评论。演示幻灯片注释与特定作者相关联。 Presentation 类在 ICommentAuthorCollection 中保存负责添加幻灯片注释的作者集合。对于每个作者，ICommentCollection 中都有一组评论。
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
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>经常问的问题</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>如何在线将 DOTM 转换为 POT？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以在上面找到用于 DOTM 转换的在线应用程序。要开始转换过程，您可以通过拖放 DOTM 文件或在白色区域内单击以导入文档来添加 DOTM 文件。添加文件后，只需单击“转换”按钮即可。 DOTM 到 POT 转换完成后，您只需单击一下即可下载转换后的文件。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>转换 DOTM 需要多长时间？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">此在线转换器的速度在很大程度上取决于正在转换的 DOTM 文件的大小。只需几秒钟即可将小型 DOTM 文件转换为 POT。如果您在 .NET 应用程序中使用转换代码，转换速度将取决于您对应用程序的优化程度。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用免费的 Aspose.Total 转换器将 DOTM 转换为 POT 是否安全？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">当然！使用我们的在线转换器将您的 DOTM 文件转换为 POT 后，POT 文件的下载链接将立即可用。我们非常重视您上传文件的安全和隐私，并会在转换过程完成 24 小时后将其删除。请放心，没有人可以访问您的文件。我们的转换过程，包括 DOTM 转换，是完全安全的。我们提供了一个用于测试目的的免费应用程序，以便您可以在集成代码之前验证结果。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>我应该使用什么浏览器来转换 DOTM？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">对于在线 DOTM 转换，您可以使用任何现代浏览器，例如 Google Chrome、Firefox、Opera 或 Safari。但是，如果您正在开发桌面应用程序，建议使用 Aspose.Total DOTM Conversion API 以获得流畅的性能。</span>
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