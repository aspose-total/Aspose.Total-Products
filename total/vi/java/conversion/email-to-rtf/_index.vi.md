---
title: Xuất EMAIL sang RTF qua Java
description: Java API để chuyển đổi EMAIL thành RTF mà không cần sử dụng Microsoft Word hoặc Outlook
url_ignore: /vi/java/conversion/email-to-rtf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: RTF
otherformats: DOC XPS TEXT OTT ODT SVG DOTM WORDML DOTX JPEG EMF GIF PDF MD EPUB DOCM PS FLATOPC TIFF PCL RTF PNG DOT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java để hiển thị EMAIL thành RTF" h2="Xuất EMAIL sang RTF bằng cách sử dụng API Java tiền đề mà không sử dụng bất kỳ phụ thuộc nào của bên thứ ba" >}}
{{% blocks/products/pf/feature-page-summary %}}
Chuyển đổi email là một tính năng mạnh mẽ mà các nhà phát triển Java có thể tích hợp trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào thông qua [Aspose.Total for Java](https://products.aspose.com/total/java/). Bằng cách sử dụng hai API trong gói, bạn có thể chuyển đổi Email EMAIL thành RTF mà không cần bất kỳ phụ thuộc nào của bên thứ ba. Trước tiên, bạn có thể sử dụng API thao tác email [Aspose.Email for Java](https://products.aspose.com/email/java/) để chuyển đổi định dạng tệp EMAIL sang HTML. Thứ hai, bạn có thể kết xuất HTML thành RTF bằng cách sử dụng API xử lý tài liệu [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi EMAIL thành RTF" %}}
1. Mở tệp EMAIL bằng lớp [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Chuyển đổi EMAIL sang HTML bằng cách sử dụng [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save (java.io.OutputStream,%20com.aspose.email.SaveOptions)) phương pháp
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng RTF bằng cách sử dụng [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save (java.lang.String, com.aspose.words.SaveOptions)) và đặt RTF làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn phải sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}