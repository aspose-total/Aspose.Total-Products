---
title: C++ API để chuyển đổi PCL sang PPTM
description: Chuyển đổi PCL sang PPTM qua C++ mà không cần sử dụng Microsoft Word hoặc Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: PPTM
otherformats: XAML POWERPOINT PPSX POTX SWF PPT ODP PPS POTM POT OTP PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất PCL sang PPTM trong Ứng dụng C++" h2="Chuyển đổi PCL sang PPTM trong Ứng dụng C++ của bạn mà không cần sử dụng Microsoft <sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có phải là nhà phát triển C++ đang tìm cách thêm để tích hợp tính năng chuyển đổi PCL sang PPTM bên trong các ứng dụng C++ của mình không? Bạn có thể làm điều đó trong hai bước đơn giản. Bạn có thể xuất PCL sang PPTX bằng cách sử dụng [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Thứ hai, bằng cách sử dụng [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), bạn có thể chuyển đổi PPTX sang PPTM. Cả hai API đều nằm trong gói [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để xuất PCL sang PPTM" %}}
1. Mở tệp PCL bằng tham chiếu lớp [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Chuyển đổi PCL sang PPTX bằng cách sử dụng hàm phương pháp [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Tải tài liệu PPTX bằng cách sử dụng tham chiếu lớp [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Lưu tài liệu sang định dạng PPTM bằng hàm thành viên [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) và đặt `Pptm` là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PCL file with an instance of Document class
auto doc = MakeObject<Document>(u"template.pcl");
// save PCL as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Pptm format
prs->Save(u"output.pptm", Aspose::Slides::Export::SaveFormat::Pptm);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Thay đổi mật khẩu của tài liệu PCL qua C++" %}}
Trong quá trình kết xuất PCL sang PPTM, bạn có thể mở PCL được bảo vệ bằng mật khẩu và cũng có thể thay đổi mật khẩu của nó. Để thay đổi mật khẩu của tệp PCL, bạn phải biết mật khẩu chủ sở hữu của tài liệu đó. Bạn có thể tải tài liệu PDF được bảo vệ bằng mật khẩu bằng [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) bằng cách chỉ định mật khẩu chủ sở hữu của nó và sử dụng phương pháp ChangePasswords để thay đổi mật khẩu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PCL Document
auto doc = MakeObject<Document>(L"input.pcl", L"owner");
// change password of PCL Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Thêm hình ảnh từ web trong tệp PPTM qua C++" %}}
Sau khi chuyển đổi PCL sang PPTM, bạn cũng có thể thêm hình ảnh từ web vào tài liệu đầu ra của mình. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) hỗ trợ các thao tác với hình ảnh ở các định dạng phổ biến sau: JPEG, PNG, BMP, GIF và các định dạng khác. Bạn có thể thêm một hoặc một số hình ảnh trên máy tính của mình vào một trang chiếu trong bản trình bày. Mã mẫu trong C++ này chỉ cho bạn cách thêm hình ảnh vào tệp PPTM
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPTM file
auto pres = System::MakeObject<Presentation>("output.pptm");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.pptm", SaveFormat::Pptm);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pcl-to-xaml/" name="PCL Đến XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pcl-to-powerpoint/" name="PCL Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pcl-to-ppsx/" name="PCL Đến PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pcl-to-potx/" name="PCL Đến POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pcl-to-swf/" name="PCL Đến SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pcl-to-ppt/" name="PCL Đến PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pcl-to-pptm/" name="PCL Đến PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pcl-to-pps/" name="PCL Đến PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pcl-to-potm/" name="PCL Đến POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pcl-to-pot/" name="PCL Đến POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pcl-to-otp/" name="PCL Đến OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pcl-to-ppsm/" name="PCL Đến PPSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}