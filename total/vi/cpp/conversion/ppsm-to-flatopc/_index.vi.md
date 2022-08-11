---
title: API C++ để chuyển đổi PPSM sang FLATOPC
description: Xuất PPSM sang FLATOPC trong các ứng dụng C++ của bạn
url: /vi/cpp/conversion/ppsm-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: FLATOPC
otherformats: RTF TEXT WORD DOTM DOCX DOCM DOC DOTX DOT OTT ODT WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ để hiển thị PPSM sang FLATOPC" h2="Xuất PPSM sang FLATOPC trong các ứng dụng C++ mà không có bất kỳ phụ thuộc Microsoft PowerPoint hoặc Word nào" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) là gói thư viện Tự động hóa Định dạng Tệp C++ hoàn chỉnh. Bằng cách sử dụng các tính năng phong phú của các API có sẵn trong pacakge, chúng tôi có thể dễ dàng chuyển đổi PowerPoint PPSM sang Word FLATOPC. Để thực hiện chuyển đổi, trước tiên bạn có thể sử dụng API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) để chuyển đổi PPSM sang HTML. Sau đó, bằng cách sử dụng API xử lý văn bản giàu tính năng [Aspose.Words for C++](https://products.aspose.com/words/cpp/), bạn có thể chuyển đổi HTML sang FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để chuyển đổi PPSM sang FLATOPC" %}}
1. Tải tệp PPSM bằng cách sử dụng tham chiếu lớp [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Kết xuất PPSM sang HTML bằng cách sử dụng [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) thành viên funciton và đặt Html làm SaveFormat
3. Tải tệp HTML đã chuyển đổi bằng cách sử dụng tham chiếu lớp [Flatopcument](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument)
4. Lưu tài liệu sang định dạng FLATOPC bằng cách sử dụng [Save](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument#save_string) thành viên fucntion
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPSM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppsm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Flatopcument
System::SharedPtr<Flatopcument> flatopc = System::MakeObject<Flatopcument>(u"htmlOutput.html");
// save flatopcument in FLATOPC format
flatopc->Save(u"output.flatopc"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ppsm-to-rtf/" name="PPSM Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ppsm-to-text/" name="PPSM Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ppsm-to-word/" name="PPSM Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ppsm-to-dotm/" name="PPSM Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ppsm-to-flatopcx/" name="PPSM Đến FLATOPCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ppsm-to-flatopcm/" name="PPSM Đến FLATOPCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ppsm-to-flatopc/" name="PPSM Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ppsm-to-dotx/" name="PPSM Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ppsm-to-dot/" name="PPSM Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ppsm-to-ott/" name="PPSM Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ppsm-to-odt/" name="PPSM Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ppsm-to-wordml/" name="PPSM Đến WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}