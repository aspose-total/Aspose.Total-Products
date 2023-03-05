---
title: Chuyển đổi DOCM sang PPSX qua C++ hoặc với Trình chuyển đổi trực tuyến miễn phí
description: Xuất DOCM sang PPSX trong các ứng dụng C++ của bạn mà không cần sử dụng Microsoft Word của PowerPoint hoặc trực tuyến. Kiểm tra nhanh trình chuyển đổi trực tuyến POT sang CSV miễn phí trước khi tích hợp mã.

family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: PPSX
otherformats: PPTM PPTX PPS PPSM ODP POT PPT POWERPOINT POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API để chuyển đổi DOCM sang PPSX hoặc Ứng dụng trực tuyến" h2="Xuất DOCM sang PPSX trong các ứng dụng C++ của bạn mà không cần sử dụng Microsoft Word <sup>&reg;</sup>; hoặc PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) bao gồm các API tự động hóa tệp mạnh mẽ cho phép tự động chuyển đổi DOCM sang PPSX trong khi sử dụng hai trong số các API của nó. Tải DOCM của bạn bằng [Aspose. AdWords for C++](https://products.aspose.com/words/cpp/) và chuyển đổi nó thành HTML, sau đó tải HTML thông qua thao tác PowerPoint API C++ [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) để tạo bản trình bày mới và lưu dưới dạng PPSX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi DOCM sang PPSX trên C++" %}}
1. Mở tệp DOCM bằng tham chiếu lớp [Document](https://reference.aspose.com/words/cpp/class/aspose.words.docmument)
2. Chuyển đổi DOCM sang HTML bằng cách sử dụng hàm thành viên [Save](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_stdbasicostream_saveoptions)
3. Khởi tạo đối tượng [Bản trình bày](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) mới
4. Thêm AutoShape trong slide của bạn và thêm AddTextFrame vào đó
5. Tải nội dung HTML và viết nó vào tệp Bản trình bày của bạn
6. Lưu tài liệu sang định dạng PPSX bằng phương pháp [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) và đặt Ppsx là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOCM file with an instance of Document
Document docmument = new Document("template.docm");
System::SharedPtr<Document> docm = System::MakeObject<Document>(u"sourceFile.docm");
// save the docmument in HTML file format
docm->Save(u"HtmlOutput.HTML");
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
// save presentation as Ppsx
pres->Save(output.ppsx, Aspose::Slides::Export::SaveFormat::Ppsx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Công cụ chuyển đổi trực tuyến miễn phí cho DOCM sang PPSX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=ppsx&from=docm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Tải tài liệu DOCM được bảo vệ bằng mật khẩu qua C++" %}}
Ngoài tính năng chuyển đổi tài liệu, API [Aspose. AdWords for C++](https://products.aspose.com/words/cpp/) cho phép nhiều tính năng thao tác tài liệu cho các nhà phát triển C++. Trong trường hợp định dạng tệp Microsoft Word DOCM của bạn được bảo vệ bằng mật khẩu, bạn vẫn có thể mở tệp đó bằng API. Để tải tài liệu được mã hóa, bạn có thể sử dụng quá tải hàm tạo đặc biệt, chấp nhận đối tượng [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Đối tượng này chứa thuộc tính Mật khẩu, thuộc tính chỉ định chuỗi mật khẩu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected docmument, the password is passed to the docmument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docmPassword");
// load the docmument from the local file system by filename:
SharedPtr<Document> docm = MakeObject<Document>(u"Encrypted.docm", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Thêm nhận xét trong tài liệu PPSX qua C++" %}}
Trong khi lưu DOCM dưới dạng PPSX, bạn cũng có thể sử dụng [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) để thêm các tính năng khác trong tài liệu PPSX của mình. Ví dụ, bạn có thể thêm nhận xét trong bản trình bày của mình. Nhận xét của slide trình bày được liên kết với một tác giả cụ thể. Lớp Trình bày có tập hợp các tác giả trong ICommentAuthorCollection chịu trách nhiệm thêm các nhận xét về trang trình bày. Đối với mỗi tác giả, có một bộ sưu tập các nhận xét trong ICommentCollection.
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
// save presentation as Ppsx
pres->Save(output.ppsx, Aspose::Slides::Export::SaveFormat::Ppsx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/docm-to-pptm/" name="DOCM Đến PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/docm-to-pptx/" name="DOCM Đến PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/docm-to-pps/" name="DOCM Đến PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/docm-to-ppsm/" name="DOCM Đến PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/docm-to-ppsx/" name="DOCM Đến PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/docm-to-pot/" name="DOCM Đến POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/docm-to-ppt/" name="DOCM Đến PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/docm-to-powerpoint/" name="DOCM Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/docm-to-potx/" name="DOCM Đến POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/docm-to-potm/" name="DOCM Đến POTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}