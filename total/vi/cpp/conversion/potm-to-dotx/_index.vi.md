---
title: API C++ để chuyển đổi POTM sang DOTX
description: Xuất POTM sang DOTX trong các ứng dụng C++ của bạn
url: /vi/cpp/conversion/potm-to-dotx/
family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: DOTX
otherformats: RTF DOCX WORDML TEXT OTT WORD ODT FLATOPC DOT DOC DOTM DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ để hiển thị POTM sang DOTX" h2="Xuất POTM sang DOTX trong các ứng dụng C++ mà không có bất kỳ phụ thuộc Microsoft PowerPoint hoặc Word nào" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) là gói thư viện Tự động hóa Định dạng Tệp C++ hoàn chỉnh. Bằng cách sử dụng các tính năng phong phú của các API có sẵn trong pacakge, chúng tôi có thể dễ dàng chuyển đổi PowerPoint POTM sang Word DOTX. Để thực hiện chuyển đổi, trước tiên bạn có thể sử dụng API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) để chuyển đổi POTM sang HTML. Sau đó, bằng cách sử dụng API xử lý văn bản giàu tính năng [Aspose.Words for C++](https://products.aspose.com/words/cpp/), bạn có thể chuyển đổi HTML sang DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để chuyển đổi POTM sang DOTX" %}}
1. Tải tệp POTM bằng cách sử dụng tham chiếu lớp [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Kết xuất POTM sang HTML bằng cách sử dụng [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) thành viên funciton và đặt Html làm SaveFormat
3. Tải tệp HTML đã chuyển đổi bằng cách sử dụng tham chiếu lớp [Dotxument](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument)
4. Lưu tài liệu sang định dạng DOTX bằng cách sử dụng [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_string) thành viên fucntion
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Dotxument
System::SharedPtr<Dotxument> dotx = System::MakeObject<Dotxument>(u"htmlOutput.html");
// save dotxument in DOTX format
dotx->Save(u"output.dotx"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potm-to-rtf/" name="POTM Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potm-to-dotxx/" name="POTM Đến DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potm-to-wordml/" name="POTM Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potm-to-text/" name="POTM Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potm-to-ott/" name="POTM Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potm-to-word/" name="POTM Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potm-to-odt/" name="POTM Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potm-to-flatopc/" name="POTM Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potm-to-dot/" name="POTM Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potm-to-dotx/" name="POTM Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potm-to-dotm/" name="POTM Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potm-to-dotxm/" name="POTM Đến DOTXM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}