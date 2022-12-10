---
title: 用于将 XPS 导出到 MARKDOWN 的 C++ API
description: 在 C++ 应用程序中将 XPS 转换为 MARKDOWN。

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: MARKDOWN
otherformats: PS DOT FLATOPC RTF DOCM DOTM DOTX MHTML PCL XAMLFLOW ODT OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="用于将 XPS 导出到 MARKDOWN 的 C++ API" h2="在 C++ 应用程序中将 XPS 渲染为 MARKDOWN，无需任何第三方应用程序" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) 文件格式自动化库允许 C++ 开发人员通过两个简单的步骤将 XPS 转换为 MARKDOWN。首先，您可以使用 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API 将 XPS 文件格式转换为 DOC。其次，通过使用高级 Word 文档处理 API [Aspose.Words for C++](https://products.aspose.com/words/cpp/)，您可以将 DOC 导出到 MARKDOWN。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="将 XPS 渲染为 MARKDOWN 的 C++ API" %}}
1.使用[Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)类参考打开XPS文件
2.使用[保存](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)成员函数将XPS转换为DOC
3. 使用 Aspose.Words API 的 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 类引用加载 DOC 文件
4.使用[Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)成员函数将文档保存为MARKDOWN格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total.Cpp``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，从 [下载](https://releases.aspose.com/total/cpp) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XPS file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.xps");
// save XPS as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Markdown
wordDoc->Save(u"output.Markdown");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 更改 XPS 文档的密码" %}}
在将 XPS 渲染为 MARKDOWN 的过程中，您可以打开受密码保护的 XPS 并更改其密码。要更改 XPS 文件的密码，您必须知道该文档的所有者密码。您可以通过指定所有者密码并使用 ChangePasswords 方法更改密码来使用 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) 加载受密码保护的 PDF 文档。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XPS Document
auto doc = MakeObject<Document>(L"input.xps", L"owner");
// change password of XPS Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 限制 MARKDOWN 文件编辑" %}}
您还可以使用 [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API 限制 MARKDOWN 文件编辑。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。 API 使您能够使用 [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) 枚举参数来控制限制内容的方式。下面的代码示例演示了如何限制在文档中的编辑，以便只能在表单域中进行编辑。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Markdown");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/xps-to-ps/" name="XPS 至 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/xps-to-dot/" name="XPS 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/xps-to-flatopc/" name="XPS 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/xps-to-rtf/" name="XPS 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/xps-to-markdown/" name="XPS 至 MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/xps-to-dotm/" name="XPS 至 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/xps-to-dotx/" name="XPS 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/xps-to-mhtml/" name="XPS 至 MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/xps-to-pcl/" name="XPS 至 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/xps-to-xamlflow/" name="XPS 至 XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/xps-to-odt/" name="XPS 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/xps-to-ott/" name="XPS 至 OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}