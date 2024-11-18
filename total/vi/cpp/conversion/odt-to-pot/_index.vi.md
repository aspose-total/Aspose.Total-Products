---
title: Chuyển đổi ODT sang POT qua C++ hoặc với Trình chuyển đổi trực tuyến miễn phí
description: Xuất ODT sang POT trong các ứng dụng C++ của bạn mà không cần sử dụng Microsoft Word của PowerPoint hoặc trực tuyến. Kiểm tra nhanh trình chuyển đổi trực tuyến ODT sang POT miễn phí trước khi tích hợp mã.

family: total
platformtag: cpp
feature: conversion
informat: ODT
outformat: POT
otherformats: PPTM POTM POTX PPSM ODP PPTX PPSX POWERPOINT PPT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API để chuyển đổi ODT sang POT hoặc Ứng dụng trực tuyến" h2="Xuất ODT sang POT trong các ứng dụng C++ của bạn mà không cần sử dụng Microsoft Word <sup>&reg;</sup>; hoặc PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) bao gồm các API tự động hóa tệp mạnh mẽ cho phép tự động chuyển đổi ODT sang POT trong khi sử dụng hai trong số các API của nó. Tải ODT của bạn bằng [Aspose. AdWords for C++](https://products.aspose.com/words/cpp/) và chuyển đổi nó thành HTML, sau đó tải HTML thông qua thao tác PowerPoint API C++ [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) để tạo bản trình bày mới và lưu dưới dạng POT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi ODT sang POT trên C++" %}}
1. Mở tệp ODT bằng tham chiếu lớp [Odtument](https://reference.aspose.com/words/cpp/class/aspose.words.odtument)
2. Chuyển đổi ODT sang HTML bằng cách sử dụng hàm thành viên [Save](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_stdbasicostream_saveoptions)
3. Khởi tạo đối tượng [Bản trình bày](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) mới
4. Thêm AutoShape trong slide của bạn và thêm AddTextFrame vào đó
5. Tải nội dung HTML và viết nó vào tệp Bản trình bày của bạn
6. Lưu tài liệu sang định dạng POT bằng phương pháp [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) và đặt Pot là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load ODT file with an instance of Odtument
Odtument odtument = new Odtument("template.odt");
System::SharedPtr<Odtument> odt = System::MakeObject<Odtument>(u"sourceFile.odt");
// save the odtument in HTML file format
odt->Save(u"HtmlOutput.HTML");
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
// save presentation as Pot
pres->Save(output.pot, Aspose::Slides::Export::SaveFormat::Pot);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Công cụ chuyển đổi trực tuyến miễn phí cho ODT sang POT</h3>

<iframe title="Công cụ trực tuyến chuyển đổi từ odt sang pot" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pot&from=odt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Tải tài liệu ODT được bảo vệ bằng mật khẩu qua C++" %}}
Ngoài tính năng chuyển đổi tài liệu, API [Aspose. AdWords for C++](https://products.aspose.com/words/cpp/) cho phép nhiều tính năng thao tác tài liệu cho các nhà phát triển C++. Trong trường hợp định dạng tệp Microsoft Word ODT của bạn được bảo vệ bằng mật khẩu, bạn vẫn có thể mở tệp đó bằng API. Để tải tài liệu được mã hóa, bạn có thể sử dụng quá tải hàm tạo đặc biệt, chấp nhận đối tượng [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Đối tượng này chứa thuộc tính Mật khẩu, thuộc tính chỉ định chuỗi mật khẩu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected odtument, the password is passed to the odtument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"odtPassword");
// load the odtument from the local file system by filename:
SharedPtr<Odtument> odt = MakeObject<Odtument>(u"Encrypted.odt", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Thêm nhận xét trong tài liệu POT qua C++" %}}
Trong khi lưu ODT dưới dạng POT, bạn cũng có thể sử dụng [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) để thêm các tính năng khác trong tài liệu POT của mình. Ví dụ, bạn có thể thêm nhận xét trong bản trình bày của mình. Nhận xét của slide trình bày được liên kết với một tác giả cụ thể. Lớp Trình bày có tập hợp các tác giả trong ICommentAuthorCollection chịu trách nhiệm thêm các nhận xét về trang trình bày. Đối với mỗi tác giả, có một bộ sưu tập các nhận xét trong ICommentCollection.
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
// save presentation as Pot
pres->Save(output.pot, Aspose::Slides::Export::SaveFormat::Pot);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Các câu hỏi thường gặp</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Làm cách nào tôi có thể chuyển đổi ODT sang POT trực tuyến?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bạn có thể tìm thấy ứng dụng trực tuyến để chuyển đổi ODT ở trên. Để bắt đầu quá trình chuyển đổi, bạn có thể thêm tệp ODT bằng cách kéo và thả tệp hoặc nhấp vào bên trong vùng trắng để nhập tài liệu. Khi bạn đã thêm tệp, bạn chỉ cần nhấp vào nút "Chuyển đổi". Sau khi quá trình chuyển đổi ODT sang POT hoàn tất, bạn có thể tải xuống tệp đã chuyển đổi của mình chỉ bằng một cú nhấp chuột.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Mất bao lâu để chuyển đổi ODT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Tốc độ của trình chuyển đổi trực tuyến này phụ thuộc phần lớn vào kích thước của tệp ODT được chuyển đổi. Các tệp ODT nhỏ có thể được chuyển đổi thành POT chỉ trong vài giây. Nếu bạn đang sử dụng mã chuyển đổi trong ứng dụng C++, tốc độ chuyển đổi sẽ phụ thuộc vào mức độ bạn đã tối ưu hóa ứng dụng của mình.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Có an toàn khi chuyển đổi ODT sang POT bằng trình chuyển đổi Aspose.Total miễn phí không?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Tất nhiên rồi! Sau khi tệp ODT của bạn được chuyển đổi thành POT bằng trình chuyển đổi trực tuyến của chúng tôi, liên kết tải xuống cho tệp POT sẽ có sẵn ngay lập tức. Chúng tôi coi trọng tính bảo mật và quyền riêng tư của các tệp đã tải lên của bạn và xóa chúng sau 24 giờ sau khi quá trình chuyển đổi hoàn tất. Hãy yên tâm, sẽ không ai có quyền truy cập vào tệp của bạn. Quá trình chuyển đổi của chúng tôi, bao gồm chuyển đổi ODT, hoàn toàn an toàn. Chúng tôi cung cấp ứng dụng miễn phí cho mục đích thử nghiệm để bạn có thể xác minh kết quả trước khi tích hợp mã.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Tôi nên sử dụng trình duyệt nào để chuyển đổi ODT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Để chuyển đổi ODT trực tuyến, bạn có thể sử dụng bất kỳ trình duyệt hiện đại nào, chẳng hạn như Google Chrome, Firefox, Opera hoặc Safari. Tuy nhiên, nếu bạn đang phát triển ứng dụng dành cho máy tính để bàn, API chuyển đổi Aspose.Total ODT được khuyên dùng để có hiệu suất mượt mà.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}