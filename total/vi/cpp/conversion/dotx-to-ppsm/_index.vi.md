---
title: Chuyển đổi DOTX sang PPSM qua C++
description: Xuất DOTX sang PPSM trong các ứng dụng C++ của bạn mà không cần sử dụng Microsoft Word của PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: PPSM
otherformats: PPS PPSX PPT PPTX ODP POTX PPTM POWERPOINT POTM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API để chuyển đổi DOTX sang PPSM" h2="Xuất DOTX sang PPSM trong các ứng dụng C++ của bạn mà không cần sử dụng Microsoft Word <sup>&reg;</sup>; hoặc PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) bao gồm các API tự động hóa tệp mạnh mẽ cho phép tự động chuyển đổi DOTX sang PPSM trong khi sử dụng hai trong số các API của nó. Tải DOTX của bạn bằng [Aspose. AdWords for C++](https://products.aspose.com/words/cpp/) và chuyển đổi nó thành HTML, sau đó tải HTML thông qua thao tác PowerPoint API C++ [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) để tạo bản trình bày mới và lưu dưới dạng PPSM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi DOTX sang PPSM trên C++" %}}
1. Mở tệp DOTX bằng tham chiếu lớp [Dotxument](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument)
2. Chuyển đổi DOTX sang HTML bằng cách sử dụng hàm thành viên [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_stdbasicostream_saveoptions)
3. Khởi tạo đối tượng [Bản trình bày](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) mới
4. Thêm AutoShape trong slide của bạn và thêm AddTextFrame vào đó
5. Tải nội dung HTML và viết nó vào tệp Bản trình bày của bạn
6. Lưu tài liệu sang định dạng PPSM bằng phương pháp [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) và đặt Ppsm là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOTX file with an instance of Dotxument
Dotxument dotxument = new Dotxument("template.dotx");
System::SharedPtr<Dotxument> dotx = System::MakeObject<Dotxument>(u"sourceFile.dotx");
// save the dotxument in HTML file format
dotx->Save(u"HtmlOutput.HTML");
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
// save presentation as Ppsm
pres->Save(output.ppsm, Aspose::Slides::Export::SaveFormat::Ppsm);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Tải tài liệu DOTX được bảo vệ bằng mật khẩu qua C++" %}}
Ngoài tính năng chuyển đổi tài liệu, API [Aspose. AdWords for C++](https://products.aspose.com/words/cpp/) cho phép nhiều tính năng thao tác tài liệu cho các nhà phát triển C++. Trong trường hợp định dạng tệp Microsoft Word DOTX của bạn được bảo vệ bằng mật khẩu, bạn vẫn có thể mở tệp đó bằng API. Để tải tài liệu được mã hóa, bạn có thể sử dụng quá tải hàm tạo đặc biệt, chấp nhận đối tượng [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Đối tượng này chứa thuộc tính Mật khẩu, thuộc tính chỉ định chuỗi mật khẩu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected dotxument, the password is passed to the dotxument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"dotxPassword");
// load the dotxument from the local file system by filename:
SharedPtr<Dotxument> dotx = MakeObject<Dotxument>(u"Encrypted.dotx", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Thêm nhận xét trong tài liệu PPSM qua C++" %}}
Trong khi lưu DOTX dưới dạng PPSM, bạn cũng có thể sử dụng [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) để thêm các tính năng khác trong tài liệu PPSM của mình. Ví dụ, bạn có thể thêm nhận xét trong bản trình bày của mình. Nhận xét của slide trình bày được liên kết với một tác giả cụ thể. Lớp Trình bày có tập hợp các tác giả trong ICommentAuthorCollection chịu trách nhiệm thêm các nhận xét về trang trình bày. Đối với mỗi tác giả, có một bộ sưu tập các nhận xét trong ICommentCollection.
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
// save presentation as Ppsm
pres->Save(output.ppsm, Aspose::Slides::Export::SaveFormat::Ppsm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/dotx-to-pps/" name="DOTX Đến PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/dotx-to-ppsx/" name="DOTX Đến PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/dotx-to-ppt/" name="DOTX Đến PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/dotx-to-pptx/" name="DOTX Đến PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/dotx-to-ppsm/" name="DOTX Đến PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/dotx-to-potx/" name="DOTX Đến POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/dotx-to-pptm/" name="DOTX Đến PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/dotx-to-powerpoint/" name="DOTX Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/dotx-to-potm/" name="DOTX Đến POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/dotx-to-pot/" name="DOTX Đến POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}