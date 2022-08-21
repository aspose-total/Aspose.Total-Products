---
title: API C++ để chuyển đổi POTX sang DOT
description: Xuất POTX sang DOT trong các ứng dụng C++ của bạn
url: /vi/cpp/conversion/potx-to-dot/
family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: DOT
otherformats: WORDML OTT DOC DOCM TEXT ODT DOTX WORD FLATOPC RTF DOTM DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ để hiển thị POTX sang DOT" h2="Xuất POTX sang DOT trong các ứng dụng C++ mà không có bất kỳ phụ thuộc Microsoft PowerPoint hoặc Word nào" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) là gói thư viện Tự động hóa Định dạng Tệp C++ hoàn chỉnh. Bằng cách sử dụng các tính năng phong phú của các API có sẵn trong pacakge, chúng tôi có thể dễ dàng chuyển đổi PowerPoint POTX sang Word DOT. Để thực hiện chuyển đổi, trước tiên bạn có thể sử dụng API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) để chuyển đổi POTX sang HTML. Sau đó, bằng cách sử dụng API xử lý văn bản giàu tính năng [Aspose.Words for C++](https://products.aspose.com/words/cpp/), bạn có thể chuyển đổi HTML sang DOT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để chuyển đổi POTX sang DOT" %}}
1. Tải tệp POTX bằng cách sử dụng tham chiếu lớp [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Kết xuất POTX sang HTML bằng cách sử dụng [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) thành viên funciton và đặt Html làm SaveFormat
3. Tải tệp HTML đã chuyển đổi bằng cách sử dụng tham chiếu lớp [Dotument](https://reference.aspose.com/words/cpp/class/aspose.words.dotument)
4. Lưu tài liệu sang định dạng DOT bằng cách sử dụng [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotument#save_string) thành viên fucntion
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Dotument
System::SharedPtr<Dotument> dot = System::MakeObject<Dotument>(u"htmlOutput.html");
// save dotument in DOT format
dot->Save(u"output.dot"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potx-to-wordml/" name="POTX Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potx-to-ott/" name="POTX Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potx-to-dot/" name="POTX Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potx-to-dotm/" name="POTX Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potx-to-text/" name="POTX Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potx-to-odt/" name="POTX Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potx-to-dotx/" name="POTX Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potx-to-word/" name="POTX Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potx-to-flatopc/" name="POTX Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potx-to-rtf/" name="POTX Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potx-to-dotm/" name="POTX Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/potx-to-dotx/" name="POTX Đến DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}