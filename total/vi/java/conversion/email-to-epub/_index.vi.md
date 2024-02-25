---
title: Xuất EMAIL sang EPUB qua Java
description: Java API để chuyển đổi EMAIL thành EPUB mà không cần sử dụng Microsoft Word hoặc Outlook
url_ignore: /vi/java/conversion/email-to-epub/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: EPUB
otherformats: DOTM DOCM TIFF DOCX EMF DOT MD JPEG TEXT DOTX DOC PS WORDML RTF GIF PCL PNG PDF SVG EPUB FLATOPC XPS ODT OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java để hiển thị EMAIL thành EPUB" h2="Xuất EMAIL sang EPUB bằng cách sử dụng API Java tiền đề mà không sử dụng bất kỳ phụ thuộc nào của bên thứ ba" >}}
{{% blocks/products/pf/feature-page-summary %}}
Chuyển đổi email là một tính năng mạnh mẽ mà các nhà phát triển Java có thể tích hợp trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào thông qua [Aspose.Total for Java](https://products.aspose.com/total/java/). Bằng cách sử dụng hai API trong gói, bạn có thể chuyển đổi Email EMAIL thành EPUB mà không cần bất kỳ phụ thuộc nào của bên thứ ba. Trước tiên, bạn có thể sử dụng API thao tác email [Aspose.Email for Java](https://products.aspose.com/email/java/) để chuyển đổi định dạng tệp EMAIL sang HTML. Thứ hai, bạn có thể kết xuất HTML thành EPUB bằng cách sử dụng API xử lý tài liệu [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi EMAIL thành EPUB" %}}
1. Mở tệp EMAIL bằng lớp [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Chuyển đổi EMAIL sang HTML bằng cách sử dụng [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save (java.io.OutputStream,%20com.aspose.email.SaveOptions)) phương pháp
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng EPUB bằng cách sử dụng [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save (java.lang.String, com.aspose.words.SaveOptions)) và đặt EPUB làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn phải sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMAIL file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save EMAIL as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.EPUB
document.save("output.epub", SaveFormat.EPUB);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}