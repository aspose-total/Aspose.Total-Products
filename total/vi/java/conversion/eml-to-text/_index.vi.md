---
title: Xuất EML sang TEXT qua Java
description: Java API để chuyển đổi EML thành TEXT mà không cần sử dụng Microsoft Word hoặc Outlook
url_ignore: /vi/java/conversion/eml-to-text/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: TEXT
otherformats: PDF DOCM OTT PNG GIF DOC DOCX MD ODT XPS DOTM SVG JPEG PS TIFF PCL RTF EMF TEXT DOT DOTX EPUB FLATOPC WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java để hiển thị EML thành TEXT" h2="Xuất EML sang TEXT bằng cách sử dụng API Java tiền đề mà không sử dụng bất kỳ phụ thuộc nào của bên thứ ba" >}}
{{% blocks/products/pf/feature-page-summary %}}
Chuyển đổi eml là một tính năng mạnh mẽ mà các nhà phát triển Java có thể tích hợp trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào thông qua [Aspose.Total for Java](https://products.aspose.com/total/java/). Bằng cách sử dụng hai API trong gói, bạn có thể chuyển đổi Eml EML thành TEXT mà không cần bất kỳ phụ thuộc nào của bên thứ ba. Trước tiên, bạn có thể sử dụng API thao tác eml [Aspose.Email for Java](https://products.aspose.com/email/java/) để chuyển đổi định dạng tệp EML sang HTML. Thứ hai, bạn có thể kết xuất HTML thành TEXT bằng cách sử dụng API xử lý tài liệu [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi EML thành TEXT" %}}
1. Mở tệp EML bằng lớp [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Chuyển đổi EML sang HTML bằng cách sử dụng [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save (java.io.OutputStream,%20com.aspose.eml.SaveOptions)) phương pháp
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng TEXT bằng cách sử dụng [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save (java.lang.String, com.aspose.words.SaveOptions)) và đặt TEXT làm SaveFormat
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