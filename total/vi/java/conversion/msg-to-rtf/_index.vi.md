---
title: Xuất MSG sang RTF qua Java
description: Java API để chuyển đổi MSG thành RTF mà không cần sử dụng Microsoft Word hoặc Outlook
url_ignore: /vi/java/conversion/msg-to-rtf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: RTF
otherformats: MD DOT RTF ODT WORDML XPS TEXT JPEG PS TIFF DOTM DOCM GIF DOCX EMF OTT DOC DOTX PCL EPUB FLATOPC PDF SVG PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java để hiển thị MSG thành RTF" h2="Xuất MSG sang RTF bằng cách sử dụng API Java tiền đề mà không sử dụng bất kỳ phụ thuộc nào của bên thứ ba" >}}
{{% blocks/products/pf/feature-page-summary %}}
Chuyển đổi msg là một tính năng mạnh mẽ mà các nhà phát triển Java có thể tích hợp trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào thông qua [Aspose.Total for Java](https://products.aspose.com/total/java/). Bằng cách sử dụng hai API trong gói, bạn có thể chuyển đổi Msg MSG thành RTF mà không cần bất kỳ phụ thuộc nào của bên thứ ba. Trước tiên, bạn có thể sử dụng API thao tác msg [Aspose.Email for Java](https://products.aspose.com/email/java/) để chuyển đổi định dạng tệp MSG sang HTML. Thứ hai, bạn có thể kết xuất HTML thành RTF bằng cách sử dụng API xử lý tài liệu [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi MSG thành RTF" %}}
1. Mở tệp MSG bằng lớp [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Chuyển đổi MSG sang HTML bằng cách sử dụng [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save (java.io.OutputStream,%20com.aspose.msg.SaveOptions)) phương pháp
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng RTF bằng cách sử dụng [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save (java.lang.String, com.aspose.words.SaveOptions)) và đặt RTF làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn phải sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.RTF
document.save("output.rtf", SaveFormat.RTF);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}