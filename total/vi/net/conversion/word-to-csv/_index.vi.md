---
title: .NET API để chuyển đổi WORD sang CSV hoặc với Trình chuyển đổi trực tuyến miễn phí
description: C# API để chuyển đổi WORD sang CSV hoặc Ứng dụng trực tuyến mà không cần sử dụng Microsoft Excel hoặc Adobe Reader hoặc trực tuyến. Kiểm tra trình chuyển đổi trực tuyến CSV sang DOC miễn phí một cách nhanh chóng trước khi tích hợp mã. 
url_ignore: /vi/net/conversion/word-to-csv/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: CSV
otherformats: XLTX XLAM XLT XLSX XLTM FODS SXC XLSB TSV DIF ODS EXCEL XLSM XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API để chuyển đổi WORD sang CSV hoặc Ứng dụng trực tuyến" h2="Xuất WORD sang CSV qua C# mà không sử dụng Microsoft<sup>&reg;</sup> Word hoặc Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể bao gồm tính năng chuyển đổi WORD sang CSV trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào trong hai bước đơn giản. Thứ nhất, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể xuất WORD sang HTML. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể chuyển đổi HTML sang CSV.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi WORD sang CSV" %}}
1. Mở tệp WORD bằng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document)
2. Chuyển đổi WORD sang HTML bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu sang định dạng CSV bằng phương pháp [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) và đặt `CSV` làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Công cụ chuyển đổi trực tuyến miễn phí cho WORD sang CSV</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=csv&from=docx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Tải tài liệu WORD từ Luồng qua C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) cũng cho phép bạn tải tài liệu WORD qua luồng. Để mở tài liệu từ luồng, chỉ cần chuyển đối tượng luồng có chứa tài liệu vào phương thức khởi tạo [Document](https://reference.aspose.com/words/net/aspose.words/document). Ví dụ mã sau đây cho thấy cách mở một tài liệu từ một luồng:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Thêm thuộc tính tùy chỉnh trong tệp CSV qua C#" %}}
Trong khi chuyển đổi WORD sang CSV, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) cho phép bạn thêm các thuộc tính tùy chỉnh trong tài liệu CSV của mình. Để thêm thuộc tính tùy chỉnh, bạn có thể sử dụng phương thức [Thêm](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) cho phương thức [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) lớp. Phương thức Thêm sẽ thêm thuộc tính vào tệp Excel và trả về một tham chiếu cho thuộc tính tài liệu mới dưới dạng [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) đối tượng. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

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
                          <span itemprop="name"><b>Làm cách nào tôi có thể chuyển đổi WORD sang CSV trực tuyến?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">App chuyển đổi WORD Online đã được tích hợp bên trên. Trước tiên, bạn cần thêm tệp WORD để chuyển đổi bằng cách kéo &amp; thả hoặc bấm vào bên trong vùng trắng để nhập tài liệu. Sau đó nhấp vào nút Chuyển đổi. Khi quá trình chuyển đổi WORD sang CSV hoàn tất, bạn có thể tải xuống tệp đã chuyển đổi của mình. Vì vậy, Bạn sẽ nhận được các tệp CSV đầu ra chỉ bằng một cú nhấp chuột.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Mất bao lâu để chuyển đổi WORD?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Trình chuyển đổi trực tuyến này hoạt động nhanh nhưng chủ yếu phụ thuộc vào kích thước của tệp WORD. Bạn có thể hiển thị tệp WORD kích thước nhỏ thành CSV trong vài giây. Hơn nữa, nếu bạn đã tích hợp mã chuyển đổi trong ứng dụng .NET, điều đó phụ thuộc vào cách bạn đã tối ưu hóa ứng dụng của mình cho quá trình chuyển đổi.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Có an toàn khi chuyển đổi WORD sang CSV bằng trình chuyển đổi Aspose.Total miễn phí không?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Tất nhiên rồi! Liên kết tải xuống của các tệp CSV sẽ có sẵn ngay lập tức sau khi chuyển đổi. Chúng tôi xóa các tệp đã tải lên sau 24 giờ và các liên kết tải xuống sẽ ngừng hoạt động sau khoảng thời gian này. Không ai có quyền truy cập vào tập tin của bạn. Chuyển đổi tập tin (bao gồm cả WORD) là an toàn tuyệt đối. Ứng dụng miễn phí chủ yếu được tích hợp với mục đích thử nghiệm để người dùng có thể kiểm tra kết quả trước khi tích hợp mã.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Tôi nên sử dụng trình duyệt nào để chuyển đổi WORD?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bạn có thể sử dụng bất kỳ trình duyệt hiện đại nào để chuyển đổi trực tuyến này, chẳng hạn như Google Chrome, Firefox, Opera, Safari. Nhưng trong trường hợp bạn đang phát triển ứng dụng Desktop. API chuyển đổi Aspose.Total WORD sẽ hoạt động trơn tru.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}