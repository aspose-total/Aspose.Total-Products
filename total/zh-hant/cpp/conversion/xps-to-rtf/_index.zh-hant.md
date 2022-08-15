---
title: 用於將 XPS 導出到 RTF 的 C++ API
description: 在 C++ 應用程序中將 XPS 轉換為 RTF。
url: /zh-hant/cpp/conversion/xps-to-rtf/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: RTF
otherformats: FLATOPC DOTX DOCM MARKDOWN MHTML DOT WORDML XAMLFLOW PS ODT OTT PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="用於將 XPS 導出到 RTF 的 C++ API" h2="在 C++ 應用程序中將 XPS 渲染為 RTF，無需任何第三方應用程序" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) 文件格式自動化庫允許 C++ 開發人員通過兩個簡單的步驟將 XPS 轉換為 RTF。首先，您可以使用 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API 將 XPS 文件格式轉換為 DOC。其次，通過使用高級 Word 文檔處理 API [Aspose.Words for C++](https://products.aspose.com/words/cpp/)，您可以將 DOC 導出到 RTF。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="將 XPS 渲染為 RTF 的 C++ API" %}}
1.使用[Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)類參考打開XPS文件
2.使用[保存](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)成員函數將XPS轉換為DOC
3. 使用 Aspose.Words API 的 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 類引用加載 DOC 文件
4.使用[Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)成員函數將文檔保存為RTF格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total.Cpp``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，從 [下載](https://downloads.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XPS file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.xps");
// save XPS as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Rtf
wordDoc->Save(u"output.Rtf");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 更改 XPS 文檔的密碼" %}}
在將 XPS 渲染為 RTF 的過程中，您可以打開受密碼保護的 XPS 並更改其密碼。要更改 XPS 文件的密碼，您必須知道該文檔的所有者密碼。您可以通過指定所有者密碼並使用 ChangePasswords 方法更改密碼來使用 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) 加載受密碼保護的 PDF 文檔。
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

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 限制 RTF 文件編輯" %}}
您還可以使用 [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API 限制 RTF 文件編輯。有時您可能需要限制編輯文檔的能力，只允許對其進行某些操作。 API 使您能夠使用 [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) 枚舉參數來控制限制內容的方式。下面的代碼示例演示瞭如何限制在文檔中的編輯，以便只能在表單域中進行編輯。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Rtf");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/xps-to-flatopc/" name="XPS 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/xps-to-dotx/" name="XPS 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/xps-to-rtf/" name="XPS 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/xps-to-markdown/" name="XPS 至 MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/xps-to-mhtml/" name="XPS 至 MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/xps-to-dot/" name="XPS 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/xps-to-wordml/" name="XPS 至 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/xps-to-xamlflow/" name="XPS 至 XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/xps-to-ps/" name="XPS 至 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/xps-to-odt/" name="XPS 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/xps-to-ott/" name="XPS 至 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/xps-to-pcl/" name="XPS 至 PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}