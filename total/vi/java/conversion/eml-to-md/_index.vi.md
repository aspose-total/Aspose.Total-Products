---
title: Xuất EML sang MD qua Java
description: Java API để chuyển đổi EML thành MD mà không cần sử dụng Microsoft Word hoặc Outlook
url_ignore: /vi/java/conversion/eml-to-md/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: MD
otherformats: MD ODT EMF JPEG PS XPS EPUB WORDML PCL FLATOPC OTT TEXT DOTM RTF DOCX GIF DOTX DOT DOCM PNG SVG PDF DOC TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java để hiển thị EML thành MD" h2="Xuất EML sang MD bằng cách sử dụng API Java tiền đề mà không sử dụng bất kỳ phụ thuộc nào của bên thứ ba" >}}
{{% blocks/products/pf/feature-page-summary %}}
Chuyển đổi eml là một tính năng mạnh mẽ mà các nhà phát triển Java có thể tích hợp trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào thông qua [Aspose.Total for Java](https://products.aspose.com/total/java/). Bằng cách sử dụng hai API trong gói, bạn có thể chuyển đổi Eml EML thành MD mà không cần bất kỳ phụ thuộc nào của bên thứ ba. Trước tiên, bạn có thể sử dụng API thao tác eml [Aspose.Email for Java](https://products.aspose.com/email/java/) để chuyển đổi định dạng tệp EML sang HTML. Thứ hai, bạn có thể kết xuất HTML thành MD bằng cách sử dụng API xử lý tài liệu [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi EML thành MD" %}}
1. Mở tệp EML bằng lớp [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Chuyển đổi EML sang HTML bằng cách sử dụng [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save (java.io.OutputStream,%20com.aspose.eml.SaveOptions)) phương pháp
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng MD bằng cách sử dụng [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save (java.lang.String, com.aspose.words.SaveOptions)) và đặt MD làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn phải sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.MD
document.save("output.md", SaveFormat.MD);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-png/" name="MSG Đến PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-doc/" name="MSG Đến DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-ott/" name="MSG Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-odt/" name="MSG Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-wordml/" name="MSG Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-dotx/" name="MSG Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-svg/" name="MSG Đến SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-docx/" name="MSG Đến DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-epub/" name="MSG Đến EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-text/" name="MSG Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-xps/" name="MSG Đến XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-ps/" name="MSG Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-flatopc/" name="MSG Đến FLAĐếnPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-docm/" name="MSG Đến DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-jpeg/" name="MSG Đến JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-tiff/" name="MSG Đến TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-dot/" name="MSG Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-emf/" name="MSG Đến EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-rtf/" name="MSG Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-gif/" name="MSG Đến GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-pcl/" name="MSG Đến PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-dotm/" name="MSG Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-md/" name="MSG Đến MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-pdf/" name="MSG Đến PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}