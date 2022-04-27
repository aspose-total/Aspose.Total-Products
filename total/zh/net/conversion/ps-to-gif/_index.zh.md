---
title: C# API 将 PS 导出到 GIF
description: 在不使用 Microsoft Word 的情况下将 PS 转换为 GIF
url: /zh/net/conversion/ps-to-gif/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: GIF
otherformats: RTF MHTML XAMLFLOW GIF DOT MARKDOWN OTT ODT FLATOPC DOTX PCL WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 PS 渲染到 GIF" h2=".NET API 可在 Windows、macOS 和 Linux 上将 PS 导出为 GIF，而无需使用 Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) 是一个强大的 API，用于在您的 .NET 应用程序中添加文档操作和转换功能。通过使用高级 PDF 处理 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 PS 文件格式转换为 DOC。之后，通过使用强大的文档处理 API [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 DOC 渲染为 GIF。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 PS 转换为 GIF" %}}
1.使用[Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)类打开PS文件
2. 使用[Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将PS转换为Doc
3.使用Aspose.Words的[Document](https://apireference.aspose.com/words/net/aspose.words/document)类加载Doc文件
4. 使用[Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4)方法将文档保存为GIF格式，并将Gif设置为SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://downloads.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.ps");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.gif", SaveFormat.Gif);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 使用所有者密码解密 PS 文件" %}}
在将 PS 转换为 GIF 之前，如果您想解密您的文档，您可以使用 API 来完成。为了解密 PDF 文件，您首先需要创建一个 [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) 对象并使用所有者的密码打开 PS。之后，您需要调用 Document 对象的 [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) 方法。最后，使用 Document 对象的 Save 方法保存更新的文件。  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.ps", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 创建只读 GIF- 文件" %}}
为了保护您的 GIF 不被编辑，并防止其他人编辑您文档中的敏感和机密信息，您还可以使用 API 设置文档的保护。您可以限制编辑文档的能力，只允许对其进行某些操作。这可以使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API 来完成。它使您能够控制使用 [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数限制内容的方式。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

doc.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.gif", SaveFormat.Gif);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ps-to-ott/" name="PS 转 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ps-to-mhtml/" name="PS 转 MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ps-to-wordml/" name="PS 转 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ps-to-dot/" name="PS 转 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ps-to-odt/" name="PS 转 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ps-to-rtf/" name="PS 转 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ps-to-ps/" name="PS 转 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ps-to-flatopc/" name="PS 转 FLA转PC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ps-to-pcl/" name="PS 转 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ps-to-markdown/" name="PS 转 MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ps-to-xamlflow/" name="PS 转 XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ps-to-dotx/" name="PS 转 DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}