---
title: API C++ để chuyển đổi PPTM sang RTF
description: Xuất PPTM sang RTF trong các ứng dụng C++ của bạn
url: /vi/cpp/conversion/pptm-to-rtf/
family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: RTF
otherformats: ODT DOC DOCM WORDML FLATOPC WORD DOTM DOT DOCX DOTX OTT TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ để hiển thị PPTM sang RTF" h2="Xuất PPTM sang RTF trong các ứng dụng C++ mà không có bất kỳ phụ thuộc Microsoft PowerPoint hoặc Word nào" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) là gói thư viện Tự động hóa Định dạng Tệp C++ hoàn chỉnh. Bằng cách sử dụng các tính năng phong phú của các API có sẵn trong pacakge, chúng tôi có thể dễ dàng chuyển đổi PowerPoint PPTM sang Word RTF. Để thực hiện chuyển đổi, trước tiên bạn có thể sử dụng API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) để chuyển đổi PPTM sang HTML. Sau đó, bằng cách sử dụng API xử lý văn bản giàu tính năng [Aspose.Words for C++](https://products.aspose.com/words/cpp/), bạn có thể chuyển đổi HTML sang RTF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để chuyển đổi PPTM sang RTF" %}}
1. Tải tệp PPTM bằng cách sử dụng tham chiếu lớp [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Kết xuất PPTM sang HTML bằng cách sử dụng [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) thành viên funciton và đặt Html làm SaveFormat
3. Tải tệp HTML đã chuyển đổi bằng cách sử dụng tham chiếu lớp [Rtfument](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument)
4. Lưu tài liệu sang định dạng RTF bằng cách sử dụng [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_string) thành viên fucntion
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Rtfument
System::SharedPtr<Rtfument> rtf = System::MakeObject<Rtfument>(u"htmlOutput.html");
// save rtfument in RTF format
rtf->Save(u"output.rtf"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pptm-to-odt/" name="PPTM Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pptm-to-rtf/" name="PPTM Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pptm-to-rtfm/" name="PPTM Đến RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pptm-to-wordml/" name="PPTM Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pptm-to-flatopc/" name="PPTM Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pptm-to-word/" name="PPTM Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pptm-to-dotm/" name="PPTM Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pptm-to-dot/" name="PPTM Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pptm-to-rtfx/" name="PPTM Đến RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pptm-to-dotx/" name="PPTM Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pptm-to-ott/" name="PPTM Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pptm-to-text/" name="PPTM Đến TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}